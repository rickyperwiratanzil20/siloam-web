<template>
    <!-- informasi-tambahan -->
    <div class="informasi-tambahan">
      <div class="tab-atas">
        <div class="info">
          <img src="../../assets/Logo-Siloam.png" alt="Logo-Siloam" />
          <p>
            PT Siloam International Hospitals Tbk (Siloam) merupakan penyedia
            layanan kesehatan terdepan di Indonesia yang memiliki standar
            layanan kesehatan berkualitas di Indonesia.
          </p>
        </div>
        <div class="info">
          <h1>Penghargaan</h1>
          <img src="../../assets/Penghargaan.jpg" alt="penghargaan" />
          <img src="../../assets/Penghargaan2.png" alt="penghargaan" />
        </div>
        <div class="info">
          <h1>Rekan Kerja</h1>
          <div class="gambar-info3">
            <img
              src="../../assets/rekan-kerja/rekan-kerja1.png"
              alt="rekan-kerja1"
            />
            <img
              src="../../assets/rekan-kerja/rekan-kerja2.png"
              alt="rekan-kerja2"
            />
            <img
              src="../../assets/rekan-kerja/rekan-kerja3.png"
              alt="rekan-kerja3"
            />
            <img
              src="../../assets/rekan-kerja/rekan-kerja4.png"
              alt="rekan-kerja4"
            />
          </div>
        </div>
        <div class="info">
          <h1>Download Aplikasi</h1>
          <div class="gambar-info4">
            <img src="../../assets/Google-Play.png" alt="Google-Play" />
            <img src="../../assets/App-Store.png" alt="App-Store" />
          </div>
        </div>
        <div class="info">
          <h1>Ikuti Kami</h1>
          <div class="gambar-info5">
            <img src="../../assets/icon-footer/facebook.svg" alt="facebook" />
            <p>Facebook</p>
          </div>
          <div class="gambar-info5">
            <img src="../../assets/icon-footer/instagram.svg" alt="instagram" />
            <p>Instagram</p>
          </div>
          <div class="gambar-info5">
            <img src="../../assets/icon-footer/linkedin.svg" alt="linkedin" />
            <p>Linkedin</p>
          </div>
          <div class="gambar-info5">
            <img src="../../assets/icon-footer/youtube.svg" alt="youtube" />
            <p>Youtube</p>
          </div>
        </div>
      </div>
      <div class="tab-bawah">
        <ul>
          <li>Tentang Kami</li>
          <li>&#8226; Karir</li>
          <li>&#8226; Hubungan Investor</li>
          <li>&#8226; FAQs</li>
          <li>&#8226; Syarat dan Ketentuan</li>
          <li>&#8226; Kebijakan Privasi</li>
        </ul>
      </div>
      <hr />
    </div>
</template>

<script>
export default {
  name: "AdditionalInformation",
};
</script>

<style>
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
</style>