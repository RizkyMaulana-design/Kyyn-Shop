# Kyyn Shop - Aplikasi Pencatatan Utang Warung Digital Berbasis AI

<img width="1500" height="1125" alt="Mockupp kyyn shopa" src="https://github.com/user-attachments/assets/ade059a5-bdab-4b3f-9324-d80a1f3d01ee" />

> *Kyyn Shop: Solusi modern untuk UMKM warung sembako dalam mengelola catatan piutang secara digital, cepat, dan aman.*

## 📖 Latar Belakang Proyek

Pengembangan aplikasi Kyyn Shop berangkat dari permasalahan nyata (*real-world problem*) yang dihadapi oleh UMKM, khususnya warung sembako milik orang tua saya. Di ekosistem warung, transaksi kredit atau "ngebon" adalah strategi retensi pelanggan yang krusial. Namun, manajemen piutang yang masih mengandalkan pencatatan manual (buku/kertas) menimbulkan inefisiensi operasional:

1.  **Risiko Integritas Data:** Catatan fisik rentan hilang, rusak, atau terselip, mengakibatkan *data loss* yang berdampak pada kerugian finansial.
2.  **Inefisiensi Pencarian Data:** Proses *retrieval* data pelanggan secara manual sangat memakan waktu, mengganggu *service time* saat warung ramai.
3.  **Kendala Penagihan (Collection Issue):** Kurangnya visibilitas terhadap umur piutang membuat proses penagihan tidak terjadwal dan menimbulkan rasa canggung.

Kyyn Shop hadir sebagai solusi digital untuk mentransformasi manajemen utang dari sistem konvensional menuju sistem terkomputerisasi yang terintegrasi dalam *smartphone*, mengoptimalkan *cash flow* dan transparansi transaksi warung.

---

## 🎬 Storyboard Naratif (Perjalanan Pengguna)

<img width="1600" height="594" alt="Story boarding Kyyn shop" src="https://github.com/user-attachments/assets/7659e491-c288-4caf-abd5-5f7174d18f13" />


**Penjelasan Alur Cerita:**
Storyboard di atas memvisualisasikan *User Journey* (Perjalanan Pengguna). Dimulai dari *pain point* pengguna (kesulitan pencatatan manual), transisi penggunaan aplikasi, hingga tahap *resolution* di mana Kyyn Shop memfasilitasi pencatatan yang cepat, *monitoring* piutang yang terpusat, dan otomatisasi penagihan via asisten AI. Pendekatan ini memastikan penyelesaian masalah pengguna secara *end-to-end*.

---

## 📐 Proses Desain: Dari Wireframe ke UI Final

<img width="1600" height="472" alt="Wireframe Kyyn Shop" src="https://github.com/user-attachments/assets/ff9e5d00-fbdb-476b-a60d-425a1327cdc9" />


**1. Wireframe (Kerangka Desain)**
Tahap awal pengembangan UX dilakukan melalui perancangan *wireframe*. Fokus utamanya adalah struktur hierarki informasi (Information Architecture) dan tata letak (*layout*). Desain dirancang dengan prinsip *accessibility*, memastikan tombol-tombol krusial mudah dijangkau, mengingat target demografis pengguna utama (pemilik warung) mungkin memiliki literasi digital yang terbatas.

<br>

<img width="1600" height="490" alt="UI kyyn shop" src="https://github.com/user-attachments/assets/434f2eba-9bfa-4083-8283-71b7c74080eb" />


**2. User Interface (UI) Final**
UI final dieksekusi dengan pendekatan desain minimalis dan fungsional. Penggunaan palet warna putih dengan aksen warna primer bertujuan untuk mengurangi *cognitive load* pengguna. Area *Dashboard* difokuskan untuk menampilkan parameter finansial terpenting (*Total Piutang*) agar langsung terbaca (*glanceable*) saat aplikasi dibuka.

---

## ✨ Interaksi & Pengalaman Pengguna (UX)

<img width="1920" height="1200" alt="sflash-screen-video_kyyn-shop" src="https://github.com/user-attachments/assets/818ce807-a147-4adf-8955-674b8a764da6" />


**1. Onboarding & Keamanan**
Aplikasi dimulai dengan *splash screen* yang ringan untuk *branding*. Proses *onboarding* mencakup sistem otentikasi (Login/PIN) untuk menjamin *data privacy*, serta fitur deteksi lokasi untuk memvalidasi area transaksi.

<br>

<img width="1920" height="1200" alt="ux-video-rizky-maulana" src="https://github.com/user-attachments/assets/4cd22016-8c19-465c-a51d-037ab9d5e7de" />


**2. Dashboard Pintar & Integrasi AI**
Prototipe interaktif di atas mendemonstrasikan kelancaran alur navigasi aplikasi. Fitur-fitur unggulannya meliputi:
*   **Real-Time Dashboard:** *Summary card* yang selalu memperbarui total piutang berjalan.
*   **Seamless Navigation:** Transisi *flow* antar menu (Tambah Pelanggan, Catat Transaksi) yang intuitif.
*   **AI OCR Integration:** Kemampuan memindai kartu nama pelanggan menggunakan kamera (*Optical Character Recognition*) untuk otomatisasi *data entry*, mereduksi waktu pengetikan.
*   **AI Smart Reminder:** Asisten virtual yang menganalisis jatuh tempo piutang dan secara proaktif membuat draf pesan penagihan untuk dieksekusi melalui WhatsApp.

---

## 🛠️ Rencana Teknologi Pengembangan
*   **UI/UX Prototyping:** Figma
*   **Front-end Development:** (Isi dengan framework kamu, misal: Flutter)
*   **Back-end & Database:** (Isi dengan layanan kamu, misal: Firebase)
*   **AI Services:** (Isi dengan API yang dipakai, misal: Google Cloud Vision)

---
*Dikembangkan oleh Rizky Maulana untuk Proyek [Sebutkan Nama Mata Kuliah]*
