<template>
  <section id="features" class="features-container">
    <b-container>
      <div class="features-title text-center">
        <h2>Many Smart Online Store Features to Control Business Easier</h2>
        <p>
          You can use the features of interconnected online stores to make your
          business processes simpler, more efficient and accurate.
        </p>
      </div>
    </b-container>
    <b-container class>
      <b-row align-v="center" class="feature-card feature-content">
        <b-col sm="12" lg="6" class="feature-text">
          <h3 class="feature-title">Easy Managed Online Store Website</h3>
          <p>
            Business management is increasingly practical with an order
            management system, payment, to complete delivery of goods.
          </p>
        </b-col>
        <b-col sm="12" lg="6">
          <img src="@/assets/info-1.png" class="info-img" />
        </b-col>
      </b-row>
    </b-container>
    <b-container>
      <b-row align-v="center" class="feature-card">
        <b-col lg="6" sm="12">
          <img src="@/assets/info-2.png" class="info-img" />
        </b-col>
        <b-col lg="6" sm="12" class="feature-text">
          <h3 class="feature-title">Your product is the Center of Attention</h3>
          <p>Without rivals & price wars, visitors are more enticed to buy.</p>
        </b-col>
      </b-row>
    </b-container>
    <b-container>
      <b-row align-v="center" class="feature-card feature-content">
        <b-col sm="12" lg="6" class="feature-text">
          <h3 class="feature-title">
            Upload Thousands of Your Products to the Catalog in Minutes Count
          </h3>
          <p>No fuss, show all your products with various variants!</p>
        </b-col>
        <b-col sm="12" lg="6">
          <img src="@/assets/info-3.png" class="info-img" />
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>
<script>
export default {};
</script>
<style>
.features-container {
  padding-top: 100px !important;
  padding-bottom: 20px !important;
  background-color: #eef2ff !important;
}
.features-title {
  margin-bottom: 70px !important;
}
.features-title p {
  padding: 0 15%;
  margin-top: 20px;
  margin-bottom: 0;
  font-size: 15px;
  font-weight: 400;
}
@media (min-width: 1200px) {
  .features-title h2 {
    max-width: 775px;
    margin-left: auto;
    margin-right: auto;
  }
}
.info-1 {
  display: flex;
  align-items: center;
}
@media (min-width: 1400px) {
  .info-container {
    max-width: 1270px;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
  }
}
.info-img {
  max-width: 100%;
}
.feature-text {
    text-align: left;
}
@media (max-width: 767px) {
  .feature-content {
    flex-direction: column-reverse;
  }
  .feature-text {
    text-align: center;
  }
  .feature-title {
    font-weight: 400;
    font-size: 1.25rem;
    line-height: 1.5625rem;
    margin-bottom: 20px;
  }
  .feature-card {
    padding-bottom: 50px;
  }
}
</style>
