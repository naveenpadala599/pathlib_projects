# 📁 Pathlib Projects

This repository contains small but practical projects built using Python’s `pathlib` module.
The goal of this repo is to move beyond theory and apply `pathlib` in real-world scenarios.

---

## 🚀 Project: File Organizer CLI

A command-line based Python tool that automatically organizes files in a directory into categories such as Images, Videos, Documents, and Archives.

This project was built to practice and deeply understand `pathlib` by working with real file system operations.

---

## ✨ Features

* 📂 Organizes files by type (Images, Videos, Documents, Archives)
* 🔁 Supports **recursive mode** (organizes files inside subfolders)
* 🧪 **Dry run mode** (preview changes without actually moving files)
* 🔄 Handles **duplicate file names safely** (auto-renames files)
* 🧠 Built entirely using `pathlib` (no `os` module)

---

## 🛠️ How It Works

1. User selects:

   * Dry run or real execution
   * Recursive or normal mode
2. User provides a directory path
3. Script:

   * Creates category folders if they don’t exist
   * Scans files using `glob()` or `rglob()`
   * Moves files into appropriate folders
   * Renames duplicates automatically

---

## ▶️ Usage

Run the script:

```bash
python file_organizer.py
```

Follow the prompts:

* Choose dry run or real mode
* Choose recursive or normal mode
* Enter the directory path

---

## 🧪 Example Output

### Dry Run:

```
[DRY RUN] photo.jpg → Images/photo.jpg
[DRY RUN] video.mp4 → Videos/video.mp4
```

### Real Execution:

```
Moved: document.pdf → Documents/document.pdf
Moved: image_1.jpg → Images/image_1.jpg
```

---

## 📂 Project Structure

```
pathlib_projects/
│
├── file_organizer.py
└── README.md
```

---

## 🎯 Learning Goals

This project helped reinforce:

* Using `Path` objects effectively
* Working with `.glob()` and `.rglob()`
* File and directory manipulation
* Handling edge cases like duplicates
* Writing clean, scalable logic

---

## 🔜 Future Improvements

* Add CLI arguments (no prompts, direct command usage)
* Add logging to file
* Improve file categorization (more extensions)
* Add undo functionality

---

## 📌 Note

This is part of an ongoing learning journey.
More `pathlib`-based projects will be added to this repository over time.

---

## 💡 Author

Built as part of a hands-on Python learning journey focused on practical problem solving and real-world tools.
