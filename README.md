# SIMKES Khanza JKN Mobile Rest API

Tutorial
1. Buat tabel antrian_referensi

~~~~sql
CREATE TABLE antrian_referensi (
  tanggal_periksa date NOT NULL,
  nomor_referensi varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

ALTER TABLE antrian_referensi
  ADD PRIMARY KEY (`nomor_referensi`);
~~~~

2. Clone repo ke webapps (atau public_html)
3. Sesuaikan config.php
4. Buat user dan password asuransi dengan kode_pj BPJ (lihat di khanza desktop)
5. Gunakan user dan password pada point 3 untuk generate token
6. Silahkan test sesuai Format Test dalam file excel
