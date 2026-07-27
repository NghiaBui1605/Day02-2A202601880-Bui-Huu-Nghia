# 01 — Individual Problem Scan (Báo cáo cá nhân)

**Họ và tên:** Bùi Hữu Nghĩa  
**Mã học viên:** 2A202601880  
**Vai trò:** Thành viên nhóm (Sinh viên Công nghệ Thông tin - Chuyên ngành Công nghệ phần mềm, đang học cơ bản về Ứng dụng AI)  

---

# Phase 1 — Individual Scan (10 Problems)

Dưới đây là danh sách 10 bài toán/vấn đề được quan sát trực tiếp từ trải nghiệm thực tế cá nhân, đời sống hằng ngày và quá trình học tập/làm dự án phần mềm.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (Empirical Evidence) |
|---|---|---|---|---|
| 1 | **Tốn thời gian** & **Lặp lại** | Khó khăn khi lựa chọn món nên nấu / nên ăn phù hợp với tình trạng sức khỏe, chế độ dinh dưỡng và nguyên liệu có sẵn | Người nấu ăn gia đình, Sinh viên, Người cần ăn kiêng | Mất 20-30 phút mỗi ngày đắn đo "hôm nay ăn gì"; dễ nấu lặp món hoặc chọn món không phù hợp với bệnh lý (tiểu đường, dạ dày...). |
| 2 | **Lặp lại** | Thường xuyên quên uống thuốc khi ốm, uống sai giờ hoặc uống không đủ liều theo đơn bác sĩ kê | Người bệnh, người chăm sóc người thân bị ốm | Quên uống thuốc 2-3 lần/đợt ốm; trễ giờ uống 2-4 tiếng vì không nhớ đã uống chưa hoặc báo thức giờ cố định kêu không đúng lúc. |
| 3 | **AI có thể tốt hơn** | Bác sĩ thiếu hệ thống theo dõi và cảnh báo liên tục diễn biến chỉ số sức khỏe & sự tuân thủ đơn thuốc của bệnh nhân ngoại trú | Bác sĩ điều trị, Bệnh nhân ngoại trú | Bác sĩ chỉ biết tình trạng bệnh nhân khi tái khám sau 1-2 tuần; không phát hiện kịp thời các biến chứng hoặc việc bỏ thuốc giữa chừng. |
| 4 | **Tốn thời gian** | Gom & tổng hợp tài liệu, slide bài giảng từ nhiều nhóm Zalo/LMS thành nội dung ôn thi | Sinh viên | Mất 2-3 tiếng trước mỗi kỳ thi để tải file rời rạc và sắp xếp lại theo chương. |
| 5 | **Lặp lại** | Tìm lại câu trả lời hoặc quyết định cũ trong group chat lớp/dự án bị trôi tin nhắn | Sinh viên, Thành viên nhóm | Mất 15-20 phút cho mỗi lần tra cứu; nhiều câu hỏi bị hỏi đi hỏi lại nhiều lần. |
| 6 | **Tốn thời gian** | Đọc và tóm tắt tài liệu tham khảo dài (PDF/Paper) trước các buổi seminar môn học | Sinh viên, Trợ giảng | Mất 1.5 - 2 tiếng đọc tài liệu tiếng Anh 15-20 trang để chuẩn bị 3 slide tóm tắt. |
| 7 | **Pain từ người khác** | Theo dõi và tổng hợp deadline môn học rải rác từ nhiều kênh (Email, LMS, Zalo, Teams) | Sinh viên | Bị sót 1-2 bài tập/deadline nhỏ mỗi học kỳ do thông báo nằm ở nhiều nơi. |
| 8 | **Pain từ người khác** | Người lớn tuổi trong gia đình gặp khó khăn khi thao tác trên các ứng dụng ngân hàng hoặc dịch vụ công trực tuyến | Người lớn tuổi, Người thân hỗ trợ | Phải nhờ con cháu thao tác hộ mỗi lần chuyển tiền hoặc khai báo thủ tục; dễ bấm nhầm nút. |
| 9 | **Lặp lại** | Mất nhiều thời gian tìm chỗ gửi xe tại trung tâm thương mại hoặc bệnh viện vào giờ cao điểm | Người đi xe máy/ô tô | Mất 15-25 phút đi vòng quanh lòng nhà xe để tìm khoảng trống còn thừa. |
| 10 | **Tốn thời gian** | Đặt đồ ăn online nhưng không biết món nào thực sự ngon và phù hợp do review quá nhiều và mâu thuẫn | Người đặt đồ ăn online | Mất 15-20 phút đọc comment đánh giá trên ShopeeFood/GrabFood mà vẫn chọn nhầm quán kém chất lượng. |

