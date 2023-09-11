<template>
    <!-- Akses Data Kesehatan -->
    <div class="akses-data">
      <div class="gambar-akses">
        <img src="../../assets/akses-data.png" alt="akses-data" />
      </div>
      <div class="text-akses">
        <div class="text-akses-h1">
          <h1>Akses data kesehatan Anda dimana saja, kapan saja</h1>
        </div>
        <div class="text-box-akses">
          <div class="box-akses">
            <div class="box-akses-img">
              <img src="../../assets/icon-akses/catatan.svg" alt="catatan" />
            </div>
            <div class="box-akses-p">
              <p>Cek hasil laboratorium dan radiologi Anda</p>
            </div>
          </div>
          <div class="box-akses">
            <div class="box-akses-img">
              <img src="../../assets/icon-akses/obat.svg" alt="catatan" />
            </div>
            <div class="box-akses-p">
              <p>Akses riwayat pembelian obat</p>
            </div>
          </div>
          <div class="box-akses">
            <div class="box-akses-img">
              <img src="../../assets/icon-akses/monitoring.svg" alt="catatan" />
            </div>
            <div class="box-akses-p">
              <p>
                Monitor proses pemulangan dan jumlah tagihan berjalan selama
                dirawat inap
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "Access",
};
</script>

<style>
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
</style>