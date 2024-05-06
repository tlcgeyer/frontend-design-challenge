<!-- Hi, if you reading this, I chose to make a video comp for section1 instead of just adding in by the homeview. 
    This way it's more organized, and easier to read. -->

<template>
    <div>
        <video src="../assets/UA_Theme_1_DT.mp4" loop autoplay muted height="100%" width="100%">
        </video>
        
        <!-- overlaying text -->
        <div class="text-overlay">
          <h2 style="font-family: 'Neue Plak' ; font-size: 105px;">{{ overlayText }}</h2>
          <h4 class="sentence">{{ sentencePara }}</h4>
          <button type="button" style="background-color: black; color: white; border: none; padding: 20px; font-family: 'Neue Plak; font-size:14px;">Shop UA New Arrivals</button>
       </div>


    </div>
</template>


<script>
export default {
  data() {
    return {
      videoSource: '../../assets/UA_Theme_1_DT.mp4',
      overlayText: 'CHECK OUR LATEST GEAR',
      sentencePara: 'Advanced tech, superior comfort and all performance is what our latest UA gear is all about.Built to go further,push hard and break your boundaries.'
    };
  },
};
</script>

<style scoped>


.sentence{
    font-size: 12px;
    font-weight: 200;
}

.text-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: black;
  text-align: center;

}
</style>