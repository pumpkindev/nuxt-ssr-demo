<style lang="stylus" scoped>
.repos-page {
  font-size 20px
  margin-top 1.767rem
  text-align center
}
</style>

<template>
  <div class="repos-page">
    repos
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: '开源库',
      meta: [
        { hid: 'repos custom title', name: 'repos', content: 'repos custom title description' }
      ]
    }
  }
}
</script>
