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
          to: '/lessons/fourteen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/fourteen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/fourteen/reja'
        },
        {
          title: "PREDIKATLAR ALGEBRASI VA UNING FОRMULALARI",
          icon: '',
          to: '/lessons/fourteen/formula'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
