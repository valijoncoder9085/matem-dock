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
          to: '/lessons/ten/reja'
        },
        {
          title: "JEGALKIN KO'PHADI. MONOTON BUL FUNKSIYALARI",
          icon: 'toplam',
          to: '/lessons/ten/funksiya'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/ten/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/ten/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/ten/funksiya'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
