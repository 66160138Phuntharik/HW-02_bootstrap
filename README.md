# HW-02_bootstrap
# คำสั่ง git ที่ใช้ในการทำงาน
- git checkout -b development 
- git add .
- git commit -m "โครงสร้างต่อจากโปรเจคเดิม"
- git checkout -b indexPage
- git add .
- git commit -m "เพิ่ม bootstrap ใน index"
- git add index.html
- git commit -m "หน้าหลัก home"
- git checkout -b placesPage
- git add places.html
- git commit -m "หน้าสถานที่ท่องเที่ยว"
- git checkout -b contactPage
- git add contact.html
- git commit -m "หน้าช่องทางการติดต่อ"
- git add css/style.css
- git commit -m "ออกแบบส่วน css/style.css"
- git add README.md
- git commit -m "เพิ่มส่วนคำสั่ง git ที่ใช้ในการทำงาน"
- git checkout development 
- git merge indexPage
- git merge placesPage
- git merge contactPage
- git push origin development 