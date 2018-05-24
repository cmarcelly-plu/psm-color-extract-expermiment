<template>
  <div class="albums-menu">
    <p>{{ msg }}</p>
    <ul>
      <li>
        <a href="#"><img src="./assets/img/madonna.jpg" alt=""></a>
      </li>
      <li>
        <a href="#"><img src="./assets/img/madonna.jpg" alt=""></a>
      </li>
      <li>
        <a href="#"><img src="./assets/img/madonna.jpg" alt=""></a>
      </li>
      <li>
        <a href="#"><img src="./assets/img/madonna.jpg" alt=""></a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "AlbumsMenu",
  data() {
    return {
      msg: "Albums goes here!"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.albums-menu {
  position: absolute;
  bottom: 20px;
  width: 100%;
  border: solid 1px red;
}
</style>
