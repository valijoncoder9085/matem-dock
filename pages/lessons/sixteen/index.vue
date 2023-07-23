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
          to: '/lessons/sixteen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/sixteen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/sixteen/reja'
        },
        {
          title: "YECHILISH MUAMMОSI. CHEKLI SОHALARDA YECHILISH MUAMMОSI. YОPIQ FОRMULA.",
          icon: '',
          to: '/lessons/sixteen/formula'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
