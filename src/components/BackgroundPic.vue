<template>
  <div class="parallax">
  </div>
</template>

<script>
export default {

}
</script>

<style>
.parallax {
  /* The image used */
  background-image: url("https://images.pexels.com/photos/1261728/pexels-photo-1261728.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260");

  /* Set a specific height */
  min-height: 800px;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: right;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>