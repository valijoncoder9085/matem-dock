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
          to: '/lessons/fourteen/reja'
        },
        {
          title: "PREDIKATLAR ALGEBRASI VA UNING FОRMULALARI",
          icon: 'toplam',
          to: '/lessons/fourteen/formula'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/fourteen/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/fourteen/masala'
        },
        {
          title: "Test",
          icon: 'test',
          to: '/lessons/fourteen/formula'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
