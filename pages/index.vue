<template>
  <div class="main">
    <Navbar />
    <Sales />
    <Pricing />
    <Pricelists />
    <Footer />
    <a
      class="wa-button-container btn btn-primary"
      href="https://api.whatsapp.com/send?phone=6281296839332"
      target="_blank"
    >
      <div class="wa-button flex">
        <img src="~assets/images/whatsapp.png" alt="" class="wa-image" />
        <p class="wa-text mb-0">Hubungi WhatsApp kami!</p>
      </div>
    </a>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {}
  },
}
</script>

<style lang="scss" scoped>
.main {
  position: relative;
}

.wa-image {
  width: 20px;
  height: 20px;
  @media only screen and (min-width: 600px) {
    width: 30px;
    height: 30px;
  }
}

.wa-button {
  align-items: center;
  gap: 8px;
  text-decoration: none;
  color: #fff;

  p {
    font-size: 12px;
    @media only screen and (min-width: 600px) {
      font-size: 16px;
    }
  }
}

.wa-button-container {
  padding: 10px 22px;
  position: fixed;
  right: 30px;
  bottom: 50px;
  background: #425f57;
  @media only screen and (min-width: 600px) {
    padding: 15px 26px 15px 26px;
  }
}
.wa-button-container:hover {
  background: rgb(144, 177, 132);
}
</style>
