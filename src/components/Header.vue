<script setup>
import photo from "../assets/dave.jpg";
import discordLogo from "../assets/discord.png";
import linkedinLogo from "../assets/linkedin.png";
import twitterLogo from "../assets/twitter.png";

import Link from "./Link.vue";
</script>

<template>
  <div class="header-container">
    <div class="links-container flex">
      <Link name="Linkedin" link="#" :img="linkedinLogo" />
      <Link name="Discord" link="#" :img="discordLogo" />
      <Link name="Twitter" link="#" :img="twitterLogo" />
    </div>
    <div class="main-container flex">
      <div class="photo-name-container flex">
        <img :src="photo" alt="" width="250" class="photo" />
        <p>GROSSO ADSD</p>
      </div>
      <div class="about-me">
        <h1>About me</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam saepe
          dicta, err adipisicing elit. Veniam saepe dicta, err adipisicing elit.
          Veniam saepe dicta, err adipisicing elit. Veniam saepe dicta, err
          adipisicing elit. Veniam saepe dicta, err adipisicing elit. Veniam
          saepe dicta, err adipisicing elit. Veniam saepe dicta, err adipisicing
          elit. Veniam saepe dicta, err adipisicing elit. Veniam saepe dicta,
          err adipisicing elit. Veniam saepe dicta, err adipisicing elit. Veniam
          saepe dicta, err adipisicing elit. Veniam saepe dicta, err adipisicing
          elit. Veniam saepe dicta, err adipisicing elit. Veniam saepe dicta,
          err adipisicing elit. Veniam saepe dicta, err adipisicing elit. Veniam
          saepe dicta, err adipisicing elit. Veniam saepe dicta, err
          adipisicniam saepe dicta, err adipisicniam saepe dicta, err
          adipisicniam saepe dicta, err adipisicniam saepe dicta, err
          adipisicniam saepe dicta, err adipisicniam saepe dicta, err
          adipisicniam saepe dicta, err adipisicing elit. Veniam saepe dicta,
          error neque qui sunt fugit maxime assumenda inventore libero at culpa
          ducimus et, laborum magnam velit voluptatum nihil excepturi!
        </p>
      </div>
      <div class="anchors flex">
          <a href="#" class="anchor">Projects</a>
          <a href="#" class="anchor">Contact</a>
      </div>
    </div>
  </div>
</template>

<style scoped>

.links-container {
    flex-direction: row;
    justify-content: end;
    align-items: center;
  }
.main-container {
  background-color: red;
  height: 95vh;
  padding: 0 30px;
  align-items: center;
}

.photo-name-container {
  display: flex;
  flex-direction: column;
  margin: 20px;
  text-align: center;

  width: auto;
  height: auto;
  max-height: 350px;
  max-width: 350px;
}

.photo {
  border-radius: 50%;
  margin-bottom: 30px;
}

.about-me {
  text-align: center;
  padding: 50px;
}

.anchors{
    flex-direction: column;
}

.anchor{
    font-size: 2em;
    margin: 15px 0;

}
</style>
