# Linux Practice Lab - Instructor M.Khalid Khan ki Taraf se Create Kiya Gaya

> May 20th, 2026 - Day 20

Beginners aur Intermediate learners ke liye ek complete hands-on Linux practice environment.

Yeh project automatically files, directories, logs, scripts, CSV data aur practice resources create karta hai taake aap **100+ Linux commands** seekh aur practice kar sakein.

---

# Features

✅ Complete Linux practice environment create karta hai  
✅ Sample files aur directories generate karta hai  
✅ CSV aur log files create karta hai  
✅ Shell scripting examples include karta hai  
✅ Permissions practice setup provide karta hai  
✅ Compression practice data provide karta hai  
✅ Linux commands seekhne wale beginners ke liye bohat useful hai

---

# 📂 Project Structure

```bash
linux-practice/
│
├── files/
├── logs/
├── scripts/
├── backup/
├── data/
├── users/
├── temp/
├── projects/
└── compress_me/
```

---

# ⚙️ Requirements

- Linux OS (Ubuntu, CentOS, Fedora, Kali, WSL, etc.)
- Bash shell

---

# 🚀 Setup

## 1️⃣ Repository Clone Karein

```bash
git clone https://github.com/yourusername/linux-practice-lab.git
```

---

## 2️⃣ Project Directory ke Andar Jayein

```bash
cd linux-practice-lab
```

---

## 3️⃣ Script ko Executable Banayein

```bash
chmod +x linux-practice.sh
```

---

## 4️⃣ Script Run Karein

```bash
./linux-practice.sh
```

YA

```bash
bash linux-practice.sh
```

---

# 📁 Yeh Script Kya Create Karti Hai

## Files

- employees.txt
- fruits.txt
- story.txt
- numbers.txt
- secure.txt
- bigfile.img

---

## CSV Files

- students.csv

---

## Logs

- system.log

---

## Scripts

- hello.sh

---

## Directories

- backup/
- projects/
- temp/
- compress_me/

---

# 🧪 Linux Commands Jo Aap Practice Kar Sakte Hain

# Navigation Commands

```bash
pwd
whoami
date
ls
ls -ltr
clear
cd files
cd ..
```

---

# File Management (Create aur Delete)

```bash
touch files/test.txt

rm files/test.txt

mkdir testdir

rmdir testdir
```

---

# Copy / Move / Rename

```bash
cp files/story.txt backup/

mv files/story.txt files/newstory.txt

mv files/newstory.txt files/story.txt
```

---

# File Viewing

```bash
cat files/story.txt

less files/story.txt

more files/story.txt

head -3 files/story.txt

tail -2 files/story.txt
```

---

# Search Commands

```bash
grep "Linux" files/story.txt

egrep "ERROR|WARNING" logs/system.log

find ~/linux-practice -name "*.txt"
```

---

# Sorting aur Unique

```bash
sort files/fruits.txt

sort files/fruits.txt | uniq
```

---

# Lines Count Karna

```bash
wc -l files/fruits.txt
```

---

# Shuffle Practice

```bash
shuf files/fruits.txt
```

---

# File Split Karna

```bash
split -l 5 files/numbers.txt split_
```

---

# Files Compare Karna

```bash
cp files/story.txt files/story2.txt

cmp files/story.txt files/story2.txt

diff files/story.txt files/story2.txt
```

---

# Files Find Karna

```bash
find ~/linux-practice -name "*.txt"
```

---

# AWK Practice

Second column print karne ke liye:

```bash
awk -F "," '{print $2}' data/students.csv
```

---

# CUT Practice

```bash
cut -c1-5 files/story.txt
```

---

# SED Practice

Line 2 print karne ke liye:

```bash
sed -n '2p' files/story.txt
```

Word replace karne ke liye:

```bash
sed 's/Linux/UNIX/g' files/story.txt
```

---

# TR Practice

Lowercase ko uppercase mein convert karna:

```bash
tr '[:lower:]' '[:upper:]' < files/story.txt
```

---

# FOLD Practice

```bash
echo "ABCDEFGHIJK" | fold -w1
```

---

# Compression Practice

## gzip

```bash
gzip files/story.txt

gunzip files/story.txt.gz
```

---

## tar

```bash
tar -czf backup.tar.gz compress_me/

tar -xzf backup.tar.gz
```

---

## zip

```bash
zip files.zip files/fruits.txt files/story.txt

unzip -l files.zip
```

---

# Process Practice

Background process run karna:

```bash
sleep 300 &
```

Jobs check karna:

```bash
jobs
```

Foreground / Background:

```bash
bg

fg
```

---

# Process Kill Karna

```bash
ps -ef | grep sleep

pkill sleep
```

---

# System Information

```bash
hostname

uname -a

lscpu

free -h

df -h

du -sh ~/linux-practice
```

---

# Networking Practice

```bash
ping google.com

curl http://numbersapi.com/random

wget https://example.com
```

---

# Environment Variables

```bash
export MYNAME="Khalid"

echo $MYNAME

printenv
```

---

# Alias Practice

```bash
alias ll='ls -ltr'

ll
```

---

# Scheduling Practice

```bash
crontab -e
```

Example cron:

```text
* * * * * echo "Hello" >> ~/linux-practice/logs/cron.log
```

---

# User Management

```bash
sudo useradd testuser

sudo passwd testuser

id testuser

sudo userdel testuser
```

---

# Permissions

```bash
chmod 755 files/story.txt

chown $USER files/story.txt

chgrp $USER files/story.txt
```

---

# 🎯 Learning Goals

Yeh project aapko seekhane mein madad karega:

- Linux terminal basics
- File operations
- Directory management
- Text processing
- Shell scripting
- Permissions
- Compression tools
- Networking basics
- Process management

---

# 📚 Recommended Practice Order

Neeche diye gaye order mein practice karein:

1. Navigation Commands
2. File Management
3. Text Processing
4. Search Commands
5. Compression
6. Permissions
7. Process Management
8. Networking
9. Automation
10. User Management

---

# 🐧 Happy Learning Linux!

Rozana practice karein aur commands ke saath experiment karein taake aap Linux administration aur shell scripting mein comfortable ho sakein.

---