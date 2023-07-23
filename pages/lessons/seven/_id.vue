<template>
  <div>
    <PDFComponent v-show="src !== ''" :src="'/lessons/seven/' +`${src}` + '.pdf'"/>
  </div>
</template>

<script>

import PDFComponent from "~/components/PDF.vue";

export default {
  components: {PDFComponent},
  data() {
    return {
      src: "",
    }
  },
  async mounted() {
    const path = this.$route.params.id
    this.src = path;
  }
}
</script>

<style lang="scss" scoped>

</style>
