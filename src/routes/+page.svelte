<script>

import { base } from "$app/paths";

</script>

<body>
    <header class ='v-header container'>
        <div class='fullscreen-video-wrap'>
            <video muted="muted" loop="loop" autoplay="autoplay">
                <source src="{base}/footage/optimise.webm" type="video/webm" />
            </video>
        </div>
        <div class="header-overlay"></div>
        <div class="header-content">
            <div class='title-l1'>CRYSTAL PVP</div>
            <div class='title-l2'>explained like a</div>
            <div class='title-l3'>Fighting Game</div>
        </div>
    </header>

    <section class='section filler-bar'>

    </section>



</body>


<style>

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    overflow-x: hidden;
}

.v-header {
    height: 100vh;
    display: flex;
}

/* .container {
} */

.fullscreen-video-wrap {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100vh;
    overflow: hidden;
}

.fullscreen-video-wrap video {
    min-width: 100%;
    min-height: 100%;
    filter: brightness(100%)

}

.header-overlay {
    height:100vh;
    width: 100vw;
    position: absolute;
    top: 0;
    left: 0;
    background: #000000;
    opacity: 80%;

}

.header-content {
    z-index: 2;
    width: 100%;
    padding-right: 100px;
}


.section{ 
    padding:500px 0;
    background-color: black;
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
  padding-left: 34.5%;
  font-family: 'THICCBOI-Thin';
}

.title-l3 {
  font-size: 1200%;
  color: #e03333;
  padding-left: 41%;
  font-family: 'Makcex';
}



</style>