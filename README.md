# Pemendek pranala Frontend Indonesia

Repositori pemendek pranala untuk keperluan komunitas [Frontend Indonesia](https://feid.dev)

Pemendek pranala ini memanfaatkan [fitur _redirect_ dari Netlify](https://www.netlify.com/docs/redirects/).

## Cara penggunaan

### Manual

Silakan tambahkan baris baru di _file_ [`_redirects`](./_redirects) dengan format sebagai berikut:

```_redirects
/pranala-pendek   https://contoh.com/pranala-panjang
```

Lalu _push_ langsung ke cabang `master` atau kirim _pull request_ jika Anda tidak memiliki akses _push_ langsung ke `master`.

### Otomatis

Ikuti petunjuk di [netlify-shortener](https://github.com/kentcdodds/netlify-shortener#usage), dengan syarat Anda memiliki akses _push_ langsung ke `master`.
