# Commit Bertahap untuk Setiap Section

## Commit File Satu per Satu

### 1. Commit untuk `index.html`

```bash
git add index.html
git commit -m "Menambahkan index.html (halaman utama)"
```

> Commit ini menyimpan perubahan pada halaman utama portfolio.

<img width="1114" height="382" alt="Screenshot 2025-11-02 185411" src="https://github.com/user-attachments/assets/ee670996-0b87-4199-a2b5-ffb81c35e100" />

---

### 2. Commit untuk `styles.css`

```bash
git add styles.css
git commit -m "Menambahkan styles.css (file styling)"
```

> Commit ini fokus hanya pada bagian styling.

<img width="1114" height="247" alt="image" src="https://github.com/user-attachments/assets/33254491-2be6-415c-80ee-e9252a156da0" />

---

### 3. Commit untuk gambar `2315061026.jpeg`

```bash
git add 2315061026.jpeg
git commit -m "Menambahkan asset gambar ke project"
```

> Karena file gambar bukan perubahan kode, commit-nya dipisah untuk keteraturan dokumentasi.

---

### 4. Commit untuk `kritik_saran.html`

```bash
git add kritik_saran.html
git commit -m "Menambahkan kritik_saran.html (halaman form Kritik & Saran)"
```

> File ini dianggap sebagai section terpisah, sehingga dilakukan commit tersendiri.

---

## 🎯 Tips Commit yang Baik

* Commit hanya **1 bagian yang selesai**, bukan semuanya sekaligus.
* Gunakan pesan commit yang **jelas dan spesifik**.
* Hindari pesan seperti: `update file`, `fix`, `wip`.

Dengan cara ini, riwayat commit akan jelas, rapi, dan mudah dipahami.
