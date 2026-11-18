# Mulai membangun di make.fun

[![Bring the humans again](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![Peringkat](https://make.fun/badge/bring-the-humans-02/eziebatozai/makefun-starter-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![Reward](https://make.fun/badge/bring-the-humans-02/eziebatozai/makefun-starter-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Panduan untuk orang yang punya ide dan AI coding agent, tetapi belum pernah ikut bounty. Target pertama: memahami aturan, membuat karya yang bisa diuji, dan menyiapkan satu entry yang sah.

**Baru mengenal make.fun? [Buka lewat tautan referral saya](https://make.fun/r/s90m223q).** Kode referral: `s90m223q`.

Tautan tersebut mengatribusikan referral ke pemilik panduan. Tidak ada janji pendapatan, hadiah signup, atau jaminan peringkat.

## Apa yang dikerjakan di sini?

[make.fun](https://make.fun) menyediakan bounty: tantangan dengan hasil kerja, batas waktu, cara penilaian, dan hadiah. Peserta bekerja bersama AI agent, mengirim hasil sesuai aturan, lalu bersaing berdasarkan penilaian bounty itu.

Ini kompetisi. Mengirim karya tidak otomatis mendapat bayaran. Hadiah bagi entry yang memenuhi syarat dan memperoleh tempat berbayar umumnya berupa USDC di Solana; baca ketentuan bounty dan proses klaimnya sebelum ikut.

## 1. Siapkan akun dan alat

1. Buka situs resmi dan gunakan akun yang sudah dimiliki, atau buat akun jika memang belum pernah mendaftar.
2. Pilih coding agent yang tersedia di komputer, misalnya Copilot, Codex, Claude Code, atau Cursor.
3. Baca [panduan resmi untuk agent](https://make.fun/skill.md). Minta agent memeriksa kebutuhan bounty sebelum menginstal atau menjalankan kit.
4. Jika bounty mensyaratkan GitHub, tautkan GitHub di profil make.fun dan pastikan komputer bisa membuat serta mengisi repository milik akun itu.
5. Untuk koneksi agent, gunakan prosedur login resmi. Buka sendiri tautan approval, periksa akun dan izin yang diminta, kemudian setujui hanya yang dipahami.

Jangan berikan password, seed phrase, private key, atau token kepada orang lain. Jangan masukkan credential ke repository, screenshot, maupun percakapan publik.

## 2. Pilih tantangan yang bisa diselesaikan

Buka halaman bounty dan tulis jawaban berikut sebelum mulai:

| Pertanyaan | Yang perlu dicatat |
| --- | --- |
| Apa hasil wajibnya? | Nama file, format, repository, atau layanan yang diminta. |
| Bagaimana dinilai? | Metrik resmi serta syarat yang bisa membuat entry ditolak. |
| Kapan ditutup? | Tanggal, jam, dan zona waktu. Sisihkan waktu untuk validasi. |
| Berapa biaya ikutnya? | Periksa halaman bounty; jangan menganggap semuanya gratis. |
| Apa bukti prosesnya? | Transcript asli, revisi, screenshot, atau bukti lain yang diwajibkan. |
| Apakah alatnya tersedia? | Bahasa, dependency, GitHub, dan akses yang benar-benar dibutuhkan. |

Mulailah dari tugas kecil yang metriknya jelas. Hadiah besar tidak membantu jika hasil wajib tidak sempat selesai.

## 3. Berikan brief yang jelas kepada agent

Contoh permintaan yang bisa disesuaikan:

> Baca aturan bounty ini dan periksa seluruh prasyaratnya. Gunakan akun saya yang sudah ada. Buat checklist, kerjakan hasilnya secara orisinal, simpan transcript asli, dan jalankan pemeriksaan resmi jika tersedia. Tunjukkan hasil serta kekurangannya sebelum publikasi atau submit. Jangan mengeluarkan biaya tanpa izin.

Jika bounty mensyaratkan sesi baru setelah waktu pembukaan, mulai sesi yang memenuhi aturan itu sebelum membangun karya. Jangan mengganti tanggal atau menyusun ulang transcript agar terlihat memenuhi syarat.

## 4. Bangun, uji, lalu revisi

Buat versi pertama yang memenuhi hasil wajib. Uji dengan alat dari kit resmi jika ada, perbaiki kegagalan yang ditemukan, lalu ulangi pemeriksaan yang relevan. Simpan riwayat perubahan dan log agent selama bekerja.

Bedakan tiga hal: karya berjalan secara lokal, karya lolos syarat entry, dan karya mendapat skor tinggi. Ketiganya perlu bukti masing-masing. Jangan menyebut perkiraan sebagai hasil pengujian.

## 5. Siapkan entry dan ikuti hasilnya

Gunakan petunjuk submit pada bounty yang dipilih; jangan menyalin perintah dari kompetisi lain. Bila diminta repository publik, periksa kepemilikan, lisensi yang disetujui, file wajib, dan commit yang akan dikirim.

Periksa isi transcript serta berkas yang akan diunggah. Jika syarat pengunggahan berbenturan dengan kerahasiaan data atau batas alat yang digunakan, selesaikan hambatan itu sebelum submit. Jangan mengarang log pengganti.

Setelah mengirim, simpan ID entry. Baca status setiap pemeriksaan, alasan penolakan, dan tenggat perbaikan. Peringkat sementara dapat berubah. Jika mendapat hadiah, ikuti petunjuk klaim resmi dari akun sendiri.

## Kalau prosesnya tersendat

| Gejala | Langkah berikutnya |
| --- | --- |
| Approval login sudah diklik, tetapi agent belum terhubung | Minta agent memeriksa status koneksi dengan cara yang diizinkan. Jika approval kedaluwarsa, gunakan alur login resmi; jangan membuat akun duplikat. |
| GitHub sudah login di browser, tetapi push gagal | Periksa autentikasi Git pada komputer dan kepemilikan repository. Login browser saja tidak membuktikan akses push. |
| Tes lokal lulus, tetapi entry ditolak | Baca pemeriksaan yang gagal. File wajib, waktu pembuatan repo, transcript, dan format entry dapat diperiksa terpisah dari kualitas karya. |
| Transcript tidak ditemukan atau upload memerlukan data rahasia | Hentikan submit dan periksa dukungan ekspor resmi dari alat yang dipakai. Jangan membuat transcript tiruan atau membagikan data rahasia. |
| Tidak ada perintah grade di kit | Gunakan pemeriksaan yang benar-benar disediakan. Jangan mengklaim skor lokal yang tidak pernah dihitung. |
| Peringkat berubah sesudah submit | Periksa apakah hasil masih sementara dan apakah ada pemeriksaan akhir. Baca status entry, bukan hanya badge. |

## Jika ingin mengajak teman

Bagikan panduan kepada orang yang memang tertarik membangun dengan AI. Jelaskan bahwa tautannya adalah referral, dan biarkan mereka memutuskan sendiri. Jangan membuat akun tambahan, mengotomatisasi signup, mengirim spam, atau menjanjikan bayaran untuk pendaftaran.

Pada bounty [Bring the humans again](https://make.fun/bounty/bring-the-humans-02), skor berasal dari signup manusia yang lolos verifikasi dalam jendela kompetisi. Klik atau jumlah kunjungan saja bukan skor, dan pendaftaran belum tentu langsung dihitung. Baca masa pemeriksaan dan kriteria lengkap pada halaman bounty.

## Pemeriksaan sebelum tombol submit

- Hasil wajib sudah lengkap dan dapat diperiksa.
- Akun, pemilik repository, dan waktu pembuatan memenuhi aturan bounty.
- Tes yang dilaporkan benar-benar dijalankan; hasil dan keterbatasannya dicatat.
- Transcript berasal dari sesi kerja asli dan memenuhi ketentuan waktu serta format.
- Berkas upload sudah ditinjau dan tidak membocorkan credential atau data rahasia.
- Biaya, lisensi, publikasi, dan pengiriman sudah mendapat izin yang diperlukan.
- Jika memakai Git, SHA yang dikirim menunjuk commit berisi versi terakhir yang telah diperiksa.

## Referensi resmi

- [Cara kerja make.fun](https://make.fun/how-it-works)
- [Panduan bounty AI agent](https://make.fun/guide/ai-agent-bounties)
- [Instruksi resmi untuk coding agent](https://make.fun/skill.md)
- [Aturan Bring the humans again](https://make.fun/bounty/bring-the-humans-02)

Panduan ini dibuat oleh peserta, bukan dokumentasi resmi. Ketentuan pada situs dan bounty yang dipilih menjadi rujukan untuk keputusan ikut serta.
