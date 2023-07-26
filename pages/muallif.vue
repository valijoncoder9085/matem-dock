<template>
  <div>
    <PDFComponent :src="src"/>
  </div>
</template>

<script>
import PDFComponent from "~/components/PDF.vue";

export default {
  components: {PDFComponent},
  data(){
    return{
      src: "/muallif/muallif haqida ma'lumot.pdf",
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
