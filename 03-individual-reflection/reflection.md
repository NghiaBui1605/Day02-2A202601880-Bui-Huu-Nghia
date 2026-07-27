# 03 — Individual Reflection (Bài phản tư cá nhân)

**Họ và tên:** Bùi Hữu Nghĩa  
**Mã học viên:** 2A202601880  
**Vai trò trong nhóm:** Thành viên nhóm (Sinh viên CNTT - Chuyên ngành Công nghệ phần mềm, đang học cơ bản về Ứng dụng AI)  

---

# 1. Tôi Đã Tham Gia Vào Phần Nào Trong Quá Trình Làm Nhóm?

Bảng dưới đây ghi chép lại các hoạt động cá nhân tôi đã tham gia và đóng góp trực tiếp cho kết quả làm việc của Nhóm 11 người:

| Hoạt động | Tôi đã làm gì cụ thể? | Kết quả & Tác động tới bài làm của nhóm |
|---|---|---|
| **Scan cá nhân** | Scan 10 vấn đề thực tế và chuẩn bị 3 candidate để đưa vào phiên hội tụ của nhóm. | Đóng góp 3 candidate problems vào danh sách 33 bài toán chung của nhóm; các candidate này được dùng để so sánh trước khi nhóm chốt bài toán cuối. |
| **Pitch Problem Card** | Trình bày một Problem Card cá nhân trong 2 phút, có workflow 5 bước và baseline thời gian cụ thể. | Cung cấp một phương án đối chiếu để nhóm đánh giá actor, bottleneck, metric và mức phù hợp với AI. |
| **Challenge bài của bạn khác** | Đặt câu hỏi phản biện bài "Tra cứu quyết định cũ trên Discord" của Tiến Anh về việc giải pháp keyword search thông thường đã đủ chưa. | Giúp nhóm phân biệt rõ bài toán nào thực sự cần AI, bài toán nào chỉ cần Search/Rule truyền thống. |
| **Gom trùng / Cluster** | Cùng nhóm phân loại 33 candidate problems thành 4 cụm lớn (Sức khỏe & Dinh dưỡng, Phân loại sự cố khẩn cấp, Tóm tắt tài liệu, Quản lý task). | Tạo cấu trúc phân tích rõ ràng để nhóm tiến hành shortlist. |
| **Chọn candidate problem** | Cùng nhóm thảo luận, so sánh các candidate problems từ 11 thành viên dựa trên 7 tiêu chí. | Tích cực đóng góp ý kiến khách quan để nhóm tiến tới hội tụ đồng thuận. |
| **Validation / Research** | Cùng nhóm đối chiếu các công cụ tổng hợp tài liệu như NotebookLM và Notion AI với workflow làm đề cương ôn thi. | Làm rõ rằng việc gom tài liệu có thể chuẩn hóa bằng Rule, còn tóm tắt và draft đề cương là bước AI hỗ trợ tốt hơn nhưng vẫn cần sinh viên kiểm tra. |
| **Workflow nhóm** | Hỗ trợ nhóm thiết kế các luồng quy trình Before/After minh họa cho các bài toán shortlist. | Giúp nhóm trực quan hóa các điểm nghẽn thời gian và vị trí can thiệp AI. |
| **Problem Statement** | Thảo luận cùng nhóm các field quan trọng của Problem Statement (Actor, Bottleneck, Metric, Boundary). | Giúp nhóm sẵn sàng xây dựng Problem Statement v0/v1 chặt chẽ khi chốt bài toán cuối. |
| **Rule / Workflow / Agent** | Lập luận chọn **AI-Supported Workflow**: Rule để gom nguồn, AI tóm tắt và draft đề cương, sinh viên kiểm tra trước khi dùng. | Làm rõ vì sao workflow có kiểm soát phù hợp hơn Agent tự động truy cập Drive/chat/email. |
| **Final Decision** | Đóng góp ý kiến vào tiêu chí đánh giá Go / Not Yet / No-Go và kịch bản Rollback cho dự án. | Giúp nhóm sẵn sàng cho quyết định Go với kịch bản Pilot nhỏ an toàn. |

---

# 2. Bảng Sử Dụng AI Trong Quá Trình Làm Lab (AI Usage Breakdown)

