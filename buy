<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff5eb">
<title>Robuxie - Roblox Top Up Store</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;500;600;700;800;900;1000&display=swap" rel="stylesheet">

<style>
:root {
  --cream: #fff8ef;
  --cream2: #fff0e2;
  --pink: #f8c9d3;
  --pink2: #ffe2e8;
  --brown: #76523f;
  --dark: #49352d;
  --muted: #a58c7c;
  --white: #ffffff;
  --shadow: 0 12px 35px rgba(126, 86, 64, .10);
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Nunito', sans-serif;
  background:
    radial-gradient(circle at 10% 5%, #ffe6e9 0, transparent 25%),
    radial-gradient(circle at 95% 30%, #f8e5cb 0, transparent 25%),
    var(--cream);
  color: var(--dark);
  min-height: 100vh;
  padding-bottom: 50px;
}

button, input {
  font-family: inherit;
}

button {
  cursor: pointer;
}

.container {
  width: min(100% - 32px, 1050px);
  margin: auto;
}

/* HEADER */

header {
  padding: 20px 0;
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 23px;
  font-weight: 1000;
  color: var(--brown);
}

.logo-icon {
  width: 43px;
  height: 43px;
  border-radius: 15px;
  display: grid;
  place-items: center;
  background: linear-gradient(145deg, #ffd9df, #f6bfcf);
  box-shadow: 0 5px 12px #edc4cb;
  font-size: 22px;
}

.status {
  background: white;
  padding: 8px 13px;
  border-radius: 30px;
  color: #69976c;
  font-size: 12px;
  font-weight: 900;
  box-shadow: var(--shadow);
}

.status::before {
  content: "";
  display: inline-block;
  background: #79c783;
  width: 7px;
  height: 7px;
  border-radius: 50%;
  margin-right: 6px;
}

/* HERO */

.hero {
  position: relative;
  overflow: hidden;
  margin: 18px 0 28px;
  min-height: 235px;
  border-radius: 30px;
  background: linear-gradient(120deg, #ffe1e5, #fff0dd 65%, #f7dfc9);
  box-shadow: var(--shadow);
  display: flex;
  align-items: center;
  padding: 35px;
}

.hero::before {
  content: "✦";
  position: absolute;
  right: 40%;
  top: 20px;
  font-size: 35px;
  color: white;
}

.hero::after {
  content: "♡";
  position: absolute;
  right: 45%;
  bottom: 20px;
  font-size: 40px;
  color: #edb4c3;
}

.hero-text {
  z-index: 2;
  max-width: 60%;
}

.hero-tag {
  display: inline-block;
  background: white;
  color: #c17d91;
  border-radius: 30px;
  padding: 6px 13px;
  font-size: 11px;
  font-weight: 900;
  margin-bottom: 13px;
}

.hero h1 {
  font-size: clamp(29px, 5vw, 48px);
  font-weight: 1000;
  line-height: 1.08;
  color: #704c42;
}

.hero h1 span {
  color: #d77e9c;
}

.hero p {
  margin-top: 12px;
  font-size: 13px;
  color: #94766c;
  font-weight: 700;
}

.hero-avatar {
  position: absolute;
  right: 5%;
  bottom: -5px;
  width: 230px;
  height: 220px;
  display: grid;
  place-items: center;
  font-size: 115px;
  filter: drop-shadow(0 12px 8px rgba(120,70,70,.15));
}

/* SECTION */

.section-heading {
  display: flex;
  justify-content: space-between;
  align-items: end;
  margin: 30px 0 16px;
}

.section-heading h2 {
  font-size: 21px;
  font-weight: 1000;
}

.section-heading p {
  font-size: 12px;
  color: var(--muted);
  font-weight: 700;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
}

.product {
  background: rgba(255,255,255,.88);
  border: 2px solid transparent;
  padding: 19px 12px;
  border-radius: 23px;
  text-align: center;
  box-shadow: 0 7px 20px rgba(120,80,60,.06);
  transition: .25s;
  position: relative;
  overflow: hidden;
}

.product:hover {
  transform: translateY(-5px);
  box-shadow: var(--shadow);
}

.product.selected {
  border-color: #e99db3;
  background: #fff3f5;
  box-shadow: 0 8px 25px rgba(221,145,167,.19);
}

.product-icon {
  width: 60px;
  height: 60px;
  border-radius: 20px;
  background: linear-gradient(145deg,#fff0e3,#ffe0e7);
  display: grid;
  place-items: center;
  margin: 0 auto 12px;
  font-size: 30px;
}

.product h3 {
  font-size: 19px;
  font-weight: 1000;
}

.product small {
  font-size: 10px;
  color: #ae9484;
  font-weight: 900;
  letter-spacing: 1px;
}

.product-price {
  display: block;
  margin-top: 12px;
  color: #ce7f99;
  font-size: 15px;
  font-weight: 1000;
}

.product .choose {
  display: inline-block;
  margin-top: 9px;
  background: #fff0e7;
  color: #9e7661;
  border-radius: 20px;
  padding: 5px 13px;
  font-size: 10px;
  font-weight: 900;
}

.product.selected .choose {
  background: #e9a7b9;
  color: white;
}

/* CHECKOUT */

.checkout-layout {
  display: grid;
  grid-template-columns: 1.3fr .8fr;
  gap: 18px;
  align-items: start;
  margin-top: 28px;
}

.panel {
  background: rgba(255,255,255,.91);
  border-radius: 25px;
  padding: 23px;
  box-shadow: var(--shadow);
}

.panel h2 {
  font-size: 19px;
  font-weight: 1000;
  margin-bottom: 18px;
}

.form-group {
  margin-bottom: 16px;
}

.form-group label {
  display: block;
  font-size: 12px;
  font-weight: 900;
  margin-bottom: 8px;
  color: #806452;
}

.form-group input {
  width: 100%;
  border: 2px solid #f5e9e0;
  background: #fffbf7;
  padding: 14px;
  border-radius: 14px;
  outline: none;
  font-size: 14px;
  color: var(--dark);
  transition: .2s;
}

.form-group input:focus {
  border-color: #e9a6b8;
}

.summary {
  background: #fff5ef;
  padding: 16px;
  border-radius: 17px;
  margin-top: 18px;
}

.summary-row {
  display: flex;
  justify-content: space-between;
  font-size: 13px;
  margin-bottom: 10px;
  gap: 10px;
}

.summary-row.total {
  border-top: 1px dashed #dfc7b8;
  padding-top: 13px;
  margin-top: 12px;
  font-size: 16px;
  font-weight: 1000;
  color: #ca7d96;
}

.primary-btn {
  width: 100%;
  border: 0;
  border-radius: 15px;
  padding: 15px;
  color: white;
  background: linear-gradient(110deg,#e89eb3,#d981a0);
  font-weight: 1000;
  font-size: 14px;
  margin-top: 17px;
  box-shadow: 0 7px 15px rgba(207,125,153,.25);
  transition: .2s;
}

.primary-btn:hover {
  transform: translateY(-2px);
  filter: brightness(1.04);
}

.primary-btn:disabled {
  opacity: .5;
  cursor: not-allowed;
}

/* PAYMENT */

#paymentSection {
  display: none;
  margin-top: 20px;
  animation: appear .35s ease;
}

@keyframes appear {
  from {opacity:0;transform:translateY(10px)}
  to {opacity:1;transform:translateY(0)}
}

.qris-box {
  background: #fff7f1;
  border: 2px dashed #e6b9a8;
  border-radius: 20px;
  padding: 20px;
  text-align: center;
  margin: 15px 0;
}

.qris-box img {
  width: 100%;
  max-width: 260px;
  display: block;
  margin: 15px auto;
  border-radius: 12px;
  background: white;
}

.qris-placeholder {
  width: 230px;
  max-width: 100%;
  aspect-ratio: 1;
  background: #f2e7dd;
  border-radius: 15px;
  display: grid;
  place-items: center;
  margin: 15px auto;
  color: #a58c7c;
  font-weight: 900;
  font-size: 13px;
  padding: 20px;
}

.payment-note {
  font-size: 12px;
  color: #9c8374;
  line-height: 1.7;
}

.secondary-btn {
  width: 100%;
  background: #fff0e6;
  color: #9b6f5a;
  border: 0;
  padding: 13px;
  border-radius: 13px;
  font-weight: 900;
  margin-top: 10px;
}

/* TRUST */

.features {
  display: grid;
  grid-template-columns: repeat(3,1fr);
  gap: 13px;
  margin: 28px 0;
}

.feature {
  background: rgba(255,255,255,.8);
  padding: 17px 10px;
  text-align: center;
  border-radius: 19px;
  box-shadow: var(--shadow);
}

.feature span {
  font-size: 25px;
}

.feature h4 {
  margin-top: 7px;
  font-size: 12px;
  font-weight: 1000;
}

.feature p {
  color: var(--muted);
  font-size: 10px;
  margin-top: 3px;
}

footer {
  text-align: center;
  color: #b19b8d;
  font-size: 11px;
  padding: 20px;
}

/* POPUP ACTIVITY */

.activity {
  position: fixed;
  bottom: 18px;
  left: 18px;
  z-index: 99;
  background: white;
  padding: 12px 16px;
  border-radius: 17px;
  box-shadow: 0 8px 35px rgba(75,45,35,.16);
  display: flex;
  align-items: center;
  gap: 10px;
  max-width: 290px;
  opacity: 0;
  transform: translateY(20px);
  pointer-events: none;
  transition: .35s;
}

.activity.show {
  opacity: 1;
  transform: translateY(0);
}

.activity-icon {
  background: #ffe7ec;
  border-radius: 13px;
  padding: 10px;
  font-size: 20px;
}

.activity p {
  font-size: 11px;
  font-weight: 900;
  line-height: 1.5;
}

.activity small {
  color: #b09a8d;
  font-size: 9px;
}

@media(max-width:750px) {
  .product-grid {
    grid-template-columns: repeat(2,1fr);
    gap: 11px;
  }

  .checkout-layout {
    grid-template-columns: 1fr;
  }

  .hero {
    min-height: 205px;
    padding: 23px;
  }

  .hero-text {
    max-width: 65%;
  }

  .hero-avatar {
    right: -5px;
    width: 145px;
    font-size: 85px;
  }

  .hero h1 {
    font-size: 30px;
  }

  .hero p {
    font-size: 11px;
  }

  .features {
    gap: 8px;
  }

  .feature {
    padding: 13px 5px;
  }

  .feature h4 {
    font-size: 10px;
  }
}

@media(max-width:360px) {
  .logo {font-size:19px}
  .hero-avatar {font-size:70px}
  .product {padding:15px 7px}
}
</style>
</head>

<body>

<div class="container">

<header>
  <div class="nav">
    <div class="logo">
      <div class="logo-icon">🎀</div>
      <span>Robuxie<span style="color:#e99db3">.</span></span>
    </div>
    <div class="status">STORE ONLINE</div>
  </div>
</header>

<section class="hero">
  <div class="hero-text">
    <div class="hero-tag">♡ WELCOME TO ROBUXIE</div>
    <h1>Get Your<br><span>Dream Robux!</span></h1>
    <p>Top up Robux dengan mudah, praktis, dan nyaman ♡</p>
  </div>
  <div class="hero-avatar">🎀</div>
</section>

<div class="section-heading">
  <div>
    <h2>♡ Pilih Robux</h2>
    <p>Pilih paket sesuai kebutuhanmu!</p>
  </div>
  <span style="font-size:12px;color:#c18c86;font-weight:900">ROBLOX STORE</span>
</div>

<div class="product-grid" id="productGrid"></div>

<div class="checkout-layout">

  <section class="panel">
    <h2>🛍️ Detail Pembelian</h2>

    <form id="checkoutForm">
      <div class="form-group">
        <label>USERNAME ROBLOX</label>
        <input id="username" type="text"
          placeholder="Contoh: RobloxPlayer123"
          required minlength="3" maxlength="20">
      </div>

      <div class="form-group">
        <label>NOMOR WHATSAPP</label>
        <input id="whatsapp" type="tel"
          placeholder="Contoh: 081234567890"
          required>
      </div>

      <div class="summary">
        <div class="summary-row">
          <span>Produk</span>
          <strong id="selectedProduct">Belum dipilih</strong>
        </div>
        <div class="summary-row">
          <span>Username</span>
          <strong id="summaryUsername">-</strong>
        </div>
        <div class="summary-row total">
          <span>Total pembayaran</span>
          <strong id="totalPrice">Rp0</strong>
        </div>
      </div>

      <button class="primary-btn" type="submit">
        LANJUT KE PEMBAYARAN →
      </button>
    </form>
  </section>

  <section class="panel" id="paymentSection">
    <h2>💗 Pembayaran QRIS</h2>
    <p class="payment-note">
      Silakan scan QRIS di bawah ini menggunakan aplikasi pembayaranmu.
      Pastikan nominal pembayaran sesuai pesanan.
    </p>

    <div class="qris-box">
      <strong>SCAN QRIS DISINI</strong>

      <img id="qrisImage" src="qris.png"
        alt="QRIS pembayaran"
        onerror="this.style.display='none';document.getElementById('qrisPlaceholder').style.display='grid'">

      <div id="qrisPlaceholder" class="qris-placeholder">
        Masukkan file qris.png untuk menampilkan QRIS
      </div>

      <div class="summary">
        <div class="summary-row">
          <span>Nominal</span>
          <strong id="paymentAmount">Rp0</strong>
        </div>
        <div class="summary-row">
          <span>Order ID</span>
          <strong id="orderId">-</strong>
        </div>
      </div>
    </div>

    <p class="payment-note">
      Setelah melakukan pembayaran, klik tombol di bawah untuk mengirim
      konfirmasi kepada admin. Pesanan akan diproses setelah pembayaran
      diperiksa secara manual.
    </p>

    <button class="primary-btn" id="confirmButton">
      KONFIRMASI VIA WHATSAPP
    </button>

    <button class="secondary-btn" onclick="window.print()">
      Simpan / Cetak Detail Pesanan
    </button>
  </section>

</div>

<div class="features">
  <div class="feature">
    <span>⚡</span>
    <h4>Fast Process</h4>
    <p>Proses pesanan</p>
  </div>
  <div class="feature">
    <span>💗</span>
    <h4>Easy Payment</h4>
    <p>Pembayaran praktis</p>
  </div>
  <div class="feature">
    <span>🎀</span>
    <h4>Friendly Admin</h4>
    <p>Bantuan admin</p>
  </div>
</div>

<footer>
  Made with ♡ by Robuxie Store<br>
  © 2026 All Rights Reserved
</footer>

</div>

<!-- SIMULATED ACTIVITY POPUP -->
<div class="activity" id="activityPopup">
  <div class="activity-icon">🎮</div>
  <div>
    <p id="activityText">Aktivitas simulasi</p>
    <small>Contoh aktivitas • Bukan transaksi asli</small>
  </div>
</div>

<script>

// ========================================
// CONFIGURATION - EDIT BAGIAN INI
// ========================================

// Ganti dengan nomor WhatsApp admin.
// Format: kode negara + nomor, tanpa + atau spasi.
const ADMIN_WHATSAPP = "6281234567890";

// Daftar produk dan harga
const products = [
  { id: 1, robux: 1800, price: 35000 },
  { id: 2, robux: 2200, price: 45000 },
  { id: 3, robux: 2700, price: 50000 },
  { id: 4, robux: 3200, price: 60000 },
  { id: 5, robux: 3700, price: 70000 },
  { id: 6, robux: 4200, price: 80000 },
  { id: 7, robux: 4300, price: 90000 }
];

// ========================================
// PRODUCT SYSTEM
// ========================================

let selected = null;
let currentOrder = null;

const grid = document.getElementById("productGrid");

function formatRupiah(number) {
  return "Rp" + number.toLocaleString("id-ID");
}

function renderProducts() {
  grid.innerHTML = "";

  products.forEach(product => {
    const card = document.createElement("button");
    card.type = "button";
    card.className = "product";
    card.dataset.id = product.id;

    card.innerHTML = `
      <div class="product-icon">💎</div>
      <h3>${product.robux.toLocaleString("id-ID")}</h3>
      <small>ROBUX</small>
      <span class="product-price">${formatRupiah(product.price)}</span>
      <span class="choose">PILIH PAKET</span>
    `;

    card.addEventListener("click", () => selectProduct(product));
    grid.appendChild(card);
  });
}

function selectProduct(product) {
  selected = product;

  document.querySelectorAll(".product").forEach(card => {
    card.classList.toggle(
      "selected",
      Number(card.dataset.id) === product.id
    );
  });

  document.getElementById("selectedProduct").textContent =
    product.robux.toLocaleString("id-ID") + " Robux";

  document.getElementById("totalPrice").textContent =
    formatRupiah(product.price);

  document.getElementById("paymentSection").style.display = "none";
  currentOrder = null;

  document.getElementById("paymentSection").scrollIntoView({
    behavior: "smooth",
    block: "nearest"
  });
}

// ========================================
// LIVE FORM SUMMARY
// ========================================

document.getElementById("username").addEventListener("input", e => {
  document.getElementById("summaryUsername").textContent =
    e.target.value || "-";
});

// ========================================
// CHECKOUT
// ========================================

document.getElementById("checkoutForm").addEventListener("submit", e => {
  e.preventDefault();

  if (!selected) {
    alert("Silakan pilih paket Robux terlebih dahulu!");
    return;
  }

  const username = document.getElementById("username").value.trim();
  const whatsapp = document.getElementById("whatsapp").value.trim();

  if (!/^[a-zA-Z0-9_]{3,20}$/.test(username)) {
    alert("Username Roblox tidak valid.");
    return;
  }

  if (!/^[0-9+\-\s()]{9,20}$/.test(whatsapp)) {
    alert("Nomor WhatsApp tidak valid.");
    return;
  }

  const order = {
    id: "RBX" + Date.now().toString().slice(-8),
    username: username,
    whatsapp: whatsapp,
    robux: selected.robux,
    price: selected.price
  };

  currentOrder = order;

  document.getElementById("paymentAmount").textContent =
    formatRupiah(order.price);

  document.getElementById("orderId").textContent = order.id;

  const payment = document.getElementById("paymentSection");
  payment.style.display = "block";

  payment.scrollIntoView({
    behavior: "smooth",
    block: "start"
  });
});

// ========================================
// WHATSAPP CONFIRMATION
// ========================================

document.getElementById("confirmButton").addEventListener("click", () => {
  if (!currentOrder) return;

  const order = currentOrder;

  const message =
`Halo Admin Robuxie! ♡

Saya ingin mengonfirmasi pembayaran pesanan Robux.

📋 DETAIL PESANAN
Order ID: ${order.id}
Username Roblox: ${order.username}
Jumlah Robux: ${order.robux.toLocaleString("id-ID")}
Nominal: ${formatRupiah(order.price)}

Nomor WhatsApp: ${order.whatsapp}

Saya sudah melakukan pembayaran QRIS.
Mohon periksa pembayaran saya.

Terima kasih!`;

  const url =
    "https://wa.me/" + ADMIN_WHATSAPP +
    "?text=" + encodeURIComponent(message);

  window.open(url, "_blank");
});

// ========================================
// SIMULATED ACTIVITY
// Transparan: hanya contoh aktivitas, bukan
// bukti pembelian pelanggan sebenarnya.
// ========================================

const demoActivities = [
  { user: "na***", robux: "1.800" },
  { user: "ra***", robux: "2.200" },
  { user: "mi***", robux: "3.200" },
  { user: "zi***", robux: "4.200" },
  { user: "ka***", robux: "2.700" },
  { user: "al***", robux: "3.700" }
];

let activityIndex = 0;

function showActivity() {
  const activity = demoActivities[
    activityIndex % demoActivities.length
  ];

  const popup = document.getElementById("activityPopup");

  document.getElementById("activityText").textContent =
    `@${activity.user} • ${activity.robux} Robux`;

  popup.classList.add("show");

  setTimeout(() => {
    popup.classList.remove("show");
  }, 2400);

  activityIndex++;
}

// Mulai setelah halaman siap
setTimeout(() => {
  showActivity();
  setInterval(showActivity, 3000);
}, 1500);

// ========================================
// INITIALIZE
// ========================================

renderProducts();

</script>
</body>
</html>
