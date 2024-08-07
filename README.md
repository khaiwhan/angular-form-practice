# angular-form-practice

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/khaiwhan/angular-form-practice)

# Practice

1. จงสร้าง formGroup และ formControlName จาก html form ที่ไฟล์ app.component.html
2. เงื่อนไขมีดังนี้
    1. ที่ id ต้องเป็นตัวเลขเท่านั้นและใส่ค่าตั้งแต่ 0-9 ไม่เกิน 99999
    2. ที่ firstname ต้องเป็นตัวอักษรภาษาอังกฤษเท่านั้นและมีตัวอักษรไม่เกิน 50 ตัวอักษร
    3. ที่ lastname ต้องเป็นตัวอักษรภาษาอังกฤษเท่านั้นและมีตัวอักษรไม่เกิน 50 ตัวอักษร
    4. ที่ Jobtitle จะต้องมีข้อความ Default เป็นคำว่า I'm frontend developer
3. เมื่อกดปุ่ม submit จะต้องมีการ validate form หาก form ผิดจะ alter ว่า Form Invalid Please Check Data
4. หาก Form ถูกต้องจะต้อง log ข้อมูลที่กรอก และ alert ว่า Submit Successfully