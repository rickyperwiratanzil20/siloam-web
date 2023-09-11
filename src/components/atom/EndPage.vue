<template>
    <!-- end-page -->
    <div class="end-page">
      <img
        src="../../assets/logo-singkat-siloam.png"
        alt="logo-singkat-siloam"
      />
      <h1>"Save Your Time, Improve Your Life"</h1>
      <p>Klik link untuk mengunduh aplikasi</p>
      <div class="app-image">
        <img src="../../assets/Google-Play.png" alt="Google-Play" />
        <img src="../../assets/App-Store.png" alt="App-Store" />
      </div>
    </div>
</template>

<script>
export default {
  name: "EndPage",
};
</script>

<style>
/* end-page */
.end-page {
  background: linear-gradient(
      135deg,
      rgba(0, 57, 121, 0.5),
      rgba(0, 57, 121, 0.5)
    ),
    url(../../assets/background-footer.png);
  background-size: 100%;
  background-repeat: no-repeat;
  height: 500px;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
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
</style>