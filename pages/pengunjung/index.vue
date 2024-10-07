<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">LAPORAN</h2>
        <div class="my-3">
          <input type="search" class="form-control form-control-lg rounded-5" placeholder="Filter...">
        </div>
        <div class="my-3 text-muted">Menampilkan 1 dari 1</div>
        <table class="table">
          <thead>
            <tr>
              <td>NO</td>
              <td>NAMA</td>
              <td>KELAS</td>
              <td>HARI/TANGGAL/JAM</td>
              <td>KELUHAN</td>
              <td>RIWAYAT</td>
              <td>TINDAKAN</td>
              <td>KETERANGAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1.</td>
              <td>PIA RIPIANI</td>
              <td>XII PPLG 3</td>
              <td>Kamis, 25 september 2024, 23.31.00</td>
              <td>PUSING</td>
              <td>-</td>
              <td>TIDAK</td>
              <td>-</td>
            </tr>
          </tbody>
        </table>
        <div class="text-end">
            <button type="submit" class="btn btn-white btn-lg rounded-5 px-5">KIRIM</button>       
          </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-fluid {
  background-color: #BC5959;
  height: 100vh;
}
.btn {
  background-color: hsl(0, 0%, 85%);
}
</style>
