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
          to: '/lessons/eleven/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/eleven/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/eleven/reja'
        },
        {
          title: "TO'LIQ VA YOPIQ FUNKSIYALAR SISTEMALARI. POST TEOREMASI",
          icon: '',
          to: '/lessons/eleven/funksiya'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
