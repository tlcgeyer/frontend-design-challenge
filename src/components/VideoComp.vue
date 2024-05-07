<!-- Hi, if you reading this, I chose to make a video comp for section1 instead of just adding in by the homeview. 
    This way it's more organized, and easier to read. -->

<template>
    <div>
        <video src="../assets/UA_Theme_1_DT.mp4" loop autoplay muted height="100%" width="100%">  
        </video>
        
        <!-- overlaying text -->
        <div id="text-overlay">
          <h2 style="font-family: 'Neue Plak' ; font-size: 80px;">CHECK <br> OUR <br>LATEST <br> GEAR</h2>
          <h4 class="sentence">Advanced tech, superior comfort and all <br>performance is what our latest UA gear is all <br> about.Built to go further,push hard and break <br> your boundaries.</h4>
          <button type="button" style="background-color: black; color: white; border: none; padding: 20px; font-family: 'Neue Plak'; font-size:14px;">Shop UA New Arrivals</button>
       </div>


    </div>
</template>


<style scoped>
.sentence{
    font-size: 12px;
    font-family: 'Neue Plak';
}

#text-overlay {
  position: absolute;
  top:5%;
  left: 50%;
  color: black;
  text-align: center;
  width: 250px;
}
</style>