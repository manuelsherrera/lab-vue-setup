<script>
export default {
  data() {
    return {
      title: "Welcome to Vue.js",
      h21: "Become a coding ninja with the fastest-",
      h22: "growing JavaScript framework",
      buttonText: "Awesome",
      ironhackLogo: "../public/images/Ironhack_logo.png",
      burger: "../public/images/Burger_menu.png",
      vueLogo: "../public/images/Vue_logo.png",
      img1: "../public/images/USP-1.png",
      img2: "../public/images/USP-2.png",
      img3: "../public/images/USP-3.png",
      img1Text: "Performant",
      img2Text: "Approchable",
      img3Text: "Versatile",
      paragraph1: "Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.",
      paragraph2: "Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.",
      paragraph3: "A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.",
    };
  },
};</script>
<template>
    <nav class="flex space-between nav-style">
      <img class="" :src="ironhackLogo" alt="ironhack logo">
      <img :src="burger" alt="burger menu image">
    </nav> 
   <header class="flex column align-center margin-0 width-auto height-auto border-test">
    <img class="logo-style border-test" :src="vueLogo" alt="Vue Logo">
    <h1 class="title-style border-test">{{ title }}</h1>
    <h2 class="h2-style height-auto border-test">{{ h21 }}</h2>
    <h2 class="h2-style height-auto border-test">{{ h22 }}</h2>
    <span class="margin-top-1 button-style">{{ buttonText }}</span>
  </header>
  <section class="footer-style row flex text-align-center">
    <div class="border-test width-33 flex column align-center">
      <img class="height-80px" :src="img1" alt="performant image">
      <h3 class="margin-top-4">{{ img1Text }}</h3>
      <p class="margin-top-1 width-50 border-test">{{ paragraph1 }}</p>
    </div>
    <div class="border-test width-33 flex column align-center">
      <img class="height-80px" :src="img2" alt="approchable image">
      <h3 class="margin-top-4">{{ img2Text }}</h3>
      <p class="margin-top-1 width-50 border-test">{{ paragraph2 }}</p>
    </div>
    <div class="border-test width-33 flex column align-center">
      <img class="height-80px" :src="img3" alt="versatile image">
      <h3 class="margin-top-4">{{ img3Text }}</h3>
      <p class="margin-top-1 width-50 border-test">{{ paragraph3 }}</p>
    </div>
  </section>
</template>
<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.flex{
  display: flex;
}
.column{
  flex-direction: column;
}
.row{
  flex-direction: row;
}
.width-90{
  width: 90%;
}
.height-80px{
  height:80px ;
}
.space-between{
  justify-content: space-between;
}
.justify-center{
  justify-content: center;
}
.align-center{
  align-items: center;
}
.margin-top-1{
  margin-top: 1%;
}
.text-align-center{
  text-align: center;
}
.margin-0{
  margin: 0% 0%;
}
.height-auto{
  height: auto;
}
.width-auto{
  width: auto;
}
.width-33{
  width: 33vw;
}
.width-50{
  width: 50%;
}
.width-100{
  width: 100px;
}
.height-100{
  height: 100px;
}

.margin-top-4{
  margin-top: 4%;
}

.nav-style{
  width: 90vw;
  margin-left: 5vw;
}

.logo-style{
  height: 129px;
  width: 129px;
}
.title-style{
  margin-top: 2%;
  margin-bottom: 1%;

  font-weight: 800;
  font-size: 50px;
  line-height: 50px;
}
.h2-style{
  font-size: 14px;
  font-weight: 800;
}
.button-style{
  background-color: #34495E;
  color: white;
  padding: 1px 20px;
  border-radius: 20px;
}
.footer-style{
  background-color: #39B983;
  width: 100vw;
  height: auto;
  margin: 4% 0;
  display: flex;
  align-items: center;
  padding: 5% 0;
}
</style>