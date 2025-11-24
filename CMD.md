
---

# ⭐ **Top CMD Commands (Daily Use)**

## 🔵 **1. Folder & File Commands**

```
dir          → list files/folders
cd           → change directory
cd..         → go back one folder
md folder    → create folder (mkdir)
rd folder    → delete folder (rmdir)
type nul > filename.txt   → create file 
del file.txt → delete file
copy a b     → copy file
move a b     → move file
rename a b   → rename file
type file.txt → display file content
```

---

## 🔵 **2. System Information**

```
systeminfo         → full system info
hostname           → show computer name
ver                → Windows version
tasklist           → show running programs
taskkill /IM app.exe /F → force close program
```

---

## 🔵 **3. Network Commands**

```
ipconfig              → IP details
ipconfig /all         → full network info
ipconfig /flushdns    → clear DNS cache
ping google.com       → check connection
tracert google.com    → trace route
netstat -ano          → open ports & connections
nslookup domain.com   → DNS lookup
```

---

## 🔵 **4. Disk & Drives**

```
diskpart            → disk partition tool
chkdsk C:           → check drive errors
format E:           → format drive
vol                 → show drive volume info
wmic logicaldisk get size,freespace,caption  → disk space
```

---

## 🔵 **5. User & Permissions**

```
whoami              → show logged-in user
net user            → list system users
net user <name>     → user details
```

---

## 🔵 **6. Power & Boot Commands**

```
shutdown /s /t 0    → shutdown immediately
shutdown /r /t 0    → restart
shutdown /l         → log out
```

---

## 🔵 **7. File Operations (Advanced)**

```
attrib file         → file attributes
fc file1 file2      → compare files
xcopy a b /E        → copy folders
robocopy a b /MIR   → backup entire folder
```

---

## 🔵 **8. Environment & Path**

```
set                 → list environment variables
setx VAR value      → create environment variable
path                → show PATH variable
```

---

## 🔵 **9. Useful Admin Commands**

```
sfc /scannow        → repair Windows files
DISM /online /cleanup-image /restorehealth → fix system image
msconfig            → system configuration
services.msc        → services window
regedit             → registry editor
```

---

