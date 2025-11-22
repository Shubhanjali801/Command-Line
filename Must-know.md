<h1> **Git**, **Linux**, **Docker**, **Node**, **MongoDB**, **Networking**, **System monitoring**, **VS Code terminal**</h>


---

# ✅ **1. Linux / Command Line (Must-Know for Every Developer)**

### **Navigation & Files**

```
ls
ls -la
cd <folder>
pwd
mkdir <folder>
rmdir <folder>
rm <file>
rm -rf <folder>
cp <src> <dest>
mv <src> <dest>
touch <file>
cat <file>
less <file>
head <file>
tail <file>
tail -f <file>
```

### **System & Processes**

```
top
htop
ps aux
kill <pid>
kill -9 <pid>
```

### **Permissions**

```
chmod 755 <file>
chmod +x <file>
chown user:group <file>
sudo <command>
```

### **Networking**

```
ping google.com
curl <url>
wget <url>
ifconfig
ip addr
netstat -tlnp
```

### **Archive & Compression**

```
tar -xzvf file.tar.gz
zip -r file.zip folder/
unzip file.zip
```

---

# ✅ **2. Git & GitHub Commands (Professional Level)**

### **Basic**

```
git init
git clone <url>
git status
git add .
git commit -m "message"
git push
git pull
git fetch
```

### **Branching**

```
git branch
git branch <name>
git checkout <name>
git switch <name>
git merge <name>
git branch -d <name>
```

### **Remote**

```
git remote -v
git remote add origin <url>
git remote remove origin
```

### **Undo / Fix**

```
git reset --soft HEAD~1
git reset --hard HEAD~1
git revert <commit>
git stash
git stash pop
```

### **Advanced**

```
git log
git log --oneline
git diff
git reflog
git cherry-pick <commit>
git tag <tagname>
```

---

# ✅ **3. VS Code Terminal / CMD / PowerShell**

```
code .
code <filename>
cls (Windows)
clear (Linux)
```

---

# ✅ **4. Node.js / NPM**

```
node app.js
npm init -y
npm install <package>
npm install -g <package>
npm uninstall <package>
npm run dev
npm run build
```

---

# ✅ **5. MongoDB (Shell + Compass + Atlas)**

### **Mongo Shell**

```
mongosh
show dbs
use <database>
show collections
db.<collection>.find()
db.<collection>.find().pretty()
db.<collection>.insertOne({ })
db.<collection>.updateOne(...)
db.<collection>.deleteOne(...)
db.<collection>.drop()
```

### **Atlas / Compass**

```
mongodb+srv://<username>:<password>@cluster.mongodb.net/
```

---

# ✅ **6. Docker (Very Important in Pro Work)**

### **Containers**

```
docker ps
docker ps -a
docker run <image>
docker stop <id>
docker start <id>
docker rm <id>
```

### **Images**

```
docker pull <image>
docker images
docker rmi <image>
docker build -t <name> .
```

### **Docker Compose**

```
docker compose up
docker compose down
docker compose up --build
```

---

# ✅ **7. System Monitoring (Linux / DevOps)**

```
df -h
du -sh *
free -m
uptime
journalctl -xe
systemctl status <service>
```

---

# ✅ **8. Networking & API Testing**

```
curl <url>
curl -X POST -H "Content-Type: application/json" -d '{}' <url>
ping 8.8.8.8
nslookup google.com
```

---

# ✅ **9. Python (Basics for Professionals)**

```
python file.py
pip install <package>
pip uninstall <package>
pip freeze > requirements.txt
```

---


