<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

   <div class="paragraph">
      <div>
        I'm <b>Muhammad Akbar</b>, your go-to Senior Game Engineer with a knack for turning gaming dreams into pixelated realities.
        I live and breathe game development, fueled by a passion for crafting immersive experiences. Professionally Over the course of 4 years, I have worked on multiple <router-link to="/game-projects">games</router-link>.
      </div>

      <div style="margin-top: 20px;">Master of <b>Unity & C#</b>, wielding expertise in <b>gameplay mechanics</b>, <b>game backend</b> wizardry, and crafting epic <b>meta features</b> !!! 🚀🕹️🧰
      <br><router-link to="/resume">Still curious about my skills ??</router-link></div>

      <div style="margin-top: 20px;">I'm on the lookout for an opportunity to join an elite game studio renowned for its cutting-edge innovations and boasting a massive user base. 
      I'm driven by the thrill of creating experiences that captivate and engage millions of players worldwide,
       and I'm ready to bring my aexpertise to a team that shares my passion for pushing the boundaries of gaming excellence.
       
       
       You can reach me <a href="mailto:muhammadakbar13995@gmail.com">@</a> or <router-link to="/contact">through here</router-link>.
       
       
       </div>
       


    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of John" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: -30px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>