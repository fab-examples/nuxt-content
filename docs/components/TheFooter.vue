<template>
  <footer class="h-24 w-full border-t dark:border-gray-800 bg-white dark:bg-gray-900">
    <div class="h-full w-full container mx-auto px-4 lg:px-8 flex items-center justify-between">
      <div class="flex items-end">
        <span class="mr-2 text-sm leading-none">© {{ new Date().getFullYear() }}</span>
        <a href="https://nuxtjs.org" target="_blank" rel="noopener">
          <IconNuxt class="h-4" />
        </a>
      </div>
      <div class="flex">
        <Dropdown v-if="availableLocales.length">
          <template #trigger="{ open }">
            <button
              class="p-2 rounded-md hover:text-green-500 focus:outline-none focus:outline-none"
              :class="{ 'text-green-500': open }"
            >
              <icon-translate class="w-6 h-6" />
            </button>
          </template>

          <ul class="py-2">
            <li v-for="locale in availableLocales" :key="locale.code">
              <nuxt-link
                v-if="$i18n.locale !== locale.code"
                :to="switchLocalePath(locale.code)"
                class="flex px-4 items-center hover:text-green-500 leading-7"
              >{{ locale.name }}</nuxt-link>
            </li>
          </ul>
        </Dropdown>
        <ColorSwitcher class="p-2 pr-0" />
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  computed: {
    availableLocales () {
      return this.$i18n.locales.filter(i => i.code !== this.$i18n.locale)
    }
  }
}
</script>

<style>

</style>
