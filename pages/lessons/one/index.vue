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
          to: '/lessons/one/reja'
        },
        {
          title: 'TО‘PLAMLAR NAZARIУASI.',
          icon: 'toplam',
          to: '/lessons/one/nazariya'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/one/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR',
          icon: 'masala',
          to: '/lessons/one/masala'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/one'
        },
        {
          title: 'Diskret matematika va matematika matiq',
          icon: 'prezintatsiya',
          to: '/lessons/one/1'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
