# Membuat Branch untuk Eksperimen Styling Baru

Dokumen ini berisi langkah membuat **branch baru** pada Git untuk melakukan eksperimen perubahan styling pada file `styles.css`, tanpa mengubah branch utama (`main`).

---

## Tujuan Branch

Branch digunakan untuk **mencoba perubahan** pada styling (misalnya desain warna, layout, atau efek hover) tanpa mengganggu project utama.

> Dengan branch, kamu bisa mengubah CSS sesuka hati. Jika bagus → merge ke `master`, jika tidak → hapus branch.

---

## 1. Membuat Branch Baru

Jalankan perintah berikut untuk membuat branch dengan nama `experiment-styling`:

```bash
git branch experiment-styling
```

---

## 2. Pindah ke Branch Baru

```bash
git checkout experiment-styling
```

> Setelah ini, kamu resmi berada di branch eksperimen.

---

## 3. Lakukan Perubahan di `styles.css`

Misalnya kamu mengubah styling seperti warna, font, atau tampilan hover.

---

## 4. Commit Perubahan Styling

Setelah selesai mengubah `styles.css`, simpan perubahan dengan commit:

```bash
git add styles.css
git commit -m "Eksperimen styling baru pada styles.css"
```

---

## 5. Kembali ke Branch Utama (main)

Jika sudah selesai bereksperimen:

```bash
git checkout main
```

---
