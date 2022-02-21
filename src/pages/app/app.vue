<style lang="scss" src="./app.scss"></style>
<style src="C:\Users\AlyshaWoolcock\Desktop\RDVue\newtest\aw-learningrdvue-proj\src\theme\tailwind.css"></style>
<script lang="ts" src="./app.ts"></script>
<template>
  <div id="app" class="[ grid ]">
    <component v-if="layout" :is="layout">
      <router-view />
    </component>
    <div v-else class="[ self-center ]" style="justify-self: center">
      Loading...
    </div>
  </div>
</template>
