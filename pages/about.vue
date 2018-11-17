<template lang="html">
  <nuxt-link to="/">TOP</nuxt-link>
</template>
​
<script>
export default {
  head() {
    return {
      // タイトルテンプレートがある場合は "ABOUT - ポートフォリオ" になる
      title: 'ABOUT',
      meta: [
        { hid: 'description', name: 'description', content: 'About ページ' }
      ]
    }
  },
  layout: 'dark'
}
</script>
​
<style lang="scss">
</style>
