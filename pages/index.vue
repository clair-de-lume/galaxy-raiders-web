<template>
  <div class="background-container">
    <div class="background-gif"></div>
    <div class="content-container">
      <div class="title">
        <h1 class="gradient-title">GALAXY RAIDERS</h1>
      </div>
      <div class="buttons-container">
        <NuxtLink to="play" class="button button1" style="color: white;">PLAY</NuxtLink>
        <NuxtLink to="leaderboard" class="button button2" style="color: white;">LEADERBOARD</NuxtLink>
        <NuxtLink to="exit" class="button button3" style="color: white;">QUIT</NuxtLink>
      </div>
    </div>
  </div>
</template>

<style>
.title {
  text-align: center;
  margin: 20px auto;
}

.gradient-title {
  background: linear-gradient(45deg, #ff007f, #29abe2);
  -webkit-background-clip: text;
  background-clip: text;
  color: white;
  font-size: 72px;
  font-family: "Orbitron", sans-serif;
}

.buttons-container {
  display: flex;
  position: page;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 100%;
}

.button {
  padding: 15px 40px;
  font-size: 24px;
  font-weight: bold;
  text-transform: uppercase;
  text-decoration: none;
  margin: 10px;
  outline: none;
  border: none;
  cursor: pointer;
  background-color: transparent;
  box-shadow: 0 0 0 2px white;
}

.background-gif {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  background: url("https://i.pinimg.com/originals/e1/b9/c5/e1b9c5f696d6f136c3eca1b26ac8c846.gif");
  background-size: cover;
  background-repeat: no-repeat;
  z-index: -1;
  opacity: 1;
}

.background-container {
  position: relative;
  width: 100%;
  height: 100%;
}

.content-container {
  position: relative;
  z-index: 1;
}

* {
  margin: 0;
  padding: 0;
}
</style>
