# 🔀 Export & Import รายการ

## Export data รายการทั้งหมด

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

1. กดเมนู กรอกข้อมูลรายการตรวจวัด
2. กดปุ่ม “Export data”

{% hint style="info" %}
_**การ Export data จะเป็นการนำประวัติข้อมูลรายการตรวจวัดทุกรายการที่ได้กรอกลงในระบบทั้งหมดออกมาเป็น ไฟล์ .CSV File,.XLSX File โดยสามารถเลือกช่วงเวลาที่ต้องการนำข้อมูลออกมาได้**_


{% endhint %}



<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

1. เลือกประเภทไฟล์
2. เลือกช่วงเวลา (หากไม่ได้เลือกช่วงเวลาระบบจะ Export ข้อมูลออกมาทั้งหมดทุกช่วงเวลา)
3. กดปุ่ม ส่งออกข้อมูล

#### เมื่อกดปุ่ม ส่งออกข้อมูล แล้วตัวไฟล์ข้อมูลจะถูกอัพโหลดลงเครื่องอัตโนมัติ

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

#### เมื่อ Export data ออกมาแล้วจะแสดงรายการและข้อมูลที่ได้กรอกไว้ทั้งหมดตามระยะเวลาที่ได้เลือกไว้



## Export data บางรายการ

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

1. ค้นหาชื่อรายการที่ต้องการ Export data
2. กดปุ่ม Export data

{% hint style="info" %}
_**การ Export data จะเป็นการนำประวัติข้อมูลรายการตรวจวัดทุกรายการที่ได้กรอกลงในระบบทั้งหมดออกมาเป็น ไฟล์ .CSV File,.XLSX File โดยสามารถเลือกช่วงเวลาที่ต้องการนำข้อมูลออกมาได้**_
{% endhint %}



<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

1. เลือกประเภทไฟล์
2. เลือกช่วงเวลา (หากไม่ได้เลือกช่วงเวลาระบบจะ Export ข้อมูลออกมาทั้งหมดทุกช่วงเวลา)
3. กดปุ่ม “ส่งออกข้อมูล”

#### เมื่อกดปุ่ม “ส่งออกข้อมูล” แล้วตัวไฟล์ข้อมูลจะถูกอัพโหลดลงเครื่องอัตโนมัติ

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

#### เมื่อ Export data ออกมาแล้วจะแสดงรายการและข้อมูลที่ได้กรอกไว้ทั้งหมดตามระยะเวลาและตัวรายการที่ได้เลือกไว้

##

## Import data

### ขั้นตอนการเตรียมข้อมูลสำหรับการ Import data&#x20;

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

1. สร้างรายการตรวจวัดเสร็จเรียบร้อย
2. ค้นหารายการที่ต้องการ Import data&#x20;
3. กดปุ่ม Export data&#x20;



<figure><img src="../.gitbook/assets/Screenshot 2567-02-22 at 15.03.09.png" alt=""><figcaption></figcaption></figure>

#### หลังจาก Export รายการออกมาแล้ว ให้ใส่ข้อมูลให้ครบถ้วนตาม Format ในไฟล์ที่ได้ทำการ Export ออกมา



<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

### **กรุณาอ่านรายละเอียดและกรอกข้อมูลให้ครบถ้วน Import data**

1. คอลัมน์ **ลำดับ** ให้เรียงลำดับตามช่องบรรทัดไปจนถึงรายการสุดท้าย
2. คอลัมน์ **ID** ให้นำ ID ของรายการตรวจวัดนั้นมาใส่ จะเห็นได้ว่าตอนที่ Export รายการออกมาจะมี ID ใส่มาให้แล้ว สามารถ Copy ID ใส่บรรทัดถัดไปได้เลย
3. คอลัมน์ **บริษัท, สาขา, อาคาร, แผนก, ขอบเขต, หมวดหมู่, ชื่อรายการ, EF, หน่วย, วันที่เริ่มต้นกรอกข้อมูล, รูปแบบในการกรอก, ความถี่ในการกรอก** ให้นำข้อมูลของรายการนั้นมาใส่ จะเห็นได้ว่าตอนที่ Export รายการออกมาจะมี ข้อมูลใส่มาให้แล้ว สามารถ Copy ใส่บรรทัดถัดไปได้เลย
4. คอลัมน์ **วันที่ของบันทึกข้อมูล** ให้ใส่วันที่บันทึกข้อมูล เช่น  01/01/2022 00:00:00 โดย Format ต้องตรงตามตัวอย่าง วันที่บันทึกข้อมูลจะต้องเรียงตามเดือนไม่ข้ามเดือนและไม่สามารถใส่ข้อมูลล่วงหน้าได้
5. คอลัมน์ **ค่าที่ใช้จริง** ให้ใส่ปริมาณค่าที่ใช้จริง
6. คอลัมน์ **ค่ารีเซทมิเตอร์** ใช้ในกรณีที่รูปแบบในการกรอกเป็นแบบสะสมเท่านั้น
7. คอลัมน์ จำนวน (พนักงาน), จำนวน (วัน) ใช้กรอกข้อมูลในรายการของ Septic Tank เท่านั้น
8. คอลัมน์ **kg CO2eq/unit** ไม่ต้องใส่ข้อมูล เนื่องจากเป็นช่องที่ระบบคำนวณ kg CO2eq/unit หากต้องการรู้ปริมาณให้ Import ข้อมูล 1 ครั้ง และ Export ข้อมูลออกมาอีกครั้งจะมีปริมาณ kg CO2eq/unit คำนวณออกมาให้
9. คอลัมน์ **ผู้บันทึกข้อมูล** ให้ใส่ชื่อผู้บันทึกข้อมูล โดยต้องมีชื่อในระบบและได้รับมอบหมายงานเท่านั้น
10. คอลัมน์ **วันที่อัปเดตล่าสุด** ให้ใส่วันที่ที่อัปเดตข้อมูล



### ขั้นตอนการ Import data

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

1. เข้าหน้า กรอกข้อมูลรายการตรวจวัด
2. กดปุ่ม Import data
3. เลือก Import data



<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

1. กดปุ่ม ถัดไป



<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

1. คลิ๊กเพื่อเลือกไฟล์ที่เตรียมไว้สำหรับ Import



<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

1. เลือกไฟล์สำหรับ Import



<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

1. กดปุ่ม ถัดไป



<figure><img src="../.gitbook/assets/Screenshot 2567-02-22 at 15.55.21.png" alt=""><figcaption></figcaption></figure>

1. Import data สำเร็จ



### ขั้นตอนการตรวจเช็คข้อมูลหลังจาก Import data

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

1. เข้าหน้ากรอกข้อมูลรายการตรวจวัดที่ได้ Import data สำเร็จ



<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

1. แสดงชื่อรายการถูกต้อง
2. แสดงข้อมูล เดือน, จำนวน ถูกต้อง
3. สถานะจะแสดงเป็นร่างเท่านั้น สามารถแก้ไข หรือ ส่งคำขออนุมัติ

