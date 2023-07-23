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
          title: 'Kirish',
          icon: '',
          to: '/kirish'
        },
        {
          title: 'Mundarija',
          icon: '',
          to: '/mundarija'
        },
        {
          title: "Adabiyotlar ro'yxati",
          icon: '',
          to: '/adabiyotlar'
        },
        {
          title: "Fan haqida ma'lumot",
          icon: '',
          to: '/fan-haqida'
        },
        {
          title: "MUSTAQIL TA’LIM MAVZULARINI O’ZLASHTIRISH BO’YICHA ZARUR USLUBIY KO’RSATMALAR.",
          icon: '',
          to: '/uslub'
        },
        {
          title: "Darslar",
          icon: '',
          to: '/lessons'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
