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
          to: '/lessons/fifteen/reja'
        },
        {
          title: "PREDIKATLAR HISОBI AKSIОMALARI.",
          icon: 'toplam',
          to: '/lessons/fifteen/aksioma'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/fifteen/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/fifteen/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/fifteen/test'
        },
        {
          title: "PREDIKATLAR ALGEBRASI VA UNING FОRMULALARI",
          icon: 'prezintatsiya',
          to: '/lessons/fifteen/15'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
