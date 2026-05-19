# Script Vietnamese Senior Health Skill

Skill chuyên dụng tạo kịch bản voice-over tiếng Việt cho kênh YouTube sức khỏe người 50-75 tuổi (phong cách 100 Tuổi Khoẻ Mạnh, Sống Khỏe Mỗi Ngày).

## File chính

- **SKILL.md** — Skill definition đầy đủ với YAML frontmatter

## Trigger

Skill kích hoạt khi user gõ:
- "viết script Việt"
- "Việt hóa kịch bản"
- "kịch bản sức khỏe"
- "voice-over tiếng Việt"
- "remake kênh Việt"
- Và các từ khóa liên quan tới senior health Vietnam

## Input types (hỗ trợ kết hợp)

- **A**: Script tiếng Anh nguồn → Việt hóa
- **B**: Script tiếng Việt khác → Remake góc mới
- **C**: Chỉ topic / tiêu đề → Viết từ đầu
- **A+B+C**: Kết hợp tinh hoa từ cả 3

## Output

Văn xuôi tiếng Việt thuần, 100% sạch (không ngoặc vuông, không markers), copy thẳng vào ElevenLabs / Vbee / FPT.AI / HeyGen.

## 7-Phase Workflow

0. Input Analysis
1. Topic Lock
2. Research Bank
3. Outline P-E-S-T-B
4. Draft theo khúc
5. Humanization Việt
6. Final Clean Pass

## Kết thúc

Mọi run kết thúc chính xác bằng:
```
✅ KỊCH BẢN HOÀN THÀNH. BẢY GIAI ĐOẠN ĐÃ XONG. SẴN SÀNG GHI ÂM.
```

## Related files (trong cùng repo)

- `PROMPT_VIET_HOA_KICH_BAN_YOUTUBE_SUC_KHOE.md` — Master prompt gốc
- `COMPETITOR_ANALYSIS_100TUOIKHOEMANH.md` — Phân tích đối thủ + 30 title ideas
- `CHARACTER_DOCTOR_PROMPTS.md` — Tạo nhân vật bác sĩ AI
- `RESOURCES_TOOLS_LIST.md` — Tool stack đầy đủ
