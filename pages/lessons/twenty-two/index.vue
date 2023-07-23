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
          to: '/lessons/twenty-two/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/twenty-two/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/twenty-two/reja'
        },
        {
          title: "REKURSIV VA REKURSIV SANALUCSHI TО‘PLAMLAR.",
          icon: '',
          to: '/lessons/twenty-two/rekursiv'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
