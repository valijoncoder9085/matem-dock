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
          to: '/lessons/thirteen/masala'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: '',
          to: '/lessons/thirteen/savol'
        },
        {
          title: 'Reja va tayanch iboralar',
          icon: '',
          to: '/lessons/thirteen/reja'
        },
        {
          title: "L NAZARIУA UCHUN GУОDELNING TО‘LIQLIK HAQIDAGI TEОREMASI.",
          icon: '',
          to: '/lessons/thirteen/teorea'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>

</style>
