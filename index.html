
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SmartPocket - Keuangan Mahasiswa</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f7fb;
  color: #243047;
}

header {
  background: #244c75;
  color: white;
  padding: 25px 7%;
}

header h1 {
  margin: 0;
  font-size: 28px;
}

header p {
  margin: 8px 0 0;
  color: #dce9f6;
}

main {
  max-width: 1100px;
  margin: 28px auto;
  padding: 0 18px;
}

.welcome {
  margin-bottom: 22px;
}

.welcome h2 {
  margin-bottom: 5px;
}

.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 15px;
}

.card, .section {
  background: white;
  padding: 20px;
  border-radius: 14px;
  box-shadow: 0 3px 12px #20304012;
}

.card p {
  color: #718096;
  margin: 0 0 12px;
}

.card h2 {
  margin: 0;
  font-size: 24px;
}

.green { color: #15966b; }
.red { color: #d9534f; }
.blue { color: #2869a5; }

.section {
  margin-top: 20px;
}

.section h3 {
  margin-top: 0;
}

form {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px;
}

input, select, button {
  width: 100%;
  padding: 12px;
  border: 1px solid #d8e0e9;
  border-radius: 8px;
  font-size: 14px;
}

button {
  background: #2869a5;
  color: white;
  border: 0;
  cursor: pointer;
  font-weight: bold;
}

button:hover {
  background: #1d527f;
}

.full {
  grid-column: 1 / -1;
}

.small {
  font-size: 13px;
  color: #718096;
}

.progress {
  height: 12px;
  background: #e8edf3;
  border-radius: 20px;
  overflow: hidden;
  margin: 12px 0;
}

.progress div {
  height: 100%;
  background: #2b9b78;
  width: 0%;
  transition: .3s;
}

.chart-wrap {
  position: relative;
  width: 100%;
  height: 300px;
}

canvas {
  width: 100%;
  height: 100%;
}

.filter-row {
  display: flex;
  gap: 10px;
  align-items: center;
  margin-bottom: 15px;
}

.filter-row select {
  max-width: 230px;
}

.table-wrap {
  overflow-x: auto;
}

table {
  width: 100%;
  border-collapse: collapse;
  min-width: 650px;
}

th, td {
  text-align: left;
  padding: 12px 8px;
  border-bottom: 1px solid #edf0f4;
  font-size: 14px;
}

th {
  color: #718096;
}

.delete {
  background: #fff0ef;
  color: #c13f3b;
  padding: 7px;
  border-radius: 6px;
  width: auto;
}

.stat {
  line-height: 1.9;
  margin-top: 12px;
}

footer {
  text-align: center;
  color: #8290a0;
  padding: 28px;
  font-size: 13px;
}

@media(max-width:650px) {
  .cards {
    grid-template-columns: 1fr;
  }

  form {
    grid-template-columns: 1fr;
  }

  .full {
    grid-column: auto;
  }

  .section {
    padding: 16px;
  }

  .filter-row {
    flex-direction: column;
    align-items: stretch;
  }

  .filter-row select {
    max-width: none;
  }
}
</style>
</head>

<body>

<header>
  <h1>SmartPocket</h1>
  <p>Kelola uang saku, rencanakan kebutuhan, dan capai target tabunganmu.</p>
</header>

<main>

<div class="welcome">
  <h2>Dashboard Keuangan Mahasiswa</h2>
  <p class="small">Pantau kondisi keuanganmu dengan perhitungan matematika.</p>
</div>

<div class="cards">
  <div class="card">
    <p>Saldo Saat Ini</p>
    <h2 class="blue" id="saldo">Rp0</h2>
  </div>

  <div class="card">
    <p>Total Pemasukan</p>
    <h2 class="green" id="pemasukan">Rp0</h2>
  </div>

  <div class="card">
    <p>Total Pengeluaran</p>
    <h2 class="red" id="pengeluaran">Rp0</h2>
  </div>
</div>

<div class="section">
  <h3>Tambah Transaksi</h3>

  <form id="formTransaksi">

    <select id="jenis" required>
      <option value="masuk">Pemasukan</option>
      <option value="keluar">Pengeluaran</option>
    </select>

    <input id="jumlah" type="number" min="1"
      placeholder="Jumlah uang (Rp)" required>

    <input id="keterangan" type="text"
      placeholder="Keterangan transaksi" required>

    <select id="kategori">
      <option value="Uang saku">Uang saku</option>
      <option value="Makan">Makan</option>
      <option value="Transportasi">Transportasi</option>
      <option value="Kuliah">Kebutuhan kuliah</option>
      <option value="Hiburan">Hiburan</option>
      <option value="Tabungan">Tabungan</option>
      <option value="Lainnya">Lainnya</option>
    </select>

    <input id="tanggal" type="date" required>

    <button class="full" type="submit">
      Simpan Transaksi
    </button>

  </form>
</div>

<div class="section">
  <h3>Perencanaan Anggaran</h3>
  <p class="small">Tentukan batas pengeluaran yang ingin kamu tetapkan.</p>

  <input id="anggaran" type="number" min="0"
    placeholder="Contoh: 1000000">

  <button onclick="simpanAnggaran()" style="margin-top:10px">
    Simpan Anggaran
  </button>

  <div class="progress">
    <div id="barAnggaran"></div>
  </div>

  <p id="infoAnggaran" class="small">
    Belum ada anggaran yang ditetapkan.
  </p>
</div>

<div class="section">
  <h3>Target Tabungan</h3>

  <input id="target" type="number" min="0"
    placeholder="Masukkan target tabungan (Rp)">

  <button onclick="simpanTarget()" style="margin-top:10px">
    Simpan Target
  </button>

  <div class="progress">
    <div id="barTarget"></div>
  </div>

  <p id="infoTarget" class="small">
    Tentukan target tabunganmu.
  </p>
</div>

<div class="section">
  <h3>Grafik Keuangan Bulanan</h3>

  <p class="small">
    Perbandingan jumlah pemasukan dan pengeluaran selama enam bulan terakhir.
  </p>

  <div class="chart-wrap">
    <canvas id="grafikKeuangan"></canvas>
  </div>

  <p class="small">
    Biru: pemasukan | Merah: pengeluaran.
  </p>
</div>

<div class="section">
  <h3>Analisis Keuangan</h3>
  <div class="stat" id="analisis"></div>
</div>

<div class="section">
  <h3>Riwayat Transaksi</h3>

  <div class="filter-row">
    <label for="filterTanggal">Tampilkan:</label>

    <select id="filterTanggal" onchange="tampilkan()">
      <option value="semua">Semua transaksi</option>
      <option value="hari">Hari ini</option>
      <option value="bulan">Bulan ini</option>
    </select>
  </div>

  <div class="table-wrap">
    <table>
      <thead>
        <tr>
          <th>Tanggal</th>
          <th>Keterangan</th>
          <th>Kategori</th>
          <th>Jenis</th>
          <th>Jumlah</th>
          <th>Aksi</th>
        </tr>
      </thead>

      <tbody id="riwayat"></tbody>
    </table>
  </div>

  <p id="kosong" class="small">
    Belum ada transaksi.
  </p>
</div>

</main>

<footer>
  SmartPocket | Media Pengelolaan Uang Saku Mahasiswa Berbasis Matematika
</footer>

<script>

function tanggalHariIni() {
  let d = new Date();
  let tahun = d.getFullYear();
  let bulan = String(d.getMonth()+1).padStart(2,"0");
  let hari = String(d.getDate()).padStart(2,"0");
  return `${tahun}-${bulan}-${hari}`;
}

let transaksi = JSON.parse(
  localStorage.getItem("transaksiSmartPocket") || "[]"
);

let anggaran = Number(
  localStorage.getItem("anggaranSmartPocket") || 0
);

let target = Number(
  localStorage.getItem("targetSmartPocket") || 0
);

// Menyesuaikan transaksi lama yang belum memiliki tanggal.
transaksi.forEach(t => {
  if (!t.tanggal) {
    t.tanggal = tanggalHariIni();
  }
});

document.getElementById("tanggal").value = tanggalHariIni();

function rupiah(angka) {
  return new Intl.NumberFormat("id-ID", {
    style: "currency",
    currency: "IDR",
    maximumFractionDigits: 0
  }).format(angka);
}

function simpanData() {
  localStorage.setItem(
    "transaksiSmartPocket",
    JSON.stringify(transaksi)
  );
}

function formatTanggal(tanggal) {
  if (!tanggal) return "-";

  let bagian = tanggal.split("-");
  return bagian[2] + "/" + bagian[1] + "/" + bagian[0];
}

function hapus(i) {
  if (confirm("Hapus transaksi ini?")) {
    transaksi.splice(i,1);
    simpanData();
    tampilkan();
  }
}

function simpanAnggaran() {
  let nilai = Number(
    document.getElementById("anggaran").value
  );

  if (nilai < 0) {
    alert("Anggaran tidak boleh negatif.");
    return;
  }

  anggaran = nilai;

  localStorage.setItem("anggaranSmartPocket", anggaran);
  tampilkan();
}

function simpanTarget() {
  let nilai = Number(
    document.getElementById("target").value
  );

  if (nilai < 0) {
    alert("Target tidak boleh negatif.");
    return;
  }

  target = nilai;

  localStorage.setItem("targetSmartPocket", target);
  tampilkan();
}

function gambarGrafik() {
  let canvas = document.getElementById("grafikKeuangan");
  let ctx = canvas.getContext("2d");

  let lebar = canvas.clientWidth;
  let tinggi = canvas.clientHeight;
  let rasio = window.devicePixelRatio || 1;

  canvas.width = lebar * rasio;
  canvas.height = tinggi * rasio;

  ctx.setTransform(rasio,0,0,rasio,0,0);
  ctx.clearRect(0,0,lebar,tinggi);

  let data = [];

  for (let i=5; i>=0; i--) {
    let d = new Date();
    d.setDate(1);
    d.setMonth(d.getMonth()-i);

    let tahun = d.getFullYear();
    let bulan = String(d.getMonth()+1).padStart(2,"0");

    let idBulan = `${tahun}-${bulan}`;

    let masuk = transaksi
      .filter(t => t.jenis==="masuk" && t.tanggal.startsWith(idBulan))
      .reduce((a,b)=>a+b.jumlah,0);

    let keluar = transaksi
      .filter(t => t.jenis==="keluar" && t.tanggal.startsWith(idBulan))
      .reduce((a,b)=>a+b.jumlah,0);

    data.push({
      label: d.toLocaleDateString("id-ID",{month:"short"}),
      masuk: masuk,
      keluar: keluar
    });
  }

  let max = Math.max(
    1,
    ...data.map(d=>Math.max(d.masuk,d.keluar))
  );

  let kiri = 45;
  let kanan = 12;
  let atas = 18;
  let bawah = 42;

  let areaW = lebar-kiri-kanan;
  let areaH = tinggi-atas-bawah;

  ctx.font = "11px Arial";
  ctx.fillStyle = "#718096";
  ctx.strokeStyle = "#e8edf3";
  ctx.lineWidth = 1;

  for (let i=0;i<=4;i++) {
    let y = atas + areaH*i/4;

    ctx.beginPath();
    ctx.moveTo(kiri,y);
    ctx.lineTo(lebar-kanan,y);
    ctx.stroke();

    let nilai = max*(1-i/4);

    ctx.textAlign = "right";
    ctx.fillText(
      nilai>=1000000
        ? (nilai/1000000).toFixed(1)+"jt"
        : Math.round(nilai/1000)+"rb",
      kiri-7,
      y+4
    );
  }

  let kelompok = areaW/data.length;
  let lebarBar = Math.min(16,kelompok*0.25);

  data.forEach((d,i)=>{
    let tengah = kiri+kelompok*(i+0.5);

    let tinggiMasuk = d.masuk/max*areaH;
    let tinggiKeluar = d.keluar/max*areaH;

    ctx.fillStyle = "#2869a5";
    ctx.fillRect(
      tengah-lebarBar-2,
      atas+areaH-tinggiMasuk,
      lebarBar,
      tinggiMasuk
    );

    ctx.fillStyle = "#d9534f";
    ctx.fillRect(
      tengah+2,
      atas+areaH-tinggiKeluar,
      lebarBar,
      tinggiKeluar
    );

    ctx.fillStyle = "#718096";
    ctx.textAlign = "center";
    ctx.fillText(d.label,tengah,tinggi-15);
  });
}

function tampilkan() {
  let masuk = transaksi
    .filter(t=>t.jenis==="masuk")
    .reduce((a,b)=>a+b.jumlah,0);

  let keluar = transaksi
    .filter(t=>t.jenis==="keluar")
    .reduce((a,b)=>a+b.jumlah,0);

  let saldo = masuk-keluar;

  document.getElementById("saldo").textContent = rupiah(saldo);
  document.getElementById("pemasukan").textContent = rupiah(masuk);
  document.getElementById("pengeluaran").textContent = rupiah(keluar);

  let persen = masuk>0 ? keluar/masuk*100 : 0;

  let jumlahTransaksi = transaksi.filter(
    t=>t.jenis==="keluar"
  ).length;

  let rata = jumlahTransaksi>0 ? keluar/jumlahTransaksi : 0;

  document.getElementById("analisis").innerHTML =
    "Persentase pengeluaran: <b>"+persen.toFixed(2)+"%</b><br>"+
    "Persentase sisa uang: <b>"+(100-persen).toFixed(2)+"%</b><br>"+
    "Rata-rata pengeluaran per transaksi: <b>"+rupiah(rata)+"</b>";

  document.getElementById("anggaran").value = anggaran || "";
  document.getElementById("target").value = target || "";

  let persenAnggaran = anggaran>0 ? keluar/anggaran*100 : 0;

  document.getElementById("barAnggaran").style.width =
    Math.min(persenAnggaran,100)+"%";

  document.getElementById("infoAnggaran").textContent =
    anggaran
      ? "Terpakai "+rupiah(keluar)+" dari "+rupiah(anggaran)+
        " ("+persenAnggaran.toFixed(1)+"%)."
      : "Belum ada anggaran yang ditetapkan.";

  let tabungan = transaksi
    .filter(t=>t.kategori==="Tabungan" && t.jenis==="keluar")
    .reduce((a,b)=>a+b.jumlah,0);

  let persenTarget = target>0 ? tabungan/target*100 : 0;

  document.getElementById("barTarget").style.width =
    Math.min(persenTarget,100)+"%";

  document.getElementById("infoTarget").textContent =
    target
      ? "Tabungan tercatat "+rupiah(tabungan)+" dari target "+
        rupiah(target)+" ("+persenTarget.toFixed(1)+"%)."
      : "Tentukan target tabunganmu.";

  let filter = document.getElementById("filterTanggal").value;
  let hariIni = tanggalHariIni();
  let bulanIni = hariIni.substring(0,7);

  let daftar = transaksi
    .map((t,i)=>({...t,index:i}))
    .filter(t=>{
      if(filter==="hari") return t.tanggal===hariIni;
      if(filter==="bulan") return t.tanggal.startsWith(bulanIni);
      return true;
    })
    .sort((a,b)=>b.tanggal.localeCompare(a.tanggal));

  let tbody = document.getElementById("riwayat");
  tbody.innerHTML = "";

  document.getElementById("kosong").style.display =
    daftar.length ? "none" : "block";

  daftar.forEach(t=>{
    let row = document.createElement("tr");

    let values = [
      formatTanggal(t.tanggal),
      t.keterangan,
      t.kategori,
      t.jenis==="masuk" ? "Pemasukan" : "Pengeluaran",
      rupiah(t.jumlah)
    ];

    values.forEach((v,index)=>{
      let cell = document.createElement("td");
      cell.textContent = v;

      if(index===3) {
        cell.style.color =
          t.jenis==="masuk" ? "#15966b" : "#d9534f";
      }

      row.appendChild(cell);
    });

    let cell = document.createElement("td");
    let btn = document.createElement("button");

    btn.textContent = "Hapus";
    btn.className = "delete";
    btn.onclick = ()=>hapus(t.index);

    cell.appendChild(btn);
    row.appendChild(cell);
    tbody.appendChild(row);
  });

  gambarGrafik();
}

document.getElementById("formTransaksi")
.addEventListener("submit",function(e){
  e.preventDefault();

  let jumlah = Number(
    document.getElementById("jumlah").value
  );

  if(jumlah<=0) {
    alert("Masukkan jumlah uang yang valid.");
    return;
  }

  let tanggal = document.getElementById("tanggal").value;

  if(!tanggal) {
    alert("Pilih tanggal transaksi.");
    return;
  }

  transaksi.unshift({
    jenis: document.getElementById("jenis").value,
    jumlah: jumlah,
    keterangan: document.getElementById("keterangan").value,
    kategori: document.getElementById("kategori").value,
    tanggal: tanggal
  });

  simpanData();
  this.reset();

  document.getElementById("tanggal").value = tanggalHariIni();

  tampilkan();
});

window.addEventListener("resize",gambarGrafik);

simpanData();
tampilkan();

</script>
</body>
</html>
