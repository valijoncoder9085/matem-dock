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
          to: '/lessons/twelve/reja'
        },
        {
          title: "MULОHAZALAR HISОBI UCHUN AKSIОMALAR SISTEMASI.",
          icon: 'toplam',
          to: '/lessons/twelve/aksioma'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/twelve/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/twelve/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/twelve'
        },
        {
          title: "Keltirib chiqarish va ISBOT.",
          icon: 'prezintatsiya',
          to: '/lessons/twelve/Keltirib chiqarish va ISBOT.'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
