<template>
    <!-- rumah-sakit-siloam -->
    <div class="rumah-sakit-siloam">
      <div class="gambar-hospital">
        <img
          src="../../assets/rumah-sakit-siloam.png"
          alt="rumah-sakit-siloam"
        />
      </div>
      <div class="text-hospital">
        <h1>Rumah Sakit Siloam</h1>
        <p>
          Siloam Hospitals tersebar di lebih dari 20 kota di Indonesia untuk
          mendukung pemeliharaan kesehatan Anda. Pesan janji temu Anda dengan
          kami.
        </p>
      </div>
    </div>
</template>

<script>
export default {
  name: "SiloamHospital",
};
</script>

<style>
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
</style>