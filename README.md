# UASOOP
JAWABAN NO 1
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1bml2ZXJzaXRhcyI6IkRqdWFuZGEiLCJwcm9kaSI6IklsbXUgS29tcHV0ZXIiLCJpYXQiOjE2NzQyNzAwMDB9.Yr3mvqeWO9wVYkKaBAv6dzQHDCvnfN3wqazpe_j97-g

JAWABAN NO 2

<table border="1">
  <tr>
    <th>Fitur</th>
    <th>Arsitektur Monolitik</th>
    <th>Arsitektur Mikroservis</th>
  </tr>
  <tr>
    <td>Struktur Aplikasi</td>
    <td>Satu aplikasi tunggal (monolit)</td>
    <td>Berbagai layanan independen (mikroservis)</td>
  </tr>
  <tr>
    <td>Skalanilitas</td>
    <td>Keseluruhan aplikasi</td>
    <td>Skala secara terpisah untuk setiap mikroservis</td>
  </tr>
  <tr>
    <td>Pengembangan</td>
    <td>Pembaruan keseluruhan aplikasi</td>
    <td>Pembaruan per layanan secara terpisah</td>
  </tr>
  <tr>
    <td>Pemeliharaan</td>
    <td>Memerlukan waktu dan upaya besar</td>
    <td>Pemeliharaan lebih modular dan dapat diisolasi</td>
  </tr>
  <tr>
    <td>Ketergantungan</td>
    <td>Ketat, perubahan mempengaruhi semua</td>
    <td>Lemah, perubahan dapat diisolasi ke mikroservis</td>
  </tr>
  <tr>
    <td>Teknologi dan Bahasa Pemrograman</td>
    <td>Satu set teknologi dan bahasa pemrograman</td>
    <td>Fleksibel, setiap mikroservis dapat menggunakan teknologi dan bahasa yang berbeda</td>
  </tr>
  <tr>
    <td>Pengelolaan Data</td>
    <td>Sering kali satu basis data tunggal</td>
    <td>Setiap mikroservis dapat memiliki basis data sendiri</td>
  </tr>
</table>






JAWABAN NO 3

Middleware adalah perangkat lunak yang berada di antara sistem operasi dan aplikasi, bertindak sebagai perantara atau penghubung untuk memfasilitasi komunikasi antara berbagai komponen perangkat lunak atau perangkat keras dalam suatu sistem distribusi.

Beberapa keuntungan dari penerapan middleware meliputi:
Interoperabilitas: Middleware memungkinkan sistem atau aplikasi yang dikembangkan menggunakan teknologi atau platform yang berbeda untuk berkomunikasi satu sama lain. Ini meningkatkan interoperabilitas dan memungkinkan integrasi yang lebih mudah antar sistem yang heterogen.

Skalabilitas: Middleware mendukung skala secara efisien dengan menyediakan mekanisme untuk menangani peningkatan beban. Ini memungkinkan sistem untuk berkembang atau menyusut sesuai dengan kebutuhan tanpa mengganggu fungsionalitas keseluruhan.

Abstraksi Kompleksitas: Middleware menyediakan abstraksi yang memungkinkan pengembang untuk fokus pada fungsionalitas aplikasi daripada menghadapi kompleksitas infrastruktur jaringan atau protokol komunikasi yang mendasarinya.

Pengelolaan Distribusi dan Komunikasi: Middleware menyederhanakan pengelolaan distribusi dan komunikasi antar komponen aplikasi atau sistem. Ini dapat mencakup manajemen pesan, pemantauan kinerja, dan penanganan kesalahan komunikasi.

Keamanan: Middleware dapat memberikan lapisan keamanan tambahan dengan menyediakan mekanisme autentikasi, otorisasi, dan enkripsi data selama pertukaran informasi antar komponen atau sistem.

Fleksibilitas Pengembangan: Middleware memungkinkan pengembang untuk membangun aplikasi atau sistem yang modular dan dapat diintegrasikan lebih mudah. Komponen-komponen yang terpisah dapat dikembangkan secara independen dan kemudian diintegrasikan melalui middleware.

Manajemen Transaksi: Middleware dapat menyediakan dukungan untuk manajemen transaksi, memastikan konsistensi data dan integritas transaksi di seluruh sistem yang terdistribusi.

JAWABAN NO 4

Unit Testing adalah jenis pengujian perangkat lunak di mana unit atau komponen kecil dari suatu program diuji secara terisolasi untuk memastikan bahwa setiap unit berfungsi sebagaimana mestinya. Tujuan utama unit testing adalah untuk memastikan bahwa setiap bagian kecil dari perangkat lunak beroperasi dengan benar, dan juga untuk mendeteksi dan memperbaiki kesalahan sejak dini dalam siklus pengembangan.

Beberapa metode yang umum digunakan dalam unit testing meliputi:
Test Case: Ini adalah kasus uji individual yang dirancang untuk menguji satu aspek atau fitur tertentu dari unit. Setiap test case berfokus pada satu kondisi atau skenario tertentu.

Fixture: Fixture adalah kondisi awal atau konteks yang ditetapkan sebelum menjalankan serangkaian test case. Ini memastikan bahwa unit diuji dalam situasi yang dikontrol.

