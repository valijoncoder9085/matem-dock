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
          to: '/lessons/eight/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/eight/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/eight/reja'
        },
        {
          title: 'Mulohazalar algebrasi funksiyalari (BUL funksiyasi)',
          icon: '',
          to: '/lessons/eight/funksiya'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