---

# Phase 2 — Top 3 Problem Cards & Draft Workflows

## 1. Chọn Top 3

| Rank | Problem Candidate | Vì sao chọn? | Điều còn chưa chắc chắn |
|---|---|---|---|
| **1** | **Khó khăn khi lựa chọn món nên nấu / nên ăn theo sức khỏe & nguyên liệu sẵn có** | Vấn đề diễn ra hàng ngày, gây tốn thời gian suy nghĩ (20-30 phút/ngày). Workflow rõ ràng từ kiểm tra nguyên liệu $\rightarrow$ cân đối sức khỏe/dinh dưỡng $\rightarrow$ gợi ý thực đơn $\rightarrow$ nấu ăn. Dễ áp dụng AI Workflow (Vision / Text LLM). | Cơ sở dữ liệu món ăn Việt Nam cần phong phú và khả năng gợi ý linh hoạt theo nguyên liệu thực tế trong tủ lạnh. |
| **2** | **Thường xuyên quên uống thuốc khi ốm (Smart Medication Schedule)** | Pain point rất thật và phổ biến với bản thân và người thân. Workflow rõ ràng: scan đơn $\rightarrow$ lên lịch bối cảnh $\rightarrow$ xác nhận uống. | Khả năng đọc chính xác chữ viết tay bác sĩ của AI OCR. |
| **3** | **Bác sĩ thiếu hệ thống theo dõi & cảnh báo liên tục cho bệnh nhân ngoại trú** | Tác động lớn đến hiệu quả điều trị y tế; mở rộng từ bài toán theo dõi sức khỏe. | Cần giao diện tích hợp cho bác sĩ; rủi ro bảo mật dữ liệu y tế. |

---

## 2. Problem Card #1 — Detailed (Smart Meal & Menu Recommendation)

```text
┌────────────────────────────────────────────────────────────────────────┐
│ PROBLEM CARD #1                                                        │
│                                                                        │
│ Problem 1 câu: Người nấu ăn / người bệnh mất 20-30 phút mỗi ngày đắn   │
│ đo không biết nên nấu / nên ăn món gì vừa hợp khẩu vị, vừa đúng chế   │
│ độ sức khỏe và tận dụng nguyên liệu sẵn có trong tủ lạnh.             │
│                                                                        │
│ Ai chịu ảnh hưởng? Người nấu ăn gia đình, Sinh viên, Người ăn kiêng.   │
│                                                                        │
│ Workflow hiện tại:                                                     │
│ 1. Mở tủ lạnh xem nguyên liệu → 2. Nghĩ món hoặc tra cứu Tiktok/Google │
│ → 3. Đắn đo 20-30 phút so sánh bệnh lý, dị ứng & khẩu vị               │
│ → 4. Quyết định nấu món lặp lại hoặc chọn món không phù hợp sức khỏe  │
│ → 5. Bắt đầu sơ chế & nấu ăn.                                         │
│                                                                        │
│ Bước nghẽn nhất: Bước 3 — Đắn đo so sánh nguyên liệu & sức khỏe        │
│ (Mất 20-30 phút/ngày, dễ bỏ cuộc chọn đồ ăn nhanh không lành mạnh).    │
│                                                                        │
│ Đo thành công bằng gì?                                                 │
│ Giảm thời gian quyết định từ 25 phút xuống dưới 3 phút;                │
│ Giảm tỷ lệ bỏ thừa nguyên liệu trong tủ lạnh xuống < 10%.              │
│                                                                        │
│ Quick gut: [ ] No AI   [ ] Rule   [X] Workflow   [ ] Agent            │
└────────────────────────────────────────────────────────────────────────┘
```

