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
          to: '/lessons/eight/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/eight/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: 'reja',
          to: '/lessons/eight/reja'
        },
        {
          title: 'Mulohazalar algebrasi funksiyalari (BUL funksiyasi)',
          icon: 'toplam',
          to: '/lessons/eight/funksiya'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/eight'
        },
        {
          title: 'Бул FUNKSIYALARNI FORMULALAR KORINISHIDA IFODALASH',
          icon: 'prezintatsiya',
          to: '/lessons/eight/Бул FUNKSIYALARNI FORMULALAR KORINISHIDA IFODALASH'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
