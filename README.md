# Minesweeper

Minesweeper adalah permainan komputer klasik yang menguji keterampilan pemain dalam logika dan strategi. Tujuan utama dari permainan ini adalah untuk mengungkap semua kotak di papan permainan tanpa mengenai satu pun ranjau yang tersembunyi.

## Cara Bermain

1. **Mulai Permainan**: Permainan dimulai dengan papan yang terdiri dari kotak-kotak yang belum diungkapkan.
2. **Klik Kotak**: Pemain dapat mengklik kotak untuk mengungkap isinya.
   - Jika kotak yang diklik berisi ranjau, permainan berakhir dan pemain kalah.
   - Jika kotak tersebut kosong atau berisi angka, pemain dapat melanjutkan permainan dengan mengklik kotak-kotak lainnya.
3. **Tandai Ranjau**: Pemain dapat menandai kotak yang mereka yakini berisi ranjau dengan bendera, untuk menghindari mengkliknya secara tidak sengaja.
4. **Analisis Angka**: Gunakan angka-angka yang terungkap untuk menentukan lokasi ranjau. Misalnya, jika sebuah kotak berisi angka "1", itu berarti ada satu ranjau di salah satu kotak tetangganya.
5. **Menang**: Pemain menang jika berhasil mengungkap semua kotak tanpa mengenai ranjau.

## Fitur

- **Input Jumlah Ranjau**: Pemain dapat memasukkan jumlah ranjau yang diinginkan sebelum memulai permainan.
- **Tombol Restart**: Pemain dapat memulai ulang permainan kapan saja dengan mengklik tombol restart.
- **Tingkat Kesulitan**: Permainan memiliki berbagai tingkat kesulitan, mulai dari pemula hingga ahli.

## Instalasi

1. Clone repositori ini:
   ```bash
   git clone https://github.com/ravano-2464/Minesweeper-Game.git

2. Buka proyek di IDE pilihan Anda.
3. Jalankan program utama:

```bash
javac Minesweeper.java
java Minesweeper