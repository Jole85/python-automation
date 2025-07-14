# 📂 day02_file_info

**Project type:** Python Automation  
**Date:** 2025-07-14  
**Status:** ✅ Completed  
**Preview images:**  
![Preview 1](../assets/day02_file_info/day02_file_info-preview-1.png)
![Preview 2](../assets/day02_file_info/day02_file_info-preview-2.png)
![Preview 3](../assets/day02_file_info/day02_file_info-preview-3.png)
![Preview 4](../assets/day02_file_info/day02_file_info-preview-4.png)

---

## 📌 Description (EN)

This project analyzes files in a selected folder and logs information about each file, including:

- File name
- Extension
- File size in bytes
- Last modified timestamp

It also features:

- Color-coded terminal output using ANSI escape codes
- Log rotation using Python's `RotatingFileHandler`
- Flexible input via `input()`
- Clean error handling and logging using a custom `logger.py` module

**Goal:** Practice Python modules like `os`, `datetime`, `logging`, and improve command-line interaction and logging discipline.

---

## 📌 Opis (SR)

Ovaj projekat analizira fajlove u izabranom folderu i beleži informacije o svakom fajlu, uključujući:

- Ime fajla
- Ekstenziju
- Veličinu u bajtovima
- Datum poslednje izmene

Takođe sadrži:

- Boje u terminalu (ANSI escape kodovi)
- Rotaciju log fajla putem `RotatingFileHandler` klase
- Unos foldera putem `input()`
- Robusno logovanje uz sopstveni `logger.py` modul

**Cilj:** Vežbanje rada sa modulima `os`, `datetime`, `logging` i rad u terminalu. Projektom sam dodatno učvrstio rad sa putanjama i logovanjem grešaka.

---

## 🧠 What I Learned / Šta sam naučio

### What I Learned (EN)

- How to work with `os.path` and `os.listdir`
- Use of `os.path.getsize` and `os.path.getmtime`
- Parsing file extensions with `os.path.splitext`
- Formatting timestamps using `datetime.fromtimestamp`
- Creating and rotating logs with `RotatingFileHandler`
- Adding terminal colors using ANSI escape codes
- Structuring code into reusable modules (e.g., `logger.py`)
- Accepting user input via `input()` and validating it
- Practicing dynamic folder analysis and command-line interaction

### Šta sam naučio (SR)

- Rukovanje fajl sistemom koristeći `os.path` i `os.listdir`
- Dohvatanje veličine fajla (`getsize`) i datuma poslednje izmene (`getmtime`)
- Parsiranje ekstenzije fajla preko `os.path.splitext`
- Formatiranje vremena pomoću `datetime.fromtimestamp`
- Kreiranje i rotacija log fajlova uz `RotatingFileHandler`
- Dodavanje boja u terminal koristeći ANSI escape kodove
- Modularizacija koda – pravljenje sopstvenog `logger.py` modula
- Korišćenje `input()` za unos foldera i validacija unosa
- Analiza sadržaja foldera i logovanje sa modernim CLI pristupom


---

## 🚀 How to Run

```bash
python main.py
```

Then enter the name of the folder you want to analyze (e.g., `test_files`).

---

## 📁 Folder Structure

```
day02_file_info/
│
├── main.py
├── logger.py
├── test_files/
│   ├── test1.txt
│   ├── test2.pdf
│   └── ...
├── log.txt
└── README.md
```

---

## 🖼️ Gallery

![Preview 1](../assets/day02_file_info/day02_file_info-preview-1.png)
![Preview 2](../assets/day02_file_info/day02_file_info-preview-2.png)
![Preview 3](../assets/day02_file_info/day02_file_info-preview-3.png)
![Preview 4](../assets/day02_file_info/day02_file_info-preview-4.png)

---

## ©️ Author

Josip Pavlović  
Repository: [python-automation](https://github.com/yourusername/python-automation)