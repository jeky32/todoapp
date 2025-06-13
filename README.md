# ToDo List App (Flutter + Laravel API)

Aplikasi ToDo List sederhana berbasis **Flutter** sebagai frontend dan **Laravel REST API** sebagai backend. Aplikasi ini memungkinkan pengguna untuk membuat, membaca, mengedit, dan menghapus daftar tugas secara real-time.

## 📱 Fitur Aplikasi

- ✅ **Autentikasi (Login & Register)**
- 📋 **CRUD ToDo List**
  - Tambah Tugas
  - Edit Tugas
  - Hapus Tugas
  - Tandai sebagai Selesai
- 🔔 **Prioritas Tugas** (Low, Medium, High)
- 📅 **Tenggat Waktu (Deadline)**
- 🎨 **Dark Mode**
- 🌐 **Terintegrasi dengan REST API Laravel**

## 🗂️ Teknologi yang Digunakan

### Frontend (Flutter)
- Flutter SDK
- Provider / Riverpod (state management)
- Dio / HTTP (API request)
- SharedPreferences (token storage)

### Backend (Laravel)
- Laravel 10.x
- Sanctum (Authentication)
- MySQL / MariaDB

## ⚙️ Instalasi & Setup

### Backend (Laravel API)

1. Clone repository Laravel:
   ```bash
   git clone https://github.com/username/todolist-api.git
   cd todolist-api
Install dependencies:

bash
Salin
Edit
composer install
Setup environment:

bash
Salin
Edit
cp .env.example .env
php artisan key:generate
Konfigurasi database di file .env.

Jalankan migrasi database:

bash
Salin
Edit
php artisan migrate
Jalankan server API:

bash
Salin
Edit
php artisan serve
Default URL API: http://127.0.0.1:8000/api

Frontend (Flutter App)
Clone repository Flutter:

bash
Salin
Edit
git clone https://github.com/username/todolist-flutter.git
cd todolist-flutter
Install dependencies:

bash
Salin
Edit
flutter pub get
Konfigurasi URL API (jika perlu):

Ubah baseUrl di file lib/utils/constants.dart atau sesuai struktur proyek Anda.

Jalankan aplikasi:

bash
Salin
Edit
flutter run
🔑 Endpoints API Laravel
Method	Endpoint	Description
POST	/api/register	Register User
POST	/api/login	Login User (get Token)
GET	/api/todos	Get All Todos
POST	/api/todos	Create New Todo
PUT	/api/todos/{id}	Update Todo
DELETE	/api/todos/{id}	Delete Todo

Semua endpoint yang berhubungan dengan ToDo memerlukan token Bearer (Sanctum).

📸 Dokumentasi video

https://github.com/user-attachments/assets/bff5ddb2-004b-48b4-a776-51f076538f56



🧑‍💻 Kontributor
Nama : Zacky Noor Faizi
Kelas : XI RPL 2
Absen : 34









