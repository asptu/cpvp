<script>
  import { base } from "$app/paths";
</script>


<div class='container'>
  <div class='title-l1'>CRYSTAL PVP</div>
  <div class='title-l2'>explained like a</div>
  <div class='title-l3'>Fighting Game</div>
</div>

<video class='bg' width="1280" height="720" muted="muted" loop="loop" autoplay="autoplay">
  <source type="video/mp4" src="/cpvp/footage/h264.mp4">
</video>


<style>

.bg {
  position: fixed;
    width: 100%;
    height: 108.38vh;
    left: 0;
    top: 0;
    z-index: -1;
    filter: brightness(20%);
}


.title-l1 {
  font-size: 900%;
  color: #ea5180;
  padding-left: 25%;
  padding-top: 15%;
  font-family: 'THICCBOI-ExtraBold';
}

.title-l2 {
  font-size: 500%;
  color: #ffffff;
  padding-left: 35%;
  font-family: 'THICCBOI-Thin';
}

.title-l3 {
  font-size: 1200%;
  color: #e03333;
  padding-left: 45%;
  font-family: 'Makcex';
}

@font-face {
  font-family: 'THICCBOI-ExtraBold';
  src: URL('/cpvp/fonts/THICCCBOI-ExtraBold.ttf') format('truetype');
}

@font-face {
  font-family: 'THICCBOI-Thin';
  src: URL('/cpvp/fonts/THICCCBOI-Thin.ttf') format('truetype');
}

@font-face {
  font-family: 'Makcex';
  src: URL('/cpvp/fonts/Makcex.otf') format('truetype');
}



</style>