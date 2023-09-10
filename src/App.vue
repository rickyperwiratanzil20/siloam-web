<template>
  <Header></Header>
  <Main></Main>
  <Footer></Footer>
</template>

<script>
import Header from "./components/molecule/Header.vue";
import Main from "./components/molecule/Main.vue";
import Footer from "./components/molecule/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style>
/* Body */
* {
  margin: 0 auto;
  font-family: Mulish, sans-serif;
  font-size: 12px;
}
body {
  width: 1300px;
}

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

/* navigation */
.navigation {
  margin: 10px;
  margin-top: 100px;
}

/* landing-main */
.landing-main {
  background-image: url(./assets/Background-Image-First-Page.png);
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
  margin-top: 10px;
}
.landing-main-left .app-image img {
  width: 150px;
}
.landing-main-right img {
  width: 400px;
}

/* tentang-aplikasi */
.tentang-aplikasi {
  background-color: #eff7ff !important;
  text-align: center;
}
.tentang-aplikasi h1 {
  color: #1e266d;
  font-weight: 1000;
  line-height: 40px;
  font-size: 32px;
  padding-top: 70px;
}
.tentang-aplikasi p {
  color: #848485;
  font-size: 16px;
  line-height: 25px;
  padding-top: 5px;
  padding-bottom: 20px;
}
.tentang-aplikasi iframe {
  width: 900px;
  height: 500px;
  margin-bottom: 100px;
}

/* fitur-aplikasi */
.fitur-aplikasi {
  background-color: #1e266d;
  text-align: center;
  height: 700px;
}
.fitur-aplikasi h1 {
  font-weight: 1000;
  line-height: 40px;
  color: #fff !important;
  font-size: 32px;
  padding-top: 70px;
}
.scroll-container {
  overflow: auto;
  white-space: nowrap;
  padding: 5px 00px 5px 0px;
  margin: 30px;
  height: 100%;
}
.gambar-fitur {
  display: inline-block;
}
.gambar-fitur img {
  width: 300px;
  margin-right: 22px;
}

/* mysiloam */
.mysiloam {
  height: 500px;
  display: flex;
  align-items: center;
}
.mysiloam-image-app {
  height: 80%;
}
.mysiloam .text-data {
  height: 50%;
  width: 50%;
  overflow: visible;
  text-align: justify;
}
.mysiloam .text-data p {
  font-size: 18px;
  color: #848485;
  margin-top: 10px;
  line-height: 25px;
}
.mysiloam .text-data img {
  width: 300px;
}

