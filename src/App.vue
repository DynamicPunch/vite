<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


.s1 {
  width: 350px;
  text-align: center;
  background: pink;

  
  margin-top: 16px;
  margin-bottom: 16px;
  margin-left: 16px;
  margin-right: 16px;
  
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 8px;
  padding-right: 8px;
  
  border: 2px solid red;
  border-radius: 16px;
  box-shadow: 4px 4px;
}


.h1 {
  font: 28px Comic Sans MS;
  color: white;
  text-shadow: 2px 2px #000000;
  line-height: 0px;
  
}
.h2 {
  font: 20px Comic Sans MS;
  color: white;
  margin-bottom: 16px;
  text-shadow: 2px 2px #000000;
}

.p1 {
  font: 14px Comic Sans MS;
  color: white;
  margin-top: 16px;
  margin-left: 16px;
  margin-right: 16px;
  text-shadow: 2px 2px #000000;
}

.l1 {
  font: 14px Comic Sans MS;
  color: white;
  margin-bottom: 24px;
  margin-left: 16px;
  margin-right: 16px;
  text-shadow: 2px 2px #000000;
  
}

ul {
    text-align: center;
    list-style-position: inside;
}


.b1 {
  font: 12px Comic Sans MS;
  border-radius: 16px;
  box-shadow: 2px 2px;
  margin-bottom: 16px;
  
}

.i1 {
  border: 3px solid blue;
  border-radius: 16px;
  box-shadow: 4px 4px;
  
}


@media (max-width: 800px) and (min-width: 500px) {
  .b1 {
    display: none;
  }
}

@media (max-width: 500px) {
  * {
    transform: scale(0.9);
  }
}

body {
  background: cyan;
}


 .but{
   padding: 4px;
       box-shadow: 2px 2px #000000;
    background-color: cyan;
     border-radius: 16px;
     border: 2px solid blue;
  text-shadow: 2px 2px #000000;
    font: 14px Comic Sans MS;
  color: white;

}

.but:hover{
  background-color: red;
}

.but:focus {
  background-color: blue; 
}


.tog
{
  background-color: cyan;
}

.tog2
{
  background-color: pink;
}




</style>
