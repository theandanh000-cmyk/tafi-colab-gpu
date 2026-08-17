# TaFi Video Studio

Web + pipeline chạy **CPU** trên máy thường (không cần GPU):
- Bước 1/2: tải video (yt-dlp/BBDown/lux) + ASR JianYing cloud (fallback bcut) trích phụ đề Trung
- Bước 5: dịch Trung → Việt bằng **xKiro** (Qwen3.8 Max) + QC chính tả (DeepSeek V4 Pro)
- Bước 6: lồng tiếng **CapCut** duy nhất — giọng Nhỏ Ngọt Ngào ×1.30
- Bước 8: render FFmpeg (libx264) + che mờ chữ đè

File đầy đủ: `TaFi-VS-Tool-Web.zip` (giải nén → `cd TaFi-VS-Tool-Web && node server.js` → mở http://localhost:3000).
