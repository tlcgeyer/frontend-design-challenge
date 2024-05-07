<template>
  <div>
    <VideoComp/>
  </div>
  <div class="section2">
    <p style="font-size: 24px; font-weight: bold;">Our best gear</p>
    <p style="font-size: 14px;">Unlock your potential with the best UA Gear</p>
    <div class="row">
      <div class="col">
        <img src="../assets/other/Train.jpg" style="width: 300px;" alt="training"><br>
        <p style="text-decoration: underline; font-size: 14px;" >Shop now</p>
      </div>

      <div class="col">
        <img src="../assets//other/Run.jpg" style="width: 300px;" alt="run">
        <p style="text-decoration: underline;  font-size: 14px;">Shop now</p>
      </div>

      <div class="col">
        <img src="../assets/other/Golf.jpg" style="width: 300px;" alt="golf">
        <p style="text-decoration: underline;  font-size: 14px;">Shop now</p>
      </div>

      <div class="col">
        <img src="../assets/other/Accessories.jpg" style="width: 300px;" alt="accessories">
        <p style="text-decoration: underline;  font-size: 14px;">Shop now</p>
      </div>
    </div>
  </div>
</template>

<script>
import VideoComp from '../components/VideoComp.vue'

export default {
  components: {
   VideoComp
  } 

}
</script>

<style scoped>

.section2{
  display: block;
  justify-content: space-between;
  padding: 60px;

}

</style>