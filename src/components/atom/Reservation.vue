<template>
    <!-- Reservasi -->
    <div class="reservasi">
      <div class="text-reservasi">
        <h1>Reservasi Dokter Anda</h1>
        <p>nikmati kemudahan membuat janji temu dengan dokter via MySiloam.</p>
        <h1>Reservasi Medical Check Up Anda</h1>
        <p>
          jelajahi paket kami atau ikuti kuisioner 10 menit untuk mengetahui
          paket medical <br />
          check up mana yang paling cocok untuk Anda.
        </p>
      </div>
      <div class="gambar-reservasi">
        <img src="../../assets/reservasi.png" alt="reservasi" />
      </div>
    </div>
</template>

<script>
export default {
  name: "Reservation",
};
</script>

<style>
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
</style>