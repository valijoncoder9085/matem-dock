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
          to: '/lessons/fifteen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/fifteen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/fifteen/reja'
        },
        {
          title: "PREDIKATLAR HISОBI AKSIОMALARI.",
          icon: '',
          to: '/lessons/fifteen/aksioma'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
