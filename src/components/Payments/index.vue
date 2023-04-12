<template>
    <section id="features" class="payments-container">
        <b-container>
          <b-row align-v="center">
            <b-col sm="12" lg="6">
              <h3>Many Payment Methods</h3>
              <p>
                Buyers can choose the payment method that is most convenient for them. Options ranging from virtual account / bank transfer, QRIS, e-wallet to cash on delivery (COD).
              </p>
            </b-col>
            <b-col sm="12" lg="6">
              <img src="@/assets/payment-partners.png" class="img-wrapper"/>
            </b-col>
          </b-row>
        </b-container>
        <b-container>
          <b-row align-v="center">
            <b-col sm="12" lg="6">
              <img src="@/assets/shipping-partners.png" class="img-wrapper"/>
            </b-col>
            <b-col sm="12" lg="6">
              <h3>Various Shipping Options</h3>
              <p>
                Your buyers will also be spat out with the many types of shipments that can be chosen as they need, starting from regular, instant and same-day shipments.
              </p>
            </b-col>
          </b-row>
        </b-container>
    </section>
  </template>
  <script>
  export default {};
  </script>
  <style>
  .payments-container {
    padding-top: 100px !important;
    padding-bottom: 20px !important;
    background-color: #eef2ff !important;
  }
  @media (min-width: 1200px) {
    .features-title h2 {
      max-width: 775px;
      margin-left: auto;
      margin-right: auto;
    }
  }
  .img-wrapper {
    width: 100%
  }
  </style>
  