<template>
  <div class="hello">
    <!-- input +inline validation flexbox -->
    <div type="input-wrapper">
      <input type="text" v-model="inputValue" v-bind:class="inputValidationClass">
      <div v-if="inlineValidationClass" class="inline-validation">you exceeded 50 characters!</div>
    </div>

    <!--button flexbox-->
    <div class="button-wrapper">
        <button v-bind:disabled="isButtonDisabled">Submit</button>
    </div>
  </div>

 </template>
<script src="./HelloWorld.js"></script>
<style src="./HelloWorld.css"></style>
