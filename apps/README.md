# wilayah v2.7
Aplikasi sederhana menggunakan Kode dan Data Wilayah Administrasi Pemerintahah Indonesia sesuai Kepmendagri No 100.1.1-6117 Tahun 2022 dengan PHP+MySQL+AJaX

(Kode dan Data Wilayah Pemerintahan Indonesia  dalam db wilayah.sql sesuai Kepmendagri No 100.1.1-6117 Tahun 2022, utk aplikasi ini hanya menggunakan data level 1 dan 2 (provinsi dan kabupaten/kota) di /db/archive/wilayah_level_1_2.sql yang sesuai dengan Kepmendagri No 100.1.1-6117 Tahun 2022, dengan penambahan data lat/long/elv/timezone,boundaries/polygon,luas dan jumlah penduduk)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/cahyadsn/wilayah.svg)](https://github.com/cahyadsn/wilayah/issues)
[![GitHub forks](https://img.shields.io/github/forks/cahyadsn/wilayah.svg)](https://github.com/cahyadsn/wilayah/network)
[![GitHub stars](https://img.shields.io/github/stars/cahyadsn/wilayah.svg)](https://github.com/cahyadsn/wilayah/stargazers)

## DEMO
tautan demo web [apps versi 2.7](https://wilayah.cahyadsn.com/apps) 

## SCREENSHOT
![screenshot](https://github.com/cahyadsn/wilayah/blob/master/apps/img/250514.png?raw=true)

Database Data dan Kode Wilayah Administrasi Pemerintahan sesuai Kepmendagri No 100.1.1-6117 Tahun 2022 untuk tingkat Provinsi dan Kota/Kabupaten beserta data latitude/longitude (koordinat) dan polygon boundaries-nya dan aplikasi sederhananya

Untuk aplikasi wilayah v2.7 ini mengguanakan database dengan nama tabel wilayah_level_1_2 yang terdapat di folder /db/archive/wilayah_level_1_2.sql

Sesuaikan data konfigurasi database yang ada di apps/inc/db.php

| id_prov | nama                      | kab  | kota |
|---------|---------------------------|-----:|-----:|
| 11      | Aceh                      |   18 |    5 |
| 12      | Sumatera Utara            |   25 |    8 |
| 13      | Sumatera Barat            |   12 |    7 |
| 14      | Riau                      |   10 |    2 |
| 15      | Jambi                     |    9 |    2 |
| 16      | Sumatera Selatan          |   13 |    4 |
| 17      | Bengkulu                  |    9 |    1 |
| 18      | Lampung                   |   13 |    2 |
| 19      | Kepulauan Bangka Belitung |    6 |    1 |
| 21      | Kepulauan Riau            |    5 |    2 |
| 31      | DKI Jakarta               |    1 |    5 |
| 32      | Jawa Barat                |   18 |    9 |
| 33      | Jawa Tengah               |   29 |    6 |
| 34      | DI Yogyakarta             |    4 |    1 |
| 35      | Jawa Timur                |   29 |    9 |
| 36      | Banten                    |    4 |    4 |
| 51      | Bali                      |    8 |    1 |
| 52      | Nusa Tenggara Barat       |    8 |    2 |
| 53      | Nusa Tenggara Timur       |   21 |    1 |
| 61      | Kalimantan Barat          |   12 |    2 |
| 62      | Kalimantan Tengah         |   13 |    1 |
| 63      | Kalimantan Selatan        |   11 |    2 |
| 64      | Kalimantan Timur          |    7 |    3 |
| 65      | Kalimantan Utara          |    4 |    1 |
| 71      | Sulawesi Utara            |   11 |    4 |
| 72      | Sulawesi Tengah           |   12 |    1 |
| 73      | Sulawesi Selatan          |   21 |    3 |
| 74      | Sulawesi Tenggara         |   15 |    2 |
| 75      | Gorontalo                 |    5 |    1 |
| 76      | Sulawesi Barat            |    6 |    0 |
| 81      | Maluku                    |    9 |    2 |
| 82      | Maluku Utara              |    8 |    2 |
| 91      | Papua                     |    8 |    1 |
| 92      | Papua Barat               |   12 |    1 |
| 93      | Papua Selatan             |    4 |    0 |
| 94      | Papua Tenagh              |    8 |    0 |
| 95      | Papua Pegunungan          |    8 |    0 |
|         | TOTAL                     |  416 |   98 |


link demo bisa dilihat [di sini](https://wilayah.cahyadsn.com/apps/) (data sesuai Kepmendagri No 100.1.1-6117 Tahun 2022)

## Referensi
- Dokumen Referensi : https://github.com/cahyadsn/wilayah_ref
- Keputusan Menteri Dalam Negeri Nomor 100.1.1-6117 Tahun 2022 Tentang Pemberian dan Pemutakhiran Kode, Data Wilayah Adminstrasi Pemerintahan, dan Pulau (Ditetapkan pada 9 November 2022) *
- UU No 14 Tahun 2022 tentang Pembentukan Provinsi Papua Selatan (LN.2022/No.157, TLN No.6803, jdih.setneg.go.id: 15 hlm., 25 Juli 2022)
- UU No 15 Tahun 2022 tentang Pembentukan Provinsi Papua Tengah (LN.2022/No.158, TLN No.6804, jdih.setneg.go.id: 14 hlm., 25 Juli 2022)
- UU No 16 Tahun 2022 tentang Pembentukan Provinsi Papua Pegunungan (LN.2022/No.159, TLN No.6805, jdih.setneg.go.id: 14 hlm., 25 Juli 2022)
- Keputusan Menteri Dalam Negeri Nomor 050-145 Tahun 2022 Tentang Pemberian Kode, Data Wilayah Administrasi Pemerintahan, Dan Pulau Tahun 2021 (Kepmendagri No. 050-145 Tahun 2022, https://www.kemendagri.go.id/arsip/detail/10857/keputusan-menteri-dalam-negeri-nomor-050145-tahun-2022-tentang-pemberian-kode-data-wilayah-administrasi-pemerintahan-dan-pulau-tahun-2021 (Ditetapkan pada tanggal 14 Februari 2022)
- Peraturan Menteri Dalam Negeri Republik Indonesia Nomor 58 Tahun 2021 Tentang Kode, Data Wilayah Administrasi Pemerintahan, Dan Pulau https://paralegal.id/peraturan/peraturan-menteri-dalam-negeri-nomor-58-tahun-2021/ (Permendagri No.58 2021, Ditetapkan pada tanggal 13 Desember 2021,Berita Negara Tahun 2021 Nomor 1391)
- Penetapan Nama, Kode Dan Jumlah Desa Seluruh Indonesia Tahun 2020 (Kepmendagri No. 146.1-4717 - 2020) http://binapemdes.kemendagri.go.id/produkhukum/detil/keputusan-menteri-dalam-negeri-nomor-1461-4717-tahun-2020 (Ditetapkan pada tanggal 21 Desember 2020)
- Kode dan Data Wilayah Administrasi Pemerintahan (Permendagri No.72-2019) https://www.kemendagri.go.id/page/read/48/peraturan-menteri-dalam-negeri-no72-tahun-2019 (Berita Negara Republik Indonesia Tahun 2019 Nomor 1327, Ditetapkan pada tanggal 8 Oktober 2019)
- Kode dan Data Wilayah Administrasi Pemerintahan (Permendagri No.137-2017) http://www.kemendagri.go.id/produk-hukum/2018/01/18/kode-dan-data-wilayah-administrasi-pemerintahan-tahun-2017 (Berita Negara Republik Indonesia Tahun 2017 Nomor 1955, Ditetapkan pada tanggal 27 Desember 2017)
- Kode dan Data Wilayah Administrasi Pemerintahan (Permendagri No.56-2015) www.kemendagri.go.id/pages/data-wilayah (Berita Negara Republik Indonesia Tahun 2015 Nomor 1045, Ditetapkan pada tanggal 29 Juni 2015)

## New Update
- update web apps demo ke v2.7 2025-05-13
- update library javascript dari jquery ke zepto js (done 2025-01-27)
- update data db/archive/wilayah_level_1_2.sql sesuai Kepmendagri No 100.1.1-6117 Tahun 2022 (done 2024-05-15)

## DONASI
- untuk donasi via transfer 
    - Bank BCA Digital (Blu) (501) 000 576 776 186
    - Bank Jago (542) 5003 5796 1022
    - Bank Sinarmas (153) 005 462 4719
    - Bank Syariah Indonesia (BSI) 821-342-5550
- untuk donasi via PayPal [https://paypal.me/cahyadwiana]
- untuk donasi via Ko-fi [https://ko-fi.com/cahyadsn]


