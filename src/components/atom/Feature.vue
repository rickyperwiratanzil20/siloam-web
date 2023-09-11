<template>
    <!-- Fitur Aplikasi -->
    <div class="fitur-aplikasi">
      <h1>Fitur Aplikasi</h1>
      <div class="scroll-container">
        <div class="gambar-fitur">
          <img src="../../assets/fitur-aplikasi/fitur1.png" alt="fitur1" />
          <img src="../../assets/fitur-aplikasi/fitur2.png" alt="fitur2" />
          <img src="../../assets/fitur-aplikasi/fitur3.png" alt="fitur3" />
          <img src="../../assets/fitur-aplikasi/fitur4.png" alt="fitur4" />
          <img src="../../assets/fitur-aplikasi/fitur5.png" alt="fitur5" />
          <img src="../../assets/fitur-aplikasi/fitur6.png" alt="fitur6" />
          <img src="../../assets/fitur-aplikasi/fitur7.png" alt="fitur7" />
          <img src="../../assets/fitur-aplikasi/fitur8.png" alt="fitur8" />
          <img src="../../assets/fitur-aplikasi/fitur9.png" alt="fitur9" />
          <img src="../../assets/fitur-aplikasi/fitur10.png" alt="fitur10" />
          <img src="../../assets/fitur-aplikasi/fitur11.png" alt="fitur11" />
          <img src="../../assets/fitur-aplikasi/fitur12.png" alt="fitur12" />
          <img src="../../assets/fitur-aplikasi/fitur13.png" alt="fitur13" />
          <img src="../../assets/fitur-aplikasi/fitur14.png" alt="fitur14" />
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "Feature",
};
</script>

<style>
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
  height: 80%;
}
.gambar-fitur {
  display: inline-block;
}
.gambar-fitur img {
  width: 300px;
  margin-right: 22px;
}
</style>