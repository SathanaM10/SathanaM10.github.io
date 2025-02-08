## OWASP Application Security Verification Standard 
__V12.5.1 : File Download Security Configuration__

- Verify that the web tier is configured to serve only files with specific file
extensions to prevent unintentional information and source code leakage.
For example, backup files (e.g. .bak), temporary working files (e.g. .swp),
compressed files (.zip, .tar.gz, etc) and other extensions commonly used by
editors should be blocked unless required.

- 🤖 ChatGPT :
ตรวจสอบให้แน่ใจว่าเว็บเซิร์ฟเวอร์ถูกกำหนดค่าให้ให้บริการเฉพาะไฟล์ที่มีนามสกุลที่กำหนดเท่านั้น เพื่อป้องกันการรั่วไหลของข้อมูลและซอร์สโค้ดโดยไม่ตั้งใจ ตัวอย่างเช่น ไฟล์สำรอง (เช่น .bak), ไฟล์ชั่วคราวจากการทำงาน (เช่น .swp), ไฟล์บีบอัด (.zip, .tar.gz ฯลฯ) และไฟล์นามสกุลอื่น ๆ ที่มักใช้ในโปรแกรมแก้ไขโค้ด ควรถูกบล็อก เว้นแต่มีความจำเป็นต้องใช้งาน


- 🤖 Gemini :
ตรวจสอบว่าเว็บเทียร์ (web tier) ได้รับการกำหนดค่าให้ให้บริการเฉพาะไฟล์ที่มีนามสกุลไฟล์ที่ระบุ เพื่อป้องกันการรั่วไหลของข้อมูลและซอร์สโค้ดโดยไม่ได้ตั้งใจ ตัวอย่างเช่น ไฟล์สำรอง (เช่น .bak), ไฟล์งานชั่วคราว (เช่น .swp), ไฟล์บีบอัด (.zip, .tar.gz ฯลฯ) และนามสกุลอื่นๆ ที่มักใช้โดยโปรแกรมแก้ไข ควรถูกบล็อก เว้นแต่จำเป็น


- 💡 My Summary :
เว็บเซิร์ฟเวอร์ควรถูกตั้งค่าให้ให้บริการเฉพาะไฟล์ที่มีนามสกุลที่กำหนดไว้เท่านั้น เพื่อป้องกันการรั่วไหลของข้อมูลที่ไม่ตั้งใจและป้องกันการเปิดเผยซอร์สโค้ดที่อาจถูกนำไปใช้ในทางที่ไม่ปลอดภัย ไฟล์บางประเภท เช่น ไฟล์สำรอง (.bak), ไฟล์ชั่วคราว (.swp), และ ไฟล์บีบอัด (.zip, .tar.gz) ควรถูกบล็อก เพราะอาจมีข้อมูลสำคัญที่ไม่ควรเข้าถึงหรือดาวน์โหลดได้โดยบุคคลทั่วไป 


🫂 BUDDY : [Thatthep Satharanaporn (security-requirement)](https://bastackle.github.io/security-requirement)