<template>
  <div class="home">
    <img alt="Omna logo" src="../assets/omna.svg" />
    <p>Loading...</p>
  </div>
</template>

<style>
.home {
  background-color: #001C1A;
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
}
.home::before {
  content: "";
  background-image: url("../assets/noise.gif");
  position: absolute;
  width: 100%;
  height: 100%;
  opacity: 0.04;
}
.home::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  box-shadow: inset 0 0 200px #ceff001c;
}
.home p {
  color: var(--color-primary);
  font-size: 2.5rem;
  font-weight: 500;
  animation: pulse 3s infinite;
}
@keyframes pulse {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0;
  }
}
</style>

<script>
export default {
  name: "HomeView",
  components: {},
};
</script>
