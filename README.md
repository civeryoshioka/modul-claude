# Modul Belajar

Kumpulan modul belajar interaktif berbentuk HTML (cukup buka file di browser, tanpa instalasi).

**Mulai dari [`index.html`](index.html)**: beranda berisi jalur belajar yang disarankan, ringkasan setiap modul, dan pelacak progres.

## Reinforcement Learning

| Level | File | Status |
|---|---|---|
| 0 · Penunjang: Matematika untuk RL | [`reinforcement-learning/00-matematika.html`](reinforcement-learning/00-matematika.html) | ✅ Selesai |
| 1 · Beginner | [`reinforcement-learning/01-beginner.html`](reinforcement-learning/01-beginner.html) | ✅ Selesai |
| 2 · Intermediate | [`reinforcement-learning/02-intermediate.html`](reinforcement-learning/02-intermediate.html) | ✅ Selesai |
| 3 · Advanced | [`reinforcement-learning/03-advanced.html`](reinforcement-learning/03-advanced.html) | ✅ Selesai |

## Deep Learning

| Modul | File | Status |
|---|---|---|
| Backpropagation dari Nol (jaringan 3 lapisan 2–2–1: forward pass, loss, gradient descent, aturan rantai, satu iterasi dengan angka, simulator tahap demi tahap, gradient checking, melatih XOR di browser, bentuk matriks dan kode NumPy yang sudah dijalankan, vanishing gradient; 13 simulasi, latihan, dan 29 soal kuis) | [`deep-learning/00-backpropagation-dari-nol.html`](deep-learning/00-backpropagation-dari-nol.html) | ✅ Selesai |
| Deep Learning & Transformer (jembatan ke LLM/RLHF) | [`deep-learning/01-deep-learning-transformer.html`](deep-learning/01-deep-learning-transformer.html) | ✅ Selesai |

## Pemrosesan Sinyal

| Modul | File | Status |
|---|---|---|
| Memahami Transformasi Fourier (intuisi, DFT/FFT, aliasing, filter) | [`fourier/01-transformasi-fourier.html`](fourier/01-transformasi-fourier.html) | ✅ Selesai |

## Menyajikan Model AI

Ikuti urutan bernomor: **1 FastAPI untuk AI/ML → 2 Serving Deep Learning**. Modul pendamping (boleh dibaca kapan saja setelah modul 2, atau saat ingin memahami isi CNN-nya): **Membedah CNN Angka**.

| Modul | File | Status |
|---|---|---|
| 1 · Memahami FastAPI untuk AI/ML (HTTP, Pydantic, memuat model sekali, async vs def, dependency injection, streaming ala LLM, dynamic batching, keamanan, testing, deployment, studi kasus API sentimen; 12 simulasi dan kode Python yang sudah dijalankan) | [`fastapi/01-fastapi-untuk-ai-ml.html`](fastapi/01-fastapi-untuk-ai-ml.html) | ✅ Selesai |
| 2 · Serving Model Deep Learning dengan FastAPI (praproses dan train–serve skew, format artifact yang aman, PyTorch vs ONNX Runtime, kuantisasi, cold start, batching, model generatif, memori GPU, drift, autoscaling; 13 simulasi, sebagian menjalankan CNN sungguhan di browser; kode dijalankan dengan PyTorch 2.14 dan ONNX Runtime 1.31) | [`fastapi/02-serving-deep-learning.html`](fastapi/02-serving-deep-learning.html) | ✅ Selesai |
| Pendamping · Membedah CNN Angka: Hitungan dan Simulasi (CNN angka dari modul 2 dibedah: piksel → konvolusi → ReLU → pooling → linear → softmax → loss dengan bobot nyata, backpropagation dengan angka, melatih CNN langsung di browser, matriks konfusi, oklusi, dan uji geser; 13 simulasi dan kode NumPy yang dicocokkan dengan PyTorch) | [`deep-learning/02-cnn-angka-langkah-demi-langkah.html`](deep-learning/02-cnn-angka-langkah-demi-langkah.html) | ✅ Selesai |

## Kalkulus

Ikuti urutan bernomor: **1 Limit → 2 Turunan → 3 Integral → 4 Studi Kasus Anggaran**.

| Modul | File | Status |
|---|---|---|
| 1 · Memahami Limit dari Nol (limit kiri/kanan, 0/0, teorema apit, bilangan e, deret, ε–δ) | [`kalkulus/01-limit.html`](kalkulus/01-limit.html) | ✅ Selesai |
| 2 · Memahami Turunan dari Nol (laju sesaat, limit, aturan rantai, optimasi, gradient descent) | [`kalkulus/02-turunan.html`](kalkulus/02-turunan.html) | ✅ Selesai |
| 3 · Memahami Integral dari Nol (intuisi, jumlah Riemann, Teorema Dasar, teknik, numerik, aplikasi) | [`kalkulus/03-integral.html`](kalkulus/03-integral.html) | ✅ Selesai |
| 4 · Studi Kasus Anggaran (titik impas, pajak, bunga, harga optimal, EOQ, kurva S, arus kas) | [`kalkulus/04-studi-kasus-anggaran.html`](kalkulus/04-studi-kasus-anggaran.html) | ✅ Selesai |

## Rekayasa Perangkat Lunak

Ikuti urutan bernomor: **1 SOLID → 2 Design Pattern**.

| Modul | File | Status |
|---|---|---|
| 1 · Memahami SOLID dari Nol (SRP, OCP, LSP, ISP, DIP dengan contoh Java, simulasi, dan studi kasus refactoring) | [`oop/01-solid.html`](oop/01-solid.html) | ✅ Selesai |
| 2 · Memahami Design Pattern dari Nol (15 pattern GoF dengan analogi, diagram kelas, 15 simulasi, contoh Java, dan studi kasus aplikasi pesan-antar) | [`oop/02-design-pattern.html`](oop/02-design-pattern.html) | ✅ Selesai |
