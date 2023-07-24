<template>
  <div>
   <CardPage :items="items"/>
  </div>
</template>

<script>
import CardPage from "@/components/Card.vue";

export default {
  components: {CardPage,},
  data(){
    return{
      items: [
        {
          title: "Majmua",
          icon: 'mundarija',
          to: '/majmua'
        },
        {
          title: "Ishchi dastur",
          icon: 'mustaqil',
          to: '/dastur'
        },
        {
          title: "Namunaviy dastur",
          icon: 'kirish',
          to: '/ndastur'
        },
        {
          title: "Axborot tizimlari va texnologiyalari",
          icon: 'axborot',
          to: '/axborot'
        },
        {
          title: "Kompyuter ilmlari va dasturlash texnologiyalari",
          icon: 'fan',
          to: '/kompyuter'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
