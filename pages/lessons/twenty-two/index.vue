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
          to: '/lessons/twenty-two/reja'
        },
        {
          title: "REKURSIV VA REKURSIV SANALUCSHI TО‘PLAMLAR.",
          icon: 'toplam',
          to: '/lessons/twenty-two/rekursiv'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/twenty-two/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/twenty-two/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/twenty-two'
        },
        {
          title: "REKURSIV VA REKURSIV SANALUCSHI TО‘PLAMLAR.",
          icon: 'prezintatsiya',
          to: '/lessons/twenty-two/рекурсив функц'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
