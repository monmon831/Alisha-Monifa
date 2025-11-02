# 🏴‍☠️ One Piece Tweet Scraping & ETL Pipeline

## 📌 Deskripsi
Project ini adalah ETL pipeline untuk scraping, cleaning, dan menyimpan tweet tentang One Piece menggunakan PySpark dan MongoDB Atlas.

## 🎯 Fitur
- ✅ Web scraping tweet dengan tweet-harvest
- ✅ Data cleaning menggunakan PySpark
- ✅ Storage ke MongoDB Atlas
- ✅ ETL pipeline lengkap

## 📊 Hasil
- **234 tweets** berhasil dikumpulkan
- **100%** success rate untuk data cleaning
- Data tersimpan di MongoDB Atlas

## 🛠️ Teknologi
- Python 3.10
- PySpark 3.5.3
- MongoDB Atlas
- Pandas 2.2.2
- PyMongo 4.10.1
- Node.js 20.x
- Tweet-Harvest 2.6.1

## ⚙️ Cara Menggunakan

### 1. Clone Repository
```bash
git clone https://github.com/username/onepiece-tweet-scraping.git
cd onepiece-tweet-scraping
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Setup Environment Variables
Buat file `.env` dari template:
```bash
cp .env.example .env
```

Edit `.env` dan isi dengan credentials Anda:
```bash
TWITTER_AUTH_TOKEN=token_anda_disini
MONGODB_URI=mongodb+srv://user:pass@cluster.mongodb.net/
```

### 4. Jalankan Notebook
- Upload ke Google Colab
- Set environment variables
- Run all cells

## 📸 Screenshot
<img width="1711" height="696" alt="image" src="https://github.com/user-attachments/assets/5ac0e945-6b77-4410-b260-f8a831300494" />
<img width="1125" height="272" alt="image" src="https://github.com/user-attachments/assets/1417d144-1035-4f7c-97e0-5378bea19b75" />



## 🙏 Acknowledgments
- Tweet-Harvest by Helmi Satria
- Apache Spark Community
- MongoDB Team
```
