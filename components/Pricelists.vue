<template>
  <section class="" id="pricelist">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-md-12 mb-4 mb-lg-0">
          <img
            src="~assets/images/sewa-2.jpg"
            class="w-100 shadow-1-strong rounded mb-4"
            alt="Boat on Calm Water"
          />

          <img
            src="~assets/images/jual.jpg"
            class="w-100 shadow-1-strong rounded mb-4"
            alt="Wintry Mountain Landscape"
          />
        </div>

        <div class="col-lg-4 mb-4 mb-lg-0">
          <img
            src="~assets/images/scaffolding_img (1).JPG"
            class="w-100 shadow-1-strong rounded mb-4"
            alt="Wintry Mountain Landscape"
          />
          <img
            src="~assets/images/scaffolding_img (3).JPG"
            class="w-100 shadow-1-strong rounded mb-4"
            alt="Wintry Mountain Landscape"
          />
        </div>

        <div class="col-lg-4 mb-4 mb-lg-0">
          <img
            src="~assets/images/scaffolding_img (2).JPG"
            class="w-100 shadow-1-strong rounded mb-4"
            alt="Wintry Mountain Landscape"
          />
          <!--
          <img
            src="~assets/images/scaffolding_img (4).JPG"
            class="w-100 shadow-1-strong rounded mb-4"
            alt="Wintry Mountain Landscape"
          /> -->
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      pricelists: [
        {
          item: 'MAIN FRAME (MF) 190',
          price: 'Rp.11.500,00 / pcs',
        },
        {
          item: 'MAIN FRAME (MF) 170',
          price: 'Rp.   11.500.00 / pcs',
        },
        {
          item: 'LADDER FRAME (LF) 090',
          price: 'Rp.   11.000.00 / pcs',
        },
        {
          item: 'CROSS BRACE (CB) 220',
          price: 'Rp.     6.000.00 / pcs',
        },
        {
          item: 'CROSS BRACE (CB) 193',
          price: 'Rp.     6.000.00 / pcs',
        },
        {
          item: 'JOINT PIN STANDART',
          price: 'Rp.     2.500.00 / pcs',
        },
        {
          item: 'JACK BASE AJ-40',
          price: 'Rp.     5.000.00 / pcs',
        },
        {
          item: 'JACK BASE AJ-60',
          price: 'Rp.     6.000.00 / pcs',
        },
        {
          item: 'U HEAD JACK AJ-40',
          price: 'Rp.     5.000.00 / pcs',
        },
        {
          item: 'CAT WALK',
          price: 'Rp.   35.000.00 / pcs',
        },
        {
          item: 'TANGGA 170',
          price: 'Rp.   75.000.00 / pcs',
        },
        {
          item: 'TANGGA 190',
          price: 'Rp. 100.000.00 / pcs',
        },
        {
          item: 'PIPA SUPPORT TS 90',
          price: 'Rp.     6.000.00 / pcs',
        },
        {
          item: 'Rp.   35.000.00 / pcs',
          price: 'Rp.     6.000.00 / pcs',
        },
        {
          item: 'RODA 6',
          price: 'Rp. 100.000.00 / set',
        },
        {
          item: 'TIE ROAD',
          price: 'Rp.   10.000.00 / mtr',
        },
        {
          item: 'WING NUT',
          price: 'Rp.     6.000.00 / pcs',
        },
        {
          item: 'PIPA HITAM 1½” x 6MTR',
          price: 'Rp.   30.000.00 / btg',
        },
        {
          item: 'PIPA HITAM 1½” x 4MTR',
          price: 'Rp.   20.000.00 / btg',
        },
        {
          item: 'PIPA HITAM 1½” x 3MTR',
          price: 'Rp.   15.000.00 / btg',
        },
        {
          item: 'SWIVEL CLAMP',
          price: 'Rp.     6.000.00 / pcs',
        },
      ],
    }
  },
}
</script>

<style lang="scss" scoped>
#pricelist {
  padding: 70px 0;
}

table {
  border-radius: 12px;
  font-size: 14px;
  @media only screen and (min-width: 600px) {
    font-size: 16px;
  }

  thead {
    background-color: #425f57;
    color: #fff;
    border-radius: 10px;
  }
}
</style>
