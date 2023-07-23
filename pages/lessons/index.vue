<template>
  <div>
    <CardPage :items="item"/>
  </div>
</template>

<script>
import CardPage from "~/components/Card.vue";

export default {
  components: {CardPage},
  data(){
    return{
      item: [
        {
          title: '1',
          icon: '',
          to: '/lessons/one'
        },
        {
          title: '2',
          icon: '',
          to: '/lessons/two'
        },
        {
          title: "3",
          icon: '',
          to: '/lessons/three'
        },
        {
          title: "4",
          icon: '',
          to: '/lessons/four'
        },
        {
          title: "5",
          icon: '',
          to: '/lessons/five'
        },
        {
          title: "6",
          icon: '',
          to: '/lessons/six'
        },
        {
          title: "7",
          icon: '',
          to: '/lessons/seven'
        },
        {
          title: "8",
          icon: '',
          to: '/lessons/eight'
        },
        {
          title: "9",
          icon: '',
          to: '/lessons/nine'
        },
        {
          title: "10",
          icon: '',
          to: '/lessons/ten'
        },
        {
          title: "11",
          icon: '',
          to: '/lessons/eleven'
        },
        {
          title: "12",
          icon: '',
          to: '/lessons/twelve'
        },
        {
          title: "13",
          icon: '',
          to: '/lessons/thirteen'
        },
        {
          title: "14",
          icon: '',
          to: '/lessons/fourteen'
        },
        {
          title: "15",
          icon: '',
          to: '/lessons/fifteen'
        },
        {
          title: "16",
          icon: '',
          to: '/lessons/sixteen'
        },
        {
          title: "17",
          icon: '',
          to: '/lessons/seventeen'
        },
        {
          title: "18",
          icon: '',
          to: '/lessons/eighteen'
        },
        {
          title: "19",
          icon: '',
          to: '/lessons/nineteen'
        },{
          title: "20",
          icon: '',
          to: '/lessons/twenty'
        },{
          title: "21",
          icon: '',
          to: '/lessons/twenty-one'
        },
        {
          title: "22",
          icon: '',
          to: '/lessons/twenty-two'
        },

      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
