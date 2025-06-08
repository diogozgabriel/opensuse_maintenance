# 🧰 OpenSUSE Maintenance

**A modular Python application to automate and simplify maintenance tasks on openSUSE Linux.**  
Created with care and precision by a former pharmacologist turned fullstack developer in Brazil 🇧🇷

---

## ⚙️ Features

- System update via `zypper dup`
- Flatpak updates
- Removal of orphan packages
- Cache cleaning
- Modular architecture (each task is a separate Python module)
- Easy to extend and customize

---

## 🐍 Technologies Used

- Python 3.x
- Standard library only (no external dependencies)
- Compatible with openSUSE Tumbleweed

---

## 📁 Project Structure (WIP)

```
opensuse_maintenance/
├── main.py
├── modules/
│   ├── zypper_update.py
│   ├── flatpak_update.py
│   ├── orphan_removal.py
│   ├── cache_cleaner.py
│   └── ...
└── README.md
```

---

## 🚀 Getting Started

Clone the repo:

```bash
git clone https://github.com/diogozgabriel/opensuse_maintenance.git
cd opensuse_maintenance
python3 main.py
```

> 📝 *Make sure to run with sudo if needed for system-level operations.*

---

## 📌 Motivation

After years in academia and healthcare, this tool reflects my new path in technology.  
It automates the kind of daily tasks I used to do manually — and now shares it with the community.

---

## 📃 License

MIT License – use it freely, with respect.

---

## ✉️ Contact

**Diogo Gabriel**  
[LinkedIn](https://www.linkedin.com/in/diogozgabriel) | Santa Bárbara do Sul, Brazil  
