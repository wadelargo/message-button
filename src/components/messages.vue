<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <text :class="type"> {{ title }} </text>

  </template>
  
  <script>
  export default{
    props: {
        title: String,
        type: String
    }
  }
  </script>




  
  <style scoped>

  
  text {
    font-family: 'Quicksand', sans-serif;
    padding: 10px 20px;
    width: 305px;
    height: 120px;
    margin: 7%;
    cursor: pointer;
    border: 0;
    font-weight: 500;
    display: flex;
    justify-content: center;
    font-size: 18px
  }
  
  .regular{
    color: white;
    background-color: #91d0f7;
    border: 4px solid #1802bd ;
  }
  .regular:hover {
    background-color: #0d83cccf;

  }
  
  .happy{
    color: white;
    background-color: rgb(165, 227, 146);
    border: 4px solid #308506 ;
  }
  .happy:hover {
    background-color: rgba(106, 246, 63, 0.7);
  }

  .sad{
    color: white;
    background-color: #d7d594;
    border: 4px solid #837b0a ;
  }
  .sad:hover {
    background-color: #f3d113e4;
  }

  .angry{
    color: white;
    background-color: #f143189c;
    border: 4px solid #870c0c ;
  }
  .angry:hover {
    background-color:#f41d1dac ;
  }
  
  
  </style>