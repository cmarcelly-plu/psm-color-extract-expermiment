<template>
  <div class="albums-menu">
    <ul>
      <li>
        <a href="#"><img src="https://d24jnm9llkb1ub.cloudfront.net/icpn/00028947981039/00028947981039-cover-225.jpg" alt=""></a>
      </li>
      <li>
        <a href="#"><img src="https://d24jnm9llkb1ub.cloudfront.net/icpn/00028948340941/00028948340941-cover-225.jpg" alt=""></a>
      </li>
      <li>
        <a href="#"><img src="https://s3.amazonaws.com/preview.prostudiomasters.com/icpn/00602567502432/00602567502432-cover-225.jpg" alt=""></a>
      </li>
      <li>
        <a href="#"><img src="https://s3.amazonaws.com/preview.prostudiomasters.com/icpn/00602567723905/00602567723905-cover-225.jpg" alt=""></a>
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
  background: rgba(0, 0, 0, 0.2);
}

ul {
  font-size: 0;
  display: block;
  list-style-type: none;
  margin: 10px auto;
  padding: 0;
  text-align: center;
  width: 50%;
}

ul li {
  display: inline-block;
  padding: 0 10px 0;
  width: 25%;
  // width: 80%;
}

ul li a {
  display: block;
}

ul li a:hover {
  border: solid 2px white;
}

ul li img {
  display: block;
  width: 100%;
  height: auto;
}
</style>
