# Aplikasi Emergency Response Covid-19

## Introduction
Pandemi Covid-19 telah menimbulkan tantangan besar bagi masyarakat, termasuk dalam mendapatkan informasi yang cepat, akurat, dan mudah diakses terkait penanganan dan pencegahan Covid-19. Aplikasi ini hadir sebagai solusi untuk memberikan informasi terstruktur dan real-time kepada masyarakat tentang situasi Covid-19, langkah-langkah pencegahan, serta akses cepat ke layanan darurat.

Aplikasi ini dirancang untuk memberikan panduan yang jelas tentang pencegahan Covid-19, menyediakan statistik terkini mengenai penyebaran virus, serta memungkinkan pengguna mengakses nomor darurat dan layanan terkait lainnya. Dengan fitur notifikasi real-time dan antarmuka yang intuitif, aplikasi ini berperan penting dalam mendukung respon cepat terhadap kondisi darurat yang disebabkan oleh Covid-19.

## Objective
- Menyediakan informasi lengkap dan real-time terkait Covid-19, termasuk statistik, langkah pencegahan, dan kontak darurat.
- Mempermudah akses masyarakat terhadap layanan darurat dan informasi penting terkait pandemi.
- Memberikan notifikasi terkait peringatan dan pembaruan Covid-19 untuk meningkatkan kewaspadaan masyarakat.

## Scope
- Aplikasi dapat digunakan oleh seluruh lapisan masyarakat.
- Informasi yang tersedia mencakup langkah pencegahan, statistik Covid-19, dan layanan darurat.

## Business Requirement

### Business Requirement Definition

| **Produk**         | **Keterangan**                                                                                             |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| Jenis Layanan      | Layanan Informasi dan Darurat Covid-19                                                                      |
| Definisi           | Aplikasi mobile yang memberikan informasi real-time tentang penyebaran Covid-19, langkah-langkah pencegahan, serta menyediakan akses ke layanan darurat. |
| Abstrak (Narasi)   | Aplikasi ini bertujuan untuk membantu masyarakat dalam mendapatkan informasi penting terkait Covid-19. Pengguna dapat melihat statistik terkini, panduan pencegahan, dan menghubungi layanan darurat melalui aplikasi ini. Aplikasi ini dirancang untuk mendukung respons cepat terhadap situasi darurat yang diakibatkan oleh pandemi. |

## Features

### Technical Features

| No  | Fitur                      | Deskripsi                                                                                                                                           |
|-----|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Halaman Beranda             | Menampilkan pesan singkat tentang pentingnya pencegahan Covid-19 dan informasi terkini tentang penyebaran virus di wilayah pengguna.                 |
| 2   | Panduan Pencegahan Covid-19 | Menyediakan langkah-langkah pencegahan seperti penggunaan masker, menjaga jarak, dan mencuci tangan dengan penjelasan yang jelas.                   |
| 3   | Statistik Covid-19          | Menampilkan data real-time mengenai jumlah kasus aktif, pasien sembuh, dan jumlah kematian berdasarkan wilayah pengguna.                            |
| 4   | Help & Support              | Menyediakan akses cepat ke nomor layanan darurat, rumah sakit, dan FAQ terkait Covid-19.                                                             |
| 5   | Layanan Darurat             | Tombol untuk langsung menghubungi layanan darurat melalui telepon atau WhatsApp, memberikan respons cepat kepada masyarakat dalam kondisi genting.   |

### Strategic Features

| No  | Fitur                      | Deskripsi                                                                                                                                           |
|-----|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Efektivitas                 | Aplikasi ini menyediakan informasi dan akses layanan darurat yang cepat dan terstruktur untuk masyarakat yang terdampak oleh Covid-19.               |
| 2   | Kelebihan                   | Antarmuka yang sederhana dan intuitif memudahkan penggunaan oleh seluruh kalangan masyarakat, baik muda maupun tua.                                  |

## Functional & Specification

### Process Flows
1. **Pengguna Mengakses Informasi**: Pengguna dapat melihat langkah-langkah pencegahan dan informasi statistik terkait Covid-19.
2. **Pengguna Menghubungi Layanan Darurat**: Pengguna dapat langsung menghubungi layanan darurat dengan tombol akses cepat.
3. **Pengguna Melihat Statistik**: Pengguna dapat memantau situasi terkini terkait kasus Covid-19 di wilayah mereka secara real-time.
4. **Pengguna Menerima Notifikasi**: Pengguna mendapatkan notifikasi jika ada pembaruan terkait data Covid-19 atau peringatan penting dari otoritas kesehatan.

### Specification

- **Framework**: Flutter
- **Assets Management**: Penggunaan Pubspec Assets untuk gambar dan data statistik Covid-19.
- **Page Structure**: Penambahan halaman seperti homepage, statistik page, dan emergency page untuk menampilkan informasi terkait.
- **Data Selection**: Data statistik Covid-19 dipilih dan diorganisir menggunakan API untuk menampilkan informasi real-time di halaman yang relevan.

---

**Aplikasi ini bertujuan untuk:**
- Menyediakan informasi penting terkait pencegahan dan penanganan Covid-19.
- Memberikan akses cepat ke layanan darurat dan nomor kontak penting.
- Memastikan pengguna mendapatkan informasi terkini tentang Covid-19 melalui notifikasi real-time.
