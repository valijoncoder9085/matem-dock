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
          to: '/lessons/four/reja'
        },
        {
          title: 'FОRMULALAR. TENGKUCHLI FОRMULALAR',
          icon: 'toplam',
          to: '/lessons/four/formula'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/four/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/four/masala'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/four'
        },
        {
          title: 'Aynan chin',
          icon: 'prezintatsiya',
          to: '/lessons/four/Айнан чин'
        },
        {
          title: 'Formulalar teng kuchli formulalar',
          icon: 'prezintatsiya',
          to: '/lessons/four/Формулалар тенг кучли фор'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
