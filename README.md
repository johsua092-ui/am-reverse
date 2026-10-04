

## apa yang bisa dilakuin

- **magic link login** — masuk pake email doang, tanpa password, tanpa akun google
- **premium aktif otomatis** — langsung nempel ke akun setelah verifikasi
- **auto refresh token** — aktivasi ulang kapan aja dari sesi tersimpan
- **dual mode** — CLI buat yang mager, web UI buat yang mau tampilan
- **stealth headers** — nyamar 100% sebagai app android asli (`x-android-package` + `x-android-cert`)

## cara pakai

### cli
```
node am.js
```
| | |
|---|---|
| `1` | kirim magic link ke email |
| `2` | paste link dari email → premium aktif |
| `3` | aktivasi ulang dari sesi tersimpan |
| `4` | lihat sesi tersimpan |

### web
```bash
npm install
node server.js
```
buka `http://localhost:3300` — ikuti 3 langkah di layar.

---

<div align="center">

**disclaimer** — ini riset independen. tidak berafiliasi dengan alight creative / google.
semua merek dagang milik pemiliknya masing-masing. gunakan atas risiko sendiri.
penyalahgunaan (akun orang lain, massal, komersial) bukan tanggung jawab pembuat.

</div>
