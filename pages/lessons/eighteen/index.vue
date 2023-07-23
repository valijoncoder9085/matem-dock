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
          to: '/lessons/eighteen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/eighteen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/eighteen/reja'
        },
        {
          title: "GRAFLAR, IZОMОFIZM, TIPLAR, BОGLANISHLIK EYLER VA GAMILTОN GRAFLARI.",
          icon: '',
          to: '/lessons/eighteen/graf'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
