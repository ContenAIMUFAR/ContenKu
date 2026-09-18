<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Halaman Rahasia</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: Arial, sans-serif;
      color: #222;
    }

    .halaman {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }

    #halamanKode {
      background: linear-gradient(135deg, #32105f, #a044ff);
    }

    .kotak-kode {
      width: 100%;
      max-width: 420px;
      padding: 35px 25px;
      text-align: center;
      background: white;
      border-radius: 22px;
      box-shadow: 0 15px 40px rgba(0, 0, 0, 0.3);
    }

    .ikon {
      font-size: 52px;
      margin-bottom: 12px;
    }

    h1,
    h2 {
      margin-top: 0;
    }

    .keterangan {
      color: #666;
      line-height: 1.6;
    }

    input[type="password"],
    input[type="file"] {
      width: 100%;
      margin-top: 10px;
      padding: 14px;
      border: 1px solid #ccc;
      border-radius: 10px;
      font-size: 16px;
    }

    button {
      width: 100%;
      margin-top: 16px;
      padding: 14px;
      border: none;
      border-radius: 10px;
      color: white;
      background: #7224c9;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background: #521491;
    }

    #pesanSalah {
      min-height: 22px;
      margin-top: 14px;
      color: #d00000;
      font-weight: bold;
    }

    #halamanFoto {
      display: none;
      flex-direction: column;
      justify-content: flex-start;
      background: white;
      text-align: center;
    }

    .isi-foto {
      width: 100%;
      max-width: 900px;
    }

    .isi-foto h2 {
      margin-bottom: 8px;
    }

    .isi-foto p {
      color: #666;
    }

    .tempat-gambar {
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 250px;
      margin-top: 20px;
      padding: 10px;
      background: white;
      border: 1px solid #ddd;
      border-radius: 14px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
    }

    #gambarFoto {
      display: none;
      max-width: 100%;
      width: auto;
      height: auto;
      max-height: 75vh;
      object-fit: contain;
      border-radius: 8px;
    }

    #pesanGambar {
      color: #777;
      line-height: 1.6;
    }

    .tombol-kunci {
      width: auto;
      min-width: 170px;
      margin: 22px auto 0;
    }

    .label-file {
      display: block;
      margin-top: 22px;
      font-weight: bold;
      color: #444;
    }

    @media (max-width: 600px) {
      .halaman {
        padding: 15px;
      }

      .kotak-kode {
        padding: 28px 20px;
      }

      .tempat-gambar {
        min-height: 220px;
        padding: 6px;
      }

      #gambarFoto {
        max-height: 70vh;
      }
    }
  </style>
</head>
<body>

  <!-- HALAMAN 1: KODE RAHASIA -->
  <section id="halamanKode" class="halaman">
    <div class="kotak-kode">
      <div class="ikon">🔐</div>

      <h1>Selamat Datang</h1>

      <p class="keterangan">
        Silakan masukkan kode rahasia untuk membuka halaman berikutnya.
      </p>

      <form id="formKode">
        <label for="kodeRahasia">Masukkan kode rahasia</label>

        <input
          id="kodeRahasia"
          type="password"
          placeholder="Masukkan kode rahasia"
          autocomplete="off"
          required
        >

        <button type="submit">🔓 Buka</button>

        <div id="pesanSalah"></div>
      </form>
    </div>
  </section>

  <!-- HALAMAN 2: FOTO -->
  <section id="halamanFoto" class="halaman">
    <div class="isi-foto">
      <h2>Halaman Foto</h2>

      <p>Halaman rahasia berhasil dibuka.</p>

      <label class="label-file" for="pilihGambar">
        Pilih gambar yang ingin ditampilkan:
      </label>

      <input
        id="pilihGambar"
        type="file"
        accept="image/*"
      >

      <div class="tempat-gambar">
        <img id="gambarFoto" alt="Foto halaman rahasia">

        <div id="pesanGambar">
          Silakan pilih gambar Anda terlebih dahulu.
        </div>
      </div>

      <button id="tombolKunci" class="tombol-kunci" type="button">
        🔒 Kunci Lagi
      </button>
    </div>
  </section>

  <script>
    const halamanKode = document.getElementById("halamanKode");
    const halamanFoto = document.getElementById("halamanFoto");
    const formKode = document.getElementById("formKode");
    const kodeRahasia = document.getElementById("kodeRahasia");
    const pesanSalah = document.getElementById("pesanSalah");
    const tombolKunci = document.getElementById("tombolKunci");

    const pilihGambar = document.getElementById("pilihGambar");
    const gambarFoto = document.getElementById("gambarFoto");
    const pesanGambar = document.getElementById("pesanGambar");

    // Kode rahasia
    const kodeBenar = "aku";

    formKode.addEventListener("submit", function(event) {
      event.preventDefault();

      if (kodeRahasia.value.trim() === kodeBenar) {
        halamanKode.style.display = "none";
        halamanFoto.style.display = "flex";
        pesanSalah.textContent = "";
      } else {
        pesanSalah.textContent = "Kode rahasia salah. Silakan coba lagi.";
        kodeRahasia.select();
      }
    });

    // Menampilkan gambar yang dipilih pada halaman 2
    pilihGambar.addEventListener("change", function() {
      const file = pilihGambar.files[0];

      if (!file) {
        return;
      }

      const alamatGambar = URL.createObjectURL(file);

      gambarFoto.src = alamatGambar;
      gambarFoto.style.display = "block";
      pesanGambar.style.display = "none";
    });

    // Kembali ke halaman kode
    tombolKunci.addEventListener("click", function() {
      halamanFoto.style.display = "none";
      halamanKode.style.display = "flex";
      kodeRahasia.value = "";
      pesanSalah.textContent = "";
      kodeRahasia.focus();
    });
  </script>

</body>
</html>
