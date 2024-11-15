# Aplikasi Destinasi Wisata Indonesia

## Introduction
Indonesia memiliki banyak destinasi wisata menarik yang mencakup keindahan alam, kekayaan budaya, situs bersejarah, dan wisata modern. Namun, wisatawan sering mengalami kesulitan untuk mendapatkan informasi yang jelas, terperinci, dan mudah diakses mengenai destinasi-destinasi tersebut. 

Aplikasi ini hadir sebagai solusi yang memberikan informasi terstruktur mengenai destinasi wisata di Indonesia, dengan fokus khusus pada daerah **Bali** dan **Yogyakarta**.

Aplikasi ini dirancang untuk membantu wisatawan dalam menemukan dan memahami berbagai tempat wisata di Indonesia. Informasi yang disediakan mencakup deskripsi, gambar, jam operasional, harga tiket, dan lokasi yang dapat diakses melalui tautan peta. Selain itu, aplikasi ini juga memungkinkan wisatawan untuk memberikan ulasan dan rating pada destinasi yang telah dikunjungi, memberikan pengalaman yang lebih interaktif dan bermanfaat bagi pengguna lainnya.

Dengan antarmuka yang intuitif dan informasi yang akurat, aplikasi ini bertujuan untuk memudahkan eksplorasi wisatawan, mendukung pengembangan pariwisata Indonesia, dan memberikan pengalaman wisata yang nyaman serta informatif.

## Objective
- Memudahkan wisatawan menemukan informasi lengkap tentang destinasi wisata di Indonesia, termasuk deskripsi, gambar, jam operasional, harga tiket, dan lokasi.
- Memberikan pengalaman pengguna yang interaktif melalui fitur ulasan dan rating.

## Scope
- Aplikasi dapat digunakan oleh siapa saja tanpa batasan.
- Informasi yang tersedia mencakup destinasi wisata di **Bali** dan **Yogyakarta**.

## Business Requirement

### Business Requirement Definition

| **Produk**         | **Keterangan**                                                                                             |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| Jenis Layanan      | Layanan Informasi Destinasi Wisata                                                                         |
| Definisi           | Aplikasi mobile yang memberikan informasi lengkap dan terstruktur mengenai destinasi wisata di Indonesia, khususnya Bali dan Yogyakarta. Informasi ini mencakup deskripsi, gambar, jam operasional, harga tiket, dan lokasi. |
| Abstrak (Narasi)   | Aplikasi ini memudahkan wisatawan dalam menemukan dan mengeksplorasi tempat wisata melalui daftar destinasi yang dilengkapi dengan gambar, deskripsi, jam operasional, harga tiket, dan lokasi. Aplikasi ini menawarkan pengalaman eksplorasi yang nyaman dan informatif bagi wisatawan domestik maupun internasional. |

## Features

### Technical Features

| No  | Fitur                      | Deskripsi                                                                                                                                           |
|-----|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Destinasi Wisata            | Pengguna dapat memilih destinasi wisata yang tersedia di Bali dan Yogyakarta serta mendapatkan informasi terkait.                                      |
| 2   | Navigasi Peta               | Pengguna dapat melihat lokasi destinasi wisata pada peta melalui URL yang disediakan.                                                                |
| 3   | Pemesanan Tiket             | Pengguna dapat memesan tiket untuk destinasi wisata langsung melalui tautan pemesanan yang tersedia.                                                  |
| 4   | Ulasan Pengguna             | Pengguna dapat memberikan ulasan dan rating terhadap destinasi yang telah mereka kunjungi.                                                            |

### Strategic Features

| No  | Fitur                      | Deskripsi                                                                                                                                           |
|-----|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Efektivitas                 | Aplikasi ini menyediakan informasi wisata secara terstruktur, membantu wisatawan yang memerlukan akses cepat dan lengkap ke destinasi wisata di Indonesia. |
| 2   | Kelebihan                   | Antarmuka yang sederhana dan intuitif membuat aplikasi ini mudah digunakan oleh semua kalangan.                                                      |

## Functional & Specification

### Process Flows
1. **Pengguna Memilih Destinasi**: Pengguna memilih destinasi wisata berdasarkan lokasi (Bali atau Yogyakarta).
2. **Pengguna Melihat Informasi**: Informasi mengenai destinasi, termasuk deskripsi, jam operasional, dan harga tiket, akan ditampilkan.
3. **Pengguna Membuat Pemesanan**: Pengguna dapat melakukan pemesanan tiket melalui tautan yang tersedia jika destinasi memerlukan tiket.
4. **Pengguna Memberikan Ulasan**: Setelah mengunjungi destinasi, pengguna dapat memberikan ulasan dan rating.

### Specification

- **Framework**: Flutter
- **Assets Management**: Penggunaan Pubspec Assets untuk gambar dan data wisata.
- **Page Structure**: Penambahan halaman seperti homepage dan destination page untuk menampilkan daftar destinasi dan informasi detail destinasi.
- **Data Selection**: Data destinasi dipilih menggunakan class `destinationPage` untuk ditampilkan di halaman destinasi.

---

**Aplikasi ini bertujuan untuk:**
- Memberikan informasi lengkap dan terstruktur tentang destinasi wisata.
- Mendukung pengembangan sektor pariwisata Indonesia.
- Mempermudah eksplorasi wisatawan dengan menyediakan antarmuka yang mudah digunakan dan fitur yang bermanfaat.
