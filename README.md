# 📬 Postman Collection - Tugas 10 API Testing (Reqres.in)

Repositori ini berisi file **Postman Collection** dan (opsional) **Environment** untuk pengujian API publik dari [https://reqres.in](https://reqres.in).

---

## 📁 Isi Repositori

- `tugas10-collection.json` — berisi request-request ke endpoint Reqres.in.
- `tugas10-environment.json` *(opsional)* — berisi variabel seperti `{{base_url}}` yang digunakan dalam request.

---

## 🚀 Cara Menggunakan

1. **Import ke Postman**:
   - Buka Postman.
   - Klik `File > Import`.
   - Pilih file `tugas10-collection.json`.
   - Jika kamu menggunakan variabel seperti `{{base_url}}`, import juga file `tugas10-environment.json`.

2. **Aktifkan Environment**:
   - Di kanan atas Postman, klik dropdown `No Environment`.
   - Pilih `reqres` atau nama environment yang sesuai.

3. **Jalankan Request**:
   - Buka collection di sidebar kiri.
   - Klik salah satu request, lalu klik tombol `Send`.

---

## 🛠️ Catatan

- Jika tidak mengimpor environment, pastikan semua URL tidak menggunakan variabel seperti `{{base_url}}`.
- Environment digunakan agar URL atau token bisa diganti-ganti tanpa ubah isi request satu per satu.

---

## 📌 Variabel di Environment

| Variable   | Value             |
|------------|-------------------|
| base_url   | https://reqres.in |

---

## 🧑‍💻 Author

- Nama: *Haruna Elfathin*
- Tugas 10 Automation API Test
