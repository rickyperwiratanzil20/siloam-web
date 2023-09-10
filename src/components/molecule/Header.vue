<template>
  <header>
    <!-- Main-Navigasi -->
    <nav>
      <div class="nav-top">
        <div class="nav-top-left">
          <p>Hubungi Kami</p>
          <p>|</p>
          <img src="../../assets/icon-header/whatsapp.svg" alt="whatsapp" />
          <p>+62 811-8951-181</p>
          <img src="../../assets/icon-header/headphone.svg" alt="headphone" />
          <p>Contact Center: 1-500-181</p>
          <img src="../../assets/icon-header/instagram.svg" alt="instagram" />
          <p>siloamhospitals</p>
          <img src="../../assets/icon-header/facebook.svg" alt="facebook" />
          <p>Siloam Hospitals</p>
        </div>
        <div class="nav-top-center">
          <img src="../../assets/icon-header/ambulance.svg" alt="ambulance" />
          <p>For emergency 1-500-911</p>
        </div>
        <div class="nav-top-right">
          <img src="../../assets/icon-header/global.svg" alt="global" />
          <p>ID</p>
        </div>
      </div>
      <div class="nav-bottom">
        <div class="nav-bottom-left">
          <img src="../../assets/Logo-Siloam.png" alt="Logo-Siloam" />
          <p>Buat Janji Temu</p>
          <p>Medical Check Up</p>
          <p>Laboratorium & Radiologi</p>
          <p>Rumah Sakit & Pusat Kami</p>
          <p>Paket Medis</p>
          <p>Informasi Siloam</p>
        </div>
        <div class="nav-bottom-right">
          <img src="../../assets/icon-header/search.svg" alt="search" />
          <div class="login-button">
            <p>Login</p>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
/* Nav */
nav {
  position: fixed;
  top: 0;
  width: 1300px;
  border-bottom: 0.1px solid grey;
}
.nav-top {
  padding: 7px;
  background-color: #1e266d;
  color: white;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}
.nav-top-left {
  display: flex;
}
.nav-top-left p {
  margin-right: 30px;
  margin-left: 5px;
}
.nav-top-center {
  background: #ff5c5d;
  border: 1px solid #ff5c5d;
  color: #fff !important;
  padding: 5px;
  padding-left: 10px;
  padding-right: 10px;
  border-radius: 5px;
  display: flex;
}
.nav-top-center p {
  margin-left: 10px;
}
.nav-top-right {
  display: flex;
  align-items: center;
}
.nav-top-right p {
  margin-left: 10px;
}
.nav-bottom {
  padding: 5px;
  background-color: white;
  color: #2f495e;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.nav-bottom-left {
  display: flex;
  align-items: center;
  width: 100%;
}
.nav-bottom-left img {
  width: 150px;
}
.nav-bottom-right {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  width: 25%;
}
.login-button {
  background-color: #1e266d;
  width: 100px;
  height: 30px;
  display: flex;
  align-items: center;
  border-radius: 5px;
}
.login-button p {
  color: white;
}
</style>
