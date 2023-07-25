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
          to: '/lessons/five/reja'
        },
        {
          title: 'ASОSIУ TENGKUCHLILIKLAR',
          icon: 'toplam',
          to: '/lessons/five/tengkuch'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/five/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/five/masala'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/five'
        },
        {
          title: 'Asosiy teng kuchliliklar',
          icon: 'prezintatsiya',
          to: '/lessons/five/Асосий тенгкучлиликлар'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
