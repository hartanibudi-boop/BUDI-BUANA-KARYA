
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#163d30">
  <meta name="description" content="PT. Budi Buana Karya — penyedia bibit tanaman dan komoditas pertanian dari Kalimantan Selatan dengan jaringan petani se-Nusantara.">
  <title>PT. Budi Buana Karya | Mitra Agribisnis Nusantara</title>
  <style>
    :root {
      --green: #163d30;
      --green-light: #eaf0e9;
      --gold: #c5a567;
      --cream: #faf9f5;
      --text: #28352e;
      --muted: #68736b;
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: var(--text);
      background: var(--cream);
      line-height: 1.7;
    }
    a { color: inherit; text-decoration: none; }
    .container { width: min(1120px, 90%); margin: auto; }

    header {
      background: var(--cream);
      position: sticky;
      top: 0;
      z-index: 10;
      border-bottom: 1px solid #e8e7df;
    }
    nav {
      min-height: 78px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
    }
    .brand { color: var(--green); font-weight: 800; }
    .brand small {
      display: block;
      font-size: 10px;
      letter-spacing: 2px;
      color: var(--muted);
    }
    .navlinks { display: flex; gap: 24px; align-items: center; }
    .navlinks a { font-size: 14px; }
    .button {
      display: inline-block;
      padding: 13px 20px;
      border-radius: 5px;
      background: var(--gold);
      color: #183326;
      font-weight: 700;
      border: 0;
    }
    .button:hover { filter: brightness(.94); }

    .hero {
      background: var(--green);
      color: white;
      padding: 100px 0 90px;
      position: relative;
      overflow: hidden;
    }
    .hero:after {
      content: "✳";
      position: absolute;
      right: 4%;
      top: 0;
      font-size: 300px;
      color: #ffffff09;
    }
    .eyebrow {
      color: var(--gold);
      letter-spacing: 3px;
      text-transform: uppercase;
      font-size: 12px;
      font-weight: bold;
    }
    h1 {
      font-family: Georgia, "Times New Roman", serif;
      font-size: clamp(38px, 6vw, 68px);
      font-weight: 500;
      line-height: 1.13;
      max-width: 750px;
      margin: 20px 0;
    }
    .hero p { max-width: 620px; color: #e0e9e1; }
    .hero-actions { display: flex; gap: 14px; flex-wrap: wrap; margin-top: 28px; }
    .button-outline {
      border: 1px solid #ffffff80;
      color: white;
      padding: 12px 20px;
      border-radius: 5px;
    }

    section { padding: 78px 0; }
    .section-head { max-width: 680px; margin-bottom: 35px; }
    .section-head h2 {
      font: 500 clamp(30px, 4vw, 43px)/1.2 Georgia, serif;
      color: var(--green);
      margin: 8px 0 14px;
    }
    .section-head p { color: var(--muted); }

    .products {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }
    .product {
      background: white;
      border: 1px solid #e9e8df;
      border-radius: 8px;
      padding: 28px;
    }
    .product .number { color: var(--gold); font-size: 13px; }
    .product h3 { color: var(--green); margin-bottom: 8px; }
    .product p { color: var(--muted); font-size: 14px; }
    .product a {
      display: inline-block;
      color: var(--green);
      font-weight: bold;
      margin-top: 12px;
      border-bottom: 1px solid var(--gold);
    }

    .about { background: var(--green-light); }
    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 55px;
      align-items: start;
    }
    .about h2 {
      font: 500 clamp(30px, 4vw, 42px)/1.25 Georgia, serif;
      color: var(--green);
    }
    .values {
      display: grid;
      gap: 16px;
      margin-top: 25px;
    }
    .value {
      background: #ffffffa8;
      padding: 18px;
      border-left: 3px solid var(--gold);
    }
    .value strong { color: var(--green); }

    .cta {
      text-align: center;
      background: var(--green);
      color: white;
    }
    .cta h2 {
      font: 500 clamp(30px, 4vw, 44px)/1.2 Georgia, serif;
    }
    .cta p { color: #dce5dd; max-width: 600px; margin: 16px auto 25px; }

    footer { background: #102d23; color: #dce5dd; padding: 32px 0; }
    .footer-row {
      display: flex;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap;
    }
    footer small { color: #b6c5ba; }

    @media (max-width: 760px) {
      .navlinks a:not(.button) { display: none; }
      .navlinks { gap: 8px; }
      .navlinks .button { padding: 10px 12px; font-size: 12px; }
      .hero { padding: 75px 0; }
      section { padding: 55px 0; }
      .products, .about-grid { grid-template-columns: 1fr; }
      .about-grid { gap: 15px; }
    }
  </style>
</head>
<body>

<header>
  <nav class="container">
    <a href="#" class="brand">
      PT. BUDI BUANA KARYA
      <small>AGRIBISNIS NUSANTARA</small>
    </a>
    <div class="navlinks">
      <a href="#produk">Produk</a>
      <a href="#tentang">Tentang Kami</a>
      <a href="#kontak" class="button">Hubungi Kami ↗</a>
    </div>
  </nav>
</header>

<main>
  <section class="hero">
    <div class="container">
      <div class="eyebrow">Mitra Pertanian Indonesia</div>
      <h1>Tumbuh Bersama Alam, Membangun Masa Depan.</h1>
      <p>
        Penyedia bibit tanaman dan komoditas pertanian dari
        Kalimantan Selatan, didukung jaringan petani se-Nusantara.
        Bersama membangun kemitraan agribisnis yang berkelanjutan.
      </p>
      <div class="hero-actions">
        <a class="button" href="#kontak">Konsultasi via WhatsApp ↗</a>
        <a class="button-outline" href="#produk">Jelajahi Produk</a>
      </div>
    </div>
  </section>

  <section id="produk">
    <div class="container">
      <div class="section-head">
        <div class="eyebrow">Produk Kami</div>
        <h2>Potensi Pertanian untuk Pasar Nusantara.</h2>
        <p>
          Pilihan bibit dan komoditas pertanian untuk kebutuhan
          budidaya, perdagangan, serta kemitraan usaha.
          Hubungi kami untuk mengecek ketersediaan.
        </p>
      </div>

      <div class="products">
        <article class="product">
          <div class="number">01 / JAHE</div>
          <h3>Bibit & Komoditas Jahe</h3>
          <p>Jahe Merah, Jahe Gajah, dan Jahe Emprit untuk kebutuhan budidaya dan perdagangan.</p>
          <a href="#kontak" onclick="pilihProduk('Bibit dan komoditas jahe')">Tanyakan produk ↗</a>
        </article>

        <article class="product">
          <div class="number">02 / KENCUR</div>
          <h3>Bibit & Komoditas Kencur</h3>
          <p>Pilihan bibit dan komoditas kencur sesuai kebutuhan dan ketersediaan.</p>
          <a href="#kontak" onclick="pilihProduk('Bibit dan komoditas kencur')">Tanyakan produk ↗</a>
        </article>

        <article class="product">
          <div class="number">03 / BIBIT BUAH</div>
          <h3>Bibit Buah Bersertifikasi</h3>
          <p>Informasikan jenis tanaman yang Anda cari untuk konfirmasi stok dan dokumen sertifikasi.</p>
          <a href="#kontak" onclick="pilihProduk('Bibit buah bersertifikasi')">Tanyakan produk ↗</a>
        </article>

        <article class="product">
          <div class="number">04 / KOMODITAS</div>
          <h3>Kayu Manis</h3>
          <p>Komoditas pertanian untuk kebutuhan perdagangan sesuai spesifikasi dan ketersediaan.</p>
          <a href="#kontak" onclick="pilihProduk('Kayu manis')">Tanyakan produk ↗</a>
        </article>

        <article class="product">
          <div class="number">05 / KOMODITAS</div>
          <h3>Jengkol</h3>
          <p>Komoditas hasil pertanian dari jaringan pemasok dan petani Nusantara.</p>
          <a href="#kontak" onclick="pilihProduk('Jengkol')">Tanyakan produk ↗</a>
        </article>

        <article class="product">
          <div class="number">06 / KEMITRAAN</div>
          <h3>Jaringan Petani</h3>
          <p>Terbuka untuk komunikasi dan penjajakan kerja sama dengan petani, pemasok, dan pembeli.</p>
          <a href="#kontak" onclick="pilihProduk('Kemitraan pertanian')">Jalin kemitraan ↗</a>
        </article>
      </div>
    </div>
  </section>

  <section id="tentang" class="about">
    <div class="container about-grid">
      <div>
        <div class="eyebrow">Tentang Perusahaan</div>
        <h2>Berakar di Daerah, Terhubung ke Nusantara.</h2>
        <p>
          PT. Budi Buana Karya bergerak dalam penyediaan bibit
          tanaman dan komoditas pertanian, dengan basis usaha
          di Kalimantan Selatan serta jaringan petani dari
          berbagai wilayah Indonesia.
        </p>
        <p>
          Kami membangun hubungan usaha melalui komunikasi
          yang jelas, kemitraan, dan perhatian pada kebutuhan
          produk setiap pelanggan.
        </p>
      </div>
      <div class="values">
        <div class="value">
          <strong>Kemitraan</strong><br>
          Menghubungkan petani, pemasok, dan pembeli.
        </div>
        <div class="value">
          <strong>Transparansi</strong><br>
          Konfirmasi jenis produk, mutu, stok, dan pengiriman.
        </div>
        <div class="value">
          <strong>Pertumbuhan berkelanjutan</strong><br>
          Mendukung pengembangan peluang agribisnis Nusantara.
        </div>
      </div>
    </div>
  </section>

  <section id="kontak" class="cta">
    <div class="container">
      <div class="eyebrow">Mari Berkolaborasi</div>
      <h2>Temukan Produk yang Anda Butuhkan.</h2>
      <p>
        Hubungi PT. Budi Buana Karya untuk informasi bibit,
        komoditas pertanian, ketersediaan produk, dan peluang kemitraan.
      </p>
      <a id="waButton" class="button" href="#" target="_blank" rel="noopener">
        Hubungi via WhatsApp ↗
      </a>
    </div>
  </section>
</main>

<footer>
  <div class="container footer-row">
    <div>
      <strong>PT. Budi Buana Karya</strong><br>
      <small>Mitra Agribisnis Nusantara</small>
    </div>
    <small>© <span id="year"></span> PT. Budi Buana Karya</small>
  </div>
</footer>

<script>
  // GANTI dengan nomor WhatsApp resmi perusahaan.
  // Format internasional tanpa tanda +, spasi, atau strip.
  const nomorWhatsApp = "6283824018117";
  let produkPilihan = "";

  function pilihProduk(produk) {
    produkPilihan = produk;
  }

  document.getElementById("waButton").addEventListener("click", function(e) {
    if (!/^62\d{8,15}$/.test(nomorWhatsApp)) {
      e.preventDefault();
      alert("Silakan isi nomor WhatsApp resmi perusahaan pada kode website.");
      return;
    }

    const pesan = "Halo PT. Budi Buana Karya, saya ingin bertanya tentang " +
      (produkPilihan || "produk dan layanan perusahaan") + ". Mohon informasi lebih lanjut.";
    this.href = "https://wa.me/" + nomorWhatsApp +
      "?text=" + encodeURIComponent(pesan);
  });

  document.getElementById("year").textContent = new Date().getFullYear();
</script>

</body>
</html>
