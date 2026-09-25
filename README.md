#ขั้นตอนการส่งไฟล์ขึ้น GitHub
cd ~/Documents/Calculate-salary
git add .
git commit -m "add index.html"
#เปิดหน้าเว็บ GitHub กดสร้าง Repository ใหม่ ตั้งชื่อว่า Calculate-salary แล้วคัดลอกลิงก์มา
git remote add origin ลิงก์ที่คัดลอกมา
git push -u origin main
=============================
สรุปสั้นๆ ให้จำง่าย:
git push = ดันโค้ดจาก เครื่อง ➡️ ขึ้นเว็บ (ส่งงาน)
git pull = ดึงโค้ดจาก เว็บ ➡️ ลงเครื่อง (อัปเดตงาน)

=============================

git clone https://github.com/athiwus019/pi-test-code.git

git add . (git add test.py)
git commit -m "test auto pull"
git push origin main