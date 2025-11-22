
---

# ⭐ **Some PowerShell Commands (Beginner Friendly)**

## 🔵 **1. Navigation (moving inside folders)**

```powershell
pwd             # Show current directory
ls              # List files (alias of Get-ChildItem)
cd <path>       # Change directory
cd ..           # Go back
mkdir <name>    # Create folder
```

---

## 🔵 **2. File & Folder Operations**

```powershell
Get-ChildItem           # List files/folders
New-Item file.txt       # Create file
Remove-Item file.txt    # Delete file/folder
Copy-Item file.txt D:\  # Copy file
Move-Item file.txt D:\  # Move file
Rename-Item old.txt new.txt   # Rename file
```

---

## 🔵 **3. Reading / Writing Files**

```powershell
Get-Content file.txt                # Read file
Set-Content file.txt "Hello"        # Overwrite
Add-Content file.txt "New line"     # Append
```

---

## 🔵 **4. System Information**

```powershell
Get-Date               # Current date/time
Get-ComputerInfo       # System info
Get-Location           # Current directory
Get-Host               # PowerShell details
Get-ExecutionPolicy    # Security policy
```

---

## 🔵 **5. Software & Processes**

```powershell
Get-Process                    # All running processes
Stop-Process -Name notepad     # Kill a process
Start-Process notepad          # Open app
```

---

## 🔵 **6. Services**

```powershell
Get-Service                    # List services
Start-Service <name>           # Start a service
Stop-Service <name>            # Stop a service
Restart-Service <name>         # Restart service
```

---

## 🔵 **7. Searching & Filtering**

```powershell
Get-ChildItem -Recurse | Select-String "text"      # Search in files
Get-Command *firewall*                             # Find commands
Get-Help Get-Process                               # Command help
```

---

## 🔵 **8. Networking**

```powershell
Test-Connection google.com         # Ping
Get-NetIPAddress                   # IP addresses
Get-NetAdapter                    # Network adapter info
```

---

## 🔵 **9. Task Automation Basics**

```powershell
foreach ($i in 1..5) { echo $i }        # Loop
```

---

## 🔵 **10. Useful Aliases (shortcuts)**

These are shortcuts in PowerShell:

| Alias | Full Command  |
| ----- | ------------- |
| ls    | Get-ChildItem |
| cat   | Get-Content   |
| gc    | Get-Content   |
| pwd   | Get-Location  |
| cd    | Set-Location  |
| rm    | Remove-Item   |
| cp    | Copy-Item     |
| mv    | Move-Item     |

---
