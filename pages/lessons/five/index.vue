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
          to: '/lessons/five/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/five/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/five/reja'
        },
        {
          title: 'ASОSIУ TENGKUCHLILIKLAR',
          icon: '',
          to: '/lessons/five/tengkuch'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
