<template>
  <div style="margin-bottom: 80px;">
    <h1>Welcome to the World of Gaming Magic!</h1>

    <div class="paragraph">
      <div>
        Hey there, fellow adventurer! I'm <b>Akbar</b>, your Senior
        Game Engineer extraordinaire. If you can dream it, I can pixelate it
        into gaming reality. 🎮✨ Over the past 4 years, I've embarked on epic
        quests, crafting numerous
        <router-link to="/game-projects">GAMESS</router-link> that have
        transported players to realms beyond imagination.
      </div>

      <div style="margin-top: 20px;">
        Behold, for I am the Master of <b>Unity & C#</b>, wielding powers in
        <b>gameplay mechanics</b>, conjuring up <b>game backend</b> magic, and
        crafting epic <b>meta features</b> that defy the laws of gaming physics!
        🚀🕹️🧰 <br /><router-link to="/resume"
          >Curious to witness my skills in action?</router-link
        >
        Venture forth, if you dare!
      </div>

      <div style="margin-top: 20px;">
        Seeking to align my destiny with an elite game studio renowned for its
        groundbreaking innovations and boasting a legion of loyal players. I
        hunger for the challenge of creating experiences that ensnare the hearts
        of millions worldwide, and I stand ready to unleash my expertise upon a
        team that shares my fervor for pushing the boundaries of gaming
        excellence. Should you wish to summon me for this noble quest, dispatch
        a raven to
        <a href="mailto:muhammadakbar13995@gmail.com"
          >muhammadakbar13995@gmail.com</a
        >
        or <router-link to="/contact">send a signal here</router-link>.
        Together, let's forge legends!
      </div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of Muhammad" />
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

@media only screen and (min-width: 620px) {
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
