# Solamiscan

Solamiscan is an open-source desktop application for monitoring Solana wallet activity and analyzing token interactions in real time.

Built as a Windows-first application, Solamiscan provides a clean interface for tracking wallet behavior, identifying new token interactions, and storing historical on-chain activity locally.

---

## 🚀 Vision

Solamiscan aims to provide accessible wallet intelligence tools without requiring paid APIs or complex setups. The long-term goal is to evolve into a modular Solana analytics platform.

---

## ✅ Features (v0.1.0 – MVP)

* Add and remove tracked wallets
* View recent wallet transactions
* Detect token transfer activity
* Highlight first-time token interactions
* Track SOL spent per transaction
* Local SQLite storage for historical logging
* Windows desktop UI (PySide6)

---

## 🔮 Planned Features

* Volume and liquidity analytics
* Dev wallet tracking
* Token risk indicators
* Real-time migration detection
* Behavioral analytics modules
* CSV export functionality
* Multi-wallet dashboard view
* Cross-platform support

---

## 🛠 Tech Stack

* Python 3.10+
* PySide6 (Qt for Python)
* SQLite
* Free Solscan API wrapper (data layer)
* PyInstaller (Windows executable builds)

---

## 📦 Installation

### 1. Clone the Repository

```bash
https://github.com/B3an-B0i/SolamiScan.git
cd solamiscan
```

### 2. Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python main.py
```

---

## 🖥 Building a Windows Executable

Install PyInstaller:

```bash
pip install pyinstaller
```

Build:

```bash
pyinstaller --onefile --windowed main.py
```

The executable will appear in the `dist/` folder.

---

## 🧠 Project Structure

```
solamiscan/
│
├── solamiscan/
│   ├── core/
│   ├── services/
│   ├── database/
│   ├── ui/
│   ├── workers/
│   └── config.py
│
├── tests/
├── main.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 Data Disclaimer

Solamiscan retrieves publicly available blockchain data. It does not provide financial advice and is intended strictly for research and informational purposes.

Users are responsible for complying with applicable laws and respecting API usage limits.

---



## Version

Current Version: v0.1.0 (MVP Development Phase)
