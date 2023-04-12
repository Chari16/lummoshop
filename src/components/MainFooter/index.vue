<template>
  <footer class="main-footer">
    <b-container>
      <b-row>
        <b-col sm="12" md="3">
          <div class="footer-img">
            <a
              href="https://play.google.com/store/apps/details?id=tokko.onlineshop.jual.mitra.app&amp;hl=id"
            >
              <img
                src="@/assets/lummo-shop-footer-logo.png"
                width="199"
                height="79"
              />
            </a>
          </div>
          <div class="footer-desc">
            <p>
              LummoSHOP helps you to create your online store website easily,
              safely and for FREE!
            </p>
            <p class="copyright-text d-none d-md-block">
              2022 © PT BeeGroup Financial Indonesia, a subsidies of Tulp Street
              Pte. Ltd. All Rights Reserved
            </p>
          </div>
        </b-col>
        <b-col sm="12" md="3">
          <div class="footer-links">
            <h5>Product</h5>
            <div>
              <ul>
                <li>
                  <a href="https://link.lummoshop.com/sxDkNU0XSmb"
                    >Download LummoSHOP</a
                  >
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/lummoshop-plus/"
                    >LummoSHOP Plus</a
                  >
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/toko-online/"
                    >Online shop</a
                  >
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/jualan/">
                    Jualan Online
                  </a>
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/syarat-dan-ketentuan/">
                    Terms & Conditions</a
                  >
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/kebijakan-privasi/"
                    >Privacy Policy</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </b-col>
        <b-col sm="12" md="3">
          <div class="footer-links">
            <h5>Help</h5>
            <div>
              <ul>
                <li>
                  <a href="https://link.lummoshop.com/sxDkNU0XSmb">FAQ</a>
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/lummoshop-plus/"
                    >Education Center</a
                  >
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/toko-online/"
                    >User Testimonials</a
                  >
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/jualan/">
                    Business Tool
                  </a>
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/syarat-dan-ketentuan/">
                    Contact Us</a
                  >
                </li>
                <li>
                  <a href="https://www.lummoshop.co.id/kebijakan-privasi/"
                    >Careers</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </b-col>
        <b-col sm="12" md="3">
          <b-row class="connects mb-3 md-mb-0">
            <b-col lg="6" sm="12">
              <div class="footer-links">
                <h5>Connect</h5>
                <div>
                  <ul>
                    <li>
                      <a href="https://link.lummoshop.com/sxDkNU0XSmb"
                        >Twitter</a
                      >
                    </li>
                    <li>
                      <a href="https://www.lummoshop.co.id/lummoshop-plus/"
                        >Facebook</a
                      >
                    </li>
                    <li>
                      <a href="https://www.lummoshop.co.id/toko-online/"
                        >Instagram</a
                      >
                    </li>
                    <li>
                      <a href="https://www.lummoshop.co.id/jualan/">
                        Youtube
                      </a>
                    </li>
                    <li>
                      <a
                        href="https://www.lummoshop.co.id/syarat-dan-ketentuan/"
                      >
                        TikTok</a
                      >
                    </li>
                  </ul>
                </div>
              </div>
            </b-col>
            <b-col lg="6" sm="12">
              <img
                class="play-img"
                src="@/assets/gplay_badge.svg"
                alt="googleplay-logo"
              />
            </b-col>
          </b-row>
        </b-col>
        <b-col sm="12" class="d-md-none">
          <div class="footer-desc">
            <p class="copyright-text">
              2022 © PT BeeGroup Financial Indonesia, a subsidies of Tulp Street
              Pte. Ltd. All Rights Reserved
            </p>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </footer>
</template>
<script>
export default {};
</script>
<style>
.main-footer {
  background-color: #eef2ff;
}
.footer-img {
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 20px;
  text-align: left;
}
.footer-desc {
  text-align: left;
  margin-bottom: 40px;
  font-size: 16px;
  line-height: 23px;
  color: #311b92;
}
.main-footer .row {
  padding-top: 30px;
}
.footer-links {
  text-align: left;
  margin-bottom: 40px;
}
.footer-links ul {
  list-style: none;
  padding-left: 0;
}
.footer-links ul li {
  width: auto !important;
  display: block !important;
  clear: none !important;
  margin: 0 0 12px 0;
  padding: 0;
}
.footer-links ul li a {
  color: #333;
}
.main-footer .footer-links h5 {
  font-family: "Circular", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 1.25rem;
  line-height: 1.5625rem;
  margin-bottom: 20px;
  color: #311b92;
}
.play-img {
  width: 100%;
}
.connects {
  padding-top: 0 !important;
}
.copyright-text {
  color: #6f5fb3;
  font-size: 14px;
  line-height: 23px;
}
@media (max-width: 575px) {
  .play-img {
    width: 50%;
  }
  .footer-img {
    text-align: center;
  }
  .footer-desc {
    text-align: center;
  }
}
</style>
