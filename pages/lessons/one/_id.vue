<template>
  <div>
    <PDFComponent :src="'/lessons/one/' +`${src}` + '.pdf'"/>
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
    this.src = this.$route.params.id;
  }
}
</script>

<style lang="scss" scoped>

</style>
