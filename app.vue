<script setup lang="ts">
    import { NuxtPage } from '#components';
    import TheHeader from './components/TheHeader.vue';
    
    </script>
    
    <template>
      <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com">

        <link href="https://fonts.cdnfonts.com/css/geoform" rel="stylesheet">
    
      </head>
      <div class="body absolute">
        <TheHeader/>
        <main>
                <NuxtPage/>
        </main>
        
    </div>
    <img src="/bcgImg.jpg" alt="">
    </template>
    
    <style scoped>
      .body{
        margin: 0px 0px;
        width: 1472px;
        /* background-color: black; */
      }
    </style>
    