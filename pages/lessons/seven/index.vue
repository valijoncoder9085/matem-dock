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
          to: '/lessons/seven/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/seven/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: 'reja',
          to: '/lessons/seven/reja'
        },
        {
          title: 'FОRMULALARNING ASОSIY XОSSALARI. FОRMULALARNING CHINLIK TО’PLAMI',
          icon: 'toplam',
          to: '/lessons/seven/formula'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/seven/formula'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
