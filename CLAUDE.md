# my-site

เว็บไซต์ static ที่ deploy ขึ้น GitHub Pages

- **Repo:** https://github.com/earth-38/my-site
- **เว็บไซต์จริง (live):** https://earth-38.github.io/my-site/
- **Deploy จาก:** branch `main` โฟลเดอร์ root (มี `index.html` เป็นหน้าแรก)

---

## Workflow: คำสั่ง "update: ..."

เมื่อผู้ใช้พิมพ์ข้อความขึ้นต้นด้วย **`update:`** (เช่น `update: เปลี่ยนหัวข้อเป็น My Portfolio`)
ให้ทำตามลำดับนี้ทุกครั้ง:

1. **แก้ไฟล์** ตามที่ผู้ใช้สั่ง
2. `git add -A`
3. `git commit -m "<สรุปสั้น ๆ ว่าทำอะไร>"`
4. `git push`
5. **ยืนยันกับผู้ใช้** ว่า push สำเร็จ + เตือนว่าเว็บจะอัปเดตใน ~1–2 นาที พร้อมลิงก์ https://earth-38.github.io/my-site/

### กฎสำคัญ
- ถ้าคำสั่งไหน **error** → หยุดทันที เอาข้อความ error มาอธิบายเป็นภาษาไทยง่าย ๆ **อย่าเดาแก้เอง**
- ผู้ใช้เป็นดีไซเนอร์ เขียนโค้ดได้นิดหน่อย → อธิบายสั้น กระชับ เป็นภาษาไทย
- commit message เขียนเป็นภาษาอังกฤษสั้น ๆ บอกว่าทำอะไร

---

## หมายเหตุสภาพแวดล้อม
- `gh` (GitHub CLI) ติดตั้งผ่าน Homebrew — ถ้า shell หา `brew`/`gh` ไม่เจอ ให้รัน
  `eval "$(/opt/homebrew/bin/brew shellenv)"` ก่อน
- login GitHub ในชื่อบัญชี `earth-38`
