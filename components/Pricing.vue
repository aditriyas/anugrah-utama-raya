<template>
  <section class="pricing" id="services">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 col-12 text-center">
          <h1 class="header">Harga Terjangkau.</h1>
          <p class="description">
            Harga jual dan penyewaan yang terjangkau, <br />
            telah menjual dan menyewakan Scaffolding ke 15++ perusahaan. <br />
            Yang membuat kami, terjamin dan terpercaya!
          </p>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-7 col-12">
          <div class="row">
            <div class="col-lg-6 col-12">
              <div class="master-card basic-card card-1">
                <h5 class="name">Sewa Scaffolding Baru & Bekas</h5>
                <!-- <h1 class="price">Rp.1xxx,xx</h1> -->
                <div class="image-container">
                  <img src="~assets/images/jual.jpg" alt="" />
                </div>
                <p class="desc">
                  Penyewaan Scaffolding bersama PT. Anugrah Utama Raya,
                  menyediakan scaffolding berbagai ukuran, kami menyediakan
                  mainframe 1.7 meter dan main frame 1.9 meter untuk penyewaan
                  scaffolding di Bekasi. Dimanapun anda berada kami mencoba
                  untuk memberikan pelayanan yang maksimal untuk sewa menyewa
                  scaffolding.
                </p>
                <a
                  href="https://api.whatsapp.com/send?phone=6281284956358"
                  target="_blank"
                  class="btn btn-primary me-2"
                >
                  Start With This
                </a>
              </div>
            </div>
            <div class="col-lg-6 col-12">
              <div class="master-card most-card">
                <h5 class="name">Jual Scaffolding Baru & Bekas</h5>
                <!-- <h1 class="price">Rp.2xxx,xx</h1> -->
                <div class="image-container">
                  <img src="~assets/images/sewa-2.jpg" alt="" />
                </div>
                <p class="desc-2">
                  Melayani Jual Scaffolding Baru ukuran 1.2 meter - 1.5 meter -
                  1.7 meter dan scaffolding 1.9 meter. Sedangkan untuk jual
                  scaffolding bekas kami hanya menyediakan scaffolding ukuran
                  1.7 meter dan scaffolding 1.9 meter.
                </p>
                <a
                  href="https://api.whatsapp.com/send?phone=6281284956358"
                  target="_blank"
                  class="btn btn-primary me-2"
                >
                  Choose This Plan
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.support {
  margin-bottom: 16px !important;
}

.desc {
  text-align: justify;
  color: #5c6944;
  margin-bottom: 0;

  &-2 {
    color: #fff;
  }
}

.card-1 {
  box-shadow: 15px 15px 5px -8px rgba(0, 0, 0, 0.13);
  -webkit-box-shadow: 15px 15px 5px -8px rgba(0, 0, 0, 0.13);
  -moz-box-shadow: 15px 15px 5px -8px rgba(0, 0, 0, 0.13);
}

.master-card {
  .image-container {
    width: 100%;
    img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 8px;
    }
  }
}
</style>
