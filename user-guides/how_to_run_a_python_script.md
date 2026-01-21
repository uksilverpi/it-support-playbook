# How to Run a Python Script (Beginner-Friendly Guide)

This walkthrough explains how to run a Python script on Windows or macOS, using the example of a simple automation tool such as `daily_log_generator.py`.

---

## 1. Make Sure Python Is Installed

### Windows
1. Press the Windows Key.
2. Type `python`.
3. If a Microsoft Store page appears, install Python from there.
4. Once installed, close and reopen any Command Prompt window.

### macOS
Python 3 usually comes preinstalled.  
To check, open Terminal and type:

```
python3 --version
```

If you see a version number, you're ready.

---

## 2. Download the Script

1. Open the GitHub repository.
2. Click the script name (e.g., `daily_log_generator.py`).
3. Click **Raw**.
4. Right-click → **Save As…**.
5. Save the file in an easy-to-find folder (e.g., Desktop → `automation_scripts`).

---

## 3. Open a Terminal / Command Prompt

### Windows
- Press **Windows Key**
- Type `cmd`
- Press **Enter**

### macOS
- Press **Command + Space**
- Type `terminal`
- Press **Enter**

---

## 4. Move Into the Script’s Folder

If your folder is on your Desktop:

### Windows
```
cd Desktop\automation_scripts
```

### macOS
```
cd ~/Desktop/automation_scripts
```

---

## 5. Run the Script

### Windows or macOS (Python 3):
```
python daily_log_generator.py
```
or
```
python3 daily_log_generator.py
```

---

## 6. What Happens

A new file appears in the same folder, e.g.:

```
daily_log_2026-01-21.md
```

Inside you’ll find:

- Summary
- Key Tasks
- Notes

---

## 7. Common Issues & Fixes

### Error: “python not found”
Python isn’t installed or isn’t added to PATH.  
Reinstall Python from python.org or the Microsoft Store.

### Error: “No such file or directory”
You’re not in the right folder.  
Navigate using `cd` to the correct location.

### Nothing happens
Try:
- using `python3` instead of `python`
- checking the filename is correct

---

This guide is written for non-technical users and junior staff learning fundamental scripting workflows.
