# 🖼️ Python Image Report Cheatsheet

## 🔍 What does the script do? | Šta ova skripta radi?

#### 🇬🇧: Extracts metadata (filename, format, size, dimensions) from all images in a specified folder and exports results to a CSV file.
#### 🇷🇸: Ekstrahuje metapodatke (naziv, format, veličinu, dimenzije) iz svih slika u zadatom folderu i čuva rezultate u CSV fajlu.

---

## 📦 Used Modules | Korišćeni moduli

| Modul | Opis / Description                             |
| ----- | ---------------------------------------------- |
| os    | Rad sa fajl sistemom / File system operations  |
| PIL   | Obrada slika / Image processing (via `Pillow`) |
| csv   | Pisanje CSV fajla / Writing CSV output         |

#### 🇬🇧: 🔧 Note: It is necessary to install `Pillow` library via `pip install pillow`
#### 🇷🇸: 🔧 Napomena: Potrebno je instalirati `Pillow` biblioteka preko `pip install pillow`


---

## 🧠 Key Concepts | Ključni koncepti

#### ✅ `Image.open(path)` – opens the image for analysis | otvara sliku radi analize

- `img.format` – image format (JPEG, PNG...) | format slike (JPEG, PNG...)
- `img.width`, `img.height` – image size | dimenzije slike

#### ✅ `os.path.getsize(path)` – file size in bytes | veličina fajla u bajtovima

#### ✅ CSV export from `csv.DictWriter` | CSV eksport iz `csv.DictWriter` 

- Write header first (`writeheader()`) | Prvo piše zaglavlje (`writeheader()`)
- Then data rows (`writerows()`) | Zatim redove sa podacima (`writerows()`)

---

## 🧪 How to run | Kako pokrenuti

```bash
python image_report.py
```

#### 🇬🇧:💡 Rezultat će biti snimljen kao `test_folder/image_report.csv`
#### 🇷🇸:💡 The result will be saved as `test_folder/image_report.csv`
---

## 🗂️ Folder Structure | Struktura foldera

```
day03_file_management/
│
├── test_folder/
│   ├── images/                 # slike za analizu | images for analysis
│   └── image_report.csv        # rezultat | final result
│
├── image_report.py            # glavna skripta | main script
```

## 🧠 Useful Tips | Korisni saveti

- 📸 You can extend the script to read `.webp`, `.gif`... | Možeš proširiti skriptu da čita i `.webp`, `.gif`...
- 🗑️ Add option to delete small images (eg < 10 KB) | Dodaj opciju za brisanje malih slika (npr. < 10 KB)
- 📊 Create a histogram of sizes or dimensions | Napravi histogram veličina ili dimenzija
- 🔁 Automatically scan all subfolders (recursively) | Automatski skeniraj sve podfoldere (rekurzivno)

---

## 🎯 Learning Goals | Ciljevi učenja

- Apply work with images and metadata | Primeniti rad sa slikama i metapodacima
- Master basic image processing without a GUI | Savladati osnovnu obradu slika bez GUI-ja
- Working with the file system and CSV files | Rad sa fajl sistemom i CSV fajlovima

---

## 📚 Resources | Resursi

- [Pillow Docs](https://pillow.readthedocs.io/en/stable/)
- [CSV Module](https://docs.python.org/3/library/csv.html)
- [os module](https://docs.python.org/3/library/os.html)

#### 🇷🇸: Kreirano kao deo projekta `day03_file_management` u okviru `python-automation` repozitorijuma.
#### 🇬🇧: Created as part of the `day03_file_management` project within the `python-automation` repository.

---
### 🖼️ Visual Walkthrough | Vizuelni vodič

<table>
  <tr>
    <td align="center">
      <img src="../assets/image_report-step1.png" width="400"/><br/>
      <strong>🇬🇧: Opening <code>image_report.py</code> script in VS Code<br/>🇷🇸: Otvaranje skripte ,<code>image_report.py</code> u VS Code-u</strong>
    </td>
    <td align="center">
      <img src="../assets/image_report-step2.png" width="280"/><br/>
      <strong>🇬🇧: Terminal output while processing images<br/>🇷🇸: Prikaz izlaza u terminalu tokom obrade slika</strong>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="../assets/image_report-step3.png" width="380"/><br/>
      <strong>🇬🇧: Preview of generated <code>CSV file</code><br/>🇷🇸: Pregled generisanog <code>CSV fajla</code> sa podacima o slikama</strong>
    </td>
    <td align="center">
      <img src="../assets/image_report-step4.png" width="280"/><br/>
      <strong>🇬🇧: Folder structure with <code>image_report.csv</code><br/>🇷🇸: Struktura foldera sa <code>image_report.csv</code> fajlom</strong>
    </td>
  </tr>
</table>


