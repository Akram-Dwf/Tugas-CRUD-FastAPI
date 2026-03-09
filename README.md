# Tugas Praktikum CRUD Dasar - RESTful API & ORM

Repositori ini berisi implementasi tugas CRUD Dasar untuk mata kuliah Pemrograman Web Lanjutan. Proyek ini mendemonstrasikan pembuatan endpoint API menggunakan FastAPI, integrasi database SQLite menggunakan SQLAlchemy (ORM), dan validasi output menggunakan Pydantic.

* **Nama:** Akram Alfadli Tamir

## Teknologi yang Digunakan
* **Framework:** FastAPI
* **ORM:** SQLAlchemy
* **Database:** SQLite
* **Validasi Data:** Pydantic
* **Server:** Uvicorn

## Struktur Endpoint API
* `POST /items/` : Menambahkan data item baru ke database (Endpoint tambahan untuk pengisian data awal).
* `GET /items/` : Mengambil semua data item dari database.
* `GET /items/{id}` : Mengambil data item spesifik berdasarkan ID.

## Cara Menjalankan Proyek Lokal

1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/Akram-Dwf/Tugas-CRUD-FastAPI.git](https://github.com/Akram-Dwf/Tugas-CRUD-FastAPI.git)
   cd Tugas-CRUD-FastAPI
   ```
2. **AVirtual Environmentktifkan :**
    ```bash
    .\.venv\Scripts\activate
    ```
3. **Install dependencies:**
    ```bash
    pip install fastapi uvicorn sqlalchemy pydantic
    ```
4. **Jalankan server aplikasi:**
    ```bash
    uvicorn main:app --reload
    ```
5. **Akses Dokumentasi API:**
    http://127.0.0.1:8000/docs