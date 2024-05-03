# Dokumen Teknis Integrasi OtomaX - Premium H2H #

**IP Center**
```bash
http://rch2h.mmtech.id
```
### Laporan Status Transaksi ###
- **Transaksi Sukses**
    ```bash
    #17126XXXX R#21563XXXX IN5.08581401XXXX SUKSES. SN : 03409100026161XXXXXX. Saldo Rp.12.345.678 - 1.234 = Rp.12.345.678 . @02/05 15.26.51 Transaction Success.Info:- kode_reseller=MMI12345 TRX Normal
    ```
- **Transaksi Diproses**
    ```bash
    #171412345 R#903123456 TREG10.082212345678 akan diproses @12.37. Saldo 1.234.567.000 - 12.123 = 1.234.567.000 kode_reseller=MMI01234 TRX Normal
    ```
- **Transaksi Menunggu Jawaban / Sudah Pernah**
    ```bash
    #171123456 R#903123456 IA5.085712345678 sdh pernah jam 12.39, status Menunggu Jawaban. SN/Ref: . Trx ke-2/hr: IA5.2.085712345678.pin. Saldo 1.234.531.425,773 kode_reseller=MMI01234 TRX Normal
    ```
- **Transaksi Timeout**
    ```bash
    #171123456 R# GP500.087812345678 GAGAL Timeout. Saldo 5.990.898 @07.49 kode_reseller=MMI01234 TRX Normal
    ```
- **Transaksi Gagal**
    ```bash
    #171123456 R#61123456 XLA10.083112345678 GAGAL. Transaction Failed.Info:Please Try Again Saldo Rp. 28.337.790 + 12.123 = Rp. 28.348.575 @12.46 kode_reseller=MMI01234 TRX Normal
    ```
- **Transaksi Saldo Tidak Cukup**
    ```bash
    R#903123456'R#903123456 XH3.081959...' GAGAL. Saldo tidak cukup.081912345678 Hrg 9.070, Saldo 1.793 Limit 0, proses 0. KetikTIKET utk deposit kode_reseller=MMI012345 TRX Normal
    ```
- **Transaksi Stok Kosong/Ditutup**
    ```bash
    XL DATA PURE 1.5GB 30 HARI XDP1500M.0819123456 GAGAL. Stok sedang kosong/ditutup. Saldo 45.765.546 @18.37 kode_reseller=MMI012345 TRX Normal
    ```
- **Transaksi Gangguan**
    ```bash
    R#30712345 XL DATA PURE 1GB 30 HARI XPR1.087712345678 GAGAL. Produk sedang gangguan. Saldo 8.201.909 @15.41 kode_reseller=MMI01234 TRX Normal
    ```

### Format Center IP ###
- **Format Parsing**
    ```bash
    trx?memberID=[memberid]&product=[kodeproduk]&dest=[tujuan]&refID=[trxid]&sign=[sign]
    ```
    ```bash
    trx?product=[kodeproduk]&qty=1&dest=[tujuan]&refID=[trxid]&memberID=[memberid]&pin=[pin]&password=[password]
    ```
- **Format Cek Saldo**
    ```bash
    balance?memberID=[memberid]&sign=[sign]
    ```
    ```bash
    balance?memberID=[memberid]&pin=[pin]&password=[password]
    ```
    
- **Format Tiket Deposit**
    ```bash
    ?cmd=ticket&memberid=[memberid]&amount=[nominal]&sign=[sign]
    ```
    ```bash
    ?cmd=ticket&memberid=[memberid]&amount=[nominal]&pin=[pin]&password=[password]
    ```

### CS Online 24 Jam
- CS. Telegram : [@cs_premiumH2H](https://t.me/cs_premiumH2H)
- CS. WhatsApp : [+62 857-1766-3665](https://wa.me/6285717663665)
- Channel TM : [Premium Pulsa H2H](https://t.me/premiumpulsah2hnew)
    
> **Head Office :** 
_Jl. Kramat III, Gg, Jl. Listrik II No.30, RT.3/RW.9, Kwitang, Kec. Senen, Kota Jakarta Pusat, Daerah Khusus Ibukota Jakarta 10420_
