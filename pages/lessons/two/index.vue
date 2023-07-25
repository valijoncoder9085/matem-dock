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
          to: '/lessons/two/reja'
        },
        {
          title: 'MUNОSABATLAR. BINAR MUNОSABAT. EKVIVALENTLIK MUNОSABATI. TARTIBLASH MUNОSABATI',
          icon: 'toplam',
          to: '/lessons/two/binar'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/two/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR',
          icon: 'masala',
          to: '/lessons/two/masala'
        },
        {
          title: "Qisman tartiblangan to'plamlar",
          icon: 'prezintatsiya',
          to: '/lessons/two/2'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
