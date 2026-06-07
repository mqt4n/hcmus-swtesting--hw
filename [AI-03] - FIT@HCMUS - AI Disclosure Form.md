**Khoa Công nghệ Thông tin (FIT) – Trường Đại học Khoa học Tự nhiên TP.HCM (HCMUS)**

**CS423 / CSC15003 – Kiểm thử Phần mềm (Tích hợp AI · 2026)**

**CHÍNH SÁCH AI · MẪU BIỂU — 2026 v1.0**

# Mẫu Công Bố Sử Dụng AI

_Đính kèm vào các bài tập có sử dụng AI theo bất kỳ hình thức nào được phép._

_Được điều chỉnh từ Med Kharbach, PhD (2026) — AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0. Bản điều chỉnh này được chuẩn bị cho FIT@HCMUS – CS423 / CSC15003 Kiểm thử Phần mềm._

## 1. Thông Tin Môn Học & Sinh Viên

| Trường                         | Giá trị                                           |
| :----------------------------- | :------------------------------------------------ |
| **Môn học:**                   | CS423 / CSC15003 – Kiểm thử Phần mềm              |
| **Mã bài tập:**                | HW01-AI                                           |
| **Tên bài tập:**               | QA/QC Jobs · 20 Defects · Test a Physical Product |
| **Danh mục Sử dụng AI (1–5):** | Danh mục\_\_\_                                    |
| **Công cụ AI đã sử dụng:**     | Gemini, Antigravity IDE with AI Agent             |
| **Ngày:**                      | 08/06/2026                                        |
| **Họ và tên sinh viên:**       | MẠCH QUỐC TẤN                                     |
| **Mã số sinh viên:**           | 23127115                                          |

## 2. Câu Hỏi Công Bố

### 1. Công cụ AI đã sử dụng:

1. **Antigravity IDE with AI Agent** — sử dụng cho Req01 (phân tích 14 tin tuyển dụng QA/QC) và Req02 (tổng hợp 30 lỗi phần mềm, format lại sau khi chắt lọc).
2. **Gemini** — sử dụng cho Req03 (thiết kế 15 ca kiểm thử, checklist, test summary report) và Req01/Mindmap (vẽ và chỉnh sửa sơ đồ tư duy QA/QC) và giải thích từng lỗi phần mềm trong Req02.

### 2. Giai đoạn bài tập có sử dụng AI:

- [x] **brainstorming** (ý tưởng) — Đặt câu hỏi gợi ý về các lỗi phần mềm nổi bật và định hướng nghiên cứu thị trường QA/QC.
- [x] **outlining** (lập dàn ý) — AI hỗ trợ thiết lập cấu trúc bảng cho test cases, checklist và test summary report.
- [x] **drafting** (soạn thảo) — AI viết nháp nội dung phân tích JD tuyển dụng (Req01), 30 sự cố phần mềm (Req02) và 15 ca kiểm thử (Req03).
- [ ] **feedback** (phản hồi)
- [x] **revision** (chỉnh sửa) — Yêu cầu AI chỉnh sửa lại sơ đồ tư duy QA/QC theo 6 yêu cầu chi tiết.
- [ ] **coding** (lập trình)
- [x] **data analysis** (phân tích dữ liệu) — AI hỗ trợ tổng hợp thông tin, trích lọc dữ liệu kỹ năng từ 14 tin tuyển dụng và phân tích mức độ tác động của AI.
- [x] **visual design** (thiết kế trực quan) — AI vẽ và khởi tạo sơ đồ tư duy QA/QC Role Mindmap ban đầu.
- [ ] **other** (khác) (ghi rõ): \***\*\*\*\*\***\_\_\_\_\***\*\*\*\*\***

### 3. Các prompt hoặc yêu cầu chính đã giao cho AI:

**Prompt 1** — **Antigravity IDE with AI Agent** (17:58 04/06/2026 — Req01 – Job Market):

> "Hiện tại, tôi đã tổng hợp được 14 đường dẫn về các công việc liên quan đến QA/QC ở file QA_QC-Job_Market_2026.md và ngoài ứng với mỗi link theo thứ tự thì tôi đã chụp màn hình lại và để trong img/job/xy với xy là thứ tự của mỗi đường dẫn, tôi muốn bạn hãy truy cập vào mỗi đường dẫn và lấy ra cho tôi các thông tin sau: mô tả ngắn về bài tuyển dụng, ngày đăng, yêu cầu kĩ năng AI/LLM, hình ảnh minh họa, phân tích tác động AI 1–2 câu. Cuối cùng rút ra kết luận về thị trường QA/QC..."

**Prompt 2** — **Antigravity IDE with AI Agent** (20:06 04/06/2026 — Req02 – 20 Defects):

> "Bạn hãy tìm 30 lỗi phần mềm được công bố từ năm 2022 đến 2026. Với điều kiện có lớn hơn hoặc bằng 10 lỗi liên quan đến AI/LLM (ảo giác - hallucination, tiêm mã độc vào prompt - prompt injection, thiên kiến - bias). Mỗi lỗi cần có: link nguồn, mô tả, mức độ nghiêm trọng, hậu quả, giải pháp. Câu trả lời được ghi vào trong file Software_Defect_22_26.md, văn phong của một bài báo cáo nghiêm túc."

