https://dashboard.heroku.com/apps/medforupload
# Some briefing for you:

## Susunan Direktori
Untuk direktori saya buatkan tetapan yakni:
```
<Bulan>_<Tahun>
```
Berbeda dengan versi Website yang nama filenya bisa berubah, kalau anda bermain di GitHub saya tekankan **anda wajib rename nama pictnya sesuai konteks di bawah**. 
```
<Tanggal2Digit><Bulan2Digit><Tahun4Digit>_<Index>_<Jam><Menit>_<Judul>
```
Jadi bisa disimulasikan seperti ini:
```
root
  | Januari_2019
    | 29012019_0_0734_Samseng.png
    | 29012019_1_0924_Siaomay.png
  | Februari_2019
    | 14022019_0_1021_DavidGanteng.png
    | 17022019_0_2045_Loplep.png
    | 17022019_1_2045_Loplep.png
    | 17022019_0_2123_21IM@S.png
    | 17022019_0_2300_Bandori.png
```
Ya, kira-kira kek gitu deh.

## Nama commit.
Untuk nama commit, konteksnya gini aja biar nanti di commit dicari jadi gampang.
```
<Tanggal2Digit><Bulan2Digit><Tahun4Digit>_<Jam><Menit>_<JudulGapakeSpasi>
```
Contoh seperti nama file di atas, cuma bedanya gapake index, jam, ama extension.

## Upload gambar untuk pemegang kunci github.
Sebenarnya ada dua langkah untuk menambahkan file di GitHub secara langsung dari repo ini:
1. Langsung komunikasi dengan Git CLI.
2. Drag & Drop (PC)

### Komunikasi dengan Git CLI
Anda bisa langsung tarik data-data dalam git ini di direktori kesukaan kalian dengan cara:
```git
git clone https://github.com/mediaformasi/medfor-img-hoster.git
```
Kemudian ente taruh fotonya di folder sesuai dengan tutorial di atas tadi. Kemudian ente dorong lagi ke GitHub dengan cara:
```git
git remote add origin https://github.com/mediaformasi/medfor-img-hoster.git
git add .
git commit -am "17022019_2045_Loplep"
git push origin master
```
Benefitnya anda bisa rearrange file sesuka hati, hapus tambah foto sesuka hati.
Kekurangannya, anda terima juga sakitnya size total gambar di sini.

### Drag & Drop
Tinggal drag aja gih di folder tertentu, udah gitu aja.
Benefitnya gaperlu git apalah gitu.
Kekurangannya jelas, cuma upload doang.

*(C) 2019 Ikramullah Latif - Media Formasi*
