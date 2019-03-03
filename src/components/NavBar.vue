<template>
  <div>
    <b-navbar toggleable="md" type="light">
      <b-navbar-brand href="#">
        <img src="http://fsthai.com/images/logotext.png">
      </b-navbar-brand>

      <b-navbar-toggle target="nav_collapse" />

      <b-collapse is-nav id="nav_collapse">

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">About</b-nav-item>
          <b-nav-item href="#">Services</b-nav-item>
          <b-nav-item href="#">Check Price</b-nav-item>
          <b-nav-item href="#">Tracking</b-nav-item>
          <b-nav-item href="#">Contacts</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  img {
    height: 40px;
    margin: none;
  }

  .nav-link {
    font-family: 'Raleway', sans-serif;
    font-weight: 300;
    font-size: 16px;
    color: #333 !important;
    padding: 20px 10px !important;
  }

  .nav-link:hover {
    font-weight: bold;
    box-shadow: inset 0 3px 0 rgba(0,0,0,0.5);
  }

  nav {
    box-shadow: inset 0 3px 0 rgba(0,0,0,0.1);
    padding: 0px !important;
  }

  button {
    border: 0px !important;
  }
</style>
