<template>
  <div class="home">
    <player />
  </div>
</template>

<script>
import Player from "../components/Player";
export default {
  components: {
    Player
  }
};
</script>

<style scoped>
.home {
  display: flex;
  width: 100%;
  height: 100%;
  background-color: #fff;

  z-index: 0;

  position: relative;
  justify-content: center;
  align-items: center;
}
.mytips {
  position: absolute;
  top: 0;
  left: 0;
}
.project_img {
  width: 20%;
  height: 20%;
  float: left;
}
.mytips p {
  width: 60%;
  float: left;
}
</style>