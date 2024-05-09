<!-- Hi, if you reading this, I chose to make a video comp for section1 instead of just adding in by the homeview. 
    This way it's more organized, and easier to read. -->

<template>
    <div>
        <video class="desktopVid"  src="../assets/UA_Theme_1_DT.mp4" loop autoplay muted height="100%" width="100%">  
          
        </video>
        
        <!-- This is the video for the mobile:  -->
         <video class="mobileVid" src="../assets/mobile/UA_Theme_1_MB.mp4" loop autoplay muted></video> 

        <!--This is the text overlaying the video, also I typed it out in this manner so that the code can be easier to read and understand. -->
        <div id="text-overlay">
         <h1 class="heading">
          <span style="justify-content: start; display: flex;">CHECK</span>
          <span style="justify-content: start; display: flex;">OUT<span>&nbsp;</span>OUR</span>
          <span style="justify-content: start; display: flex;">LATEST</span>
          <span style="justify-content: start; display: flex;">GEAR</span>
         </h1> 
         <p class="subHeading">CHECK OUT OUR<br> <span>LATEST GEAR</span></p>
         <br>
         
         <h2 class="sentence">
          <span style="justify-content: start; display: flex;">Advanced tech, superior comfort and all</span>
          <span style="justify-content: start; display: flex;">performance is what our latest UA gear is all</span>
          <span style="justify-content: start; display: flex;">about.Built to go further,push hard and break</span>
          <span style="justify-content: start; display: flex;">your boundaries.</span>
        </h2> 
        <p class="subPara">Advanced tech, superior comfort and all performance is what our latest UA gear is all about.Built to go further,push hard and break your boundaries.</p>
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

/* For a montior */

@media screen and (max-width: 2048px)and (min-width: 1920px) {
  .heading {
    font-size: 80px;
  }
.sentence {
  font-size: 20px
}
  .mobileVid {
    display: none;
  }

  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
  }
  .deBtn{
  background-color: black; 
  color: white; 
  border: none; 
  margin-top: 15px;
  padding: 20px; 
  font-family:'Neue Plak Regular'; 
  font-size:14px; 
  width: 100%; 
  justify-content: flex-start; 
  align-items: center;
}

}


@media screen and (max-width: 1920px)and (min-width: 1801px) {
  .heading {
    font-size: 80px;
  }
.sentence {
  font-size: 20px
}
  .mobileVid {
    display: none;
  }

  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
  }
}





/* Actual large devices like like larger desktops */
@media screen and (max-width: 1800px)and (min-width: 1601px) {
  .heading {
    font-size: 80px;
  }
.sentence {
  font-size: 20px
}
  .mobileVid {
    display: none;
  }

  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
  }
}

/* For the large devices */
@media screen and (max-width: 1600px) and (min-width: 1401px){
  .heading {
    font-size: 70px;
  }
  .mobileVid {
    display: none;
  }

  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
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
.mobileVid {
    display: none;
  }
  
  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
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

.mobileVid {
    display: none;
  }

  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
  }

}

@media screen and (max-width:1200) and (min-width: 1101px) {
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

.mobileVid {
    display: none;
  }


  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
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
.mobileVid {
    display: none;
  }


  .subHeading{
    display: none;
  }

  .subPara{
    display: none;
  }

}

/* Media query for smaller desktop devices */
@media screen and (max-width: 991px) and (min-width: 768px) {
   .heading {
      font-size: 30px;
    }

  .sentence{
    font-size: 8px;
    font-family: 'Neue Plak Regular';
}

  #text-overlay {
  position: absolute;
  top:6%;
  left: 57%;
  color: black;
  width: 200px;
} 
.mobileVid {
    display: none;
  }

  .deBtn{
  background-color: black; 
  color: white; 
  border: none; 
  padding: 7px; 
  font-family:'Neue Plak Regular'; 
  font-size:10px; 
  width: 70%; 
  justify-content: flex-start; 
  align-items: center;
}

.subHeading{
    display: none;
  }

  .subPara{
    display: none;
  }

}

/* Media query for mobile devicess*/
@media screen and (max-width: 430px) and (min-width: 300px){  
  .desktopVid{
    display: none;
  }
  
 .mobileVid{
  width:100%
 }

 #text-overlay {
  position: static;
  top:8%;
  margin-left: 10%;
  color: black;
  width: 250px;
}

.heading {
  display: none;
}

.sentence {
  display: none;
}

.subHeading{
  margin-top: 20px;
 font-family: 'Neue Plak Condensed Black' ; 
 font-size: 48px;
 letter-spacing: normal;
}


.subPara{
    font-size: 14px;
    font-family: 'Neue Plak Regular';
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

#text-overlay .subHeading {
  line-height: 0.8; 
}

}
</style>