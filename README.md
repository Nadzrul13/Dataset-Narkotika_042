#  Dataset Putusan Pengadilan Negeri Pelaihari - Kasus Narkotika & Psikotropika

Repositori ini berisi **dataset putusan pengadilan** dari **Pengadilan Negeri Pelaihari** yang berkaitan dengan perkara **Narkotika dan Psikotropika**. Dataset ini dikumpulkan dan disusun untuk mendukung penelitian dan pengembangan sistem **Information Retrieval for Legal Cases**, khususnya dalam konteks hukum pidana narkotika di Indonesia.


Setiap file PDF merupakan dokumen resmi **putusan pengadilan** yang diperoleh dari sumber terbuka (website Pengadilan Negeri Pelaihari).  
File putusan mencakup elemen-elemen hukum seperti:
- Identitas terdakwa  
- Jenis tindak pidana  
- Barang bukti  
- Dasar hukum dan pertimbangan hakim  
- Amar putusan  


##  File Pendukung

### `Overview.xlsx`
File ini berfungsi sebagai **rekapan metadata** dari setiap putusan yang ada dalam folder `Dataset/`.  
Berisi kolom-kolom berikut:

| Kolom | Deskripsi |
|-------|------------|
| **No** | Nomor urut data |
| **No Putusan** | Nomor resmi putusan pengadilan |
| **Lembaga Peradilan** | Nama lembaga pengadilan yang mengeluarkan putusan |
| **Barang Bukti** | Jenis barang bukti yang disita dalam kasus |
| **Amar Putusan** | Hasil akhir putusan (misalnya: penjara, denda, rehabilitasi) |

---

##  Tujuan Dataset

Dataset ini disiapkan untuk:
- Penelitian bidang **Legal Information Retrieval**  
- Analisis teks hukum dan ekstraksi informasi dari dokumen putusan  
- Penerapan **Natural Language Processing (NLP)** untuk hukum  
- Pengembangan sistem pencarian cerdas (semantic/legal search engine)