### Chi tiết Problem Card #1

- **Problem 1 câu:** Người nấu ăn gia đình hoặc người đang cần điều trị/ăn kiêng mất 20-30 phút mỗi ngày đắn đo suy nghĩ không biết nên nấu hay nên ăn món gì vừa hợp khẩu vị, vừa đảm bảo chế độ dinh dưỡng/bệnh lý (tiểu đường, dạ dày, mỡ máu) và tận dụng được các nguyên liệu đang có sẵn trong tủ lạnh.
- **Actor:** Bùi Hữu Nghĩa (Người nấu ăn cá nhân / Người cần lựa chọn thực đơn lành mạnh cho gia đình).
- **Thời điểm / Bối cảnh:** Diễn ra 2-3 lần mỗi ngày trước các bữa ăn sáng, trưa, tối hoặc khi chuẩn bị đi chợ/nấu ăn.
- **Current Workflow (5 bước):**
  1. Inspect: Mở tủ lạnh hoặc xem danh mục nguyên liệu thực phẩm đang có trong nhà.
  2. Search: Tự nhớ lại các món quen thuộc hoặc lướt TikTok/Google/Cookpad để tìm công thức.
  3. Compare & Hesitate (Bottleneck): Đắn đo 20-30 phút để so sánh: nguyên liệu này có đủ không, món này có bị dị ứng hay ảnh hưởng bệnh lý không, có bị lặp món với hôm qua không.
  4. Decision: Quyết định chọn một món quen thuộc lặp đi lặp lại hoặc chán nản đặt đồ ăn nhanh không lành mạnh ngoài hàng.
  5. Cook: Bắt đầu sơ chế và nấu ăn.
- **Bottleneck:** Bước 3 (Đắn đo so sánh nguyên liệu & chế độ dinh dưỡng/bệnh lý $\rightarrow$ tốn 20-30 phút mỗi ngày, gây mệt mỏi tâm lý và dễ chọn sai món).
- **Impact:** Tốn 2.5 - 3.5 giờ/tuần chỉ để đắn đo chọn món; lãng phí thực phẩm trong tủ lạnh do để hỏng; ảnh hưởng không tốt đến sức khỏe do ăn uống thiếu cân đối.
- **Success Metric:**
  - *Thời gian:* Giảm thời gian quyết định chọn món từ 25 phút xuống dưới 3 phút.
  - *Hiệu quả dinh dưỡng:* 100% thực đơn gợi ý tuân thủ đúng cảnh báo sức khỏe/bệnh lý của người dùng.
  - *Tiết kiệm:* Giảm tỷ lệ nguyên liệu bị bỏ thừa/hỏng trong tủ lạnh xuống dưới 10%.
- **Non-AI Alternative:** Lập sẵn Bảng thực đơn cố định theo tuần (Meal Plan Excel). (Hạn chế: Cứng nhắc, không linh hoạt khi tủ lạnh phát sinh nguyên liệu thừa hoặc khi đổi khẩu vị).
- **AI Hypothesis:** Sử dụng AI Workflow: Chụp ảnh tủ lạnh/Nhập nguyên liệu sẵn có + Khai báo tình trạng sức khỏe $\rightarrow$ AI gợi ý 3 phương án món ăn kèm công thức & bảng phân tích dinh dưỡng $\rightarrow$ Người dùng chọn 1 món và bắt đầu nấu.
- **Quick Gut:** `Workflow` (Nhập nguyên liệu/sức khỏe $\rightarrow$ AI gợi ý 3 lựa chọn $\rightarrow$ Người dùng chọn món $\rightarrow$ Hiển thị công thức).

---

### Draft Current Workflow (Kịch bản hiện tại — 25 phút đắn đo)

