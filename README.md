# 🐾 MetroPal Virtual Pet

**MetroPal Virtual Pet** adalah game simulasi hewan peliharaan virtual berbasis web yang interaktif, dirancang menggunakan **HTML5, CSS3, dan Vanilla JavaScript (ES6)**. Game ini menyajikan mekanik perawatan pet, sistem leveling, fitur gacha blind box, farming coin, hingga bonus pasif karakter eksklusif.

---

## 🌟 Fitur Utama

### 1. 🐶 Sistem Perawatan & Status Karakter
* **Mekanik Status Real-Time:** Menjaga 5 indikator utama agar hewan peliharaan Anda tetap bahagia dan sehat:
  * ❤️ **Mood:** Memengaruhi tingkat perolehan koin pasif.
  * 🍲 **Hunger:** Berkurang secara berkala. Makanan dapat diberikan tanpa *cooldown* selama **Hunger < 75%**.
  * ⚡ **Energy:** Dipulihkan melalui aksi *Sleep*.
  * 🧼 **Hygiene:** Dipulihkan melalui aksi *Shower*.
  * ➕ **Health:** Jika Health $\le 50\%$, pet akan mengalami kondisi sakit (membutuhkan **Antidote**). Jika Health menyentuh $0\%$, pet akan **Mati (Dead State)**.
* **Mekanik Kematian & Revival:** 
  * Jika pet mati, semua status (*Hunger, Energy, Hygiene, Mood, Health*) otomatis menjadi $0\%$ dan XP di-reset ke 0.
  * Gunakan item **Revivalia** untuk menghidupkan kembali pet dan mengembalikan seluruh status ke **100%**.

---

### 2. 👑 Karakter & Bonus Pasif
* **Grand:** Maskot utama MetroPal.
* **Gina (SSR Superstar Bunny):** Memiliki **Passive Bonus 2x Coin Gain** (perolehan koin pasif dari Mood berjalan 2 kali lebih cepat).
* **Dibo, Aiko, Erri:** Karakter eksklusif SSR yang dapat diperoleh melalui sistem *Blind Box Gacha*. 

---

### 3. 🛍️ MetMart & Fitur Sorting
* Beli berbagai pilihan makanan, minuman, dan obat-obatan medis di toko **MetMart**.
* **Mekanik XP Makanan:** Mengonsumsi makanan/minuman memberi nilai XP yang **setara dengan harga beli item tersebut di MetMart**.
* **Fitur Filter/Sort MetMart & Inventory:**
  * 📌 **Bawaan**
  * 💰 **Harga (Termurah & Termahal)**
  * ⚡ **Efek Terbesar**
  * 🔤 **Nama (A-Z)**

---

### 4. 🎁 Blind Box Gacha & Pity System
* Nikmati simulasi pembukaan Blind Box 1x atau 10x secara instan dengan efek suara dan animasi khusus.
* **Joy System (Pity Meter):** Garansi mendapatkan karakter SSR pada *pull* ke-100.
* **Duplikat SSR:** Jika mendapatkan karakter yang sudah dimiliki, duplikat akan otomatis dikonversi menjadi **+50.000 Coins**.
* **Gacha History Log:** Catatan riwayat hasil gacha yang transparan.

---

### 5. 🏆 Achievements, Tasks & Promo Codes
* **50+ Achievements:** Misi bertingkat (*Easy, Medium, Hard, Very Hard*) dengan hadiah XP dan Koin.
* **Daily & Monthly Tasks:** Tugas harian dan bulanan untuk mempercepat progres level.
* **Redeem Code & Referral System:** Dapatkan bonus koin/XP dengan memasukkan kode promo atau mereferensikan nomor *Metland Card* teman.

---

### 6. 🎧 Pengaturan Audio & Dev Mode
* **Audio Engine (Web Audio API):** Dilengkapi dengan BGM serta berbagai efek suara *synthesizer* internal (suara makan, mandi, gacha, level up, dll).
* **Developer Mode:** Panel tersembunyi (*Password Protected*) untuk simulasi kondisi pet (Sakit/Mati), pengatur *Odds Gacha*, serta *Unlimited Coins & Level Boost*.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & CSS3:** Desain antarmuka responsif berbentuk perangkat genggam kompak (*Mobile Device Frame*) dengan animasi CSS.
* **Vanilla JavaScript (ES6):** Seluruh logika game, *offline decay calculation*, *sound synthesizer*, dan pengolahan data terenkapsulasi dalam satu file tunggal.
* **LocalStorage API:** Menyimpan progres game secara otomatis pada peramban pengguna.
* **Web Audio API:** Menghasilkan efek suara dinamis tanpa memerlukan *file audio vfx* eksternal.

---

## 🚀 Cara Menjalankan Game

1. **Unduh / Clone Repositori:**
   ```bash
   git clone [https://github.com/username/metropal-virtual-pet.git](https://github.com/username/metropal-virtual-pet.git)
