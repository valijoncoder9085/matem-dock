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
      src: "/uslub/MUSTAQIL-TA’LIM-MAVZULARINI-O’ZLASHTIRISH-BO’YICHA-ZARUR-USLUBIY-KO’RSATMALAR.pdf",
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
