# ✦ Todo List App

Aplikasi web Todo List sederhana berbasis Python (Flask).
Demo https://todo-app-python-6rgc.onrender.com/

## Fitur
- ➕ Tambah tugas baru
- ✅ Tandai tugas selesai / belum selesai
- 🗑️ Hapus tugas
- 🧹 Hapus semua tugas yang sudah selesai
- 🔍 Filter: Semua / Aktif / Selesai
- 💾 Data disimpan di file JSON (tidak butuh database)

## Cara Menjalankan

**1. Clone / download project ini**
```bash
git clone https://github.com/username/todo-app.git
cd todo-app
```

**2. Buat virtual environment (opsional tapi disarankan)**
```bash
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Jalankan aplikasi**
```bash
python app.py
```

**5. Buka browser dan akses:**
```
http://localhost:5000
```

## Struktur Project
```
todo-app/
├── app.py              # Logika utama Flask
├── requirements.txt    # Dependencies
├── todos.json          # Data todo (otomatis dibuat)
├── .gitignore
└── templates/
    └── index.html      # Tampilan web
```

## Tech Stack
- **Backend**: Python + Flask
- **Frontend**: HTML, CSS, Vanilla JS
- **Storage**: JSON file

---
Made with ♥ using Flask
