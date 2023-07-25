<template>
  <div>
    <v-card class="px-3">
      <v-card-subtitle>
        <div class="font-weight-bold text-uppercase text-h5 text-center">
          dars yuzasidan testlar
        </div>
      </v-card-subtitle>
      <v-card-text>
        <v-container fluid>
          <v-radio-group  v-model="radios_value[radio.id - 1]" v-for="(radio, idx) in array" :key="idx">
            <template v-slot:label>
              <div class="font-weight-bold text-h6">{{radio.title}}</div>
            </template>
            <v-radio ripple :value="item.value" v-for="(item, idx) in radio.value_arr" :key="idx">
              <template v-slot:label>
                <div>{{item.value_text}}</div>
              </template>
            </v-radio>
          </v-radio-group>

        </v-container>
      </v-card-text>
      <v-card-actions class="p6-5">
        <v-spacer/>
        <v-btn small @click="click" color="green" rounded dark>
          submit
        </v-btn>
        <v-spacer/>
      </v-card-actions>
    </v-card>
  </div>
</template>

<script>
export default {
  props: {
    radios: {
      type: Array,
      require: false,
      default: []
    }
  },
  data(){
    return{
      radios_value: [],
      array: []
    }
  },
  methods:{
    click(){
      console.log(this.radios_value)
    }
  },
  mounted() {
    this.array = JSON.parse(JSON.stringify(this.$props.radios))
  }
}
</script>

<style lang="scss" scoped>

</style>
