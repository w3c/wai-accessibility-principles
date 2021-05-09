---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: Prinsip Aksesibilitas   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Prinsip Aksesibilitas"   # A short title that is used in the navigation

lang: id   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2021-05-09   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators: 
- name: "Fri Rasyidi"   # Replace @@ with translator name
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple translators
# contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

ref: /fundamentals/accessibility-principles/   # Do not change this
layout: default
github:
  repository: w3c/wai-accessibility-principles
  path: content/index.id.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
permalink: /fundamentals/accessibility-principles/id   # Add the language shortcode to the end; for example /fundamentals/accessibility-principles/fr

description: Gambaran umum persyaratan dasar aksesibilitas untuk situs web, aplikasi web, browser, dan sarana lainnya.   # translate this sentence
image: /content-images/wai-accessibility-principles/social.png

teaser_text: Halaman Prinsip Aksesibilitas memperkenalkan beberapa persyaratan aksesibilitas untuk situs web, aplikasi web, browser, dan alat lainnya. Halaman ini memberikan referensi ke standar internasional dari Inisiatif Aksesibilitas Web (WAI) W3C dan ke cerita-cerita para pengguna web.

footer: >   # Translate all the words below, including "Date:", "Editor:", Updated, and the month. Do not change these dates.
  <p><strong>Tanggal:</strong> Diperbarui 10 May 2019. CHANGELOG</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/shadi/">Shadi Abou Zahra</a>. <a href="https://www.w3.org/WAI/intro/people-use-web/acknowledgments">Ucapan Terima Kasih</a>.</p>
  <p>Dikembangkan oleh Kelompok Kerja Edukasi dan Pendampingan (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Sebelumnya dikembangkan bersama <a href="https://www.w3.org/WAI/EO/2008/wai-age-tf">Satuan Tugas WAI-AGE</a>, dengan dukungan dari <a href="https://www.w3.org/WAI/WAI-AGE/">Proyek WAI-AGE</a>.</p>

changelog: /fundamentals/accessibility-principles/changelog/

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-accessibility-principles/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Ringkasan" class="full" %}
{:/}

Halaman ini memperkenalkan beberapa persyaratan aksesibilitas untuk situs web, aplikasi web, browser, dan sarana lainnya. Halaman ini menyediakan referensi ke Standar Internasional dari Inisiatif Aksesibilitas Web (WAI) W3C dan [cerita-cerita mengenai pengguna web](/people-use-web/user-stories/).

**Catatan:** Ini bukan daftar lengkap dari semua persyaratan aksesibilitas.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Daftar Isi" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}


{% include excol.html type="all" %}

## Standar aksesibilitas web {#standards}

Aksesibilitas web bergantung pada kerjasama beberapa komponen. Beberapa diantaranya termasuk:

-   **Konten web**{:#webcontent} - merujuk pada bagian mana pun dari sebuah situs web, termasuk teks, gambar, form, dan multimedia, serta kode penanda apa pun, skrip, aplikasi, dan sejenisnya.
-   **Agen pengguna**{:#useragents} - perangkat lunak yang digunakan seseorang untuk mengakses konten web, termasuk browser dektop dengan antarmuka grafis, browser berbasis suara, browser ponsel, pemutar multimedia, plugin, dan beberapa [teknologi pembantu](/people-use-web/tools-techniques/#at "definition").
-   **Sarana penulisan**{:#authoringtools} - perangkat lunak atau jasa yang digunakan seseorang untuk membuat konten web, termasuk editor kode, sarana konversi dokumen, sistem manajemen konten, blog, skrip database, dan sarana lainnya.

{% include excol.html type="start" %}

### Lebih lanjut tentang standar aksesibilitas web
{:.no_toc}

{% include excol.html type="middle" %}

Komponen-komponen berikut saling berkaitan dan mendukung satu sama lain. Contohnya, **konten web** perlu menyertakan alternatif teks untuk gambar. Informasi ini perlu bisa diproses oleh **browser web** dan disalurkan ke **teknologi pembantu**, seperti pembaca layar. Penulis memerlukan **sarana penulisan** yang mampu mendukung mereka untuk membuat alternatif teks. Latar belakang lebih lanjut dapat dilihat di [[Komponen Esensial dari Aksesibilitas Web]](/fundamentals/components/).

Standar memainkan peranan penting dalam mendefinisikan persyaratan aksesibilitas untuk setiap komponen. Beberapa persyaratan aksesibilitas dapat dipenuhi dengan mudah, namun memahami dasar tentang bagaimana para penyandang disabilitas menggunakan Web akan membantu penerapannya lebih efektif dan efisien. Beberapa aspek aksesibilitas membutuhkan kemampuan teknis atau pengetahuan yang lebih tinggi mengenai bagaimana seseorang menggunakan Web. Dalam kasus mana pun, [melibatkan pengguna sejak awal dan selama proyek berjalan](/test-evaluate/involving-users/) akan membuat pekerjaan Anda lebih baik dan mudah.

Inisiatif Aksesibilitas Web (WAI) W3C menyediakan satu set panduan yang telah diakui secara internasional sebagai standar untuk aksesibilitas web. Termasuk:

-   **[Panduan Aksesibilitas Konten Web (WCAG)](/standards-guidelines/wcag/)**
-   **[Panduan Aksesibilitas Agen Pengguna (UAAG)](/standards-guidelines/uaag/)**
-   **[Panduan Aksesbilitas Sarana Penulisan (ATAG)](/standards-guidelines/atag/)**

Terdapat pula spesifikasi WAI untuk **[Aplikasi Internet Kaya yang Aksesibel (WAI-ARIA)](https://www.w3.org/WAI/intro/aria.php)**, yang mencakup konten dinamis dan kontrol antarmuka pengguna tingkat lanjut yang dikembangkan dengan Ajax, JavaScript, dan teknologi web terkait.

{% include excol.html type="end" %}

## Informasi dan antarmuka yang Dapat Dipersepsikan {#perceivable}

### Alternatif teks untuk konten non-teks {#alternatives}

Alternatif teks sepadan dengan konten non-teksnya. Contohnya termasuk:

-   Padanan pendek untuk gambar, termasuk ikon, tombol, dan elemen grafis
-   Deskripsi data yang direpresentasikan pada bagan, diagram, dan ilustrasi
-   Penjelasan singkat tentang konten non-teks seperti file audio dan video
-   Label untuk kontrol isian, input, dan komponen antarmuka lainnya

Alternatif teks menyampaikan tujuan gambar atau berfungsi untuk memberikan pengalaman pengguna yang sepadan. Misalnya, alternatif teks yang sesuai untuk tombol penelusuran adalah "*penelusuran*" dan bukan "*lensa pembesar*".

Alternatif teks dapat disajikan dalam berbagai cara. Misalnya, dibacakan atau ditampilkan di perangkat braille untuk orang yang tidak dapat melihat layar, dan diperbesar ke ukuran teks tertentu untuk yang kesulitan membaca. Alternatif teks berfungsi sebagai label pada fungsi dan kontrol untuk membantu navigasi kibor dan navigasi dengan pengenalan suara (input suara). Mereka juga berperan sebagai label untuk mengidentifikasi audio, video, file dalam format lain, serta aplikasi yang disematkan sebagai bagian dari sebuah situs web.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait dengan alternatif teks (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 1.1 - Alternatif Teks](https://www.w3.org/WAI/WCAG21/quickref/#text-alternatives)

**UAAG**

-   [Pedoman 1.1 - Konten Alternatif](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman aksesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.2.1: (Untuk antarmuka sarana penulisan) Sediakan konten alternatif untuk penulis](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [Pedoman A.2.2: (Untuk antarmuka sarana penulisan) Pastikan tampilan pada halaman edit bisa ditentukan via program](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pedoman A.3.7: (Untuk antarmuka sarana penulisan) Pastikan pratinjau setidaknya sama aksesibel dengan agen pengguna yang tersedia di pasaran](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

#### Cerita terkait alternatif teks
{:#stories-related-to-text-alternatives.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Martine, siswi daring yang kesulitan mendengar](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Teks dan alternatif lainnya untuk multimedia {#captions}

Orang-orang yang tidak bisa mendengar audio atau melihat video membutuhkan alternatif. Contoh:

-   Transkripsi dan teks untuk konten audio, seperti rekaman sebuah wawancara di radio
-   Deskripsi audio, narasi yang mendeskripsikan detail visual dalam sebuah video
-   Interpretasi bahasa isyarat dari konten audio, mencakup bagian pengalaman audio yang relevan

Teks transkripsi yang ditulis dengan baik dan memiliki urutan informasi yang tepat dari konten audio atau video memberikan aksesibilitas level dasar dan memfasilitasi pembuatan teks dan deskripsi audio.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait multimedia (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 1.2 - Media berbasis waktu](https://www.w3.org/WAI/WCAG21/quickref/#time-based-media)

**UAAG**

-   [Pedoman 1.1 - Konten alternatif](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman akseesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.2.1: (Untuk antarmuka sarana penulisan) Sediakan konten alternatif untuk penulis](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [PPedoman A.3.7: (Untuk antarmuka sarana penulisan) Pastikan pratinjau setidaknya sama aksesibel dengan agen pengguna yang tersedia di pasaran](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}
{% include excol.html type="start" %}

#### Cerita terkait multimedia {#stories-related-to-multimedia}
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, siswi daring yang kesulitan mendengar](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Konten dapat disediakan dengan berbagai cara {#adaptable}

Agar pengguna bisa mengubah cara penyediaan konten, penting untuk:

-   Judul, daftar, tabel, kolom input, dan struktur konten ditandai dengan benar
-   Urutan informasi atau instruksi terpisah dari cara penyediaannya
-   Browser dan teknologi pembantu menyediakan pengaturan untuk mengubah cara penyediaannya

Memenuhi persyaratan ini memungkinkan konten untuk bisa diucapkan dengan benar, diperbesar, atau disesuaikan untuk memenuhi kebutuhan dan preferensi orang yang berbeda-beda. Sebagai contoh, konten tersebut dapat disediakan menggunakan kombinasi warna, ukuran teks, atau gaya tampilan tertentu untuk memudahkan saat membaca. Persyaratan ini juga memfasilitasi bentuk adaptasi lainnya, termasuk pembuatan garis besar dan ringkasan halaman untuk membantu seseorang mendapatkan gambaran umum dan kemudian dengan lebih mudah dapat fokus ke bagian tertentu.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait cara penyediaan yang dapat disesuaikan (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 1.3 - Dapat Disesuaikan](https://www.w3.org/WAI/WCAG21/quickref/#adaptable)

**UAAG**

-   [Pedoman 1.4 - Pengaturan teks](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [Pedoman 1.5 - Pengaturan volume](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [Pedoman 1.6 - Pengaturan ujaran sintesis](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [Pedoman 1.7 - Pengaturan lembar gaya tampilan pengguna](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [Pedoman 1.9 - Tampilan alternatif](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [Pedoman 1.10 - Informasi elemen](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman akseesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.2.2: (Untuk antarmuka sarana penulisan) Pastikan tampilan halaman edit bisa ditentukan melalui pemrograman](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pedoman A.3.7: (Untuk antarmuka sarana penulisan) Pastikan pratinjau setidaknya sama aksesibel dengan agen pengguna yang tersedia di pasaran](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait cara penyediaan yang dapat disesuaikan
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, pembeli daring penyandang buta warna](/people-use-web/user-stories/#shopper)
-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Konten yang lebih mudah dilihat dan didengar {#distinguishable}

Konten yang dapat dikenali lebih mudah untuk dilihat dan didengar. Konten tersebut meliputi:

-   Warna tidak digunakan sebagai satu-satunya cara untuk menyediakan informasi atau mengenali sebuah konten
-   Kombinasi warna latar dan kontennya memiliki kontras yang cukup
-   Ketika pengguna memperbesar teks hingga 400% atau mengubah jarak antar teks, tidak ada informasi yang hilang
-   Teks menyesuaikan pada jendela kecil ("area-pandang") dan ketika pengguna membuat teks menjadi lebih besar
-   Ukuran gambar dan teks dapat diubah, dapat diganti dengan teks padanannya, atau dihindari ketika memungkinkan
-   Pengguna bisa menjeda, menghentikan, atau menyesuaikan volume audio yang dimainkan dalam situs web
-   Suara latar kecil atau bisa dimatikan, untuk menghindari gangguan atau distraksi

Memenuhi persyaratan ini membantu memisahkan konten dari latarnya, untuk membuat informasi yang penting lebih mudah dikenali. Hal ini mempertimbangkan orang yang tidak dan yang menggunakan teknologi pembantu dan mungkin terganggu oleh konten audio mau pun visual yang ada di latar. Sebagai contoh, banyak orang dengan buta warna tidak menggunakan sarana tertentu dan hanya bisa bergantung pada sarana dengan desain yang menyediakan kontras warna yang cukup antara teks dan warna latar di sekitarnya. Contoh lainnya, audio yang secara otomatis dimainkan dapat mengganggu mereka yang menggunakan teknologi teks-ke-suara atau [alat bantu pendengaran (ALDs)](http://www.w3.org/WAI/training/accessible#ald).

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait konten yang dapat dibedakan (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 1.4 - Dapat Dibedakan](https://www.w3.org/WAI/WCAG21/quickref/#distinguishable)

**UAAG**

-   [Pedoman 1.3 - Menyoroti](https://www.w3.org/TR/UAAG20/#gl-interaction-highlight)
-   [Pedoman 1.4 - Pengaturan teks](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [Pedoman 1.5 - Pengaturan volume](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [Pedoman 1.6 - Pengaturan ujaran sintesis](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [Pedoman 1.7 - pengaturan lembar gaya tampilan pengguna](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [Pedoman 1.8 - Orientasi pada area-pandang](https://www.w3.org/TR/UAAG20/#gl-viewport-orient)
-   [Pedoman 1.9 - Tampilan alternatif](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [Pedoman 1.10 - Informasi elemen](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman akseesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.3.7: (Untuk antarmuka sarana penulisan) Pastikan pratinjau setidaknya sama aksesibel dengan agen pengguna yang tersedia di pasaran](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait konten yang dapat dibedakan
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, pembeli daring penyandang buta warna](/people-use-web/user-stories/#shopper)
-   [Martine, siswi daring yang kesulitan mendengar](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

## Antarmuka dan navigasi yang dapat diopersikan {#operable}

### Fungsi tersedia melalui kibor {#keyboard}

Banyak orang yang tidak menggunakan tetikus dan bergantung pada kibor untuk berinteraksi dengan web. Mereka membutuhkan akses kibor ke semua fungsi, termasuk kontrol pada isian, input, dan berbagai komponen antarmuka lainnya.

Aksesibilitas kibor termasuk:

-   Semua fungsi yang tersedia pada tetikus dapat diakses melalui kibor
-   Fokus kibor tidak tertahan di bagian mana pun dari konten
-   Browser web, sarana penulisan, dan sarana lainnya menyediakan dukungan kibor

Memenuhi persyaratan ini membantu pengguna kibor, termasuk mereka yang menggunakan kibor alternatif seperti kibor dengan tata letak ergonomis, kibor dalam-layar, atau perangkat pengalihan. Akan membantu pula bagi orang-orang yang menggunakan pengenalan suara (input suara) untuk mengoperasikan situs web dan mendikte teks melalui kibor dalam-layar.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait aksesibilitas kibor (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 2.1 - Kibor yang aksesibel](https://www.w3.org/WAI/WCAG21/quickref/#keyboard-accessible)

**UAAG**

-   [Pedoman 2.1 - Akses kibor](https://www.w3.org/TR/UAAG20/#gl-keyboard-access)
-   [Pedoman 2.2 - Navigasi berurutan](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Pedoman 2.3 - Navigasi dan aktivasi langsung](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Pedoman 2.11 - Perangkat Input Lainnya](https://www.w3.org/TR/UAAG20/#gl-other-devices)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman akseesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.3.1: (Untuk antarmuka sarana penulisan) Sediakan akses kibor untuk fitur-fitur penulisan](https://www.w3.org/TR/ATAG20/#gl_a31)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait aksesibilitas kibor
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)

{% include excol.html type="end" %}

### Pengguna memiliki waktu yang cukup untuk membaca dan menggunakan konten {#time}

Beberapa orang membutuhkan waktu lebih dari yang lainnya untuk membaca dan menggunakan sebuah konten. Sebagai contoh, beberapa orang membutuhkan waktu lebih untuk mengetik, memahami instruksi, mengoperasikan kontrol, atau pun menyelesaikan tugas dalam sebuah situs web.

Contoh dari menyediakan waktu yang cukup termasuk menyediakan mekanisme untuk:

-   Menghentikan, memperpanjang, atau menyesuaikan batasan waktu, kecuali jika diperlukan
-   Menjeda, menghentikan, atau menyembunyikan konten bergerak, berkedip, atau bergulir
-   Menunda atau menghambat interupsi, kecuali jika diperlukan
-   Mengautentikasi ulang tanpa kehilangan data ketika sesi berakhir

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait waktu yang cukup (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 2.2 - Waktu yang cukup](https://www.w3.org/WAI/WCAG21/quickref/#enough-time)

**UAAG**

-   [Pedoman 2.8 - Interaksi yang tidak dibatasi waktu](https://www.w3.org/TR/UAAG20/#gl-time-independent)
-   [Pedoman 2.10 - Media berbasis waktu](https://www.w3.org/TR/UAAG20/#gl-control-inaccessible-content)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman akseesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.3.2: (Untuk antarmuka sarana penulisan) Berikan penulis waktu yang cukup](https://www.w3.org/TR/ATAG20/#gl_a32)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait waktu yang cukup
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Konten tidak mengakibatkan kejang dan reaksi fisik {#safe}

Konten yang berkedip dengan kecepatan atau pola tertentu dapat mengakibatkan reaksi fotosensitif, termasuk kejang. Konten berkedip idealnya dihindari sepenuhnya atau hanya digunakan dengan cara yang diketahui tidak mengakibatkan resiko. Animasi dan konten bergerak juga dapat mengakibatkan ketidaknyamanan dan munculnya reaksi fisik.

Contoh untuk menghindari mengakibatkan kejang dan reaksi fisik:

-   Jangan menyertakan konten yang berkedip pada kecepatan dan pola tertentu
-   Beri tahu pengguna sebelum menampilkan konten yang berkedip, dan sediakan alternatif
-   Sediakan mekanisme untuk mematikan animasi, kecuali penting

{% include excol.html type="start" %}

#### Persyaratan aksesbilitas terkait kejang (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 2.3 - Kejang](https://www.w3.org/WAI/WCAG21/quickref/#seizures-and-physical-reactions)

**UAAG**

-   [Pedoman 2.9 - Berkedip](https://www.w3.org/TR/UAAG20/#gl-prevent-flash)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman akseesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.3.3: (Untuk antarmuka sarana penulisan) Bantu penulis menghindari konten berkedip yang dapat mengakibatkan kejang](https://www.w3.org/TR/ATAG20/#gl_a33)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}

### Pengguna dapat dengan mudah menavigasi, mencari konten, dan menentukan dimana mereka {#navigable}

Konten yang terorganisasi dengan baik membantu pengguna mengorientasikan dirinya dan melakukan navigasi secara efektif. Konten tersebut meliputi:

-   Halaman dengan judul yang jelas dan terorganisasi menggunakan judul bagian yang deskriptif
-   Terdapat lebih dari satu cara untuk mencari halaman yang relevan pada situs web
-   Pengguna diberikan informasi mengenai lokasi mereka saat ini relatif pada halaman-halaman terkait
-   Terdapat cara untuk melewati sepenggal konten yang berulang di banyak halaman
-   Fokus kibor dapat dilihat, dan urutan fokus mengikuti pola yang bermakna
-   Tujuan adanya sebuah tautan jelas, idealnya bahkan ketika tautan itu dilihat secara mandiri

Memenuhi persyaratan ini membantu orang untuk menavigasi halaman web dengan berbagai cara, tergantung dari kebutuhan dan preferensi mereka. Sebagai contoh, ada yang bergantung pada struktur navigasi hierarkis seperti bilah menu untuk mencari halaman web spesifik, ada pula yang bergantung pada fungsi penelusuran pada situs web. Beberapa orang mungkin melihat konten ketika yang lain mendengarkannya atau bahkan melihat serta mendengarkan pada waktu bersamaan. Beberapa mungkin meenggunakan konten hanya dengan tetikus atau kibor, sedangkan yang lain mungkin menggunakan keduanya.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait navigasi (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 2.4 - Dapat Dinavigasikan](https://www.w3.org/WAI/WCAG21/quickref/#navigable)

**UAAG**

-   [Pedoman 2.2 - Navigasi berurutan](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Pedoman 2.3 - Navigasi dan aktivasi langsung](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Pedoman 2.4 - Penelusuran teks](https://www.w3.org/TR/UAAG20/#gl-search-text)
-   [Pedoman 2.5 - Navigasi struktural](https://www.w3.org/TR/UAAG20/#gl-nav-structure)
-   [Pedoman 2.7 - Kontrol grafis](https://www.w3.org/TR/UAAG20/#gl-configure-controls)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman akseesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.2.2: (Untuk antarmuka sarana penulisan) Pastikan tampilan halaman edit bisa ditentukan melalui pemrograman](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pedoman A.3.4: (Untuk antarmuka sarana penulisan) Tingkatkan pengalaman navigasi dan pengeditan melalui struktur konten](https://www.w3.org/TR/ATAG20/#gl_a34)
-   [Pedoman A.3.5: (Untuk antarmuka sarana penulisan) Sediakan penelusuran teks untuk konten](https://www.w3.org/TR/ATAG20/#gl_a35)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait navigasi
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Pengguna bisa menggunakan berbagai mode input di luar kibor {#modalities}

Berbagai mode input di luar kibor, seperti aktivasi sentuh, pengenalan suara (input suara), dan gestur membuat konten lebih mudah untuk digunakan bagi banyak orang. Namun tidak semua bisa menggunakan berbagai mode input ini, dan dengan kemampuan yang sama. Pertimbangan desain tertentu memaksimalkan keuntungan dari berbagai mode input ini. Termasuk:

-   Gestur yang membutuhkan ketangkasan atau gerakan yang cekatan memiliki alternatif mode yang tidak membutuhkan ketangkasan tinggi
-   Komponen didesain untuk menghindari aktivasi yang tidak disengaja, sebagai contoh dengan menyediakan fungsi pembatalan
-   Label yang disediakan kepada pengguna sesuai dengan nama objek dalam kode, untuk mendukung aktivasi dengan suara
-   Fungsi yang diaktifkan oleh gerakan juga dapat diaktifkan melalui komponen antarmuka
-   Tombol, tautan, dan komponen aktif lainnya cukup besar untuk membuatnya lebih mudah diaktifkan dengan sentuhan

Memenuhi persyaratan ini membuat konten lebih mudah digunakan oleh banyak orang dengan kemampuan yang beragam melalui berbagai perangkat. Hal ini termasuk konten yang digunakan di ponsel, tablet, dan terminal mandiri seperti mesin tiket.

{% include excol.html type="start" id="" %}

#### Persyaratan aksesibilitas terkait berbagai mode input (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 2.5 - Berbagai Mode Input](https://www.w3.org/WAI/WCAG21/quickref/#input-modalities)

{% include excol.html type="end" %}{% include excol.html type="start" id="" %}

#### Cerita terkait berbagai mode input
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

## Antarmuka dan informasi yang dapat dipahami {#understandable}

### Teks dapat dibaca dan dipahami {#readable}

Penulis konten perlu memastikan konten teks dapat dibaca dan dimengerti oleh seluas mungkin khalayak, termasuk ketika dibacakan oleh teknologi teks-ke-suara. Konten tersebut meliputi:

-   Mengidentifikasi bahasa utama sebuah halaman web, seperti Bahasa Arab, Bahasa Belanda, atau Bahasa Korea
-   Mengidentifikasi bahasa dari penggalan teks, frasa, atau bagian lainnya dalam sebuah halaman web
-   Menyediakan definisi untuk kata, frase, idiom, dan singkatan yang tidak biasa
-   Menggunakan bahasa yang sejelas dan sesederhana mungkin, atau menyediakan versi yang disederhanakan

Memenuhi persyaratan ini membantu perangkat lunak, termasuk teknologi pembantu, untuk memproses konten teks dengan benar. Sebagai contoh, persyaratan ini membantu perangkat lunak untuk mengucapkan konten, atau membuat ringkasan halaman, dan untuk menyediakan definisi pada kata yang tidak umum digunakan seperti jargon teknis. Hal ini juga membantu mereka yang memiliki kesulitan memahami kalimat, frase, dan kosakata yang kompleks. Lebih spesifik, hal ini membantu orang-orang dengan berbagai tipe disabilitas kognitif.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait keterbacaan (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 3.1 - Dapat Dibaca](https://www.w3.org/WAI/WCAG21/quickref/#readable)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman aksesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.4.2: (Untuk antarmuka sarana penulisan) Dokumentasikan antarmuka pengguna, termasuk semua fitur aksesibilitas](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Bagian B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait keterbacaan
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, siswi daring yang kesulitan mendengar](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

### Konten muncul dan beroperasi dengan cara yang dapat diprediksi {#predictable}

Banyak orang bergantung pada antarmuka yang dapat diprediksi dan akan mengalami disorientasi atau terdistraksi oleh tampilan atau perilaku yang tidak konsisten. Contoh dalam membuat konten yang lebih dapat diprediksi meliputi:

-   Mekanisme navigasi yang berulang pada banyak halaman selalu muncul di tempat yang sama
-   Komponen antarmuka yang berulang pada halaman situs selalu memiliki label yang sama
-   Perubahan signifikan pada halaman situs tidak terjadi tanpa persetujuan pengguna

Memenuhi persyaratan ini membantu orang untuk dengan cepat mempelajari fungsionalitas dan mekanisme navigasi yang tersedia pada situs web, dan untuk mengoperasikannya sesuai dengan kebuutuhan dan preferensi spesifik mereka. Sebagai contoh, beberapa orang menetapkan kunci pintasan ke fungsi yang sering mereka gunakan untuk meningkatkan pengalaman penggunaan navigasi kibor. Yang lain mengingat langkah-langkan untuk mencapai sebuah halaman atau menyelesaikan proses pada situs web. Keduanya bergantung pada fungsionalitas yang konsisten dan dapat diprediksi.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait kemampuan diprediksi (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 3.2 - Dapat Diprediksi](https://www.w3.org/WAI/WCAG21/quickref/#predictable)

**UAAG**

-   [Pedoman 3.3 - Dapat Diprediksi](https://www.w3.org/TR/UAAG20/#gl-predictable-operation)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman aksesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.2.2: (Untuk antarmuka sarana penulisan) Pastikan tampilan halaman edit bisa ditentukan melalui pemrograman](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pedoman A.4.2: (Untuk antarmuka sarana penulisan) Dokumentasikan antarmuka pengguna, termasuk semua fitur aksesibilitas](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait kemampuan diprediksi
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Pengguna dibantu untuk menghindari dan memperbaiki kesalahan {#tolerant}

Isian dan interaksi lainnya dapat membingungkan dan sulit untuk digunakan oleh banyak orang, hasilnya, mereka lebih mungkin melakukan kesalahan. Contoh dari membantu pengguna menghindari dan memperbaiki kesalahan termasuk menyediakan:

-   Instruksi deskriptif, pesan eror, dan saran untuk perbaikan
-   Bantuan yang peka konteks untuk fungsi dan interaksi yang kompleks
-   Kesempatan untuk meninjau, memperbaiki, atau meralat isian yang telah dikirim jika diperlukan

Memenuhi persyaratan ini membantu orang yang tidak melihat mau pun mendengar konten yang mungkin tidak menyadari hubungan, urutan, dan petunjuk lain yang implisit. Hal ini juga membantu orang yang tidak memahami fungsi, mengalami disorientasi atau bingung, lupa, atau melakukan kesalahan ketika berinteraksi dan mengisi isian untuk alasan apa pun.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait bantuan input (tautan ke spesifikasi teknis)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 3.3 - Bantuan input](https://www.w3.org/WAI/WCAG21/quickref/#input-assistance)

**UAAG**

-   [Pedoman 3.1 - Kesalahan](https://www.w3.org/TR/UAAG20/#gl-avoid-mistakes)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman aksesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pedoman A.2.2: (Untuk antarmuka sarana penulisan) Pastikan tampilan halaman edit bisa ditentukan melalui pemrograman](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pedoman A.4.1: (Untuk antarmuka sarana penulisan) Bantu penulis menghindari dan memperbaiki kesalahan](https://www.w3.org/TR/ATAG20/#gl_b41)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait bantuan input
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, pembeli daring penyandang buta warna](/people-use-web/user-stories/#shopper)
-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Yun, pensiunan yang memiliki rabun, tremor di tangan, dan kehilangan memori jangka pendek ringan](/people-use-web/user-stories/#retiree)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

## Konten yang ulet dan interpretasi yang bisa diandalkan {#robust}

### Konten kompatibel dengan sarana yang ada sekarang dan di masa depan {#compatible}

Konten yang ulet adalah konten yang kompatibel dengan berbagai browser, teknologi pembantu, dan agen pengguna lainnya. Contoh bagaimana hal ini dapat diraih meliputi:

-   Memastikan penanda bisa diinterpretasikan dengan andal, contohnya dengan memastikan validitasnya
-   Menyediakan nama, peran, dan nilai untuk komponen antarmuka yang tidak standar

Memenuhi persyaratan ini membantu memaksimalkan kompatibilitas dengan agen pengguna, termasuk teknologi pembantu, yang ada sekarang dan di masa depan. Secara spesifik, hal ini memungkinkan teknologi pembantu untuk memproses konten dengan andal, dan untuk menyediakan atau mengoperasikannya dengan cara yang berbeda. Ini termasuk tombol non-standar (melalui skrip), bidang input, dan kontrol lainnya.

{% include excol.html type="start" %}

#### Persyaratan aksesibilitas terkait kompatibilitas (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pedoman 4.1 - Kompatibel](https://www.w3.org/WAI/WCAG21/quickref/#compatible)

**UAAG**

-   [Guideline 2.6 - Pengaturan preferensi](https://www.w3.org/TR/UAAG20/#gl-store-prefs)
-   [Guideline 4.1 - Teknologi pembantu](https://www.w3.org/TR/UAAG20/#gl-AT-access)
-   [Guideline 5.1 - Ikuti spesifikasi](https://www.w3.org/TR/UAAG20/#gl-obs-env-conventions)

**ATAG**

-   [Prinsip A.1: Antarmuka sarana penulisan mengikuti pedoman aksesibilitas yang berlaku](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Bagian B. Dukung pembuatan konten yang aksesibel](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Cerita terkait kompatibilitas
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, pembeli daring penyandang buta warna](/people-use-web/user-stories/#shopper)
-   [Alex, reporter dengan cedera kambuhan](/people-use-web/user-stories/#reporter)
-   [Ilya, anggota staf senior penyandang tunanetra](/people-use-web/user-stories/#accountant)
-   [Preety, siswi tingkat menengah dengan Gangguan Pemusatan Perhatian dan Hiperaktivitas (ADHD)](/people-use-web/user-stories/#classroomstudent)
-   [Luis, asisten supermarket dengan Sindrom Down](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, remaja penyandang tunarungu dan tunanetra](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

{% include excol.html type="all" %}

