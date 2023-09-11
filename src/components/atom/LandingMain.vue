<template>
    <!-- Landing Main -->
    <div class="landing-main">
      <div class="box-white"></div>
      <div class="landing-main-left">
        <div class="left-text">
          <img src="../../assets/MySiloam-Image.png" alt="MySiloam-Image" />
          <p class="text-grey">Dibuat oleh Siloam Hospitals, untuk</p>
          <h1 class="text-blue">
            Mempermudah Perjalanan <br />
            Kesehatan Anda
          </h1>
          <p class="text-grey">Klik link untuk mengunduh aplikasi</p>
        </div>
        <div class="app-image">
          <img src="../../assets/Google-Play.png" alt="Google-Play" />
          <img src="../../assets/App-Store.png" alt="App-Store" />
        </div>
      </div>
      <div class="landing-main-right">
        <img src="../../assets/Smartphone-Siloam.png" alt="Smartphone-Siloam" />
      </div>
    </div>
</template>

<script>
export default {
  name: "LandingMain",
};
</script>

<style>
/* landing-main */
.landing-main {
  background-image: url(../../assets/Background-Image-First-Page.png);
  background-size: 100%;
  background-repeat: no-repeat;
  height: 700px;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  z-index: -1;
}
.box-white {
  position: absolute;
  bottom: 4;
  width: 1000px;
  height: 1000px;
  background-color: white;
  transform: rotate(45deg);
  border-radius: 50px;
  right: 70%;
  z-index: 0;
}
.landing-main-left {
  width: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 10px;
  z-index: 1;
}
.landing-main-right {
  width: 50%;
  display: flex;
  z-index: 1;
}
.text-grey {
  margin-top: 20px;
  font-size: 16px;
  line-height: 25px;
  color: #848485;
}
.text-blue {
  font-size: 32px;
  font-weight: 1000;
  line-height: 40px;
  color: #1e266d;
}
.landing-main-left .left-text img {
  width: 300px;
}
.landing-main-left .app-image {
  width: 72%;
  margin-top: 10px;
}
.landing-main-left .app-image img {
  width: 150px;
}
.landing-main-right img {
  width: 400px;
}
</style>