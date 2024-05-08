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
/* @media screen and (min-width: 1920px) {
    Hide the mobile video
    #mobileVid {
        display: none;
    }
} */


/* 
@media screen and (max-width: 393px) {
    #text-overlay {
        position: relative; /* Change to relative positioning 
        top: auto;
        left: auto;
        transform: none;
    }
    
    #desktopVid {
        display: none;
    }
    
    Display the second video 
    #mobileVid {
        display: contents;
        width: 100%;
        height: auto;
    }
  
} */

</style>