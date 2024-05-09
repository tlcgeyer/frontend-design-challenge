<template>
  <div>
    <VideoComp/>
  </div>
  <div class="section2">
    <div class="text-content">
      <p style="font-size: 24px; font-family: 'Neue Plak Bold'; margin-bottom: 10px;">Our best gear</p>
      <p style="font-size: 14px; font-family: 'Neue Plak Regular'; margin-bottom: 20px;">Unlock your     potential with the best UA Gear</p>
    </div>

    <div class="row">
      <div class="col">
        <img src="../assets/other/Train.jpg" alt="training"> <br><br>
        <p style="text-decoration: underline; font-size: 14px; font-family: 'Neue Plak SemiBold'; margin-right: 250px;" >Shop now</p>
      </div>

      <div class="col">
        <img src="../assets//other/Run.jpg" alt="run"><br><br>
        <p style="text-decoration: underline;  font-size: 14px; font-family: 'Neue Plak SemiBold'; margin-right: 250px;">Shop now</p>
      </div>

      <div class="col">
        <img src="../assets/other/Golf.jpg" alt="golf"><br><br>
        <p style="text-decoration: underline;  font-size: 14px; font-family: 'Neue Plak SemiBold'; margin-right: 250px;">Shop now</p>
      </div>

      <div class="col">
        <img src="../assets/other/Accessories.jpg" alt="accessories"><br><br>
        <p style="text-decoration: underline;  font-size: 14px; font-family: 'Neue Plak SemiBold'; margin-right: 250px;">Shop now</p>
      </div>
    </div>
  </div>
  <div class="section3">
    <div class="image-container">
     <img src="../assets/other/UA_Theme_2_DT.jpg" alt="theRockisCooking">
    </div>

    <!-- The text overlaying sections 3 image-->
    <div class="text-overlay2">
         <p style="font-size: 16px; font-family: 'Neue Plak Bold';">
          <span style="justify-content: start; display: flex;">Project Rock</span>
        </p> 

         <p style="font-size: 64px; font-family: 'Neue Plak Condensed Black'; line-height: 0.9; ">EVERYSIDE SIDE<br>
          <span style="  justify-content: start; display: flex;">OF &nbsp;STRONG</span>
        </p>
            <br>
         <p style="font-size: 14px; font-family: 'Neue Plak Regular';">The Underground collection is inspired by the idea of a <br>
         <span style="justify-content: start; display: flex;">Project Rock  fight club.A place where we push each</span>
         <span style="justify-content: start; display: flex;">other harder to make each other stronger. A drop</span>
         <span style="justify-content: start; display: flex;">dedicated to you and your crew. The neon colourways</span>
         <span style="justify-content: start; display: flex;">are a reflection of the energy we bring to every rep,</span>
         <span style="justify-content: start; display: flex;">every set and every challenge.</span></p>
         <br>
          <button type="button" class="rockbtn">Shop Project Rock</button>
    </div>

  </div>
  <div class="section4">
    <div class="text-content">
      <p style="font-size: 24px; font-family: 'Neue Plak Bold';  margin-bottom: 10px;">Discover our latest promotions</p>
      <p style="font-size: 14px; font-family: 'Neue Plak Regular';  margin-bottom: 20px;">Get the best deals on the best gear.</p>
    </div>
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
  <div class="section5">
   <div class="text-content">
    <p style="font-size: 24px; font-family: 'Neue Plak Bold';  margin-bottom: 10px;">What's happening on Instagram</p>
    <p style="font-size: 14px; font-family: 'Neue Plak Regular'; margin-bottom: 20px;">Don't miss out on the latest news and updates from Under Armour.</p>
   </div>
    
    <div class="section6">
        <video src="../assets/other/ig_video.mp4" loop autoplay muted width="920px" style="
          margin-left: 2.5%;"></video>

      
      <div class="images">
       <div class="image-block">
        <img src="../assets/other/IG Image 2_DT.jpg" alt="deRock">
       </div>
       <div class="image-block">
        <img src="../assets/other/IG Image 3_DT.jpg" alt="brainedDude">
       </div>
       <div class="image-block">
        <img src="../assets/other/IG Image 4_DT.jpg" alt="womanRunning">
       </div>
       <div class="image-block">
        <img src="../assets/other/IG Image 5_DT.jpg" alt="deRock2">
       </div>
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

/*---------------------------- SECTION 2:------------------------  */
.section2{
  display: block;
  padding: 60px;
  align-items: flex-start;
}

.text-content {
  margin-left: 2.5%;
}

.text-content p {
  margin: 0;
}

.row {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.col {
  flex: 0 0 calc(25% - 20px); 
  max-width: calc(25% - 20px); 
  margin-bottom: 20px; 
  text-align: center;
}

img[alt="training"]{
  width: 314px;
  height: 313px;
  top: 1100px;
  left: 317px;
}

img[alt="run"] {
  width: 314px;
  height: 313px;
  top: 1100px;
  left: 643px;
}

img[alt="golf"]{
  width: 314px;
  height: 313px;
  top: 1100px;
  left: 967px;
}

img[alt="accessories"]{
  width: 314px;
 height: 313px;
 top: 1100px;
 left: 1294px;
}

/*---------------------------- SECTION 3:------------------------  */
.section3{
  display: block;
  padding: 60px;
}

.image-container {
  width: 95%;
  margin: 0 auto;
  text-align: center;
}

.image-container img {
  max-width: 100%; 
  height: auto; 
}


.text-overlay2 {
  color: white;
  position: absolute;
  top:115%;
  left: 67%;
  letter-spacing: 1px
}


.rockbtn{
  font-size: 16px;
  background-color: transparent;
  color: white;
  border-radius: 4px;
  border-color: white;
  padding: 18px;
  font-family: 'Neue Plak Regular';
  width: 68%; 
  justify-content: flex-start; 
  align-items: center;
}

/*---------------------------- SECTION 4:------------------------  */
.section4{
  display: block;
  padding: 60px;
}

/*---------------------------- SECTION 5:------------------------  */
.section5{
  display: block;
  padding: 60px;
}
 img[alt="deRock"] {
  width: 350px;
  position:absolute;
  height: 530px;
  top: 213.3%;
  left: 55%;
 }

 img[alt="brainedDude"] {
  width: 350px;
  position:absolute;
  height: 530px;
  top: 213.3%;
  left: 77.5%;
 }
 img[alt="womanRunning"] {
  width: 350px;
  position:absolute;
  height: 600px;
  top: 255%;
  left: 55%;
 }
 img[alt="deRock2"] {
  width: 350px;
  position:absolute;
  height: 600px;
  top: 255%;
  left: 76.5%;
 }




</style>