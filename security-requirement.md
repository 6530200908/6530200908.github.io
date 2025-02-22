# Security Requirement
---
## 14.4.1 HTTP Security Headers

*Details* : Verify that every HTTP response contains a Content-Type header. Also specify a safe character set (e.g., UTF-8, ISO-8859-1) if the content types are text/*, /+xml and application/xml. Content must match with the provided Content-Type header. 

*ChatGPT* : ตรวจสอบให้แน่ใจว่า HTTP response ทุกฉบับมีค่า Content-Type header และระบุชุดอักขระที่ปลอดภัย (เช่น UTF-8, ISO-8859-1) หากประเภทของเนื้อหาเป็น text/*, /+xml หรือ application/xml นอกจากนี้ เนื้อหาต้องตรงกับค่าที่ระบุไว้ใน Content-Type header

*Gemini* : ตรวจสอบว่าการตอบสนอง HTTP ทุกรายการมีส่วนหัว Content-Type และระบุชุดอักขระที่ปลอดภัย (เช่น UTF-8, ISO-8859-1) สำหรับประเภทเนื้อหา text/*, /+xml และ application/xml รวมถึงตรวจสอบว่าเนื้อหาตรงกับส่วนหัว Content-Type ที่ระบุไว้

*สรุปตามความเข้าใจ* : ทุก HTTP response ต้องมี Content-Type Header เพื่อระบุประเภทของข้อมูล และควรกำหนด charset ที่ปลอดภัย 

EX : ถ้าส่ง JSON ควรระบุ Content-Type: application/json; charset=UTF-8 และเนื้อหาต้องเป็น JSON จริง ไม่ใช่ HTML หรือข้อความอื่นๆ

---
6530200339 นายภาณุพงศ์ ทองเชิด [My buddy](https://6530200339.github.io/security-requirement)

6530200908 นายอัมรินทร์ เยาวโรจน์ [My profile](https://6530200908.github.io)
