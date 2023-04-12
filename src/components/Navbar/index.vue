<template>
  <header class="header">
    <b-navbar toggleable="lg" class="fixed-top">
      <b-container>
        <img
          src="@/assets/lummo-shop-logo.png"
          alt="Lummo-shop-logo"
          width="152"
          height="60"
        />

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item>Download LummoSHOP </b-nav-item>
            <b-nav-item>LummoSHOP Upgrade </b-nav-item>
            <b-nav-item>Service</b-nav-item>
            <b-nav-item>Explore</b-nav-item>

          </b-navbar-nav>
          <div class="d-flex flex-column flex-sm-row align-items-center align-items-sm-stretch nav-items">
              <b-button class="btn-white my-2 my-sm-0 header-btn" 
                >Create a Demo Schedule</b-button
              >
              <b-button class="btn-lightgreen my-2 my-sm-0 header-btn">Login</b-button>
            </div>
        </b-collapse>
      </b-container>
    </b-navbar>
  </header>
</template>
<script>
export default {
  props: {
    msg: String,
  },
};
</script>
<style>
.navbar {
  background-color: #311b92;
  font-family: "Circular", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.navbar-light .navbar-nav .nav-link {
  color: #fff !important;
}
.navbar-toggler-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' width='30' height='30' viewBox='0 0 30 30'%3e%3cpath stroke='rgba(0, 0, 0, 0.5)' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
}
.header-btn {
  font-weight: 500 !important;
  font-size: 12px !important;
  /* height: 30px; */
  padding: 6px 10px !important;
}
.nav-items {
  display: inline-block !important;
  padding-top: 0;
  padding-bottom: 0;
  margin-left: 10px;
}
</style>
