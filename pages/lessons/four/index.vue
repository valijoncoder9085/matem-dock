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
          to: '/lessons/four/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/four/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/four/reja'
        },
        {
          title: 'FОRMULALAR. TENGKUCHLI FОRMULALAR',
          icon: '',
          to: '/lessons/four/formula'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
