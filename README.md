# GoodTube Embed

## Deskripsi
GoodTube Embed adalah userscript untuk Tampermonkey yang menghilangkan 100% iklan YouTube sambil memastikan konten Shorts tetap berfungsi normal dengan autoplay.

## Fitur Utama
- **Pemblokir Iklan 100%**: Menghilangkan semua jenis iklan YouTube
- **Dukungan Shorts**: Konten Shorts YouTube tetap berfungsi normal
- **Custom Player**: Menggunakan player iframe kustom untuk pengalaman menonton yang lebih baik
- **Navigasi Playlist**: Navigasi yang lebih baik untuk playlist
- **Picture-in-Picture**: Dukungan mode PiP yang ditingkatkan
- **Kontrol Autoplay**: Kontrol autoplay kustom yang lebih baik dari bawaan YouTube
- **Dukungan Timestamp**: Dukungan untuk link timestamp di komentar

## Cara Instalasi
1. Instal ekstensi [Tampermonkey](https://www.tampermonkey.net/) pada browser Anda
2. Klik file `remove ads banner.js`
3. Pilih "Raw" atau buka file tersebut
4. Tampermonkey akan mendeteksi userscript dan menawarkan untuk menginstalnya
5. Klik "Install" atau "Pasang"

## Cara Penggunaan
Script akan berjalan otomatis ketika Anda mengunjungi YouTube. Tidak diperlukan konfigurasi tambahan. Fitur utama:

- Video YouTube reguler akan bebas iklan
- Shorts YouTube akan berfungsi normal dengan autoplay
- Player kustom akan menggantikan player YouTube asli (kecuali di halaman Shorts)
- Tombol navigasi playlist tersedia jika Anda menonton playlist

## Pintasan Keyboard
Script mendukung semua pintasan keyboard YouTube standar, plus beberapa tambahan:

- **Spasi/K**: Putar/Jeda
- **J**: Mundur 10 detik
- **L**: Maju 10 detik
- **F**: Layar penuh
- **T**: Mode teater
- **M**: Bisu/Tidak bisu
- **I**: Mode Picture-in-Picture
- **,**: Frame sebelumnya (saat paused)
- **.**: Frame berikutnya (saat paused)
- **>**: Percepat pemutaran
- **<**: Perlambat pemutaran
- **0-9**: Lompat ke persentase video (0 = awal, 5 = 50%, 9 = 90%)
- **↑**: Tambah volume
- **↓**: Kurangi volume
- **←**: Mundur 5 detik
- **→**: Maju 5 detik
- **Home**: Ke awal video
- **End**: Ke akhir video
- **Shift+P**: Video sebelumnya (dalam playlist)
- **Shift+N**: Video berikutnya (dalam playlist)

## Catatan Teknis
- Script ini menggantikan player YouTube asli dengan iframe embed-nya sendiri untuk video reguler
- Saat berada di halaman Shorts, script akan membiarkan player asli YouTube tetap berfungsi
- Script akan otomatis melewati iklan di video reguler
- Statistik penggunaan dasar tanpa informasi pribadi dikirim untuk menghitung pengguna unik dan video yang ditonton

## Kompatibilitas
- Bekerja di semua browser utama yang mendukung Tampermonkey
- Mendukung YouTube desktop dan YouTube mobile
- Mendukung mode gelap dan terang YouTube 
