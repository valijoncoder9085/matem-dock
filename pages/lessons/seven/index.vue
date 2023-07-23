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
          to: '/lessons/seven/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/seven/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/seven/reja'
        },
        {
          title: 'FОRMULALARNING ASОSIY XОSSALARI. FОRMULALARNING CHINLIK TО’PLAMI',
          icon: '',
          to: '/lessons/seven/formula'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
