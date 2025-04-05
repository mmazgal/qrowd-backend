# Qrowd Project

A modern social platform project with protected backend endpoints, token-based authentication, and frontend integration. Built step-by-step with clean project structure and future-ready Docker & Supabase integration.

Korunaklı backend endpointleri, token tabanlı kimlik doğrulama ve frontend entegrasyonuyla adım adım geliştirilen modern sosyal platform projesi. Temiz proje yapısı ve gelecekte Docker & Supabase entegrasyonu için hazır.

---

## Technologies / Teknolojiler

- **Backend:** FastAPI (Python)
- **Database:** PostgreSQL (local)
- **Frontend:** React.js (ongoing)
- **ORM:** SQLAlchemy
- **Auth:** JWT Token (Access Token)
- **Docker:** To be added later
- **Supabase:** Will be added after base functionalities

---

## Installation / Kurulum

### 1. Clone the repository / Depoyu klonla

```bash
git clone https://github.com/mmazgal/qrowd.git
cd qrowd
```

### 2. Create virtual environment / Sanal ortam oluştur

```bash
python -m venv venv
```

Activate venv:

- **Windows:**
```bash
venv\Scripts\activate
```

### 3. Install dependencies / Bağımlılıkları yükle

```bash
pip install -r requirements.txt
```

### 4. Set up .env file / .env dosyasını ayarla

Create `.env` in the root directory and add:

```env
DATABASE_URL=postgresql://postgres:yourpassword@localhost:5432/qrowd
SECRET_KEY=SECRET1234567890
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
```

### 5. Start the backend / Backend'i başlat

```bash
uvicorn qrowd.main:app --reload
```

Now API is running at: [http://127.0.0.1:8000](http://127.0.0.1:8000) 🚀

---

## Usage / Kullanım

- Register a user (POST `/register`)
- Login to get token (POST `/login`)
- Access protected endpoints with token!

User interface will soon be connected with dashboard 🎉

---

## Roadmap / Yol Haritası

- [x] Backend setup complete
- [x] User registration & login
- [x] JWT token based auth
- [ ] Protect sensitive routes (ongoing)
- [ ] Frontend dashboard connection
- [ ] Token expiration & refresh
- [ ] Logout system
- [ ] Dockerize the project
- [ ] Supabase integration

---

## Project Status / Proje Durumu

This project is under active development! 🛠️  
Şu anda backend kurulumu tamam, frontend ile bağlantı aşamasındayız. Docker ve Supabase son aşamada entegre edilecek.

---

## License / Lisans

Private repository for personal development and future public release.  
Şimdilik özel repo, geliştirme tamamlandığında açık kaynak yapılabilir!

---

### Made with love ❤️ by Muhammed and Co-Pilot ChatGPT

