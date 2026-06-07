## 1. Sơ đồ tư duy do AI tạo ra ban đầu

> **Công cụ AI sử dụng:** Gemini
> **Thời gian thực hiện:** 02:16 08/06/2026
> **Prompt đã dùng:** hãy vẽ cho tôi QA/QC role mindmap  
> **Ảnh chụp màn hình cuộc hội thoại với AI (chứng minh sơ đồ ban đầu):**  
> ![AI Mindmap Conversation](img/mindmap/01.png)
> **Sơ đồ do AI tạo:**  
> ![AI Mindmap](img/mindmap/raw.png)

---

## 2. Phân tích 3 lỗi sai / thiếu sót của AI (MANDATORY)

| STT   | Lỗi sai / Thiếu sót                                            | Giải thích dựa trên ISTQB Syllabus                                                                                                                                                                                                                              | Cách sửa đổi / Bổ sung                                                                                                                                             |
| :---- | :------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1** | **QC — Principles: "Reactive approach"**                       | ISTQB không định nghĩa QC là "reactive". Trong các mô hình hiện đại (Agile, Shift-Left), QC hoàn toàn có thể là chủ động (proactive). ISTQB CTFL v4.0 không dùng thuật ngữ này để mô tả QC.                                                                     | Thay bằng **"Corrective approach"** hoặc **"Product-focused approach"** — phù hợp hơn với định nghĩa ISTQB.                                                        |
| **2** | **QC — Key Activities: "Verification"**                        | Theo ISTQB, Verification ("Are we building the product right?") thuộc về **QA/Static Testing**, không phải QC. QC tập trung vào **Validation** ("Are we building the right product?"). Đặt Verification trong QC là nhầm lẫn hai khái niệm cốt lõi.             | Chuyển "Verification" sang QA. Trong QC thay bằng **"Validation"** hoặc **"Test Execution"**, **"Defect Detection"**.                                              |
| **3** | **Key Differences: "QA: Static" vs "QC: Dynamic"**             | Quá đơn giản hóa và dễ gây hiểu sai. Theo ISTQB CTFL v4.0, Static/Dynamic là **kỹ thuật kiểm thử**, không phải đặc trưng riêng của QA hay QC. QA có thể bao gồm cả hai; QC cũng có thể dùng static testing trong một số ngữ cảnh.                               | Thay bằng: **QA: Process-oriented, Preventive, Proactive** / **QC: Product-oriented, Corrective, Reactive**. Ghi chú Static/Dynamic là techniques riêng.           |
| **4** | **QA — Principles: "Prevent defects" (chưa đầy đủ)**           | ISTQB CTFL v4.0 định nghĩa QA là _"part of quality management focused on providing confidence that quality requirements will be fulfilled"_. "Prevent defects" là **kết quả**, không phải nguyên tắc. Nguyên tắc đúng là đảm bảo quy trình được thực hiện đúng. | Sửa thành **"Provide confidence in quality"** hoặc **"Process compliance"**. Có thể giữ "Prevent defects" nhưng thêm chú thích là mục tiêu, không phải nguyên tắc. |
| **5** | **QA — Key Activities: Thiếu Test Planning & Test Monitoring** | ISTQB CTFL v4.0 liệt kê **Test Planning**, **Test Monitoring & Control** là các test activities chính của QA/Test Management. "Defect Prevention" không xuất hiện với tên này trong ISTQB — đây là khái niệm từ TMMi/ISO.                                       | Bổ sung **"Test Planning"** và **"Test Monitoring & Control"** vào QA Key Activities.                                                                              |
| **6** | **QA — Focus Areas: Thiếu "Test Policy" và "Test Strategy"**   | Theo ISTQB CTFL v4.0, **Test Policy** (cấp tổ chức) và **Test Strategy** (cấp dự án) là hai deliverable/hoạt động quan trọng thuộc phạm vi QA. Mindmap chỉ ghi chung "Documentation (QMS)" mà bỏ qua hai khái niệm nền tảng này.                                | Thêm **"Test Strategy"** và **"Test Policy"** vào Focus Areas hoặc Deliverables của QA.                                                                            |
| **7** | **QC — Key Activities: "Inspection" dùng sai nghĩa ISTQB**     | Trong ISTQB, **Inspection** là một dạng **Static Review** (review có cấu trúc cao nhất — có moderator, checklist, formal exit criteria), không phải kiểm tra vật lý sản phẩm. Dùng "Inspection" trong QC Dynamic Activities dễ gây nhầm nghĩa.                  | Làm rõ: **"Inspection" = Static Review technique** theo ISTQB. Hoặc đổi thành **"Static Review / Inspection"** để tránh nhầm với physical inspection.              |
| **8** | **QC — Deliverables: Thiếu "Test Summary Report"**             | ISTQB CTFL v4.0 xác định **Test Completion Report** (Test Summary Report) là testware/deliverable chính thức của giai đoạn Test Completion. Mindmap chỉ ghi "Test Results" — khác với một báo cáo tổng kết chính thức theo ISTQB.                               | Bổ sung **"Test Summary Report"** (hoặc "Test Completion Report") vào QC Deliverables.                                                                             |

---

## 3. Sơ đồ tư duy đã được hiệu chỉnh (Sản phẩm của sinh viên)

### Sơ đồ dạng đã sửa lỗi:

> **Ảnh chụp màn hình cuộc hội thoại với AI (chứng minh sơ đồ đã được chỉnh sửa):**  
> ![AI Mindmap Conversation](img/mindmap/02.png)
> **Sơ đồ đã được hiệu chỉnh:**  
> ![AI Mindmap](img/mindmap/final.png)
