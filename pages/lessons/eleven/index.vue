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
          to: '/lessons/eleven/reja'
        },
        {
          title: "TO'LIQ VA YOPIQ FUNKSIYALAR SISTEMALARI. POST TEOREMASI",
          icon: 'toplam',
          to: '/lessons/eleven/funksiya'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/eleven/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/eleven/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/eleven'
        },
        {
          title: "TО‘LIQ VA УОPIQ FUNKSIУALAR SISTEMALARI. PОST TEОREMASI",
          icon: 'prezintatsiya',
          to: '/lessons/eleven/TО‘LIQ VA УОPIQ FUNKSIУALAR SISTEMALARI. PОST TEОREMASI'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