/* Informasi Rumah Sakit */
.informasi-rumah-sakit {
  height: 400px;
  background-color: #eff7ff !important;
}
.informasi-rumah-sakit h1 {
  color: #1e266d;
  font-weight: 1000;
  line-height: 40px;
  font-size: 32px;
  text-align: center;
  padding-top: 30px;
  padding-bottom: -50px;
}
.informasi-rumah-sakit .data-informasi {
  height: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.box-informasi {
  background-color: white;
  width: 300px;
  height: 250px;
}
.box-informasi p {
  width: 100%;
  text-align: center;
  color: #848485;
  font-size: 16px;
  line-height: 25px;
}
.gambar-informasi {
  width: 100%;
  display: flex;
}
.gambar-informasi img {
  height: 150px;
}

/* Reservasi */
.reservasi {
  padding: 50px;
  height: 500px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.gambar-reservasi {
  width: 50%;
}
.gambar-reservasi img {
  width: 100%;
}
.text-reservasi {
  width: 50%;
}
.text-reservasi h1 {
  text-align: right;
  color: #1e266d;
  font-weight: 1000;
  line-height: 40px;
  font-size: 32px;
  margin-top: 20px;
}
.text-reservasi p {
  text-align: right;
  color: #848485;
  font-size: 16px;
  line-height: 25px;
}

/* akses-data */
.akses-data {
  background-color: rgb(245, 245, 245);
  height: 600px;
  display: flex;
  align-items: center;
}
.gambar-akses {
  width: 50%;
  display: flex;
}
.gambar-akses img {
  width: 70%;
}
.text-akses {
  width: 60%;
  height: 70%;
  margin-right: 80px;
}
.text-akses h1 {
  color: #1e266d;
  font-weight: 1000;
  line-height: 40px;
  font-size: 32px;
}
.text-box-akses {
  margin-top: 30px;
}
.box-akses {
  padding: 10px;
  color: #848485;
  background-color: white;
  margin-top: 20px;
  border-radius: 5px;
  box-shadow: 0 10px 25px #cecece;
  display: flex;
  align-items: center;
}
.box-akses-p {
  width: 100%;
  margin-left: 20px;
}
.box-akses p {
  font-size: 15px;
}
.box-akses img {
  width: 50px;
}

/* covid-19-app */
.covid-19-app {
  height: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(227, 227, 227);
}
.gambar-covid-19 {
  width: 50%;
  display: flex;
}
.gambar-covid-19 img {
  width: 60%;
}
.text-covid-19 {
  width: 50%;
  margin-left: 50px;
}
.text-covid-19 h1 {
  color: #1e266d;
  font-weight: 1000;
  line-height: 40px;
  font-size: 32px;
}
.box-covid-19 {
  background-color: white;
  padding: 10px;
  color: #848485;
  margin-top: 10px;
  border-radius: 5px;
  box-shadow: 0 10px 25px #cecece;
  display: flex;
  align-items: center;
}
.box-covid-p {
  width: 100%;
}
.box-covid-img {
}
.box-covid-19 p {
  font-size: 15px;
  float: right;
  margin-right: 20px;
}
.box-covid-19 img {
  width: 50px;
}

/* rumah-sakit-siloam */
.rumah-sakit-siloam {
  height: 400px;
  margin: 30px auto;
  display: flex;
  align-items: center;
}
.gambar-hospital {
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.gambar-hospital img {
  width: 100%;
}
.text-hospital {
}
.text-hospital h1 {
  color: #1e266d;
  font-weight: 1000;
  line-height: 40px;
  font-size: 32px;
}
.text-hospital p {
  color: #848485;
  font-size: 16px;
  line-height: 25px;
}

/* end-page */
.end-page {
  background: linear-gradient(
      135deg,
      rgba(0, 57, 121, 0.5),
      rgba(0, 57, 121, 0.5)
    ),
    url(./assets/background-footer.png);
  background-size: 100%;
  background-repeat: no-repeat;
  height: 500px;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color: red;
}
.end-page h1 {
  font-weight: 1000;
  line-height: 40px;
  font-size: 32px;
  color: white;
}
.end-page p {
  font-size: 16px;
  line-height: 25px;
  color: white;
}
.end-page .app-image {
  margin-top: 10px;
}
.end-page .app-image img {
  width: 150px;
}

/* Privacy */
.privacy {
  text-align: center;
  margin: 0 auto;
}
.privacy h3 {
  font-size: 15px;
  margin-top: 20px;
  margin-bottom: 10px;
  color: #1e266d;
  cursor: pointer;
  font-weight: 600;
}

/* Informasi-Tambahan */
.informasi-tambahan {
  height: 300px;
}
.tab-atas {
  display: flex;
}
.info {
  width: 250px;
  height: 200px;
  text-align: center;
  margin: 10px;
  font-weight: 700;
  color: #2f495e;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
}
.info h1 {
  font-size: 15px;
}
.info img {
  width: 250px;
}
.info p {
  color: #6c6c6d;
  text-align: left;
  font-size: 15px;
}
.gambar-info3 img {
  width: 100px;
}
.gambar-info4 img {
  width: 150px;
}
.gambar-info5 {
  display: flex;
}
.gambar-info5 img {
  width: 20px;
  margin-right: 10px;
}
.tab-bawah {
  margin-top: 10px;
  margin-bottom: 20px;
}
.tab-bawah ul {
  text-align: center;
}
.tab-bawah ul li {
  display: inline;
  margin-left: 10px;
  font-size: 15px;
  color: #848485;
}

/* footer */
footer {
  text-align: center;
  margin-bottom: 20px;
  font-size: 15px;
  color: #848485;
}
</style>
