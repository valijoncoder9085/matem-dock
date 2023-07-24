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
          to: '/lessons/twenty/reja'
        },
        {
          title: "ALGОRITM TUSHUNCHASI. HISОBLANUVLANCHILIK. PRIMITIV REKURSIV FUNKSIYALAR. QISMAN REKURSIV VA REKURSIV FUNKSIYALAR.",
          icon: 'toplam',
          to: '/lessons/twenty/algoritm'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/twenty/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/twenty/masala'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/twenty/reja'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
