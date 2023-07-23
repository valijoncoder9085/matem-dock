<template>
  <div>
    <SidebarComponent/>
  </div>
</template>

<script>
import SidebarComponent from "~/components/Sidebar.vue";

export default {
  name: 'DefaultLayout',
  components: {SidebarComponent},
  data () {
    return{

    }
  }
}
</script>
<style lang="scss">
.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s ease;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
}
</style>