Tôi đã sử dụng AI như một trợ lý gợi ý và phản biện kiến thức cơ bản về AI, tuyệt đối không để AI quyết định hoặc viết thay suy nghĩ cá nhân:

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở điểm nào? | AI sai / hời hợt / ngây thơ ở đâu? | Tôi đã sửa gì bằng nhận định cá nhân? |
|---|---|---|---|---|
| **Phase 1: Individual Scan** | Đưa các quan sát cá nhân vào AI để mở rộng theo 4 lăng kính scan. | Giúp tôi nhìn thêm các dấu hiệu có thể đo như tần suất, thời gian và hậu quả nếu không xử lý. | AI nêu nhiều ý tưởng quá rộng, không gắn với pain thực tế của tôi. | Loại các ý tưởng chung chung; chỉ giữ những candidate có actor, workflow và dấu hiệu thật để mang vào thảo luận nhóm. |
| **Phase 2: Problem Card** | Nhờ ChatGPT đóng vai Skeptical PM để phản biện Problem Card cá nhân. | Chỉ ra các lỗ hổng về actor, metric và phương án non-AI. | AI có xu hướng đề xuất tự động hóa quá mức trước khi làm rõ boundary. | Bổ sung bước con người kiểm soát và dùng card này như một candidate để so sánh, thay vì mặc định biến nó thành giải pháp của nhóm. |
| **Phase 5: Workflow** | Nhờ AI chuyển bảng mô tả workflow tổng hợp tài liệu thành mã Mermaid. | Tạo mã Mermaid nhanh để nhóm xem lại luồng trước/sau. | AI gộp bước AI tóm tắt nguồn và bước AI draft đề cương thành một bước, làm mờ vị trí kiểm soát chất lượng. | Tách rõ: AI tóm tắt từng nguồn $\rightarrow$ AI draft theo template $\rightarrow$ sinh viên kiểm và đối chiếu đề cương giảng viên. |
| **Phase 4: Research** | Tìm các công cụ tổng hợp, hỏi đáp và tạo tài liệu học từ nguồn người dùng cung cấp. | Gợi ý đúng NotebookLM và Notion AI, giúp nhóm thấy các công cụ sẵn có đã hỗ trợ được một phần workflow. | AI đưa ra vài claim về hiệu quả học tập không kèm nguồn kiểm chứng. | Chỉ giữ lại thông tin kiểm tra được từ trang chính thức; không dùng các số liệu chưa xác minh. |
| **Phase 6: Decision** | Hỏi AI: "Bài toán tổng hợp tài liệu ôn thi nên chọn Rule, Workflow hay Agent?" | Giúp phân biệt rõ phạm vi và rủi ro của ba mức giải pháp. | AI nghiêng về Agent tự quét Drive/chat/email để tự tìm tài liệu. | Bác bỏ đề xuất này vì yêu cầu quyền truy cập rộng và dễ lấy sai nguồn; chọn **Workflow** với người dùng tự gom nguồn và kiểm nội dung. |

---

# 3. Phản Tư Câu Hỏi Mở (Open Reflection)

### 3.1 Tôi học được gì khi nghe 33 Problems của các bạn khác trong nhóm 11 người?
Khi nghe 10 bạn còn lại trong nhóm pitch 30 bài toán khác nhau (từ sự cố tòa nhà khi mưa lũ của Đức, rà soát Rubric của Tiến Anh, đến trace bug Production của Tuấn Việt), tôi nhận ra một bài học lớn: **Một bài toán AI tốt không nhất thiết phải phức tạp hay viễn tưởng; nó cần có actor, workflow và bottleneck rõ ràng.** Bài toán nhóm chọn — sinh viên gom tài liệu rải rác để làm đề cương ôn thi — thuyết phục vì nhóm mô tả được cụ thể thời gian mất ở từng bước và kiểm chứng pain này với các bạn cùng lớp.

### 3.2 Nhóm có lúc nào bị "Solution-First" (Nghĩ giải pháp trước khi hiểu bài toán) không?
Có. Khi thảo luận bài toán tổng hợp tài liệu ôn thi, có ý kiến đề xuất làm ngay một Agent tự vào Drive, chat và email để tự tìm tất cả tài liệu, tự chọn nguồn rồi tự tạo đề cương. Nhóm đã quay về nguyên tắc **“Problem first, Workflow first”**: bottleneck thật là gom nguồn rải rác và cấu trúc lại nội dung, còn các bước sau đó khá cố định. Vì vậy, nhóm chọn Rule để chuẩn hóa việc gom nguồn, rồi dùng AI trong workflow tóm tắt/draft; sinh viên vẫn kiểm và chốt nội dung.

