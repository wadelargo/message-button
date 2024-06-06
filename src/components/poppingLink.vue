<template>
    <a class="grow" :href="link">
      {{ linkText }}
    </a>
  </template>
  
  <script>
  
  export default {
    props: {
        type: String,
        link: String
    }
  }
  
  </script>
  
  <style scoped>
  
    .grow{
        background: rgba(90, 85, 108, 0.914);
      padding: 20px ;
      width: 20vw;
      margin: 10px;
      font-size: 20px;
      color: rgb(242, 242, 242);
      text-align: center;
      justify-content: space-between;
      text-decoration: none;
      transition: .5s ease;
    }
  
    .grow:hover{
      transform: scale(1.2);
      -webkit-transform: scale(1.2);
      -ms-transform: scale(1.2);
    }
  
  </style>