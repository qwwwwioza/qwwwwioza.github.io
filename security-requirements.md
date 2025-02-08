<center><h1>**Input Validation**</h1></center>  

**Definition by [OWASP](https://github.com/OWASP/ASVS/raw/v4.0.3/4.0/OWASP%20Application%20Security%20Verification%20Standard%204.0.3-en.pdf)**

- Verify that URL redirects and forwards only allow destinations which appear
on an allow list, or show a warning when redirecting to potentially untrusted
content.
  
**Chat GPT**

- "ตรวจสอบให้แน่ใจว่าการเปลี่ยนเส้นทาง (redirect) และการส่งต่อ (forward) ของ URL อนุญาตให้ไปยังปลายทางที่อยู่ในรายการที่อนุญาตเท่านั้น หรือแสดงคำเตือนเมื่อเปลี่ยนเส้นทางไปยังเนื้อหาที่อาจไม่น่าเชื่อถือ

**Monica**

- หมายถึงระดับที่ข้อมูลสามารถอธิบายวัตถุหรือเหตุการณ์ใน "โลกจริง" ได้อย่างถูกต้อง ซึ่งเกี่ยวข้องกับความแม่นยำและความถูกต้องของข้อมูลในการสะท้อนสิ่งที่มีอยู่จริงในโลก.

**My summary**

- Accuracy หมายถึง ความถูกต้องและความแม่นยำของข้อมูลในการสะท้อนหรือแสดงผลสิ่งที่มีอยู่จริงในโลกหรือเหตุการณ์ที่เกิดขึ้นจริง โดยไม่มีข้อผิดพลาดหรือการบิดเบือนในข้อมูล

**Sample**

- สมมติว่าข้อมูลที่อยู่ในฐานข้อมูลร้านขายโทรศัพท์มือถือบันทึกว่ามีการขายโทรศัพท์รุ่นหนึ่งในราค 10,000 บาท แต่ราคาจริงคือ 12,000 บาท ข้อมูลนี้มี Accuracy ต่ำ เพราะไม่ตรงกับความเป็นจริง
