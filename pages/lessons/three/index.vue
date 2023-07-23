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
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR',
          icon: '',
          to: '/lessons/three/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/three/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/three/reja'
        },
        {
          title: 'MULОHAZALAR ALGEBRASI MULОHAZALAR USTIDA AMALLAR',
          icon: '',
          to: '/lessons/three/amallar'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
