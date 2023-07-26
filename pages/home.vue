<template>
  <div>
    <CardPage :items="items"/>
  </div>
</template>

<script>
import CardPage from "~/components/Card.vue";

export default {
  components: {CardPage},
  data(){
    return{
      items: [
        {
          title: "O'quv meyoriy hujjatlar",
          icon: 'normativ',
          to: '/normativ'
        },
        {
          title: 'Kirish',
          icon: 'kirish',
          to: '/kirish'
        },
        {
          title: "Fan haqida ma'lumot",
          icon: 'fan',
          to: '/fan-haqida'
        },
        {
          title: "Darslar",
          icon: 'dars',
          to: '/lessons'
        },

        {
          title: "Adabiyotlar ro'yxati",
          icon: 'axborot',
          to: '/adabiyotlar'
        },
        {
          title: "Muallif haqida ma'lumot",
          icon: 'mundarija',
          to: '/muallif'
        },
        {
          title: "MUSTAQIL TA’LIM MAVZULARINI O’ZLASHTIRISH BO’YICHA ZARUR USLUBIY KO’RSATMALAR.",
          icon: 'mustaqil',
          to: '/uslub'
        },
        {
          title: "Talabalar bilimini baholash",
          icon: 'bilim',
          to: '/bilim'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