Assertion: Pernyataan atau kode yang mengevaluasi apakah hasil yang diharapkan dari suatu test case sesuai dengan hasil aktual yang diperoleh selama pengujian. Jika hasil yang diharapkan tidak sesuai, assertion akan menghasilkan kesalahan.

Mocking: Dalam unit testing, mocking melibatkan pembuatan objek palsu atau simulasi untuk menggantikan objek nyata. Ini membantu dalam mengisolasi unit yang diuji dari dependensi eksternal.

Test Suite: Sebuah kumpulan test case yang dijalankan bersama-sama sebagai satu kesatuan. Test suite memungkinkan pengujian yang komprehensif terhadap suatu unit atau fitur.

Test Runner: Alat atau mekanisme yang menjalankan serangkaian test case atau test suite. Test runner juga melaporkan hasil pengujian, termasuk test case yang gagal.

Code Coverage: Metrik yang mengukur sejauh mana kode sumber diuji selama pengujian. Ini membantu untuk memastikan bahwa sebagian besar kode telah diuji dan mengidentifikasi bagian-bagian yang mungkin memerlukan perhatian lebih lanjut.

White Box Testing: Pendekatan di mana pengujian dilakukan dengan memahami dan memeriksa struktur internal kode sumber. Unit testing sering kali menggunakan white box testing.

Black Box Testing: Pendekatan di mana pengujian dilakukan tanpa memperhatikan struktur internal kode sumber. Test case dirancang berdasarkan spesifikasi eksternal dan perilaku yang diharapkan.

Continuous Integration (CI): Praktek yang melibatkan pengujian otomatis secara terus-menerus setiap kali ada perubahan kode dalam repositori. CI membantu mendeteksi kesalahan lebih awal dalam siklus pengembangan.

JAWABAN NO 5

1. Kontainerisasi:
Kontainerisasi adalah metode untuk mengemas, mendistribusikan, dan menjalankan aplikasi bersama dengan semua dependensinya dan konfigurasi di dalam sebuah unit yang disebut "kontainer." Kontainer memungkinkan aplikasi untuk berjalan secara konsisten di berbagai lingkungan, baik itu lingkungan pengembangan, uji, atau produksi. Kontainer memberikan isolasi, portabilitas, dan efisiensi dalam penggunaan sumber daya.
2. Docker:
Docker adalah platform kontainerisasi yang populer. Docker menyediakan alat dan layanan untuk membuat, mengelola, dan menjalankan kontainer. Dengan menggunakan Docker, pengembang dapat membangun, menguji, dan mendistribusikan aplikasi secara konsisten di berbagai lingkungan. Docker menggunakan teknologi kontainerisasi Linux seperti cgroups dan namespaces untuk memberikan isolasi antar kontainer.
3. Kubernetes:
Kubernetes (biasa disebut K8s) adalah sistem orkestrasi kontainer yang dirancang untuk otomatisasi pengelolaan, penjadwalan, dan penyebaran aplikasi kontainer. Kubernetes memungkinkan pengelolaan yang efisien dan skala besar dari kontainer di lingkungan produksi. Ini menangani penyebaran, penskalaan, dan penanganan kegagalan dengan cara yang dapat diotomatisasi.

JAWABAN NO 6

Continuous Integration (CI):

Integrasi Terus-Menerus berarti pengembang secara teratur menggabungkan perubahan kode ke dalam repositori bersama.
Setiap kali ada perubahan di repositori, CI server akan secara otomatis menjalankan rangkaian tes untuk memastikan bahwa perubahan tersebut tidak merusak fungsionalitas yang sudah ada.
Jika semua tes berhasil, perubahan tersebut dianggap aman dan siap untuk diintegrasikan ke dalam lingkungan produksi.

Continuous Deployment (CD):

Penyebaran Terus-Menerus melibatkan otomatisasi proses penyebaran aplikasi ke lingkungan produksi setelah berhasil melewati tahap CI.
Hal ini memastikan bahwa setiap kali ada perubahan yang diuji dan diintegrasikan, aplikasi tersebut dapat secara otomatis diperbarui ke lingkungan produksi tanpa intervensi manusia.

Beberapa tools yang umum digunakan untuk implementasi CI/CD termasuk:

Jenkins: Jenkins adalah alat CI/CD open-source yang sangat populer. Ini memungkinkan otomatisasi proses pengujian, integrasi, dan penyebaran.

GitLab CI/CD: GitLab menyediakan fitur CI/CD terintegrasi langsung ke dalam platform repositori Git mereka. Ini menyederhanakan konfigurasi dan manajemen CI/CD.

Travis CI: Travis CI adalah layanan CI/CD yang terintegrasi dengan GitHub. Ini mendukung otomatisasi pengujian dan penyebaran aplikasi.

CircleCI: CircleCI adalah platform CI/CD yang mendukung otomatisasi proses pengujian dan penyebaran aplikasi dalam lingkungan cloud.

GitHub Actions: GitHub menyediakan fitur Actions yang memungkinkan pengguna membuat dan mengelola workflow CI/CD langsung dari repositori GitHub mereka.

TeamCity: TeamCity adalah alat CI/CD dari JetBrains yang mendukung otomatisasi pengujian dan penyebaran aplikasi.

AWS CodePipeline: AWS CodePipeline adalah layanan manajemen CI/CD yang terintegrasi dengan layanan AWS lainnya untuk otomatisasi pengembangan dan penyebaran aplikasi di cloud.


JAWABAN NO 7
