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
          to: '/lessons/three/reja'
        },
        {
          title: 'MULОHAZALAR ALGEBRASI MULОHAZALAR USTIDA AMALLAR',
          icon: 'toplam',
          to: '/lessons/three/amallar'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/three/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR',
          icon: 'masala',
          to: '/lessons/three/masala'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/three/test'
        },
        {
          title: 'Mulohazalar algebrasi',
          icon: 'prezintatsiya',
          to: '/lessons/three/3'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
