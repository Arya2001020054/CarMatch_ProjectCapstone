# CarMatch ProjectCapstone
<img width="338" alt="Logo CarMatch" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/b72ea149-6cd3-467d-ba88-f1b15527028e">
<br>
CarMatch adalah sebuah chatbot rekomendasi mobil terbaik untuk pengguna. Dengan adanya CarMatch, pengguna dapat memilih kendaraan yang direkomendasikan sesuai dengan kebutuhan. Misalnya mobil keluarga, mobil sports, mobil tua dan mobil terbaru. Adapun hal yang mendasari pembuatan dari chatbot CarMartch ini yaitu bahwa banyak orang yang binggung dalam memilih kendaraan pertama meraka mulai dari jenis apa, tipe mobil tersebut, dan sebagainya. Terkadang mereka juga perlu menyesuaikan bujet mereka dalam membeli mobil maka dari itu CarMatch memberikan informasi harga pada setiap jenis mobil beserta tipenya.
<br>
CarMatch ini berhubungan dengan Actificial Intelligent, karena dirancang untuk dapat melakukan interaksi dan komunikasi dengan manusia menggunakan algoritma pemrosesan bahasa alami(natural language processing/NLP) dan teknik pembelajaran mesin(machine learning). Chatbot dapat memproses masukan berupa teks atau suara, menganalisis kata-kata, konteks, dan niat pengguna, serta memberikan tanggapan yang disesuaikan. Mereka dapat memahami pertanyaan yang kompleks, mencari informasi yang relevan, memberikan saran, atau menyelesaikan tugas tertentu berdasarkan instruksi yang diberikan.

<h2>Proses Pembuatan CartMatch</h2>
Dalam pembuatan chatbot CarMatch ini menggunakan layanan yang ada pada <a href="https://www.ibm.com/cloud">IBM Cloud Service</a> dengan service yang digunakan yaitu Watson Assistent. Watson Assistant adalah platform pengembangan chatbot dan asisten virtual yang dikembangkan oleh IBM. Ini adalah salah satu solusi populer yang menggunakan kecerdasan buatan (AI) untuk membangun dan melatih asisten virtual yang interaktif. Watson Assistant memungkinkan pengembang dan pemilik bisnis untuk membuat chatbot yang dapat memahami dan merespons pertanyaan atau permintaan pengguna secara otomatis. Platform ini menawarkan antarmuka yang intuitif dan alat yang kuat untuk mengembangkan skenario percakapan yang kompleks, mengintegrasikan data dan layanan eksternal, serta menyediakan analisis untuk pemantauan dan pembaruan yang lebih baik.
<br>
Berikut hal yang dipersiapkan sebelum memulai project:<br>
1. Akses dan login <a href="https://www.ibm.com/cloud">IBM Cloud Service</a>. Registrasi jika belum punya akun.<br>
2. Pilih service Watson Assistent dari catalog.<br>
3. Menyiapkan Website untuk tempat deploy chatbot.<br>
<br>
Berikut langkah-langkah dalam pembuatan chatbot CarMatch ini:<br>
1. Jalankan Watson Assistent<br>
<img width="960" alt="Launch Watson Assistent" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/0fe56db9-41d2-4edc-851a-639d32ec922b">
<br>
2. Aktifkan Dialog pada Assistent Setings<br>
<img width="595" alt="Actived Dialog" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/82f0e498-4acb-42c4-9477-44d171e765e4">
<br>
3. Buatlah beberapa intent pada menu Dialog<br>
<img width="960" alt="Intent" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/468649af-5c86-4870-b218-c18913e37599">
<br>
4. Buatlah struktur dialog dengan memilih dialog pada menu Dialog<br>
<img width="607" alt="DialogTree" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/45430ca1-6bf3-4ff5-a2d9-5c0b3d20625b">
<br>
5. Tambahkan intent yang sudah dibuat dan masukkan balasan yang akan dijawab chatbot saat mendapat sebuah inputan dari user<br>
<img width="960" alt="Dialog Respon" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/8dd8427e-9280-4179-a477-1e8d61ec8e88">
<br>
6. Lalu lakukan percobaan sebelum ingin mendeploynya, dengan menekan "Try it" yang ada pada Sisi kanan atas layar<br>
<img width="366" alt="Try It Fitur" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/2c5c5b60-8eef-445f-90ef-4d42a49c337d">
<img width="366" alt="Try It Fitur" src="https://github.com/Arya2001020054/CarMatch_ProjectCapstone/assets/104332660/4c32f7a0-7ad9-4b3c-b8fd-f7a7ad0986a7">
<br>
7. Setelah semuanya siap, sekarang waktunya untuk mendeploy kedalam website dengan memilih menu Deploy>Environment>Web Chat<br>
8. Kita dapat mengedit warna tampilan chatbot dan juga profile foto chatbot<br>

<br>
9. Setelah tampilan sesuai seperti yang diinginkan, klik "Embed" untuk mendapatkan kode yang dapat terhubung dengan website yang kita buat<br>

<br>
10. Masukkan kode embed kedalam kode html<br>

<br>
11. Chatbot pun siap untuk digunakan<br>
