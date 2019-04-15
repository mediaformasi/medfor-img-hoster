https://medforupload.herokuapp.com/
# Some briefing for you:

## Susunan Direktori.
Untuk direktori saya buatkan tetapan yakni:
```
<Tahun>_<Bulan>
```
Berbeda dengan versi Website yang nama filenya bisa berubah, kalau anda bermain di GitHub saya tekankan **anda wajib rename nama pictnya sesuai konteks di bawah**. 
```
<Tahun4Digit><Bulan2Digit><Tanggal2Digit>_<Index>_<Jam><Menit>_<Judul>
```
Jadi bisa disimulasikan seperti ini:
```
root
  | 2019_01
    | 20190129_0_0734_Samseng.png
    | 20190129_1_0924_Siaomay.png
  | 2019_02
    | 20190214_0_1021_DavidGanteng.png
    | 20190217_0_2045_Loplep.png
    | 20190217_1_2045_Loplep.png
    | 20190217_0_2123_21IM@S.png
    | 20190217_0_2300_Bandori.png
```
Ya, kira-kira kek gitu deh.

## Nama commit.
Untuk nama commit, konteksnya gini aja biar nanti di commit dicari jadi gampang.
```
<Tahun4Digit><Bulan2Digit><Tanggal2Digit>_<Jam><Menit> <JudulGapakeSpasi>
```
Contoh seperti nama file di atas, cuma bedanya gapake index, jam, ama extension.

## Upload gambar untuk pemegang kunci github.
Sebenarnya ada dua langkah untuk menambahkan file di GitHub secara langsung dari repo ini:
1. Langsung komunikasi dengan Git CLI.
2. Drag & Drop (PC)

### Komunikasi dengan Git CLI.
Anda bisa langsung tarik data-data dalam git ini di direktori kesukaan kalian dengan cara:
```git
git clone https://github.com/mediaformasi/medfor-img-hoster.git
```
Kemudian ente taruh fotonya di folder sesuai dengan tutorial di atas tadi. Kemudian ente dorong lagi ke GitHub dengan cara:
```git
git remote add origin https://github.com/mediaformasi/medfor-img-hoster.git
git add .
git commit -am "20190217_2045_Loplep"
git push origin master
```
Benefitnya anda bisa rearrange file sesuka hati, hapus tambah foto sesuka hati.
Kekurangannya, anda terima juga sakitnya size total gambar di sini.

### Drag & Drop.
Tinggal drag aja gih di folder tertentu, udah gitu aja.
Benefitnya gaperlu git apalah gitu.
Kekurangannya jelas, cuma upload doang.

*(C) 2019 Ikramullah Latif - Media Formasi*
