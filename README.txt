Tutorial
1. Extract file khanza-bpjs-api.zip ke webapps (atau public_html)
2. Sesuaikan config.php
3. Buat user dan password asuransi dengan kode_pj BPJ (lihat di khanza desktop)
4. Gunakan user dan password pada point 3 untuk generate token


CREATE TABLE antrian_referensi (
  tanggal_periksa date NOT NULL,
  nomor_referensi varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

ALTER TABLE antrian_referensi
  ADD PRIMARY KEY (`nomor_referensi`);
