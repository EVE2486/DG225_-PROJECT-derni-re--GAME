# Product Backlog

**Version:** 1.0 | **Last Updated:** 2026-09-01

> รวม User Story ทั้งหมดของโปรเจกต์ — ยังไม่ได้แปลว่าต้องทำใน Sprint นี้ทั้งหมด
> โปรเจกต์นี้แบ่งงานตลอดเทอมเป็น **4 Sprint** (Sprint 1-4) — Sprint ไหนหยิบ Story ไปทำ ให้ใส่เลข Sprint นั้น (1-4) ลงคอลัมน์ `Sprint`

## Must Have (MVP)

| # | User Story                                                                                              | Acceptance Criteria                                                                                                                       | Estimate (SP) | Sprint |
| - | ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------ |
| 1 | As a player, I want to jump, so that I can avoid obstacles                                              | กดปุ่มกระโดดแล้วตัวละครลอยขึ้นแล้วตกลงพื้นเดิม ไม่ทะลุพื้น                       | 5             | 1      |
| 2 | As a monster, I want to attack, so that I can hurt the player                                           | ให้มอนสเตอร์โจมตีตัวละคร จะได้ทำความเสียหายกับตัวละคร                                 | 8             | 2      |
| 3 | As a items, I want to pick up, so that I can use their ability.                                         | กดใช้ไอเท็มแล้วตัวละครจะสามารถใช้ความสามารถของไอเท็มนั้นได้                    | 4             | 2      |
| 4 | As a any object, I want to interact with them, so that I can get a hint.                               | กดที่วัตถุเพื่อสื่อสารหรือตอบโต้ และปลดล็อคเนื้อเรื่อง                               | 2             | 3      |
| 5 | As a player, I want to scroll inventory tab, so that I can select any items in inventory tab            | เลื่อนเมาส์กลางเพื่อเลือกใช้ไอเท็มที่ต้องการ                                                  | 4             | 3      |
| 6 | As an player, I want more level and monster, so that I came across a new challenge and more aesthetic | โทนสีและธีมของเกมไปในทิศทางเดียวกัน รวมถึงด่านที่ยังคงเน้นการไขปริศนา | 6             | 2      |
| 7 | As a player, I want to see more detail of each items                                                    | โทนสีเข้ากับฉาก ตัวละคร สังเกตได้ง่าย                                                                  | 6             | 2      |
| 8 | As a player, I want to see character move and attack smoothly, realistiic                               | เคลื่อนไหวได้สมูท ลื่นไหล สมจริง                                                                            | 8             | 1      |

## Should Have

| # | User Story                                                                     | Acceptance Criteria                                                | Estimate (SP) | Sprint |
| - | ------------------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------- | ------ |
| 1 | As a player, I want to see my damage, so that I know how close monsters to die | จำนวนตัวเลขแสดงค่าดาเมจในขณะโจมตี | 3             | 3      |

## Nice to Have

| # | User Story                                                                                                                                                           | Acceptance Criteria                                                                                                                                                                                           | Estimate (SP) | Sprint |
| - | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------ |
| 1 | As a designer, I want more level and monster, so that I can create different of level and monster. Such as adding monster skills, changing the monster's appearance | เพิ่มจำนวนเลเวลและความแตกต่างของมอนสเตอร์ เช่น เพิ่มสกิลใหม่ ๆ ให้มอนสเตอร์ ปรับเปลี่ยนรูปลักษณ์มอนสเตอร์ | 3             | —     |

## MoSCoW Legend

- **Must Have** — จำเป็นต่อ core gameplay loop เกมเล่นไม่ได้ถ้าขาด (MVP)
- **Should Have** — เพิ่มคุณภาพเกม แต่เกมเล่นได้โดยไม่มีก็ได้
- **Nice to Have** — ทำถ้ามีเวลาเหลือ

## Links

- [[docs/gdd/00-concept|GDD Concept]]
- [[docs/agile/02-sprint-backlog|Sprint Backlog]]
