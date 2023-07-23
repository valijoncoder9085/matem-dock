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
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR',
          icon: '',
          to: '/lessons/two/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/two/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/two/reja'
        },
        {
          title: 'MUNОSABATLAR. BINAR MUNОSABAT. EKVIVALENTLIK MUNОSABATI. TARTIBLASH MUNОSABATI',
          icon: '',
          to: '/lessons/two/binar'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
