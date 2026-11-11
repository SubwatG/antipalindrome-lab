# Antipalindrome Lab — ห้องทดลองการนับจำนวนแอนติพาลินโดรม

สื่อประกอบโครงงานวิจัยระดับปริญญาตรี ภาควิชาวิทยาการคำนวณและเทคโนโลยีดิจิทัล คณะศิลปศาสตร์และวิทยาศาสตร์ มหาวิทยาลัยเกษตรศาสตร์ วิทยาเขตกำแพงแสน

## เริ่มตรงนี้

| ไฟล์ | สำหรับ |
|---|---|
| [`notebooks/student-lab.ipynb`](notebooks/student-lab.ipynb) | ห้องทดลอง จูเลีย สำหรับเขียนสูตรของตัวเองแล้วทดสอบ |
| [`docs/project-brief-for-student.pdf`](docs/project-brief-for-student.pdf) | ขอบเขตโครงงาน ลำดับการอ่าน และคำถามวิจัย |
| [`papers/README.md`](papers/README.md) | รายการงานวิจัยตั้งต้นพร้อมลิงก์ |

## เปิด notebook บน Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SubwatG/antipalindrome-lab/blob/main/notebooks/student-lab.ipynb)

หรือเปิดด้วยตนเอง

1. ไปที่ <https://colab.research.google.com>
2. `File > Open notebook` → แท็บ **GitHub** → ใส่ `SubwatG/antipalindrome-lab`
3. เลือก `notebooks/student-lab.ipynb`
4. เมนู `Runtime > Change runtime type` → ช่อง *Runtime type* เลือก **Julia** → `Save`

Colab มีจูเลียติดตั้งมาให้แล้ว ไม่ต้องติดตั้งอะไรเพิ่ม

## notebook มีอะไรให้

- นิยามของพาลินโดรมและแอนติพาลินโดรมชนิด 0, 1, 2
- ตัวนับแบบตรงไปตรงมา `count_brute` ที่เชื่อถือได้
- ตัวทดสอบอัตโนมัติ `run_selftest` ที่เทียบสูตรของเรากับ `count_brute`

**สิ่งที่ยังไม่มี** คือสูตร หน้าที่ของโครงงานคือคิดสูตรเองแล้วเอามาทดสอบกับตัวนับนี้

## หมายเหตุเรื่องลิขสิทธิ์

repo นี้ไม่เก็บไฟล์ PDF ของงานวิจัยตั้งต้น ใช้การอ้างอิงและลิงก์ไปยังแหล่งเผยแพร่เดิมแทน
