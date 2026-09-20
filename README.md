# ✈️ Flight Network Analysis

### Centrality and Resilience Analysis of Indonesia's International Airport Network Using Weighted Laplacian Energy Centrality (WLEC)

## Research Overview

Transportasi udara memiliki peran penting dalam menghubungkan berbagai wilayah, terutama di Indonesia yang terdiri dari banyak pulau. Selain membantu masyarakat bepergian dengan lebih cepat, jaringan penerbangan juga mendukung aktivitas ekonomi, pariwisata, distribusi barang, hingga pengembangan bisnis antarwilayah.

Namun, jaringan penerbangan memiliki karakteristik saling terhubung dan bergantung satu sama lain. Ketika sebuah bandara mengalami gangguan, misalnya akibat kebakaran hutan dan asap, erupsi gunung yang menghasilkan abu vulkanik, atau kondisi lain yang menyebabkan bandara harus ditutup, dampaknya dapat meluas ke bagian lain dari jaringan penerbangan.

Hal tersebut menimbulkan pertanyaan:

> **Seberapa penting peran masing-masing bandara dalam suatu jaringan penerbangan, dan seberapa besar perubahan jaringan apabila salah satu bandara mengalami gangguan atau harus ditutup?**

Dalam penelitian ini, bandara direpresentasikan sebagai *node*, sedangkan hubungan penerbangan antarbandara direpresentasikan sebagai *edge*. Bobot pada setiap hubungan ditentukan berdasarkan jumlah maskapai yang menyediakan layanan pada rute tersebut, sehingga rute dengan lebih banyak penyedia layanan memiliki bobot yang lebih besar.

Analisis dilakukan menggunakan **Weighted Laplacian Energy Centrality (WLEC)** dan simulasi penghapusan bandara untuk menganalisis perubahan struktur dan ketahanan jaringan.

---

## Hasil

Hasil analisis menunjukkan bahwa bandara seperti **CGK, KNO, DPS, PKU, dan BPN** memiliki nilai WLEC tertinggi, sedangkan **KJT, BWX, dan MKQ** memiliki nilai terendah.

Berdasarkan analisis dampak penghapusan simpul terhadap struktur jaringan, setiap bandara memiliki tingkat peran yang berbeda dalam menjaga stabilitas struktur jaringan. Bandara **BPN dan CGK** berperan dominan dalam aspek konektivitas global jaringan, sementara **MDC** lebih dominan dalam menjaga konektivitas lokal antarbandara dalam kelompoknya.

Selain itu, **CGK** juga berperan penting dalam mempertahankan efisiensi aliran dan jarak lintasan rata-rata jaringan. Meskipun demikian, perubahan nilai akibat penghapusan satu simpul secara umum menunjukkan selisih yang relatif kecil. Kondisi ini mengindikasikan bahwa jaringan penerbangan menunjukkan tingkat ketahanan yang relatif tinggi terhadap gangguan tunggal.
