# Truth or Dare Pancasila — Kelas VII

Website permainan pembelajaran Pendidikan Pancasila yang dapat dipublikasikan dengan GitHub Pages. Tidak membutuhkan framework, proses build, server, atau API key.

## Fitur
- Kartu Truth dan Dare yang dipilih secara acak.
- Filter kategori materi.
- Pengaturan guru untuk menambah, mengedit, dan menghapus kartu.
- Ekspor/impor kartu dalam format JSON.
- Daftar peserta/kelompok, pergantian giliran, dan papan skor.
- Unduh skor sebagai CSV.
- Tampilan responsif untuk HP, tablet, dan laptop.
- Kartu, peserta, dan skor disimpan secara lokal di browser (`localStorage`).

## Isi folder
- `index.html` — seluruh HTML, CSS, dan JavaScript dalam satu file.
- `README.md` — petunjuk ini.

## Publikasi ke GitHub Pages
1. Masuk ke https://github.com dan buat repository baru bernama `truth-or-dare-pancasila`.
2. Pilih **Public** (atau ikuti kebijakan organisasi/sekolah), lalu klik **Create repository**.
3. Pada halaman repository, klik **Add file → Upload files**.
4. Unggah `index.html` dan `README.md` dari folder ini, lalu klik **Commit changes**.
5. Buka **Settings → Pages**.
6. Di bagian **Build and deployment**, pilih **Deploy from a branch**.
7. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
8. Tunggu beberapa menit. GitHub Pages akan menampilkan URL publik, biasanya:
   `https://USERNAME.github.io/truth-or-dare-pancasila/`
   Ganti `USERNAME` dengan nama akun GitHub Anda dan gunakan URL yang ditampilkan GitHub sebagai alamat final.
9. Buka URL tersebut dan uji tombol Truth, Dare, Ambil kartu, Pengaturan Guru, serta papan skor.

## Cara menggunakan
1. Klik **Pengaturan Guru** untuk menambah, mengedit, atau menghapus kartu.
2. Pilih **Truth**, **Dare**, atau **Acak**.
3. Pilih kategori materi atau biarkan **Semua kategori**.
4. Klik **Ambil kartu**.
5. Diskusikan jawaban/tantangan. Klik **Selesai** untuk menutup giliran. Jika mengonfirmasi poin, peserta mendapat 1 poin.
6. Tambahkan atau ubah nama peserta sesuai kebutuhan.
7. Ekspor kartu untuk menyimpan cadangan JSON atau unduh skor sebagai CSV.

## Catatan penting
- Data disimpan hanya di browser/perangkat yang digunakan. Data tidak otomatis tersinkron antarperangkat atau antar-browser.
- Jika Anda ingin mengubah kartu permanen untuk semua pengunjung, ubah `DEFAULT_CARDS` di dalam `index.html`, lalu unggah perubahan ke GitHub. Perubahan yang dibuat lewat Pengaturan Guru hanya tersimpan lokal di browser tersebut.
- Jangan memasukkan data pribadi sensitif siswa.
- Tantangan harus aman, inklusif, tidak mempermalukan, dan selalu dapat diganti dengan tugas setara.
- Skor dimaksudkan sebagai alat bantu permainan, bukan satu-satunya dasar penilaian akademik.
