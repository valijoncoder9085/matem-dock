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
          to: '/lessons/nine/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/nine/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/nine/reja'
        },
        {
          title: "BUL FUNKSIYALARINI О‘ZGARUVCHILAR BО‘YICHA YОYILMASI. MDNSH VA MKNSH",
          icon: '',
          to: '/lessons/nine/funksiya'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
