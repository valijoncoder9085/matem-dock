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
          to: '/lessons/one/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/one/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/one/reja'
        },
        {
          title: 'TО‘PLAMLAR NAZARIУASI.',
          icon: '',
          to: '/lessons/one/nazariya'
        },
        {
          title: 'Test',
          icon: '',
          to: '/lessons/one/test'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
