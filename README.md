# Asset Library Tools

### **Quickly filter assets by tags and backup/restore asset catalogues**
**Asset Library Tools** improves productivity inside Blender’s Asset Browser by making large asset libraries easier to search and safer to manage.

---

### 💡 Why this Add-on Exists

- Managing large asset libraries becomes difficult when catalogue categories aren’t enough to quickly find the right asset. Tags are more flexible and descriptive, but they’re easy to forget — and manually typing and guessing tag names wastes time.

- Unexpected crashes or power issues can corrupt catalogue files, and manually backing them up rarely happens consistently.

### ✔ Tag Filter + Indexer
Automatically indexes every tag across your active asset library and shows a clean list you can filter from instantly. No more remembering tag names or searching blindly.

### ✔ Catalogue Backup
One-click backup and restore for catalogue files, keeping your library structure safe and recoverable at any time.

---

## ✨ Key Features

- **Filter assets instantly using indexed tags**
- Automated tag indexing from all `.blend` files in the active asset library
- Incremental indexing for faster updates
- **One-click catalogue backup & restore**
- Automatic pruning (keeps recent backups only)
- **Open Library Folder button** to jump directly to the asset library location on disk

---

###  Location

**Asset Browser → T-Panel → Asset Library Tools**

Contains:
- Tag Filter
- Tag Indexer (collapsible)
- Catalogue Backup (collapsible)

---

## 🪶 How to Use

1. Open **Asset Browser** and switch to your user Asset Library.
2. Expand **Tag Indexer** → click *Build Index* to scan tags.  
   (run only once to generate tag index)
3. Use **Tag Filter** to search instantly.
4. Use **Catalogue Backup** to save or restore catalogue files with one click.

### ⚠ Important Note About Tag Indexing
Building the initial index may take time depending on the size of your library.  
You only need to run a full index **once**, unless you add or modify assets.  
Use **“Skip Indexed”** (Incremental mode) to dramatically speed up future updates.

---

## 🗂 Stored Data

- Tag index saved as `asset_tags.json` within each asset library folder
- Backups saved in `Backup catalogue/` subfolder per library
- Error logs saved in `ati_log.txt` if needed

---

## 📦 Installation

1. Download or zip the `asset_library_tools` folder.
2. In Blender: **Edit → Preferences → Add-ons → Install…**
3. Enable **Asset Library Tools**.
4. Open the Asset Browser to access the panel.

---

## 🧾 License
**GPL-3.0-or-later**

---

## 🧍 Maintainer
**Akhil Alukkaran**

---
