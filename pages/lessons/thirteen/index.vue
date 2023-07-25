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
          to: '/lessons/thirteen/reja'
        },
        {
          title: "L NAZARIУA UCHUN GУОDELNING TО‘LIQLIK HAQIDAGI TEОREMASI.",
          icon: 'toplam',
          to: '/lessons/thirteen/teorea'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/thirteen/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/thirteen/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/thirteen'
        },
        {
          title: "Umumiy deduksiya",
          icon: 'prezintatsiya',
          to: '/lessons/thirteen/Умум дедукция'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
