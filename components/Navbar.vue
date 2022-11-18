<template>
  <nav class="navbar navbar-expand-lg navbar-light navbar-tp">
    <div class="container">
      <img src="~assets/images/logo-anugrah.png" alt="Anugrah Utama Raya" />
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#about-us"
              >About Us</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="#services">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="#pricelist">Pricelist</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="#footer">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.navbar {
  position: sticky;
  top: 0;
  background-color: #fff;
  z-index: 999;
}

img {
  width: 250px;
  height: auto;

  @media only screen and (min-width: 600px) {
    width: 350px;
  }
}

.navbar-tp {
  padding: 10px;

  @media only screen and (min-width: 600px) {
    padding: 30px;
  }
}
</style>
