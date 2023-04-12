<template>
  <section class="main-hero pt-120">
    <b-container>
      <b-row>
        <b-col lg="6" sm="12">
          <div>
            <h1 class="main-hero-title limegreen-color">
              Business Place Toy Start your Online Store, Hold Control to Grow
              <span></span>
              <br />
            </h1>
            <p class="white-color p-sm main-hero-subtitle">
              With a complete & practical online store website, there are no
              more obstacles to optimizing your business growth opportunities.
            </p>
          </div>
          <div class="stores-badge d-flex">
            <b-button class="btn-white main-hero-btn"
              >Create demo schedule</b-button
            >
            <b-button class="btn-lightgreen main-hero-btn">Start now</b-button>
          </div>
        </b-col>
        <b-col lg="6" sm="12">
          <div class="mb-40">
            <img
              src="@/assets/main-hero.png"
              alt="LummoSHOP Online Store"
              class="img-fluid py-4"
            />
          </div>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>
<script>
export default {};
</script>
<style>
.main-hero {
  background-color: #311b92;
  padding-top: 120px;
  text-align: left;
}
.main-hero-img {
  padding-top: 50px;
}
.img-fluid {
  max-width: 100%;
  height: auto;
}
.limegreen-color {
  color: #aae900 !important;
}
.white-color {
  color: #fff !important;
}
.stores-badge {
  margin-top: 30px;
}
.stores-badge .btn-lightgreen::after {
  content: "Gratis";
  background: #ffffff;
  -webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 16px;
  min-width: 46px;
  padding-left: 9px;
  padding-right: 9px;
  height: 20px;
  position: absolute;
  top: -15px;
  right: -25px;
  color: #311b92;
  line-height: 1.625rem;
  font-size: 0.875rem;
  font-weight: 500;
  height: 26px;
}
.main-hero-title {
  font-size: 48px;
  font-weight: 700;
}
.main-hero-subtitle {
  font-size: 15px;
  font-weight: 400;
}
.main-hero-btn {
  font-size: 16px !important;
  font-weight: 500 !important;
  padding: 11px 29px !important;
  line-height: 24px !important;
  border-radius: 6px !important;
}
@media (max-width: 340px) {
  .main-hero-title {
    font-size: 40px;
  }
  .main-hero-btn {
    font-size: 12px !important;
    padding: 6px 10px !important;
  }
}
</style>
