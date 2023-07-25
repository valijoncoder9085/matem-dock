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
          to: '/lessons/sixteen/reja'
        },
        {
          title: "YECHILISH MUAMMОSI. CHEKLI SОHALARDA YECHILISH MUAMMОSI. YОPIQ FОRMULA.",
          icon: 'toplam',
          to: '/lessons/sixteen/formula'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/sixteen/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/sixteen/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/sixteen'
        },
        {
          title: "PREDIKATLAR HISOBI AKSIOMALAR",
          icon: 'prezintatsiya',
          to: '/lessons/sixteen/16'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
