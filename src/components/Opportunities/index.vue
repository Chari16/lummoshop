<template>
  <section id="opportunities" class="opportunities-container">
    <b-container>
      <div class="features-title text-center">
        <h2>Small Steps to Open Big Opportunities</h2>
        <p>Follow the 4 steps below to speed up your online business!</p>
      </div>
    </b-container>
    <div class="info-1">
      <div class="info-container">
        <b-row align-v="center">
          <b-col>
            <div>
                <img src="@/assets/step-1.png" class="img-wrapper"/>
            </div>
            <div class="text-center">
                <p>Step 1</p>
                <div class="steps-info-box">
                    <h3>Start your Bikin Online Shop </h3>
                    <p>
                        Enter your brand name and make sure it matches the name printed on the website link to make it easier to brand your online store.
                    </p>
                </div>
            </div>
          </b-col>
          <b-col>
            <img src="@/assets/step-2.png" class="img-wrapper"/>
            <p>Step 2</p>
            <h3>Account Verification</h3>
            <p>
                To increase the confidence of shopping buyers in your store, verify your online store account as early as possible.
            </p>
          </b-col>
        </b-row>
        <b-row align-v="center">
          <b-col>
            <div>
                <img src="@/assets/step-3.png" class="img-wrapper"/>
            </div>
            <div class="text-center">
                <p>Step 3</p>
                <div class="steps-info-box">
                    <h3>Create a Catalog </h3>
                    <p>
                        Show the best photos of all your juxtaposition products or your suit, provide a complete description, and complete the choice of payment and shipping methods.
                    </p>
                </div>
            </div>
          </b-col>
          <b-col>
            <img src="@/assets/step-4.png" class="img-wrapper"/>
            <p>Step 4</p>
            <h3>Maximize Your Sales!</h3>
            <p>
                Use our customer's data marketing and analysis features, so that your promotions can arrive at the right prospective buyers!
            </p>
          </b-col>
        </b-row>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style>
.opportunities-container {
  padding-top: 100px !important;
  padding-bottom: 20px !important;
  background-color: #fff !important;
}
.features-title {
  margin-bottom: 70px !important;
}
.features-title p {
  padding: 0 15%;
  margin-top: 20px;
  margin-bottom: 0;
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
.img-wrapper {
    width: 100%;
    max-width: 370px;
    margin-left: auto;
    margin-right: auto;
    display: block;
}
.steps-info-box {
    padding: 0 45px 0 45px !important;
    margin-left: auto !important;
    margin-right: auto !important;
    margin-bottom: 40px !important;
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
</style>
