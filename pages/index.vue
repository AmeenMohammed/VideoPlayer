<template>
  <div class="container">
    <div>
      <h1 class="title">
        Video Display
      </h1>
      <div class="video-player">
          <iframe
            class="video-frame"
            frameborder="0" type="text/html"
            src="https://www.dailymotion.com/embed/video/xwr14q"
            width="100%"
            height="100%"
            allowfullscreen >
        </iframe>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.video-player{
  position:relative;
  padding-bottom:56.25%;
  height:0;
  overflow:hidden;
  margin-top:15px;
  margin-bottom:15px;
}
.video-frame{
  width:100%;
  height:100%;
  position:absolute;
  left:0px;
  top:0px;
  overflow:hidden;
}

</style>
