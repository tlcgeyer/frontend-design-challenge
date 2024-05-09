<!-- Hi, if you reading this, I chose to make a video comp for section1 instead of just adding in by the homeview. 
    This way it's more organized, and easier to read. -->

<template>
    <div>
        <video src="../assets/UA_Theme_1_DT.mp4"  id="desktopVid" loop autoplay muted height="100%" width="100%">  
          
        </video>
        
        <!-- This is the video for the mobile:  -->
        <!-- <video src="../assets/mobile/UA_Theme_1_MB.mp4" loop autoplay muted height="100%" width="100%"  id="mobileVid"></video> -->

        <!--This is the text overlaying the video, also I typed it out in this manner so that the code can be easier to read and understand.-->
        <div id="text-overlay">
         <h1 class="heading">
          <span style="justify-content: start; display: flex;">CHECK</span>
          <span style="justify-content: start; display: flex;">OUT<span>&nbsp;</span>OUR</span>
          <span style="justify-content: start; display: flex;">LATEST</span>
          <span style="justify-content: start; display: flex;">GEAR</span>
         </h1>
         <br>
         <p class="sentence">
          <span style="justify-content: start; display: flex;">Advanced tech, superior comfort and all</span>
          <span style="justify-content: start; display: flex;">performance is what our latest UA gear is all</span>
          <span style="justify-content: start; display: flex;">about.Built to go further,push hard and break</span>
          <span style="justify-content: start; display: flex;">your boundaries.</span>
        </p>
      
        <button type="button" class="deBtn">Shop UA New Arrivals</button>
       </div>
    </div>
</template>


<style scoped>


.heading{
 font-family: 'Neue Plak Condensed Black' ; 
 font-size: 105px
}


.sentence{
    font-size: 12px;
    font-family: 'Neue Plak Regular';
}


#text-overlay {
  position: absolute;
  top:8%;
  left: 57%;
  color: black;
  width: 250px;
}

#text-overlay .heading {
  line-height: 0.9; 
}

.deBtn{
  background-color: black; 
  color: white; 
  border: none; 
  padding: 15px; 
  font-family:'Neue Plak Regular'; 
  font-size:14px; 
  width: 100%; 
  justify-content: flex-start; 
  align-items: center;
}
/* Actual large devices like like larger desktops */
@media screen and (max-width: 1800px)and (min-width: 1601px) {
  .heading {
    font-size: 80px;
  }
}

/* For the large devices */
@media screen and (max-width: 1600px) and (min-width: 1401px){
  .heading {
    font-size: 70px;
  }
}


/* media query for abit larger devices */
@media screen and (max-width: 1400px)and (min-width:1330px){
  .heading {
      font-size: 60px;
    } 

    .sentence{
    font-size: 12px;
    font-family: 'Neue Plak Regular';
}

  
}

/* Media query for larger desktop devices */
@media screen and (max-width: 1330px) and (min-width: 1200px)  {
  .heading {
      font-size: 53px;
    } 

    .sentence{
    font-size: 11.5px;
    font-family: 'Neue Plak Regular';
}

    video {
      width: 100%;
    }
}


@media screen and (min-width: 1101px) {
  .heading {
    font-size: 60px;
  }


  .sentence{
    font-size: 10px;
    font-family: 'Neue Plak Regular';
}

#text-overlay {
  position: absolute;
  top: 10%;
  left: 57%;
  color: black;
 
}

.deBtn{
  background-color: black; 
  color: white; 
  border: none; 
  padding: 10px; 
  font-family:'Neue Plak Regular'; 
  font-size:14px; 
  width: 70%; 
  justify-content: flex-start; 
  align-items: center;
}

}

/* Media query for medium-sized desktop devices */
@media screen and (max-width: 1100px) and (min-width: 992px) {
  .heading {
      font-size: 40px;
    }

  .sentence{
    font-size: 10px;
    font-family: 'Neue Plak Regular';
}

  #text-overlay {
  position: absolute;
  top: 5.5%;
  left: 57%;
  color: black;
  width: 200px;
}
}

/* Media query for smaller desktop devices */
@media screen and (max-width: 991px) and (min-width: 794px) {
   .heading {
      font-size: 10px;
    }

  .sentence{
    font-size: 10px;
    font-family: 'Neue Plak Regular';
}

  #text-overlay {
  position: absolute;
  top:4%;
  left: 57%;
  color: black;
  width: 200px;
} 
}

/* Media query for tablets and smaller desktop screens */
@media screen and (max-width: 767px) {
  #text-overlay {
    width: 150px;
    left: 50%;
    transform: translateX(-50%);
  }
}
</style>