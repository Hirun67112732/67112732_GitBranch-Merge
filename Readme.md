ชื่อ: หิรัญ สุขสมรัตน์
รหัส: 67112732

อธิบายการดำเนินการ
1. สร้าง Repo ใหม่ 
    - สร้าง Repo ใหม่ใน Github
    ![alt text](/image/1.png)
    - Clone มาลงใน Vs code แล้วนำไฟล์ Repo ใหม่ในเว็บ Github เข้า VS Code
    ![alt text](/image/2.png)

2. นำงานจาก test001 มาเป็น ตัวหลัก ใน branch main
    - คัดลอกไฟล์จาก `Test001` (Readme.md, test.txt, test.py) ไปใส่ 67112732_GitBranch-Merge
    ![alt text](/image/3.png)
    
    - Commit และ Push ไปยัง branch `main` ใส่คำสั่งใน Terminal
    ![alt text](/image/4.png)
    ![alt text](/image/5.png)

3. เพิ่ม branch FromTest2  และเพิ่ม folder ย่อย Test002 แล้วนำข้อมูลจากงาน Test002 มาวาง
    - เปิด Source Control
    ![alt text](/image/6.png)
    - กดเลือก branch → เลือก Create new branch ![alt text](/image/7.png)
    ![alt text](/image/8.png)
    - เพิ่มโฟลเดอร์ `Test002` และวางไฟล์จากงาน Test002 (`Readme.md`, `myfunc.py`, `main.py`)
    ![alt text](/image/9.png)
    - Commit และ Push ไปที่ GitHub  
    ![alt text](/image/10.png)

4. เพิ่ม ไฟล์ myfunc2.py  ที่มีฟังก์ชันการดำเนินการ ลบ เลข 2 ชุด
    - อยู่ในโฟลเดอร์ `Test002`
    - เขียนฟังก์ชันการลบเลข 2 ชุด
    ![alt text](/image/11.png)

5. ทำการ merge Test002 เข้าไปที่ main
    - ใช้วิธีการ merge ด้วย Terminal โดยใช้ Git Command
    ![alt text](/image/12.png)