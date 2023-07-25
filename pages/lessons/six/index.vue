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
          to: '/lessons/six/reja'
        },
        {
          title: 'ASОSIУ TENGKUCHLILIKLAR',
          icon: 'toplam',
          to: '/lessons/six/formula'
        },
        {
          title: 'MUSTAQIL ISHLASH UCHUN SAVОLLAR:',
          icon: 'savol',
          to: '/lessons/six/savol'
        },
        {
          title: 'MUAMMОLI MASALA VA TОPSHIRIQLAR:',
          icon: 'masala',
          to: '/lessons/six/masala'
        },
        {
          title: 'Test',
          icon: 'test',
          to: '/lessons/six/test'
        },
        {
          title: 'MUKAMMAL KONYUKTIV NORMAL FORMALAR',
          icon: 'prezintatsiya',
          to: '/lessons/six/MUKAMMAL_KONYUKTIV_NORMAL_FORMALAR'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
