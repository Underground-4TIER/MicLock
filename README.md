# MicLock — update channel

This repository is where MicLock's **«เช็คอัปเดต»** (check for updates) button looks for new versions.

* `update.json` — latest version, download address, sha256 and size
* `releases/<version>/MicLock.exe` — the program itself

MicLock only installs a file whose sha256 matches `update.json` exactly, over HTTPS.
To install MicLock for the first time, use the setup package shared by the author —
it is not published here.

---

ที่เก็บนี้คือที่ที่ปุ่ม «เช็คอัปเดต» ใน MicLock มาดูว่ามีเวอร์ชันใหม่ไหม
โปรแกรมจะติดตั้งเฉพาะไฟล์ที่ลายเซ็น sha256 ตรงกับ `update.json` เป๊ะเท่านั้น
ลงครั้งแรกให้ใช้ตัวติดตั้งที่เจ้าของแจก (ไม่ได้อยู่ในที่เก็บนี้)
