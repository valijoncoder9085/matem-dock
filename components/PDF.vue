<template>
  <div>
    <iframe class="pdf" :src="src" frameborder="0"/>
  </div>
</template>

<script>
export default {
  name: 'PDFComponent',
  props:{
    src: {
      type: String,
      require: true,
    }
  },
  data(){
    return{

    }
  }
}
</script>

<style lang="scss" scoped>
.pdf{
  width: 100%;
  height: 100vh;
}
</style>
