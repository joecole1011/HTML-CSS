# HTML-CSS
HTML CSS CTF02 (Knowledge): Coding the Future รุ่นที่ 2


สร้าง
git init

นำเข้าไฟล์ทั้งหมด
git add . 


นำไฟล์เตรียมขึ้น Server
git commit -m "first commit"


ถามสถานะในการเชื่อมต่อ
git remote

เชื่อมต่อกับ Server
git remote add origin https://github.com/joecole1011/Bootstrap.git

นำไฟล์ขี้น Server ทั้งหมด

git push origin master

นำไฟล์จากServer ลงเครื่อง
git pull

<!--
initial commit

git push -u origin main

git branch -M main
-->

============
Git ขั้นพื้นฐาน
Git คือ Version Control ที่ใช้ในการพัฒนา Software ช่วยเก็บรักษาไฟล์ สามารถติดตามการเปลี่ยนแปลงของไฟล์ได้ รวมทั้งสามารถย้อนกลับไปยัง Version ต่างๆได้

การใช้งานคำสั่งพื้นฐาน Git ที่ใช้งานกันบ่อยๆ บน Terminal

git status คือ แสดงไฟล์ที่มีการเปลี่ยนแปลง หรือยังต้องการ add หรือ commit
git add คือ การเพิ่มไฟล์เป็นสถานะ stage
git reset คือ การ unstage ไฟล์ที่เราเคย stage
git commit คือการ commit ไฟล์ที่ stage โดยมักจะใช้  git commit -m เพื่อเพิ่มข้อความในสิ่งที่ทำไป
git log คือการดุประวัติที่เคย commit ไว้
git pull คือการ remote ไฟล์มายัง local โดยคำสั่ง git pull นั้นจะทำการ git fetch และ git merge ไปด้วย โดยเราจะมักเห็นใช้ git pull –rebase เพื่อทำการเปลี่ยนฐานแทนการ merge
git merge (branch) คือการรวม branch ที่เจาะจงมายัง local
git fetch คือ การตรวจสอบไฟล์ภายใน local และ remote ว่าตรงกันหรือไม่
git push คือ ส่งการเปลี่ยนแปลงของไฟล์ไปบน remote repository
git stash คือ การเก็บซ่อนการเปลี่ยนแปลงทั้งหมดไว้ทั้งหมด และสามารถนำกลับมาโดยใช้ git stash pop
git checkout (branch) คือ การเปลี่ยน branch
git clone (url) คือการ คัดลอกโปรเจคจาก remote มายัง local

============
มาเรียนรู้ Git แบบง่ายๆกันเถอะ
https://blog.nextzy.me/%E0%B8%A1%E0%B8%B2%E0%B9%80%E0%B8%A3%E0%B8%B5%E0%B8%A2%E0%B8%99%E0%B8%A3%E0%B8%B9%E0%B9%89-git-%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B8%87%E0%B9%88%E0%B8%B2%E0%B8%A2%E0%B9%86%E0%B8%81%E0%B8%B1%E0%B8%99%E0%B9%80%E0%B8%96%E0%B8%AD%E0%B8%B0-427398e62f82
===========
Git คืออะไร … Git is your friend
https://medium.com/@pakin/git-%E0%B8%84%E0%B8%B7%E0%B8%AD%E0%B8%AD%E0%B8%B0%E0%B9%84%E0%B8%A3-git-is-your-friend-c609c5f8efea
==========
=======================================
==========
VSCode
ยกบรรทัดขึ้นทั้งแถว
Ctrl+Shift+K

จัด Format
Alt+Shift+F

จัดแท็บแถว
Ctrl+[ 
Ctrl+]
