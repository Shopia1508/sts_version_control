# Jawaban Tugas STS - Version Control
**Nama:** Shopia Amalia  
**Kelas:** 12 PPLG 2  

---

### 1. Apa yang dimaksud dengan GitHub?
GitHub adalah platform berbasis web untuk hosting kode sumber (source code) dan manajemen proyek yang menggunakan sistem *Git* (version control system). GitHub memungkinkan para pengembang untuk menyimpan, mengelola, melacak perubahan, serta berkolaborasi dalam pembuatan kode program secara bersama-sama secara online.

### 2. Apa Fitur dan Komponen Utama GitHub?
Beberapa fitur dan komponen utama yang ada di GitHub meliputi:
* **Repository (Repo):** Tempat penyimpanan seluruh file proyek, termasuk riwayat revisinya.
* **Branch (Cabang):** Fitur untuk membuat cabang kerja terpisah dari kode utama agar bisa mengembangkan fitur tanpa merusak kode asli.
* **Commit:** Catatan atau snapshot dari perubahan kode yang telah disimpan.
* **Pull Request (PR):** Fitur untuk menggabungkan (merge) perubahan dari suatu branch ke branch utama (misal dari branch tugas ke branch main) sekaligus tempat untuk melakukan *code review*.
* **Issues:** Fitur untuk melacak tugas, melaporkan bug, atau berdiskusi mengenai masalah dalam proyek.
* **Actions:** Fitur untuk otomatisasi alur kerja (CI/CD).

### 3. Sebutkan Alur Utama (GitHub Workflow)?
Alur kerja dasar (*GitHub Workflow*) yang biasa digunakan dalam kolaborasi proyek adalah:
1. **Fork / Clone:** Menyalin repository ke akun pribadi atau mengunduhnya ke komputer lokal.
2. **Create Branch:** Membuat branch baru untuk mulai mengerjakan fitur atau tugas baru.
3. **Make Changes & Commit:** Melakukan perubahan kode lalu menyimpan perubahan tersebut (*commit*) dengan pesan yang jelas.
4. **Push:** Mengunggah branch dari komputer lokal kembali ke GitHub.
5. **Pull Request & Merge:** Mengajukan permintaan penggabungan (*pull request*) agar kode baru bisa diperiksa dan digabungkan ke branch utama (*main*).

### 4. Apa keuntungan utama dari pembatasan branch main?
Keuntungan utama dari pembatasan branch `main` (seperti proteksi *branch*) adalah:
* **Menjaga Kestabilan Kode:** Mencegah perubahan atau kode yang rusak (*bug*) langsung masuk ke sistem utama yang sedang berjalan.
* **Kontrol Kualitas:** Memastikan setiap kode baru harus melalui proses pemeriksaan (*code review*) atau pengujian terlebih dahulu melalui *Pull Request* sebelum digabungkan.
* **Keamanan Kolaborasi:** Menghindari kesalahan fatal atau penghapusan file penting secara tidak sengaja oleh anggota tim yang tidak berwenang.