```text
CURRENT STATE — 25 phút đắn đo chọn món

[1. Mở tủ lạnh kiểm tra nguyên liệu: 3']
  ↓
[2. Tra cứu TikTok / Google / Nhớ lại món cũ: 5']
  ↓
[3. ĐẮN ĐO SO SÁNH: Nguyên liệu + Bệnh lý + Khẩu vị: 15']  <-- BOTTLENECK CHÍNH
  ↓
[4. Chọn đại món cũ lặp lại hoặc đặt đồ ăn nhanh không lành mạnh: 2']
  ↓
[5. Bắt đầu nấu ăn]
```

---

### Draft Future Workflow (Kịch bản tương lai có AI hỗ trợ — 3 phút quyết định)

```text
FUTURE STATE — 3 phút chọn món lành mạnh

[1. Chụp ảnh tủ lạnh hoặc chọn danh sách nguyên liệu sẵn có: 30s] -- (Rule/Input)
  ↓
[2. AI Vision/Text Parser $\rightarrow$ Nhận diện nguyên liệu & Check cảnh báo bệnh lý: 30s] -- (AI Workflow Step 1)
  ↓
[3. AI Generator $\rightarrow$ Gợi ý Top 3 món ăn chuẩn dinh dưỡng kèm công thức: 1'] -- (AI Workflow Step 2)
  ↓
[4. Người dùng chọn 1 món ưng ý (Human Decision & Confirm): 30s] -- (HUMAN BOUNDARY)
  ↓
[5. Hiển thị từng bước công thức nấu ăn chi tiết $\rightarrow$ Nấu ăn ngay: 30s]

FALLBACK MECHANISM:
Nếu AI gợi ý món người dùng không thích $\rightarrow$ Bấm nút "Gợi ý 3 món khác" hoặc nhập thêm nguyên liệu mong muốn để AI tạo lại.
```

---

## 3. Tóm tắt Problem Card #2 và #3

| Card | Actor | Bottleneck | Metric kỳ vọng | Quick Gut | Lý do chưa chọn rank 1 |
|---|---|---|---|---|---|
| **#2 Nhắc lịch uống thuốc thông minh** | Người bệnh, Người chăm sóc | Báo thức giờ cố định không bám sát bối cảnh bữa ăn, thiếu cơ chế xác nhận đã uống | Giảm số lần quên uống thuốc từ 2-3 lần xuống 0 lần | Workflow | Ưu tiên xếp sau bài toán chọn món ăn theo mong muốn cá nhân của bạn. |
| **#3 Bác sĩ theo dõi bệnh nhân ngoại trú** | Bác sĩ, Bệnh nhân | Bác sĩ thiếu dữ liệu thời gian thực về sự tuân thủ đơn thuốc của bệnh nhân | Phát hiện 100% ca bỏ thuốc sau 24h | Workflow | Quy trình kết nối phòng khám phức tạp hơn bài toán đời sống cá nhân. |

---

## 4. Lựa chọn bài pitch với nhóm

- **Card muốn pitch nhất:** Problem Card #1 — *Khó khăn khi lựa chọn món nên nấu / nên ăn theo sức khỏe & nguyên liệu*.
- **Vì sao:** Bài toán cực kỳ thực tế, ai cũng gặp hàng ngày. Workflow mạch lạc từ nhận diện nguyên liệu $\rightarrow$ kiểm tra bối cảnh sức khỏe $\rightarrow$ gợi ý thực đơn cá nhân hóa. Thể hiện ứng dụng AI hỗ trợ ra quyết định (Decision Support AI Workflow) rất rõ ràng.
- **Câu hỏi muốn nhóm challenge:**
  1. *Nếu AI gợi ý món ăn có nguyên liệu người dùng bị dị ứng mà trong hồ sơ chưa khai báo thì hệ thống cảnh báo rủi ro như thế nào?*
  2. *Liệu việc chụp ảnh tủ lạnh có đủ chính xác để AI nhận diện nguyên liệu không hay cần kết hợp danh sách chọn nhanh?*
