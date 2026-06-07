**Khoa Công nghệ Thông tin (FIT) – Trường Đại học Khoa học Tự nhiên TP.HCM (HCMUS)**

**CS423 / CSC15003 – Kiểm thử Phần mềm (Tích hợp AI · 2026)**

**CHÍNH SÁCH AI · MẪU BIỂU — 2026 v1.0**

# Báo Cáo Kiểm Tra AI – Mẫu 5 Phần cho Mỗi Sản Phẩm

_Phụ lục bắt buộc cho mọi bài tập có sử dụng AI (HW#01–HW#06 và Seminar)._

_Được điều chỉnh từ Med Kharbach, PhD (2026) — AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0. Bản điều chỉnh này được chuẩn bị cho FIT@HCMUS – CS423 / CSC15003 Kiểm thử Phần mềm._

## 1. Thông Tin Sinh Viên

| Trường                            | Giá trị                               |
| :-------------------------------- | :------------------------------------ |
| **Họ và tên sinh viên (in hoa):** | MẠCH QUỐC TẤN                         |
| **Mã số sinh viên:**              | 23127115                              |
| **Lớp / Khóa:**                   | 23KTPM3                               |
| **Mã bài tập:**                   | HW01-AI                               |
| **Ngày nộp bài:**                 | 08/06/2026                            |
| **Công cụ AI đã sử dụng:**        | Gemini, Antigravity IDE with AI Agent |
| **Bài nộp có sử dụng AI:**        | Có                                    |

## 2. Hướng Dẫn (đọc trước khi điền)

- Thêm một hàng cho mỗi sản phẩm do AI tạo ra (ca kiểm thử, script, checklist, OpenAPI spec, kế hoạch JMeter, v.v.).
- Dán nguyên văn prompt đã dùng – KHÔNG được diễn đạt lại.
- Dán nguyên văn kết quả đầu ra của AI (hoặc đính kèm ảnh chụp màn hình có nhãn trong báo cáo).
- Gán phán quyết: VALID / INVALID / INCOMPLETE.
- Phần lý giải phải trích dẫn slide bài giảng, mục ISTQB, hoặc RFC kỹ thuật.
- Trình bày sản phẩm đã chỉnh sửa với phần thay đổi được làm nổi bật.
- Các hàng mẫu in nghiêng – thay thế trước khi nộp.

## 3. Báo Cáo Kiểm Tra Chi Tiết – Từng Sản Phẩm

### Sản phẩm #1: Phân tích thị trường việc làm QA/QC

- **Công cụ:** Antigravity IDE with AI Agent
- **Thời gian thực hiện:** 17:58 04/06/2026
- **Prompt đã sử dụng:**
  > "Hiện tại, tôi đã tổng hợp được 14 đường dẫn về các công việc liên quan đến QA/QC ở file QA_QC-Job_Market_2026.md và ngoài ứng với mỗi link theo thứ tự thì tôi đã chụp màn hình lại và để trong img/job/xy với xy là thứ tự của mỗi đường dẫn, tôi muốn bạn hãy truy cập vào mỗi đường dẫn và lấy ra cho tôi các thông tin sau: mô tả ngắn về bài tuyển dụng, ngày đăng, yêu cầu kĩ năng AI/LLM, hình ảnh minh họa, phân tích tác động AI 1–2 câu. Cuối cùng rút ra kết luận về thị trường QA/QC..."
- **Kết quả AI & Minh chứng:**
  - AI tổng hợp được thông tin của cả 14 tin tuyển dụng, bao gồm mô tả công việc, ngày đăng, yêu cầu AI/LLM, ảnh minh họa và phân tích tác động AI cho từng vị trí. Kết luận về thị trường gồm: nhu cầu, mức lương, yêu cầu kỹ năng và định hướng cho sinh viên mới ra trường.
  - **Bản AI gen thô (raw):** [`[Req01]QA_QC-Job_Market_2026.md`](./[Req01]QA_QC-Job_Market_2026.md) tại Commit: [`2c61ec7`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/2c61ec7562d35bed18b8e89dd5818e0907b3e08c) (Bản sơ khởi lúc 19:52 04/06/2026)
  - **Bản hiệu chỉnh (final):** [`[Req01]QA_QC-Job_Market_2026.md`](./[Req01]QA_QC-Job_Market_2026.md) tại Commit: [`3bad089`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/3bad0898e849d80278487f0d7b939e89bc015876)
- **Phán quyết:** `INCOMPLETE`
- **Lý giải đánh giá (ISTQB):** Không có
- **Chỉnh sửa của Sinh viên:** Em đã: (1) đọc lại toàn bộ 14 JD và xác minh kết luận AI/LLM; (2) sửa lại 3 tin từ "Có" thành "Không" do AI suy diễn sai; (3) hiệu chỉnh ngày đăng bằng cách đối chiếu với ảnh chụp màn hình; (4) viết lại phần phân tích tác động AI để bám sát nội dung JD thực tế.

---

### Sản phẩm #2: Danh sách 20 lỗi phần mềm 2022–2026

- **Công cụ:** Antigravity IDE with AI Agent
- **Thời gian thực hiện:** 20:06 04/06/2026
- **Prompt đã sử dụng:**
  > "Bạn hãy tìm 30 lỗi phần mềm được công bố từ năm 2022 đến 2026. Với điều kiện có lớn hơn hoặc bằng 10 lỗi liên quan đến AI/LLM (ảo giác - hallucination, tiêm mã độc vào prompt - prompt injection, thiên kiến - bias). Mỗi lỗi cần có: link nguồn, mô tả, mức độ nghiêm trọng, hậu quả, giải pháp. Câu trả lời được ghi vào trong file Software_Defect_22_26.md, văn phong của một bài báo cáo nghiêm túc."
- **Kết quả AI & Minh chứng:**
  - AI tổng hợp danh sách 30 lỗi phần mềm, gồm các mục: link nguồn, mô tả sự kiện, mức độ nghiêm trọng, hậu quả và giải pháp. Trong đó có các lỗi AI/LLM (ảo giác, prompt injection, bias) và lỗi phần mềm truyền thống.
  - **Bản AI gen thô (raw):** [`[Req02]Software_Defect_22_26.md`](./[Req02]Software_Defect_22_26.md) tại Commit: [`fad3078`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/fad30781132fa87591ac7b38f80c1bd78f2bfa52) (Bản thô gồm 30 lỗi lúc 22:04 04/06/2026)
  - **Bản hiệu chỉnh (final):** [`[Req02]Software_Defect_22_26.md`](./[Req02]Software_Defect_22_26.md) tại Commit: [`3bad089`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/3bad0898e849d80278487f0d7b939e89bc015876)
- **Phán quyết:** `INCOMPLETE`
- **Lý giải đánh giá (ISTQB):** Không có
- **Chỉnh sửa của Sinh viên:** Em đã: (1) rà soát và xác minh toàn bộ 30 link, loại bỏ những link không còn hoạt động; (2) chắt lọc từ 30 xuống 20 lỗi đại diện nhất; (3) hiệu chỉnh mức độ nghiêm trọng dựa trên thông tin từ nguồn gốc tin tức; (4) bổ sung mục "AI giải thích về lỗi" và "Đính chính" cho mỗi lỗi để chỉ ra điểm thiên kiến/ảo giác của AI khi giải thích.

---

### Sản phẩm #3: 15 ca kiểm thử thiết bị vật lý (quạt điện Senko BX1282)

- **Công cụ:** Gemini
- **Thời gian thực hiện:** 20:50 06/06/2026
- **Prompt đã sử dụng:**
  > "Thiết kế 15 ca kiểm thử cho thiết bị gia dụng là quạt máy không có tính năng hẹn giờ và tăng chiều cao (Mục tiêu / Đầu vào / Các bước / Kết quả mong đợi / Kết quả thực tế / Phán quyết). Thêm giúp tôi cả checklist và test summary report template dạng bảng."
- **Kết quả AI & Minh chứng:**
  - AI tạo ra 15 ca kiểm thử theo đúng cấu trúc 6 cột (Mục tiêu / Đầu vào / Các bước / Kết quả mong đợi / Kết quả thực tế / Phán quyết). Các ca kiểm thử tập trung vào: bật/tắt quạt, điều chỉnh tốc độ (3 mức), chức năng xoay quạt, độ an toàn và điều kiện biên cơ bản. AI cũng tạo kèm template checklist và test summary report.
  - **Bản AI gen thô (raw):** [Test_Cases_Physica_Product .xlsx](./Test_Cases_Physica_Product%20.xlsx) tại Commit: [`901d736`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/901d736fecd7cb6116ae0daecb12350238e50ca7) (Bản thô 15 ca kiểm thử lúc 21:26 06/06/2026)
  - **Bản hiệu chỉnh (final):** [`[Req03]Test_Cases_Physical_Product.xlsx`](./[Req03]Test_Cases_Physical_Product.xlsx) & [`[Req03]Test_Cases_Physical_Product.md`](./[Req03]Test_Cases_Physical_Product.md) tại Commit: [`baf263b`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/baf263b7f5dcbf4668c0d26e6e067ba5813fa190)
- **Phán quyết:** `INCOMPLETE`
- **Lý giải đánh giá (ISTQB):** Không có
- **Chỉnh sửa của Sinh viên:** Em đã: (1) thực thi toàn bộ 15 ca kiểm thử và ghi lại kết quả thực tế vào file Excel; (2) bổ sung TC16–TC19 là các edge case về lồng quạt mà AI không tạo ra; (3) ghi lại 7 ảnh bằng chứng hội thoại AI chứng minh AI không tìm ra các edge case này; (4) quay video thực thi cho ít nhất 5 ca kiểm thử; (5) ghi nhận và log các lỗi phát hiện lên GitHub Issues.

---

### Sản phẩm #4: Sơ đồ tư duy QA/QC Role Mindmap

- **Công cụ:** Gemini
- **Thời gian thực hiện:** 02:16 08/06/2026
- **Prompt đã sử dụng:**
  > "hãy vẽ cho tôi QA/QC role mindmap"
- **Kết quả AI & Minh chứng:**
  - AI tạo ra một infographic/sơ đồ tư duy dạng text mô tả vai trò QA và QC, bao gồm các mục: Principles, Key Activities, Focus Areas, Deliverables và Key Differences giữa QA và QC.
  - **Sơ đồ AI gen thô (raw):** [raw.png](./img/mindmap/raw.png) tại Commit: [`f28b63f`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/f28b63ffbbce40a95c8f1b4b4dd29ebe885100af) (Bản thô sơ đồ lúc 02:49 08/06/2026)
  - **Sơ đồ hiệu chỉnh (final):** [final.png](./img/mindmap/final.png) & [`[Req01]QA_QC-Role_Mindmap.md`](./[Req01]QA_QC-Role_Mindmap.md) tại Commit: [`f28b63f`](https://github.com/mqt4n/hcmus-swtesting--hw/commit/f28b63ffbbce40a95c8f1b4b4dd29ebe885100af)
- **Phán quyết:** `INCOMPLETE`
- **Lý giải đánh giá (ISTQB):** Không có
- **Chỉnh sửa của Sinh viên:** Em đã: (1) phân tích và lập bảng 8 lỗi sai với dẫn chứng từ ISTQB CTFL v4.0; (2) yêu cầu AI chỉnh sửa lại infographic theo 6 điểm cụ thể (thay đổi thuật ngữ, thêm/xóa các mục sai); (3) lưu sơ đồ gốc (img/mindmap/raw.png) và sơ đồ đã sửa (img/mindmap/final.png) kèm ảnh hội thoại chứng minh.

---

## 4. Tổng Hợp Độ Chính Xác của AI

Tổng hợp các phán quyết từ Phần 3 và hoàn thiện bảng dưới đây.

| Chỉ số                                            | Số lượng | Tỷ lệ |
| :------------------------------------------------ | :------- | :---- |
| **Tổng số sản phẩm do AI tạo ra được kiểm tra**   | 4        | 100%  |
| **VALID (đúng, chấp nhận nguyên bản)**            | 0        | 0%    |
| **INVALID (sai; bị từ chối)**                     | 0        | 0%    |
| **INCOMPLETE (chấp nhận được sau khi chỉnh sửa)** | 4        | 100%  |

## 5. Kết Luận – Khi nào nên (hoặc không nên) sử dụng AI?

Qua kiểm tra 4 sản phẩm do AI tạo ra, ta thấy AI rất mạnh trong việc tạo khung dàn ý, cấu trúc báo cáo hoặc tìm kiếm thông tin ban đầu (soạn thảo thô, lập dàn ý test cases). Tuy nhiên, AI thường xuyên gặp lỗi ảo giác (hallucination), cung cấp liên kết hỏng, đánh giá sai mức độ nghiêm trọng và đặc biệt là thiếu sót hoặc sai lệch các khái niệm học thuật chuẩn (như ISTQB CTFL v4.0 trong sơ đồ tư duy) và các trường hợp biên (edge cases) trong kiểm thử thực tế. Vậy chỉ nên dùng AI như một công cụ hỗ trợ tạo bản thảo ban đầu. Sau đó bắt buộc phải kiểm chứng thủ công, rà soát đối chiếu tài liệu chuẩn và bổ sung kiểm thử thực tế để đảm bảo chất lượng.

## 6. Công Bố Bắt Buộc (dán nguyên văn)

_"Phân tích thị trường việc làm / Danh sách 20 lỗi phần mềm / 15 ca kiểm thử quạt điện / Sơ đồ tư duy QA/QC" ban đầu được tạo ra bởi Gemini và Antigravity. Em đã xem xét và chỉnh sửa toàn bộ 4 sản phẩm, bao gồm: xác minh lại 14 link tuyển dụng và sửa kết luận AI/LLM; chắt lọc và hiệu chỉnh 20/30 lỗi phần mềm; bổ sung edge case TC16–TC19 mà AI bỏ sót; phân tích và sửa 8 lỗi trong mindmap QA/QC; phần 'Đính chính' và phần bảng lỗi sai mindmap được em tự viết hoàn toàn. Báo cáo Kiểm tra AI chi tiết được đính kèm như Phụ lục A. Em xác nhận rằng em không sử dụng AI để tạo ra bất kỳ sản phẩm nào thuộc danh mục bị cấm (ảnh thiết bị, video thực thi, ảnh chụp tài khoản đăng nhập, prompt log)._

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
- Anthropic (2025). Building reliable AI test agents – engineering blog.
- Tài liệu DeepEval & Promptfoo – framework kiểm thử cho hệ thống LLM.
