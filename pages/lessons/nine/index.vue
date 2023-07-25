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
          to: '/lessons/nine/reja'
        },
        {
          title: "BUL FUNKSIYALARINI О‘ZGARUVCHILAR BО‘YICHA YОYILMASI. MDNSH VA MKNSH",
          icon: 'toplam',
          to: '/lessons/nine/funksiya'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/nine/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/nine/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/nine/test'
        },
        {
          title: "Bul funksiyalarini o'zgaruvchilar bo'yicha yoyilmasi.",
          icon: 'prezintatsiya',
          to: '/lessons/nine/бул ф.я. узгарув'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
