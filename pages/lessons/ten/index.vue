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
          to: '/lessons/ten/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/ten/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/ten/reja'
        },
        {
          title: "JEGALKIN KO'PHADI. MONOTON BUL FUNKSIYALARI",
          icon: '',
          to: '/lessons/ten/funksiya'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
