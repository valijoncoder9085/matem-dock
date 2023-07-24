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
          to: '/lessons/seventeen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/seventeen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: 'reja',
          to: '/lessons/seventeen/reja'
        },
        {
          title: "KОMBINATОRIKA ASОSLARI. О‘RIN ALMASHTIRISHLAR VA KОMBINATSIYALAR.",
          icon: 'toplam',
          to: '/lessons/seventeen/kombinatsiya'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/seventeen/kombinatsiya'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
