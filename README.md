# Dashboard: Dampak Harga Minyak Terhadap Ekonomi Rusia

Dashboard Power BI ini dirancang untuk **menganalisis pengaruh harga minyak terhadap perekonomian Rusia, dengan fokus pada indikator makroekonomi utama seperti PDB (GDP), inflasi, dan nilai tukar (EUR-RUB dan USD-RUB)**. Dashboard ini memanfaatkan berbagai visualisasi, seperti diagram batang berkelompok, diagram garis, dan matriks korelasi, guna memberikan pemahaman yang komprehensif tentang bagaimana harga minyak memengaruhi variabel-variabel tersebut dari waktu ke waktu. Desainnya mengadopsi skema warna yang terinspirasi dari bendera Rusia (biru, merah, dan putih), sehingga menciptakan tampilan yang koheren secara visual dan relevan secara budaya.

## **Tanggung Jawab**:
- Mengubah regional setting aplikasi menjadi Rusia untuk memastikan format data dan angka sesuai dengan standar Rusia.
- Menyesuaikan tipe data dari kolom-kolom pada tabel untuk memastikan keakuratan dan konsistensi data.
- Membuat clustered bar chart untuk melihat pertumbuhan harga minyak per kuartal dalam setiap tahun, dengan menambahkan conditional formatting, di mana bar berwarna merah untuk nilai negatif dan biru untuk nilai positif.
- Membuat line chart untuk menganalisis hubungan antara harga minyak dan variabel-variabel makroekonomi, seperti GDP, Inflasi, nilai tukar EUR-RUB, dan USD-RUB. Menambahkan conditional formatting agar bar berwarna merah untuk nilai negatif dan biru untuk nilai positif.
- Membuat matriks korelasi menggunakan Python script untuk melihat hubungan antara harga minyak dengan GDP, Inflasi, nilai tukar EUR-RUB, dan USD-RUB.
- Menambahkan kolom baru, yaitu Tahun dan Kuartal, menggunakan DAX untuk memudahkan analisis berdasarkan waktu.
- Membuat slicer untuk tahun dan kuartal yang memungkinkan pengguna untuk memfilter dashboard berdasarkan periode yang dipilih.
- Membuat card untuk menampilkan informasi kunci pada kuartal terakhir dari tahun yang dipilih, seperti harga minyak, pertumbuhan minyak, GDP, Inflasi, dan nilai tukar EUR-RUB serta USD-RUB.
- Menerapkan visualisasi dengan tema warna dominan biru, merah, dan putih, yang merepresentasikan warna bendera Rusia untuk meningkatkan tampilan estetika dan kesesuaian budaya dalam dashboard.

## **Hasil**:
Berhasil membangun dashboard interaktif yang menunjukkan dampak harga minyak terhadap perekonomian Rusia. Pada dashboard di bawah ini, diterapkan filter untuk khusus menampilkan data pada tahun 2018 saja. 

![23](https://github.com/user-attachments/assets/c32fb6f0-f31b-4054-a367-e5b8265576fb)

#### Interpretasi
1. Penurunan Harga Minyak dan Dampak pada Ekonomi Rusia
  - **Harga minyak di kuartal terakhir $50.57 dan pertumbuhan harga minyak turun drastis -38.87%:** Harga minyak mengalami penurunan signifikan di kuartal terakhir, setelah sebelumnya mengalami pertumbuhan positif di Q1 (+3.44%), Q2 (+12.02%), dan Q3 (+6.52%). Kejatuhan ini kemungkinan memberikan dampak besar pada ekonomi Rusia yang sangat bergantung pada ekspor minyak.
- **GDP 23T ₽:** Masih cukup tinggi, tetapi bisa saja mengalami tekanan akibat turunnya harga minyak.
- **Inflasi 1.70%:** Inflasi relatif rendah pada kuartall terakhir maupun kuartal-kuartal sebelumnya, yang bisa menunjukkan stabilitas harga barang dan jasa atau dampak dari kebijakan moneter Rusia.
- **Nilai tukar EUR-RUB 76 ₽ dan USD-RUB 66 ₽:** Nilai Rubel terhadap Euro dan USD mengalami depresiasi dibandingkan kuartal sebelumnya. Artinya, Rubel semakin melemah, kemungkinan besar akibat turunnya harga minyak, yang menyebabkan ketidakstabilan ekonomi dan kepercayaan investor menurun.

2. Analisis Hubungan Minyak dengan Faktor Ekonomi
- **Minyak vs GDP:**
Grafik menunjukkan bahwa GDP masih naik di sebagian besar kuartal, tetapi kemungkinan akan terkena dampak negatif dari turunnya harga minyak di akhir kuartal.
- **Minyak vs Inflasi:**
Inflasi tetap rendah meskipun harga minyak turun, yang bisa berarti kebijakan ekonomi Rusia berhasil menjaga stabilitas harga.
- **Minyak vs EUR-RUB dan USD-RUB:**
Nilai tukar Rubel melemah terhadap Euro dan USD, mengikuti pola pergerakan harga minyak.

#### **Kesimpulan**
- **Penurunan harga minyak di Q4 2018 cukup tajam (-38.87%)**, yang kemungkinan mempengaruhi perekonomian Rusia.
- **GDP tetap stabil di 23T ₽**, tetapi kemungkinan mengalami tekanan dari pelemahan harga minyak.
- **Inflasi tetap rendah (1.70%)**, menandakan stabilitas harga barang.
- **Rubel mengalami depresiasi terhadap Euro (76 ₽) dan USD (66 ₽)**, menunjukkan pelemahan nilai tukar yang mungkin disebabkan oleh turunnya harga minyak.

Secara keseluruhan, meskipun ada depresiasi mata uang dan penurunan harga minyak, Rusia tampaknya berhasil menjaga stabilitas ekonomi dengan inflasi yang relatif rendah.
