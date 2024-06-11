<template>
    <div>
      <h1>Nuxt 3 Video.js Player</h1>
      <!-- <VideoJsPlayer videoSrc="https://s3.us-west-1.amazonaws.com/stonetigermedia.com/Bearologist!.mp4" /> -->
     
       <!-- <VideoJsPlayer videoSrc="https://s3.us-west-1.amazonaws.com/stonetigermedia.com/Lingus.mp4  "/> -->
       <VideoJsPlayer videoSrc="https://dtlaredondo.s3.us-west-2.amazonaws.com/edit+of+remote+coaching.mp4"/>
    </div>
  </template>
  
  <script setup>
  import VideoJsPlayer from '~/components/VideoJsPlayer.vue';
  </script>