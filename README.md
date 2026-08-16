🌱 Lestari - AI Sustainable Finance Assistant
Lestari adalah asisten chatbot berbasis kecerdasan buatan (AI) yang dirancang khusus untuk memberikan edukasi dan panduan mengenai Keuangan Berkelanjutan (Sustainable Finance), Investasi Hijau (Green Investment), dan prinsip-prinsip ESG (Environmental, Social, and Governance).
Aplikasi ini dibangun dalam satu file HTML (Single-Page Application) menggunakan Tailwind CSS untuk tampilan visual dan mengintegrasikan Google Gemini API sebagai otak kecerdasan buatannya.
✨ Fitur Utama
•	Domain Eksklusif: Prompt sistem dikonfigurasi secara khusus agar AI fokus menjawab topik keuangan, investasi ramah lingkungan, dan keberlanjutan.
•	Desain UI/UX Hijau: Menggunakan palet warna Emerald dan Green yang merepresentasikan alam, dilengkapi animasi mengetik yang halus.
•	Dukungan Markdown: Chatbot mampu merender teks tebal, miring, dan bullet points untuk membuat penjelasan finansial lebih mudah dibaca.
•	Memori Percakapan: AI mengingat riwayat obrolan sebelumnya dalam satu sesi, memungkinkan diskusi yang mengalir dan berkesinambungan.
•	Rekomendasi Cepat (Quick Actions): Tombol saran pertanyaan untuk pengguna pemula yang ingin langsung berinteraksi tanpa mengetik.
•	Analisis Gambar (Vision): Pengguna dapat mengunggah gambar (seperti produk, laporan ESG, atau kemasan) untuk dianalisis dampak lingkungannya oleh AI.
•	Text-to-Speech (TTS): Dilengkapi tombol "Dengarkan" yang akan membacakan teks balasan menggunakan suara AI yang natural (Gemini TTS).
🚀 Cara Menjalankan (Local)
Karena aplikasi ini sepenuhnya berbasis client-side (HTML/JS), Anda dapat menjalankannya langsung di browser tanpa perlu menginstal server atau framework tambahan.
1.	Clone repository ini atau unduh file index.html.
2.	PENTING: Anda harus memasukkan API Key Gemini Anda sendiri agar chatbot dapat berfungsi.
o	Buka file index.html dengan text editor (VS Code, Notepad, dll).
o	Cari baris kode berikut di bagian JavaScript:
o	const apiKey = ""; // Masukkan API Key Anda di sini

o	Dapatkan API Key secara gratis di Google AI Studio.
o	Tempelkan API Key Anda di dalam tanda kutip.
3.	Buka file index.html menggunakan browser (Chrome, Firefox, Safari, dll).
🌐 Cara Hosting Gratis (GitHub Pages)
Anda dapat membuat chatbot ini bisa diakses siapa saja di internet secara gratis menggunakan GitHub Pages:
1.	Upload file index.html dan README.md ke repository GitHub Anda.
2.	Buka tab Settings di repository Anda.
3.	Di menu sebelah kiri, klik Pages.
4.	Pada bagian Build and deployment -> Branch, ubah dari None menjadi main (atau master).
5.	Klik Save.
6.	Tunggu beberapa menit, GitHub akan memberikan link publik website Anda (biasanya https://[username].github.io/[nama-repo]).
🛠️ Teknologi yang Digunakan
•	HTML5 & Vanilla JavaScript: Struktur dasar dan logika program.
•	Tailwind CSS (via CDN): Styling utilitas untuk membuat antarmuka yang responsif dan modern.
•	Gemini API (gemini-3-flash-preview): Model Large Language Model (LLM) utama untuk memproses obrolan dan analisis gambar (Multi-modal).
•	Gemini TTS API (gemini-2.5-flash-preview-tts): Model AI untuk menghasilkan suara Text-to-Speech.
Dibuat untuk tujuan edukasi investasi hijau.