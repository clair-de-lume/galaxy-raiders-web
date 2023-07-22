<template>
  <div class="background-container">
    <div class="background-exit"></div>
    <div class="content-container">
      <div class="title">
        <h1 class="thank-you-title">Thank you for playing!</h1>
      </div>
    </div>
  </div>
</template>

<style scoped>
.title {
  text-align: center;
  font-size: 20px;
  color: white;
  margin: 20px auto;
}

.thank-you-title {
  font-size: 48px;
  color: white;
  text-align: center;
  margin-top: 50vh;
  transform: translateY(-50%);
  font-family: "Orbitron", sans-serif;
}

* {
  margin: 0;
  padding: 0;
}

.background-container {
  position: relative;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.background-exit {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-size: cover;
  background-repeat: no-repeat;
  background-image: url("https://i.pinimg.com/originals/e1/b9/c5/e1b9c5f696d6f136c3eca1b26ac8c846.gif");
}
</style>
