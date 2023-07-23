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
          to: '/lessons/nineteen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/nineteen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/nineteen/reja'
        },
        {
          title: "GRAFLAR, IZОMОFIZM, TIPLAR, BОGLANISHLIK EYLER VA GAMILTОN GRAFLARI.",
          icon: '',
          to: '/lessons/nineteen/tayanch'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
