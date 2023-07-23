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
          to: '/lessons/seventeen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/seventeen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/seventeen/reja'
        },
        {
          title: "KОMBINATОRIKA ASОSLARI. О‘RIN ALMASHTIRISHLAR VA KОMBINATSIYALAR.",
          icon: '',
          to: '/lessons/seventeen/kombinatsiya'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
