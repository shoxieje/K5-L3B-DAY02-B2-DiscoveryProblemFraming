# CP4 — Desk research (bằng chứng thứ cấp)

> Đây **không phải** kết quả phỏng vấn. Là bằng chứng thứ cấp từ khảo sát/bài báo/nghiên cứu đã công bố, dùng để đối chiếu với survey 10 người của nhóm. Số liệu được trích theo nội dung của từng nguồn; nghiên cứu Elkins et al. 2024 được trích qua bản tóm tắt của RMIT.

## 1. Pain có thật ở quy mô lớn hơn nhóm không? (giả định 1, 4)

| Nguồn | Nội dung liên quan | Xác nhận / phản bác |
|---|---|---|
| Tennessee Educator Survey 2019 — https://www.tn.gov/content/dam/tn/education/data/2019-survey/Lessons_District_Leaders_Infographic.pdf | ~70% giáo viên dành hơn 4 giờ/tuần để tự tạo hoặc tìm tài liệu giảng dạy; 19% hơn 10 giờ/tuần. Giáo viên tự làm bài kiểm tra vì tài liệu có sẵn không đủ | **Xác nhận** việc "tìm và tạo" tốn thời gian. Hạn chế: số liệu gộp mọi tài liệu, không riêng đề kiểm tra; bối cảnh Mỹ |
| Giáo dục Việt Nam — "Đề kiểm tra học kỳ II năm nay rất khác…" https://giaoduc.net.vn/de-kiem-tra-hoc-ky-ii-nam-nay-rat-khac-voi-nhung-nam-truoc-day-post209834.gd | Soạn một đề kiểm tra học kỳ mất nhiều thời gian vì phải lập ma trận, biên soạn đề và đáp án | **Xác nhận** (định tính, bối cảnh VN). Không có số phút |
| Giáo dục Việt Nam — "Một số khó khăn… ra đề… các môn trắc nghiệm" https://giaoduc.net.vn/ban-in/post173487.gd | Đề trắc nghiệm đạt chuẩn tốn công hơn tự luận vì phải tạo phương án gây nhiễu; ngân hàng câu hỏi còn ít | **Xác nhận** bước "chọn/tạo câu" là khó. Gợi ý: thiếu ngân hàng câu hỏi là nguyên nhân gốc |
| Giáo dục Việt Nam — "Giáo viên không có năng lực ra đề…" https://giaoduc.net.vn/gdvn-post205560.gd | Một bộ phận giáo viên yếu kỹ năng ra đề theo ma trận; giải pháp đề xuất là xoay vòng người ra đề trong tổ chuyên môn | **Phản bác một phần**: vấn đề có thể là kỹ năng/quy trình tổ chức, giải được bằng No AI |

## 2. AI có làm bước chọn câu tốt và nhanh hơn không? (Feasibility, Usability)

| Nguồn | Nội dung liên quan | Xác nhận / phản bác |
|---|---|---|
| RMIT — "Can Gen AI create learning questions better than a human?" https://www.rmit.edu.au/about/educational-ai/blog/can-gen-ai-create-learning-questions-better-than-a-human (tóm tắt nghiên cứu Elkins et al., 2024) | Thời gian viết quiz **gần như bằng nhau** giữa dùng AI và tự viết tay; câu do AI tạo tốt hơn khi prompt có cấu trúc sư phạm (Bloom) | **Phản bác** giả định "AI giảm mạnh thời gian". Lý do: thời gian chuyển sang khâu duyệt |
| Chartered College — "How can we drive up quality standards in AI-generated teaching resources?" https://my.chartered.college/?p=37752 | Công cụ Aila phải thêm bước "AI judge" chấm chất lượng quiz cho sát với đánh giá của giáo viên chuyên môn | **Xác nhận** cần bước kiểm tra (HITL/eval) — khớp với Boundary của nhóm |
| Quiz Design Task (arXiv 2205.01730) https://arxiv.org/pdf/2205.01730 | 10 giáo viên chọn/loại câu hỏi do 7 mô hình sinh tự động, kèm lý do loại | Pattern: AI đề xuất, giáo viên chọn — giống quy trình tương lai mục 4.2 |

## 3. Kết luận cho nhóm

- **Pain:** survey nhóm và nguồn thứ cấp cùng cho thấy việc tìm/chọn/tạo câu tốn thời gian → giả định 1–2 được củng cố.
- **Phản bác quan trọng:** (a) survey: cả 3 người có ngân hàng câu hỏi đều soạn dưới 1 giờ (2 người dưới 30'); (b) báo VN: thiếu ngân hàng câu hỏi và kỹ năng ra đề là nguyên nhân gốc; (c) nghiên cứu Elkins: AI không giảm rõ thời gian vì phải duyệt. Cả ba chỉ về một hướng: **phải so AI với phương án No AI (ngân hàng câu hỏi gắn nhãn) trước khi Go** → củng cố quyết định Not Yet.
- **Metric cần sửa:** đo cả thời gian **duyệt** chứ không chỉ thời gian tạo đề; nếu thời gian duyệt ăn hết phần tiết kiệm thì AI không có giá trị.
