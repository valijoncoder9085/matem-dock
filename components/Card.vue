<template>
  <div>
    <v-row class="mt-4">
      <v-col cols="12" md="6" lg="6" sm="12" v-for="(item, idx) in items" :key="'id_'+idx">
        <nuxt-link :to="item.to">
          <div class="card rounded-lg d-flex align-center elevation-1">
            <div class="card_img mr-3">
              <v-img v-if="item.icon !== ''" style="height: 100px; background-position: center; width: 100%" :src="`/img/${item.icon}` + '.jpg'"></v-img>
            </div>
            <span style="color: #66BB6A; font-family:  'Cormorant Garamond', serif" class="text-h7 text-uppercase">
            {{item.title}}
          </span>
          </div>
        </nuxt-link>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "CardPage",
  props:{
    items: {
      type: Array,
      required: true
    }
  },
}
</script>

<style lang="scss" scoped>
.card {
  background-color: whitesmoke;
  min-width: 205px;
  transition: all .5s;
}

.card_img{
  max-width: 120px !important;
  min-height: 120px !important;
  padding: 10px;
}
.card:hover {
  cursor: pointer;
  box-shadow: rgba(0, 0, 0, 0.19) 0 10px 20px, rgba(0, 0, 0, 0.23) 0 6px 6px !important;
  display: flex;
  transform: translateX(20px);
  padding: 5px;
  background-color: rgba(92, 114, 127, 0.73);
  span{
    color:  antiquewhite !important;
  }
}
</style>
