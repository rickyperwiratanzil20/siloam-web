<template>
    <!-- MySiloam -->
    <div class="mysiloam">
      <img
        class="mysiloam-image-app"
        src="../../assets/MySiloam-ImageApp.png"
        alt="MySiloam-ImageApp"
      />
      <div class="text-data">
        <img src="../../assets/MySiloam-Image.png" alt="MySiloam" />
        <p>
          Lahir melalui komitmen kami untuk terus meningkatkan layanan kami
          kepada Anda, aplikasi ini menawarkan kemudahan dalam menjaga kesehatan
          Anda saat bepergian karena Anda dapat membuat janji dengan dokter Anda
          dalam beberapa klik di mana saja, kapan saja.
          <br />Untuk lebih meningkatkan pengalaman perawatan kesehatan Anda,
          kami juga memberi Anda informasi tentang rumah sakit kami, membantu
          Anda dalam memfasilitasi pemesanan pemeriksaan kesehatan Anda, akses
          riwayat kesehatan Anda dan memberi Anda tips & artikel kesehatan yang
          diperbarui secara berkala.
        </p>
      </div>
    </div>
</template>

<script>
export default {
  name: "MySiloam",
};
</script>

<style>
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
</style>