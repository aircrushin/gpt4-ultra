<template>
  <div class="container">
      <div class="hide"></div>
      <iframe class="outer" id="frame" frameborder="0" :src="url"></iframe>
  </div>
  </template>
   
  <script setup>
  const url = `https://www.coze.com/store/bot/7363119830733586450?panel=1&bid=6cfosji3c3008`
  </script>
   
  <style scoped>
  .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 0 auto;
      height: 90vh;
      overflow: hidden;
  }
  .hide {
      height: 12vh;
      z-index: 100;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;    
      background-color: #fff;
  }
  .outer {
      margin-top: 20px;
      width: 1000px;
      height: 100%;
  }
  </style>
   