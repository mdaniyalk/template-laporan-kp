Template Naskah Laporan Kerja Praktik LaTeX
=============================

Template Naskah Laporan Kerja Praktik dengan typesetting LaTeX untuk Departemen Teknik Elektro dan Teknologi Informasi (DTETI) Universitas Gadjah Mada. Template ini merupakan hasil modifikasi dari versi pak Guntur (DTETI UGM) yang mana merupakan hasil modifikasi dari pak Pekik Nurwantoro (FMIPA UGM) dan Pak Yohan (DTETI UGM).

Semoga bermanfaat. Anda sangat dibolehkan untuk turut berkontribusi dalam project ini dengan *Fork*, *Pull Request*, *Create New Issue*, atau turut menjadi kontributor repo ini.

Terimakasih.


Quick Start
-----------
1. Siapkan LaTeX environment pada komputer anda, begitu pula LaTeX editornya. File yang diperlukan biasanya berukuran besar, jadi siapkan koneksi internet yang lancar jaya.
	- [*Windows*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)
	- [*Linux*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=linux+setup+latex)
	- [*Mac OS X*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=mac+setup+latex)
	- [Editor LaTeX di web](https://www.overleaf.com/) bisa dengan overleaf.com. Dengan ini kita tidak usah repot siapkan LaTeX environment.

2. *Clone* repository ini dengan 
	```bash
    git clone https://github.com/mdaniyalk/template-laporan-kp
    ```


3. Mulai tulis naskah anda, keterangan dari masing-masing file dalam template ini ada di bawah.

Contents
--------
Berikut penjelasan dari file-file utama dalam template ini. File lain yang tidak tercantum hanya pelengkap dalam repository ini.

		template-skripsi/
			├── gambar/
			│	   ├── logougm.png
			│	   └── wsn.png
			├── bab1.tex
			├── bab2.tex
			├── bab3.tex
			├── bab4.tex
			├── bab5.tex
			├── daftar-pustaka.bib
			├── template-kp.pdf
			├── template-kp.tex
			└── jtetikp.cls

### bab1.tex - bab5.tex
Konten utama dari skripsi, mulai dari BAB I (pendahuluan) sampe BAB V (kesimpulan). Silakan disesuaikan dengan jumlah bab Laporan Kerja Praktik anda, hapus file yang tidak perlu atau tambahkan file baru untuk bab baru.

### daftar-pustaka.bib
File yang berisi daftar referensi-referensi yang anda gunakan dalam skripsi. File ini penting guna menyusun daftar pustaka anda. Dengan file ini menyusun daftar pustaka menjadi sangat sangat sangat mudah.

File ini adalah hasil export dari aplikasi *reference management* seperti Mendeley, Zotero, EndNote, dll. Biasakan mengorganisir referensi Laporan Kerja Praktik anda menggunakan aplikasi *reference management*.

### template-kp.tex
File ini template-kp.tex adalah file utama (kepala) dari template. Berisi informasi-informasi dasar, seperti judul skripsi, nama penulis, nama pembimbing, dll.

### template-kp.pdf
File ini adalah Laporan Kerja Praktik anda dalam bentuk matang. Sudah rapi dan dapat dicetak untuk dijilid. File ini di-*generate* secara otomatis menggunakan LaTeX.

### jtetikp.cls
File yang berisi aturan-aturan format skripsi. Contoh, format cover, halaman pengesahan, daftar isi, daftar pustaka, dan konten skripsi.

Jika anda ingin memodifikasi template Laporan Kerja Praktik ini, ubahlah file *jtetikp.cls*.

### gambar/
Masukkan gambar-gambar pada Laporan Kerja Praktik anda di folder ini. Gambar default: logougm.png (dipakai di cover) dan wsn.png (hanya dipakai di template awal, silakan dihapus jika tidak diperlukan).
			

Lisensi
-------
Template laporan kerja praktik ini diadopsi dan dimodifikasi dari [gtrdp/template-skripsi](github.com/gtrdp/template-skripsi) yang juga menggunakan [lisensi MIT](https://raw.githubusercontent.com/gtrdp/template-skripsi/master/LICENSE).