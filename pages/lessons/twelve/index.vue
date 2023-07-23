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
          to: '/lessons/twelve/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/twelve/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/twelve/reja'
        },
        {
          title: "MULОHAZALAR HISОBI UCHUN AKSIОMALAR SISTEMASI.",
          icon: '',
          to: '/lessons/twelve/aksioma'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
