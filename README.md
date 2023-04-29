<img src="https://matchboxid.my.id/box.png"/>




# imagejs
| Imagejs adalah selenium web server yang bekerja dengan javascript dan memerlukan website untuk menjalankan kode imagejs nya. gunakan cPanel untuk penyebaran yang lebih baik atau hosting menggunakan cyclic deployments.
|-----

| Imagejs tidak dapat di deploy secara asal karena anda harus mengedit fila view.js dengan url website anda yang terbuat dari javascript. website anda harus terbuat dari javascript agar bisa terhubung dengan cpanel domain anda.
|-----

# Deployment

### Windows / RDP / VPS
```
npm install ffmpeg
npm install javascript
git clone https://github.com/MatchBox-ID/imagejs.git
cd imagejs
yarn
npm install
node .
```

### cPanel
```
> Buka cPanel Anda
> Buka File Manager
> Buat File View.js
> Salin Kode View.js Pada repositori ini
> Selesai!
```

### Cyclic / Netlify / Railway / Okteto
```
> Buat Deployment Baru
> Fork Imagejs 
> Pilih Repositori Imagejs Dari github
> Pilih Imagejs
> Pilih Deploy
> Selesai!
```

### Heroku
| Maaf! Saat ini repositori ini belum dapat di deployment dengan heroku disebabkan oleh ketidaksamaan file dengan server heroku. jika anda mencoba nya di heroku mungkin kesalahan akan terjadi.
|-----

# Create Image
|Tempelkan kode dibawah di file view.js
|-----

### JPG Image
```
}
  "type":"jpg" //jenis gambar
  "type2":"imagedb" //server gambar
  "copyright":"matchtech" //this is credit
  "url":"https://matchboxid.my.id/server/server.jpg" //url gambar
  "apikey":"MTECHNO" //jangan diganti
  "size":"20Kb" //minimal 15Kb 
}
  "codeimg":"I6518" //ubah sesuai tipe gambar di file view
  "colour":"green" //warna logo
  "colour2":"red" //warna logo 2
  "colour3":"yellow" //warna logo 3
  "font":"sans-serif" //jenis font logo
  "icon":"fa fa-whatsapp" //icon logonya
{
```
### PNG Image
```
}
  "type":"png" //jenis gambar
  "type2":"imagedb", "imagejs" //server gambar
  "copyright":"matchtech" //this is credit
  "url":"https://matchboxid.my.id/server/server2.png" //url gambar
  "apikey":"MTECHPNG" //jangan diganti
  "size":35Kb" //minimal 30Kb
}
  "codeimg":"I6518" //ubah sesuai tipe gambar di file view
  "colour":"green" //warna logo
  "colour2":"red" //warna logo 2
  "colour3":"yellow" //warna logo 3
  "font":"sans-serif" //jenis font logo
  "icon":"fa fa-whatsapp" //icon logonya
{
```
### JPEG Image
```
}
  "type":"jpeg" //jenis gambar
  "type2":"imagedb", "imagendi" //server gambar
  "copyright":"matchtech" //this is credit
  "url":"https://matchboxid.my.id/server/server2.jpeg" //url gambar
  "apikey":"MTECHPNG" //jangan diganti
  "size":35Kb" //minimal 30Kb
}
  "codeimg":"I6518" //ubah sesuai tipe gambar di file view
  "colour":"green" //warna logo
  "colour2":"red" //warna logo 2
  "colour3":"yellow" //warna logo 3
  "font":"sans-serif" //jenis font logo
  "icon":"fa fa-whatsapp" //icon logonya
{
```


