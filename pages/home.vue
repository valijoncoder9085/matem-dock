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
          title: "Normativ Hujjatlar",
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
          title: 'Mundarija',
          icon: 'mundarija',
          to: '/mundarija'
        },
        {
          title: "Adabiyotlar ro'yxati",
          icon: 'axborot',
          to: '/adabiyotlar'
        },
        {
          title: "Darslar",
          icon: 'dars',
          to: '/lessons'
        },
        {
          title: "MUSTAQIL TA’LIM MAVZULARINI O’ZLASHTIRISH BO’YICHA ZARUR USLUBIY KO’RSATMALAR.",
          icon: 'mustaqil',
          to: '/uslub'
        },



      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
