<template>
    <!-- Informasi Rumah Sakit -->
    <div class="informasi-rumah-sakit">
      <h1>Informasi Rumah Sakit</h1>
      <div class="data-informasi">
        <div class="box-informasi">
          <div class="gambar-informasi">
            <img
              src="../../assets/informasi/rumah-sakit.svg"
              alt="rumah-sakit"
            />
          </div>
          <p>
            Temukan rumah sakit Siloam terdekat <br />
            dari tempat Anda.
          </p>
        </div>
        <div class="box-informasi">
          <div class="gambar-informasi">
            <img src="../../assets/informasi/stetoskop.svg" alt="stetoskop" />
          </div>
          <p>Cari & temukan spesialis kami.</p>
        </div>
        <div class="box-informasi">
          <div class="gambar-informasi">
            <img src="../../assets/informasi/paru-paru.svg" alt="paru-paru" />
          </div>
          <p>
            Temukan informasi tentang rumah sakit <br />kami meliputi alamat,
            nomor kontak, <br />dan lain lainnya.
          </p>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "InformationHostpital",
};
</script>

<style>
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
.data-informasi {
  width: 80%;
}
.box-informasi {
  background-color: white;
  width: 300px;
  height: 250px;
  box-shadow: 1px 1px 6px 1px #e0e0e0;
  border-radius: 5px;
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
</style>