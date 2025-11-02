# Membuat Branch untuk Eksperimen Styling Baru

Dokumen ini berisi langkah membuat **branch baru** pada Git untuk melakukan eksperimen perubahan styling pada file `styles.css`, tanpa mengubah branch utama (`master`).

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

<img width="1095" height="381" alt="image" src="https://github.com/user-attachments/assets/3e8ea336-5bc3-433f-ba4e-ae4bfa540371" />

---

## 2. Pindah ke Branch Baru

```bash
git checkout experiment-styling
```

> Setelah ini, kamu resmi berada di branch eksperimen.

<img width="1114" height="383" alt="image" src="https://github.com/user-attachments/assets/5355ecf9-c37b-47d9-8618-e59e1f7a5b96" />

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

<img width="1116" height="231" alt="image" src="https://github.com/user-attachments/assets/3428e144-c986-4573-a438-eb2a8ad82c87" />

---

## 5. Kembali ke Branch Utama (master)

Jika sudah selesai bereksperimen:

```bash
git checkout master
```

<img width="1111" height="380" alt="image" src="https://github.com/user-attachments/assets/d7cd7757-0cf6-4ac8-8038-7548210389b2" />

---
