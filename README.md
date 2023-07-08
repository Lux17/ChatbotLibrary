# Chatbot Library Virtual Assistant UMC dengan Watson assistant
Projek Capstone Merdeka Belajar Kampus Merdeka (MBKM) Infinite Learning Indonesia

------------------------------------------------------------------------------
# Informasi 

| Point | Informasi | 
|--------------------|------------------------------|
| Nama   | Lucky Saputra|
| Kampus | Universitas Muhammadiyah Cirebon | 
| Mentor | Agistira Lamunde | 
| Project Name         |Chatbot Library Assistant Universitas Muhammadiyah Cirebon |
| Pattern              | Enhance customer helpdesks with Smart Document Understanding using the Watson Assistant search skill (https://developer.ibm.com/patterns/enhance-customer-helpdesk-with-smart-document-understanding-using-search-skill/) |
| Ibm Service          | Watson Assistant, Watson Discovery |
| Early Build          | Visual Studio Code |

------------------------------------------------------------------------------
# Rangkuman 
Dalam project ini, kita akan menggunakan pustaka Keras untuk mengklasifikasikan gambar-gambar yang dipilih secara acak dari internet. Keras menyederhanakan proses perancangan dan pelatihan model deep learning dengan menyediakan antarmuka tingkat tinggi. Gambar-gambar dari internet akan diambil menggunakan link URL dan diunduh oleh program ini. kita akan menerapkan metode transfer learning. Transfer learning adalah teknik yang memanfaatkan pengetahuan yang diperoleh dari model yang sudah dilatih sebelumnya pada tugas sebelumnya untuk mengklasifikasikan gambar-gambar baru. Pendekatan ini membantu mengurangi waktu dan sumber daya yang dibutuhkan untuk melatih model dari awal. Kita akan menggunakan model EfficientNetV2M yang sudah dilatih sebelumnya untuk tujuan ini.

Dalam notebook ini kita akan : 
- Menggunakan model EfficientNetV2M untuk klasifikasi
- mengimport Liberary yang dibutuhkan
- Menggunakan link urls gambar yang berkaitan dengan restoran agar di klasifikasi
- Mengunduh gambar dari link urls dan merubahnya ke num array
- preproses data menggunakan model EfficientNetV2M
- Menampilkan hasil prediksi

# Alur 
![Diagram ]([https://github.com/arqualian/image-classification-Capstone-Project/assets/60522938/6ac9d586-95fd-4900-b3c4-ab0fce5672d8])


1. Buat Service Watson Assistant & Discovery.
2. Konfigurasi Watson Discovery.
3. Konfigurasikan Watson Assistant.
5. Tambahkan kredensial layanan Watson ke file website.
6. Menjalankan pemrograman yang terdapat di [link](https://github.com/Lux17/ChatbotLibrary)

# Batasan 
Dalam projek ini memiliki batasan yaitu : 
1. Tingkat akurasi mencapai 73%
2. Gambar harus sesuai format (copy image address)
3. Link harus di letakan secara manual kedalam kodingan
4. Tidak ada batasan dalam jenis gambar (bisa diluar konteks restauran). Namun dianjurkan yang sesuai dengan projek

--------------------------------------------------------------------------------------------------------------
# Saran Objek 
#Preview
![Screenshot 2023-07-06 011701](https://github.com/Lux17/ChatbotLibrary/assets/59023470/aadbf014-0340-4882-a7f1-f5f8dc2810c0)
#Website
![Screenshot 2023-07-06 010834](https://github.com/Lux17/ChatbotLibrary/assets/59023470/373f4a0d-c832-42b3-b585-0d7de724ba0c)

