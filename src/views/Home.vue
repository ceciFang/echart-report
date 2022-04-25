<template>
  <div class="home">
    <top-view/>
    <sales-view/>
    <bottom-view/>
    <map-view/>
  </div>
</template>
<script>
// @ is an alias to /src
import BottomView from '../components/BottomView/index.vue'
import mapView from '../components/mapView/index.vue'
import SalesView from '../components/SalesView/index.vue'
import TopView from '../components/TopView/inde.vue'
export default {
  name: 'Home',
  components: {
    TopView,
    SalesView,
    mapView,
    BottomView
  }
}
</script>
<style>
.home{
  width: 100%;
  height: 100%;
  padding: 20px;
  background: #eee;
}

</style>
