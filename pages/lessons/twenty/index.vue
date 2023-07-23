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
          to: '/lessons/twenty/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/twenty/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/twenty/reja'
        },
        {
          title: "ALGОRITM TUSHUNCHASI. HISОBLANUVLANCHILIK. PRIMITIV REKURSIV FUNKSIYALAR. QISMAN REKURSIV VA REKURSIV FUNKSIYALAR.",
          icon: '',
          to: '/lessons/twenty/algoritm'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
