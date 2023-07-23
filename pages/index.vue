<template>
  <div>
  </div>
</template>

<script>
export default {
  async mounted(){
    const path = this.$route.path
    if (path == '/'){
      await this.$router.push('/home')
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
