---
type: jam-pipeline
version: 0.1
date: [21/07/26]
team: [แกงเขียวหวานไก่ จำกัด]
---
# Pipeline Function Checklist — [แกงเขียวหวานไก่ จำกัด]

> เกมทุกแนวต้องมี pipeline ขั้นต่ำนี้ก่อนถึงจะเรียกว่า "เล่นได้" — เติมชื่อผู้รับผิดชอบและติ๊กสถานะระหว่างลงมือทำจริง เพิ่มแถวได้ถ้าเกมของทีมต้องการ module อื่น

## Must-Have (ต้องมีก่อน Hour 24 — Playable Build)

| Module (ตาม MonoGame Game Loop)             | หน้าที่                                                            | สถานะ     | ผู้รับผิดชอบ                     |
| ---------------------------------------------- | ------------------------------------------------------------------------- | -------------- | -------------------------------------------- |
| `GameStateManager`                           | สลับ state (Menu / Playing / Pause / GameOver)                        | 🔲 Not Started | [682110151]                                  |
| `InputManager`                               | รับ input keyboard/gamepad แบบรวมศูนย์                      | 🔲 Not Started | [682110151]                                  |
| Core `Update()` logic ของกลไกหลัก | logic ของ core mechanic 1 อย่างที่เป็นหัวใจเกม     | 🔲 Not Started | [682110151]                                  |
| Collision / interaction พื้นฐาน         | ตรวจชน/ตรวจ trigger ระหว่าง entity                       | 🔲 Not Started | [682110151]                                  |
| `SpriteBatch` render + camera/viewport       | วาดผ่าน `GraphicsDevice.Viewport` (ห้าม hardcode resolution) | 🔲 Not Started | [682110109, 682110135, 682110155]            |
| Win / Lose condition                           | เงื่อนไขจบเกม/จบด่าน                                   | 🔲 Not Started | [682110109, 682110151]                       |
| Content pipeline (MGCB)                        | โหลด asset ผ่าน `Content.Load<T>()` เท่านั้น            | 🔲 Not Started | [682110135, 682110155]                       |
| [module เพิ่มเติมของเกมนี้]  |                                                                           | 🔲 Not Started | [682110109, 682110135, 682110151, 682110155] |

## Nice-to-Have (ทำถ้าเหลือเวลา — Hour 24–34)

| Module                                | หน้าที่                           | สถานะ     | ผู้รับผิดชอบ |
| ------------------------------------- | ---------------------------------------- | -------------- | ------------------------ |
| `AudioManager` (SFX พื้นฐาน) | เสียงตอบสนอง action หลัก | 🔲 Not Started | [682110135]              |
| UI/HUD (score, timer)                 | แสดงสถานะระหว่างเล่น | 🔲 Not Started | [682110155]              |
| Music / เพลงประกอบ          |                                          | 🔲 Not Started | [682110109]              |
| [feature รองอื่นๆ]            |                                          | 🔲 Not Started | [682110151]              |

## Cut-List (ตัดทิ้งก่อนถ้าเวลาไม่พอ — ห้ามเริ่มก่อน Must-Have เสร็จ)

- ❌ Save/Load
- ❌ Settings menu
- ❌ Leaderboard
- ❌ [feature อื่นที่ทีมตกลงตัดก่อน]

> เมื่อถึง **Feature Freeze (Hour 34)** ทุก module ในตารางนี้ต้องมีสถานะ ✅ Done หรือถูกย้ายไป Cut-List อย่างชัดเจน — ห้ามค้างเป็น 🔲/🟡
