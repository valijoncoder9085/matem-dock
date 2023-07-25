<template>
  <div>
    <Test :radios="radios"/>
  </div>
</template>

<script>
export default {
  data(){
    return{
      radios: [
        {
          id: 1,
          title: "1) Quyidagi belgilar ketma-ketliklarining qaysi biri formula bo‘ladi?" ,
          value_arr: [
            {
              value: 1,
              value_text: '((B->(A/\\C))/\\-(A\\/C))'
            },
            {
              value: 2,
              value_text: '(A->\\/(B/\\C))'
            },
            {
              value: 3,
              value_text: '-(->B\\/C)/\\A,D)'
            },
            {
              value: 4,
              value_text: '(-(A->B)\\/-C))'
            }
          ]
        },
        {
          id: 2,
          title: "2) Quyidagi belgilar ketma-ketliklarining qaysi biri formula bo‘lmaydi?",
          value_arr: [
            {
              value: 1,
              value_text: '{0,2,3,4,5}'
            },
            {
              value: 2,
              value_text: '{4,5}'
            },
            {
              value: 3,
              value_text: 'Ø'
            },
            {
              value: 4,
              value_text: '{0,2,3,4,5,6,7,8,9}'
            }
          ]
        },
        {
          id: 3,
          title: "3) F=(A->B)->(-B->-A) formulaning barcha qism formulalarini yozing.",
          value_arr: [
            {
              value: 1,
              value_text: '{0,2,3}'
            },
            {
              value: 2,
              value_text: '{1}'
            },
            {
              value: 3,
              value_text: '{1,2,3}'
            },
            {
              value: 4,
              value_text: '{2,3,4,5}'
            }
          ]
        },
        {
          id: 4,
          title: "4) F=(((A\\/B/\\-C)-(A/\\B)) formulaning barcha qism formulalarini yozing.",
          value_arr: [
            {
              value: 1,
              value_text: '{2}'
            },
            {
              value: 2,
              value_text: '{6,7,8,9,}'
            },
            {
              value: 3,
              value_text: '(A->B),(-B->-A)'
            },
            {
              value: 4,
              value_text: 'A,B'
            }
          ]
        },
        {
          id: 5,
          title: "5) Qaysi tenglik munosabati o‘rinli?",
          value_arr: [
            {
              value: 1,
              value_text: 'x=x/x'
            },
            {
              value: 2,
              value_text: 'x=x->y'
            },
            {
              value: 3,
              value_text: 'x=x+x'
            },
            {
              value: 4,
              value_text: 'x=x+y'
            }
          ]
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
