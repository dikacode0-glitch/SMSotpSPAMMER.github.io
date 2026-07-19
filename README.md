# 🚀 Spammer OTP WhatsApp

**Premium OTP Spammer dengan 106+ API WhatsApp**  
**Sistem Manajemen Lisensi Terenkripsi + Admin Panel + Auto Maintenance**

<p align="center">
  <img src="https://img.shields.io/badge/Version-3.1-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/API-106%2B-brightgreen.svg" alt="API Count">
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Android%20%7C%20Windows-brightgreen.svg" alt="Platform">
  <img src="https://img.shields.io/badge/License-Premium-orange.svg" alt="License">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue.svg" alt="Python">
</p>

---

## 📌 Tentang

**Spammer OTP WhatsApp** adalah tools premium untuk spam OTP WhatsApp dengan **106+ API endpoint**.  
Dilengkapi dengan **sistem manajemen lisensi**, **Admin Panel**, **maintenance mode**, dan **animasi terminal keren**.

---

### ✨ Fitur Unggulan

| Fitur | Deskripsi |
|-------|-----------|
| 🎯 **106+ API** | 106 target OTP WhatsApp dari berbagai kategori |
| 🔐 **Sistem Lisensi** | Trial + Premium unlimited via Supabase |
| 🖥️ **Multi-Platform** | Linux, Android (Termux), Windows |
| ⚡ **Multi-Threading** | Dukungan 1-10 thread |
| 🔄 **Infinite Loop** | Auto-repeat tiap 60 detik |
| 📊 **Admin Panel** | Grant premium, list users, cari user |
| 🛡️ **Maintenance Mode** | Toggle ON/OFF, kustom pesan via database |
| 🎨 **Animasi Terminal** | Loading bar, typewriter, glow, pulse, ZSH-style menu |
| 🧬 **Device Fingerprint** | Anti-ban dengan hardware fingerprinting |
| 🔄 **User-Agent Rotation** | 34+ User-Agent acak |

---

## 🚀 Cara Install & Jalankan

### Prerequisites
- Python 3.10+
- Supabase account (free tier)
- pip (Python package manager)

### Instalasi

```bash
# Clone repository
git clone <repo-url>
cd spammer-otp

# Install dependencies
pip install -r requirements.txt

# Setup database
# Jalankan setup_supabase.sql di Supabase SQL Editor

# Ganti SUPABASE_KEY di license.py dengan anon key dari dashboard

# Jalankan tools
python main.py
```

---

## 🔧 Admin Panel

Untuk owner (Device ID: `e0c2cc66256510fe2215a3671982910a`):

| Menu | Fungsi |
|------|--------|
| **Grant Premium** | Aktivasi device ID + jumlah hari (0=unlimited) |
| **List Users** | Lihat semua user terdaftar |
| **Cari User** | Search by device ID |
| **Maintenance Mode** | Toggle ON/OFF + kustom pesan |

---

## 🛡️ Maintenance Mode

Ketika mode maintenance **AKTIF**:
- Semua user TRIAL & PREMIUM (non-owner) di-block
- Mereka melihat layar maintenance + pesan kustom
- **OWNER** tetap bisa akses tools penuh
- Data maintenance tersimpan di Supabase (config table)

---

## 🔧 File Structure

```
📁 spammer-otp/
├── main.py              # Entry point + menu ZSH-style
├── main_engine.py       # OTP spam engine (106+ targets)
├── handlers.py          # Custom OTP handler functions
├── targets.py           # 106 target API configurations
├── license.py           # License system + Supabase
├── utils.py             # Utility functions
├── animations.py        # Terminal animations
├── useragents.py        # 34+ User-Agent list
├── setup_supabase.sql   # Database setup script
└── README.md            # This file
```

---

## 📄 License

**Premium License** - Hak akses penuh dengan sistem lisensi via Supabase.  
Harga: Rp. 5.000 (sekali bayar, akses selamanya)

Kontak: Telegram @bapakmu123d