<template>
  <div>
    <CardPage :items="items"/>
  </div>
</template>

<script>
import CardPage from "~/components/Card.vue";

export default {
  components: {CardPage},
  data() {
    return {
      items: [
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: '',
          to: '/lessons/twenty-one/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/twenty-one/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/twenty-one/reja'
        },
        {
          title: "TYURING MASHINALARI. NОREKURSIV SANALUVCHAN TО‘PLAMLAR. TО‘XTASH MUAMMОSI. ALGОRITMIK YECHILMAS MUAMMОLAR",
          icon: '',
          to: '/lessons/twenty-one/yechim'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
