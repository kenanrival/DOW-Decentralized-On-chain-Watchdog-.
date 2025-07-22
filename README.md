# DOW (Decentralized On-chain Watchdog)

Platform Analisis Risiko Smart Contract Otomatis dengan Laporan Terverifikasi Blockchain untuk Ekosistem Keuangan Digital yang Lebih Aman.

## 🎯 Overview

DOW adalah platform SaaS yang menyediakan analisis keamanan smart contract secara otomatis, cepat (dalam hitungan menit), dan terjangkau. Inovasi kunci kami terletak pada arsitektur hibrida: analisis terpusat untuk kecepatan maksimal, dengan hasil laporan yang disimpan secara terdesentralisasi di IPFS dan dicatat di blockchain.

## 🏗️ Architecture

```
dow-project/
├── backend/                 # FastAPI Backend
│   ├── app/
│   │   ├── api/            # API endpoints
│   │   ├── core/           # Core configurations
│   │   ├── services/       # Business logic
│   │   └── models/         # Data models
│   ├── docker/             # Docker configurations
│   ├── requirements.txt
│   └── Dockerfile
├── frontend/               # React.js Frontend
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── pages/          # Page components
│   │   ├── services/       # API services
│   │   └── utils/          # Utilities
│   ├── public/
│   └── package.json
├── contracts/              # Smart Contracts
│   ├── DOWRegistry.sol     # Registry contract
│   └── deploy/             # Deployment scripts
├── docs/                   # Documentation
└── docker-compose.yml      # Development environment
```

## 🚀 Tech Stack

### Frontend
- **Framework**: React.js with TypeScript
- **Build Tool**: Vite
- **UI Library**: MUI (Material-UI)
- **Deployment**: Vercel

### Backend
- **Framework**: FastAPI (Python)
- **Analysis Engine**: Slither
- **Containerization**: Docker
- **Deployment**: Render

### Blockchain & Storage
- **Network**: Sepolia Testnet
- **Provider**: Alchemy/Infura
- **Storage**: IPFS
- **Smart Contracts**: Solidity

## 🎯 Target Market

1. **Primary**: Venture Capital & Angel Investor (untuk screening investasi)
2. **Secondary**: Tim developer independen (untuk pre-audit internal)

## 💰 Business Model

- **Freemium**: 1-3 analisis gratis per bulan
- **Pro**: $99/bulan untuk developer/tim kecil  
- **Institutional**: $499/bulan untuk VC dengan volume tinggi

## 🗺️ Roadmap

- **Fase 1 (Q4 2025)**: MVP dengan model hibrida
- **Fase 2 (2026)**: Pengembangan AI/ML internal
- **Fase 3 (2027)**: DOW Node Network yang fully decentralized

## 🏃‍♂️ Quick Start

```bash
# Clone repository
git clone <repository-url>
cd dow-project

# Setup backend
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload

# Setup frontend
cd ../frontend
npm install
npm run dev

# Run with Docker
docker-compose up --build
```

## 📝 License

This project is part of BI-OJK Hackathon 2025 submission.

---

**Team**: Rivaldi Murpia  
**Submission Date**: July 26, 2025
