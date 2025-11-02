# Merge Branch Setelah Styling Selesai

Dokumen ini menjelaskan cara **menggabungkan (merge)** branch hasil eksperimen styling (`experiment-styling`) ke branch utama (`master`) setelah perubahan dianggap final.

---

## Tujuan

Setelah selesai melakukan styling di branch eksperimen, kita perlu membawa perubahan tersebut ke branch utama agar menjadi bagian resmi dari project.

> Proses ini disebut **merge**.

---

## 1. Pastikan kamu sudah berada di branch `master`

Sebelum melakukan merge, pindah dulu ke branch `master`:

```bash
git checkout master
```

> Merge hanya bisa dilakukan dari branch yang akan menerima perubahan (master).

---

## 2. Lakukan Merge

Jalankan perintah berikut untuk mengambil perubahan dari branch `experiment-styling` dan memasukkannya ke `master`:

```bash
git merge experiment-styling
```

<img width="1110" height="380" alt="image" src="https://github.com/user-attachments/assets/e5aa86e3-8081-4e86-9b7a-736b82e42986" />

> Git akan menggabungkan seluruh perubahan styling ke dalam branch `master`.

---

## 📌 3. (Opsional) Hapus branch eksperimen

Jika styling sudah final dan tidak dibutuhkan lagi, hapus branch eksperimen:

```bash
git branch -d experiment-styling
```

---
