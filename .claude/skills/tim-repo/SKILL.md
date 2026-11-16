---
name: tim-repo
description: Tìm repo GitHub bằng TopRepo (toprepo.cuongit.net), trang xếp hạng repo có số sao, sao tăng theo ngày/tuần/tháng, trạng thái phát triển và danh mục. Dùng MẶC ĐỊNH khi An nói "tìm repo", "có repo nào", "có skill nào", "repo nào tốt cho...", "tìm công cụ mã nguồn mở", "repo GitHub về...", hoặc ý tương tự. Ưu tiên trang này trước khi tìm trên GitHub hay web.
---

# Tìm repo qua TopRepo

Nguồn mặc định: **https://toprepo.cuongit.net/vi**. Trang có đánh giá cho từng repo
(sao, tăng 1/7/30 ngày, trạng thái hoạt động), nên luôn quét trang này trước.

## Cách tìm

Dùng `firecrawl_scrape` (formats: markdown, onlyMainContent: true). Không có Firecrawl thì dùng agent `web-fetch`.

1. **Tìm theo từ khóa**: `https://toprepo.cuongit.net/vi?q=<từ khóa tiếng Anh>`
   - Đổi yêu cầu tiếng Việt sang từ khóa tiếng Anh (vd. "hóa đơn" → `invoice`, "vẽ ảnh" → `image`, "bộ nhớ" → `memory`).
   - Kết quả ít hoặc lệch thì thử 2–3 từ khóa khác, gọi song song.
2. **Tìm theo danh mục**: `https://toprepo.cuongit.net/vi/categories/<slug>` (top 20 theo sao),
   hoặc `https://toprepo.cuongit.net/vi?category=<slug>&sort=stars` (đủ danh sách).
   Slug: `coding-agents`, `agent-skills`, `mcp`, `code-review`, `agents`, `llm-models`, `rag-memory`,
   `inference`, `training`, `llmops`, `chat-apps`, `image-gen`, `video-generation`, `video-editing`,
   `avatar-lipsync`, `video-understanding`, `video-enhance`, `computer-vision`, `tts`, `voice-cloning`,
   `speech-recognition`, `music-audio`, `office-docs`, `notes-knowledge`, `translation`, `automation`,
   `desktop-utils`.
3. **Xem chi tiết một repo**: `https://toprepo.cuongit.net/vi/repos/<owner>/<repo>`
   (giấy phép, số fork, tag, người đóng góp, link GitHub).
4. Chỉ khi TopRepo không có kết quả phù hợp mới tìm thêm trên GitHub/web, và nói rõ là nguồn khác.

## Đánh giá khi chọn

- **Trạng thái**: ưu tiên "Đang phát triển (push trong 90 ngày)". Cảnh báo nếu "Ít hoạt động" hoặc "Ngừng phát triển / lưu trữ".
- **Độ hot**: cột "1 ngày / 7 ngày / 30 ngày" (sao tăng). Repo nhiều sao nhưng tăng 0 là đã nguội.
- **Độ phù hợp với An**: dùng được với Claude Code không, có phải skill thật không (hay là app/thư viện), cần GPU không,
  liên quan việc của An (tài chính/chứng khoán, hóa đơn, video whiteboard, đăng bài, tự động hóa).
- Bỏ qua repo prompt jailbreak hoặc đáng ngờ.

## Trả lời

Bằng tiếng Việt, dạng bảng ngắn: `Repo | Sao (tăng/ngày) | Làm gì | Hợp với An ở chỗ`.
Chọn 3–5 repo tốt nhất (không chép cả danh sách), kèm 1 dòng gợi ý nên thử cái nào trước.
Ghi rõ số liệu lấy từ TopRepo ngày nào và chưa kiểm tra trên GitHub (trừ khi đã kiểm tra).
Cuối cùng hỏi An có muốn xem kỹ README/cách cài repo nào không.