### 3.3 Tôi có thay đổi ý kiến sau khi bị nhóm Challenge không?
Có. Ban đầu tôi nghĩ chỉ cần gom tài liệu vào một thư mục chung là đã giải quyết phần lớn vấn đề. Khi thảo luận, nhóm challenge rằng việc lưu chung chỉ giảm thời gian tìm file, nhưng chưa giảm được công sức đọc, lọc trọng tâm và cấu trúc thành đề cương. Sau challenge này, tôi đồng ý rằng Rule là cần thiết nhưng không đủ; AI chỉ nên hỗ trợ tóm tắt và draft, còn sinh viên phải đối chiếu tài liệu gốc và đề cương giảng viên trước khi chốt.

### 3.4 Đóng góp thực sự của tôi vào Artifact cuối cùng của nhóm là gì?
Tôi đóng góp 3 phần chính:
1. **Đóng góp candidate cá nhân:** Chuẩn bị Problem Card có workflow và baseline cụ thể, giúp nhóm có thêm một phương án để so sánh trước khi hội tụ.
2. **Hỗ trợ trực quan hóa Workflow:** Tham gia hỗ trợ vẽ và số hóa các luồng sơ đồ Mermaid/ASCII cho nhóm.
3. **Phân tích đối soát giải pháp:** Cùng nhóm xem NotebookLM và Notion AI để làm rõ bước nào công cụ có sẵn đã hỗ trợ được, bước nào vẫn cần Rule và human review.

### 3.5 Điều khó khăn nhất khi viết Problem Statement là gì?
Điều khó nhất là **tách bạch giữa bottleneck và solution**, đồng thời đưa ra metric có thể đo. Ban đầu nhóm dễ viết chung chung là “giúp ôn thi nhanh hơn”. Sau khi vẽ workflow, nhóm chuyển sang metric cụ thể: thời gian gom và cấu trúc đề cương từ baseline khoảng 4,5 giờ/môn xuống dưới 1,5 giờ/môn, đồng thời không tăng số phần trọng tâm bị bỏ sót khi đối chiếu với đề cương giảng viên.

### 3.6 Nếu được làm lại lab này, tôi sẽ Challenge nhóm mạnh hơn ở điểm nào?
Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở khâu **đo chất lượng đầu ra**: xác định trước danh sách trọng tâm của giảng viên hoặc tiêu chí đối chiếu, rồi ghi số phần bị thiếu/sai thay vì chỉ dựa vào cảm nhận. Tôi cũng sẽ yêu cầu chạy pilot trên hai môn có mức độ tài liệu khác nhau để kiểm tra liệu workflow có thật sự hiệu quả ngoài một trường hợp thuận lợi hay không.

---

# 4. Tự Kiểm Cuối Bài (Self-Check Checklist)

Tôi đã tự kiểm tra bài làm của cá nhân và nhóm theo đúng tiêu chí đánh giá trong `README.md`:

- [x] **[12đ cá nhân]** Bùi Hữu Nghĩa (2A202601880) có danh sách 10 problems phong phú và Top 3 Problem Cards rõ ràng.
- [x] **[12đ cá nhân]** Đã pitch trực tiếp bài toán của mình và tích cực challenge làm rõ bài toán của 10 thành viên khác trong nhóm.
- [x] **[15đ nhóm]** Nhóm có danh sách 33 bài toán từ 11 thành viên và sơ đồ Workflow minh họa cụ thể.
- [x] **[20đ nhóm]** Nhóm có cấu trúc Problem Statement v0/v1 với đầy đủ các trường thông tin chuẩn bị sẵn sàng cho bước hội tụ cuối.
- [x] **[15đ nhóm]** Nhóm có bảng phân tích so sánh chi tiết giữa No AI / Rule / Workflow / Agent và giải thích vì sao chọn Workflow.
- [x] **[10đ nhóm]** Quyết định Go / Not Yet / No-Go có lập luận dựa trên bằng chứng và chiến lược Rollback an toàn.
- [x] **[10đ cá nhân]** Reflection cá nhân trung thực, thể hiện rõ vai trò thành viên nhóm 11 người và 6 bài học phản tư sâu sắc.
- [x] **[6đ cá nhân]** Giải thích thông suốt mạch logic từ Problem $\rightarrow$ Workflow $\rightarrow$ Metric $\rightarrow$ Boundary $\rightarrow$ AI Fit Level.
- [x] **[Bonus +10đ]** Scan 10 problems phong phú (+3đ); Tương tác thảo luận và challenge tích cực trong nhóm 11 người (+3đ); Thực hiện Quick Interview & Solution Research có link nguồn đối soát thật (+4đ).
