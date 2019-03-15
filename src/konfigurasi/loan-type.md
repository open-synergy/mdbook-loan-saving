# Loan Type

## A. PENJELASAN ISIAN

### A.1. BAGIAN HEADER

![](../img/loan-type/utama.png)

#### Loan Type

Nama tipe pinjaman. Wajib diisi.

#### Loan Type Code

Kode tipe pinjaman. Wajib Diisi.

#### Active

Aktifkan jika data tipe pinjaman masih aktif digunakan. Non aktifkan jika tipe pinjaman
sudah tidak digunakan lagi.

#### Direction

Pilihan yang dimungkinkan:

* **In**: Pinjaman dari pihak lain kepada perusahaan
* **Out**: Pinjaman dari perusahaan kepada pihak lain

#### Sequence

Sequence yang digunakan untuk penomeran pinjaman. Tidak wajib diisi.



### A.2. TAB LOAN

![](../img/loan-type/loan-configuration.png)

#### Interest Method

Metode perhitungan bunga pinjaman. Wajib diisi. Pilihan yang dimungkinkan:

* **Flat**
* **Anuity**
* **Effective**

#### Maximum Loan Amount

Nilai maksimum pinjaman. Wajib diisi.

#### Intereset Amount

Bunga pinjaman (p.a) dalam persen. Wajib diisi.

#### Maximum Installment Amount

Maksimum tenor pinjaman dalam bulan. Wajib diisi.


### A.3. TAB ACCOUNTING

![](../img/loan-type/accounting-configuration.png)

#### Realization Journal

Buku jurnal yang akan digunakan untuk mencatat penjurnalan realiasi pinjaman. Tidak wajib diisi.

#### Realization Account

Akun yang akan digunakan pada penjunalan realisasi pinjaman. Pada **loan in** akun ini akan didebit sedangkan 
pada **loan out** akun ini akan dikredit. Akun ini akan didebit/dikredit sebesar **Loan Amount***

#### Short-Term Principle Account

Akun yang akan digunakan pada penjunalan realisasi pinjaman. Akan terbentuk n x journal item pada penjurnalan realisasi pinjaman. n sama dengan jumlah payment schedule yang jatuh tempo setahun semenjak tanggal realisasi. Pada **loan in** akun ini akan dikredit sedangkan pada **loan out** akun ini akan didebit. Akun ini akan didebit/dikredit sebesar **Loan Amount***

#### Long-Term Principle Account

Akun yang akan digunakan pada penjunalan realisasi pinjaman. Akan terbentuk n x journal item pada penjurnalan realisasi pinjaman. n sama dengan jumlah payment schedule yang jatuh tempo lebih dari setahun semenjak tanggal realisasi. Pada **loan in** akun ini akan dikredit sedangkan pada **loan out** akun ini akan didebit. Akun ini akan didebit/dikredit sebesar **Loan Amount***

#### Rounding Principle Account

Akun yng akan digunakan untuk pembulatan

#### Interest Journal

#TODO

#### Interest Account

#TODO

#### Interest Income Account

#TODO


### A.4. TAB WORKFLOW

![](../img/loan-type/workflow-configuration.png)

#### Allow To Confirm Loan

#TODO

#### Allow To Approve Loan

#TODO

#### Allow To Cancel Loan

#TODO

#### Allow To Restart Loan

#TODO
