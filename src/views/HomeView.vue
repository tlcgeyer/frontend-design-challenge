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
  <div class="section3">
    <img src="../assets/other/UA_Theme_2_DT.jpg" alt="theROckisCooking" style="width:90%; display: block; margin: 0 auto; text-align: center;">
    <!-- overlaying text 2 -->
    <div class="text-overlay2">
         <p style="font-size: 16px;">Project Rock</p> 
         <p style="font-size: 64px;">EVERYSIDE SIDE <br>OF STRONG</p>
         <p style="font-size: 14px;">The Underground collection is inspired by the idea of a <br> Project Rock  fight club. 
        A place where we push each <br>other harder to make each other stronger. A drop <br>dedicated to you and your crew. The neon colourways <br>are a reflection of the energy we bring to every rep, <br> every set and every challenge.</p>
        <button type="button" class="rockbtn">Shop Project Rock</button>
    </div>

  </div>
  <div class="section4">
    <p style="font-size: 24px; font-weight: bold;">Discover our latest promotions</p>
    <p style="font-size: 14px;">Get the best deals on the best gear.</p>
    <div class="row">
      <div class="col">
        <img src="../assets/other/Promo 1.jpg" alt="promo1">
      </div>
      <div class="col">
        <img src="../assets/other/Promo 2.jpg" alt="promo2">
      </div>
      <div class="col">
        <img src="../assets/other/Promo 3.jpg" alt="promo3">
      </div>
      <div class="col">
        <img src="../assets/other/Promo 4.jpg" alt="promo4">
      </div>
    </div>
  </div>
  <br><br><br><br>
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

.section3{
  display: block;
  justify-content: space-between;
  padding: 60px;
}

.text-overlay2 {
  color: white;
  position: absolute;
  top:170%;
  left: 60%;
  text-align: center;
}

.rockbtn{
  font-size: 16px;
  background-color: transparent;
  color: white;
  border-radius: 4px;
  border-color: white;
  padding: 14px;
}

.section4{
  display: block;
  justify-content: space-between;
  padding: 60px;
}

</style>