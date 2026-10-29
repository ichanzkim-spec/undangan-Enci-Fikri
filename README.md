# Undangan Rapat Evaluasi Kinerja Satuan Pengamanan

## Isi paket
- `index.html` — halaman undangan responsif
- `backsound-neffex-soldier.mp3` — musik latar yang Anda unggah

## Cara menerbitkan melalui GitHub Pages
1. Masuk ke GitHub dengan akun Anda.
2. Buat repositori publik bernama `undangan-evaluasi-ikkrs`.
3. Unggah `index.html` dan `backsound-neffex-soldier.mp3` ke direktori utama repositori.
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu **Save**.
6. Setelah selesai diterbitkan, alamatnya biasanya:
   `https://ichanzkim-spec.github.io/undangan-evaluasi-ikkrs/`

## Mengaktifkan kolom komentar
Kolom komentar memakai Utterances dan GitHub Issues/Discussions.
1. Pastikan repositori publik.
2. Aktifkan **Settings → General → Features → Discussions** bila tersedia.
3. Pasang aplikasi Utterances pada repositori melalui https://github.com/apps/utterances.
4. Jika nama repositori berbeda, edit baris `const repo='ichanzkim-spec/undangan-evaluasi-ikkrs';` di `index.html`.
5. Simpan perubahan dan tunggu GitHub Pages memperbarui situs.

Catatan: musik tidak otomatis berbunyi saat halaman dibuka karena kebijakan browser; pengunjung bisa menekan tombol **Putar backsound**.