**Prompt 3** — **Gemini** (20:50 06/06/2026 — Req03 – Test Cases):

> "Thiết kế 15 ca kiểm thử cho thiết bị gia dụng là quạt máy không có tính năng hẹn giờ và tăng chiều cao (Mục tiêu / Đầu vào / Các bước / Kết quả mong đợi / Kết quả thực tế / Phán quyết). Thêm giúp tôi cả checklist và test sumary report template dạng bảng."

**Prompt 4** — **Gemini** (02:16 08/06/2026 — Mindmap QA/QC):

> "hãy vẽ cho tôi QA/QC role mindmap"

_Xem toàn bộ lịch sử prompt tại `prompt_log.md` (Phụ lục A)._

### 4. Các phần cụ thể trong bài mà AI đã đóng góp:

- **Req01** _(Antigravity IDE with AI Agent)_ – AI tạo ra bản nháp phân tích 14 tin tuyển dụng (mô tả, ngày đăng, kết luận AI/LLM, tác động AI); Em đã xác minh lại toàn bộ 14 JD, sửa 3 kết luận AI/LLM sai, hiệu chỉnh ngày đăng theo ảnh chụp màn hình, viết lại phần tác động AI bám sát JD.
- **Req02** _(Antigravity IDE with AI Agent + Gemini)_ – Antigravity IDE with AI Agent tạo ra bản nháp 30 lỗi; Gemini giải thích chi tiết từng lỗi; Em đã xác minh link nguồn, chắt lọc xuống 20 lỗi, sửa mức độ nghiêm trọng, tự viết toàn bộ phần "Đính chính" (20 mục).
- **Req03** _(Gemini)_ – AI tạo ra TC01–TC15 và template checklist/test summary; Em thực thi toàn bộ trên thiết bị thực, ghi lại kết quả thực tế, tự thiết kế TC16–TC19 (edge case về lồng quạt mà AI bỏ sót), quay video, log lỗi lên GitHub Issues.
- **Mindmap** _(Gemini)_ – AI tạo ra infographic QA/QC ban đầu; Em phân tích và chỉ ra 8 lỗi ISTQB, yêu cầu AI sửa lại theo danh sách cụ thể.
- **AI KHÔNG đóng góp vào:** ảnh chụp thiết bị, ảnh chụp tài khoản LinkedIn/ITviec, video thực thi, prompt logs, phần "Đính chính" trong Req02, phần AI Critique và Mandatory Disclosure trong báo cáo chính.

### 5. Cách em xem xét, chỉnh sửa hoặc xác minh kết quả đầu ra của AI:

- Em đã tra cứu trên Internet, xem các trang uy tín để xác thực thông tin và chỉnh sửa khi cần thiết.

### 6. Trích Dẫn

Google. (2026). Gemini (Large language model). https://gemini.google.com

Antigravity. (2026). Antigravity IDE with AI Agent (AI coding assistant). https://antigravity.google/product/antigravity-ide

## 3. Cam Kết Trung Thực

_Bằng cách ký tên dưới đây, em xác nhận rằng thông tin công bố ở trên là chính xác và đầy đủ. Em hiểu rằng việc không công bố hoặc công bố sai về việc sử dụng AI được coi là vi phạm học thuật và có thể dẫn đến điểm 0 cho bài tập và bị chuyển lên xử lý kỷ luật._

## Ký Xác Nhận

| Họ và tên sinh viên (in hoa): | MẠCH QUỐC TẤN                                                                                            |
| :---------------------------- | :------------------------------------------------------------------------------------------------------- |
| **Mã số sinh viên:**          | 23127115                                                                                                 |
| **Lớp / Khóa:**               | 23KTPM3                                                                                                  |
| **Môn học:**                  | CS423 / CSC15003 – Kiểm thử Phần mềm                                                                     |
| **Giảng viên:**               | TS. Lâm Quang Vũ, TS. Trần Duy Hoàng, ThS. Trần Thị Bích Hạnh, ThS. Hồ Tuấn Thanh, ThS. Trương Phước Lộc |
| **Ngày:**                     | 08/06/2026                                                                                               |
| **Chữ ký:**                   | Mạch Quốc Tấn                                                                                            |

## Tài Liệu Tham Khảo

- Kharbach, M. (2026). AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0.
- ISTQB Foundation Level Syllabus (phiên bản mới nhất).
- Hardman, P. (2025). A Post-AI Learning Taxonomy.
- Fuster Rabella, M. (2025). OECD Education Working Paper No. 338.
- Perkins, M., Roe, J., & Furze, L. (2025). AI Assessment Scale.
- Anthropic (2025). Building reliable AI test agents — engineering blog.
- Tài liệu DeepEval & Promptfoo — framework kiểm thử cho hệ thống LLM.
