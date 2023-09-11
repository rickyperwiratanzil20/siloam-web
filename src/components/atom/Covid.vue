<template>
    <!-- covid-19-app -->
    <div class="covid-19-app">
      <div class="text-covid-19">
        <h1>
          Pesan Test COVID-19 hanya dengan <br />
          beberapa klik
        </h1>
        <div class="box-covid-19">
          <div class="box-covid-p">
            <p>Pilih tes yang Anda perlukan</p>
          </div>
          <div class="box-covid-img">
            <img src="../../assets/icon-covid-19/tangan.svg" alt="tangan" />
          </div>
        </div>
        <div class="box-covid-19">
          <div class="box-covid-p">
            <p>Isi detail dan lengkapi proses</p>
          </div>
          <div class="box-covid-img">
            <img src="../../assets/icon-covid-19/catatan.svg" alt="catatan" />
          </div>
        </div>
        <div class="box-covid-19">
          <div class="box-covid-p">
            <p>Anda siap untuk melakukan tes</p>
          </div>
          <div class="box-covid-img">
            <img src="../../assets/icon-covid-19/benar.svg" alt="benar" />
          </div>
        </div>
      </div>
      <div class="gambar-covid-19">
        <img src="../../assets/covid-19-app.png" alt="covid-19-app" />
      </div>
    </div>
</template>

<script>
export default {
  name: "Covid",
};
</script>

<style>
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
</style>