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
          title: 'Reja va tayanch iboralar',
          icon: 'reja',
          to: '/lessons/twenty-one/reja'
        },
        {
          title: "TYURING MASHINALARI. NОREKURSIV SANALUVCHAN TО‘PLAMLAR. TО‘XTASH MUAMMОSI. ALGОRITMIK YECHILMAS MUAMMОLAR",
          icon: 'toplam',
          to: '/lessons/twenty-one/yechim'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/twenty-one/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/twenty-one/masala'
        },
        {
          title: "Tyuring mashinalari",
          icon: 'prezintatsiya',
          to: '/lessons/twenty-one/машина тюринга'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
