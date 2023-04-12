<template>
  <section id="demo" class="demo-container">
    <b-container>
      <b-row align-v="center">
        <b-col sm="12" lg="12">
          <h2 class="limegreen-color">Start Jualan Online and Open the Future Opportunities of Your Business with LummoSHOP</h2>
          <p class="white-color">
            Have an online store and sell your products more easily.
          </p>
          <div class="stores-badge d-flex justify-content-center">
            <b-button size="md" class="btn-white demo-btn">Create demo schedule</b-button>
            <b-button size="md" class="btn-lightgreen demo-btn">Start now</b-button>
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
.demo-container {
   background-color: #311b92;
   padding: 100px 0;
}
.demo-btn {
    font-weight: 500 !important;
}
@media (max-width: 767px) {
    .demo-container {
        padding: 50px 0;
    }
    .demo-btn {
        font-size: 12px !important;
        padding: 6px 10px !important;
    }
}
</style>
