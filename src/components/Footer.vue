<script setup lang="js">
import { Fb, X, Github, Linkedin, Ig } from '@/components/icons/index.js'
</script>



<template>
<footer class="flex flex-col pt-4">
  <div class="m-auto p-4">
    <img  src="@/assets/img/logo.svg" alt="logo footer">
  </div>

  <div class="m-auto p-2">
    <a class="m-4" ref="#about">About</a>
    <a class="m-4" href="#features">Features</a>
    <a class="m-4" href="#blog">Blog</a>
    <a class="m-4" href="#resources">Resources</a>
    <a class="m-4" href="#partner">Partner</a>
    <a class="m-4" href="#help">Help</a>
    <a class="m-4" href="#term">Term</a>
  </div>

  <div class="flex m-auto p-1">
    <Fb class="m-4"/>
    <X class="m-4"/>
    <Github class="m-4"/>
    <Linkedin class="m-4"/>
    <Ig class="m-4"/>
  </div>

  <div class="flex m-auto">
    <h1 class="m-4">© 2023, Horizon UI Library. All rights reserved.</h1>
  </div>


</footer>


</template>