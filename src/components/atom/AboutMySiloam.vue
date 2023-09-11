<template>
    <!-- Tentang Aplikasi MySiloam -->
    <div class="tentang-aplikasi">
      <h1>Tentang Aplikasi MySiloam</h1>
      <p>Ketahui lebih banyak tentang MySiloam</p>
      <iframe
        src="https://www.youtube.com/embed/Ewrb0bmI1XA"
        title="Sehat Lebih Mudah Dengan MySiloam"
      ></iframe>
    </div>
</template>

<script>
export default {
  name: "AboutMySiloam",
};
</script>

<style>
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
</style>