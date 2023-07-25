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
          icon: 'masala',
          to: '/lessons/eighteen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/eighteen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: 'reja',
          to: '/lessons/eighteen/reja'
        },
        {
          title: "GRAFLAR, IZОMОFIZM, TIPLAR, BОGLANISHLIK EYLER VA GAMILTОN GRAFLARI.",
          icon: 'toplam',
          to: '/lessons/eighteen/graf'
        },
        {
          title: "Graflar nazariyasi",
          icon: 'prezintatsiya',
          to: '/lessons/eighteen/Граф'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
