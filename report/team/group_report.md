# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: B2
- Thành viên: xem `TEAM.md` (Phạm Đăng Quang, Nguyễn Minh Đức, Nguyễn Ngọc Quang)
- Candidate problem được chọn (1 câu): Gia sư/giáo viên tự soạn đề ôn tập nhưng chưa có ngân hàng câu hỏi gắn nhãn mất phần lớn từ 30 phút đến hơn 2 giờ cho mỗi đề (survey 10 người), chủ yếu ở bước tìm và chọn câu hỏi hợp bài học; khi không kịp thì dùng lại đề cũ.
- Quyết định cuối: **Not Yet**

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Phạm Đăng Quang | Quản lý dự án code nhóm, muốn tự động nắm tiến độ Git và thảo luận chat để điều phối dự án mà không cần dev tự báo cáo | Tech Lead nhóm sinh viên CNTT (3–5 người) | Mở từng repo/branch đọc commit diff để kiểm tra tiến độ thật (25') | "Nếu dev commit code thử nghiệm/chưa chạy được hoặc lưu code ở local thì làm sao biết đó là tiến độ thật?" (Minh Đức hỏi) |
| 2 | Phạm Đăng Quang | Khi giảng viên dời lịch học/hạn nộp bài bằng lời nói trên lớp, muốn nắm đúng mốc thời gian để không bị trễ deadline | Sinh viên trên lớp | Nhắn tin hỏi chéo bạn bè sau buổi học để đối chiếu lại ngày giờ (15') | "Giảng đường rất ồn, âm thanh STT có thể dịch sai ngày, nếu sai thì ai chịu trách nhiệm?" (Ngọc Quang hỏi) |
| 3 | Phạm Đăng Quang | Khi mở tủ lạnh thấy đồ thừa dở dang, muốn biết món ăn kết hợp từ nguyên liệu sẵn có để nấu nhanh và không bỏ phí thực phẩm | Sinh viên tự nấu ăn ở trọ | Tìm kiếm công thức phù hợp từ các nguyên liệu lẻ tẻ trên Google/YouTube (15') | "Sinh viên ở trọ sao có tiền mua tủ lạnh thông minh, làm sao AI biết trong tủ có gia vị gì nếu không nhập tay?" (Minh Đức hỏi) |
| 4 | Nguyễn Minh Đức | Chuẩn bị đề kiểm tra/ôn tập, muốn có sẵn đề mới đúng cấu trúc quen thuộc để không phải dựng lại từ đầu | Gia sư dạy toán online | Tìm đề thi trên mạng và chọn câu hỏi phù hợp với bài học (30') | "Ngân hàng câu hỏi lấy từ đâu, và có vướng vấn đề bản quyền đề thi không?" (Đăng Quang hỏi) |
| 5 | Nguyễn Minh Đức | Cuối ngày muốn ghi lại các khoản đã chi vào Excel mà không phải nhớ lại và đoán nội dung chuyển khoản | Cá nhân tự quản lý chi tiêu | Nhớ lại các khoản chi tiền mặt và đoán nội dung giao dịch ngân hàng (15') | "Tiền mặt không có log số liệu thì AI đọc kiểu gì nếu người dùng lười ghi ngay lúc mua?" (Ngọc Quang hỏi) |
| 6 | Nguyễn Minh Đức | Có file PDF đề sẵn, muốn tự động tách và phân loại câu hỏi để đưa lên hệ thống thi online nhanh chóng | Giáo viên/gia sư tạo đề online | Copy từng câu hỏi từ PDF và paste lên form online lặp lại 20–30 lần (20–25') | "Đề toán có nhiều công thức LaTeX/ảnh hình học, PDF scan thì script hay AI có bóc tách nổi không?" (Đăng Quang hỏi) |
| 7 | Nguyễn Ngọc Quang | Theo dõi bài tập nằm rải rác ở LMS, Phoenix, Discord, email, muốn thấy hết hạn nộp ở một chỗ để không suýt trễ bài | Học viên toàn khóa AI | Lướt kênh thông báo và chat lớp trên Discord vì deadline nằm lẫn trong tin nhắn thường (7') | "Nếu lớp trưởng lập 1 Google Calendar chung rồi ghim lên Discord thì đã giải quyết được chưa, có cần AI không?" (Đăng Quang hỏi) |
| 8 | Nguyễn Ngọc Quang | Gặp lỗi lab, muốn tìm xem câu hỏi tương tự đã được trả lời trên Discord lớp chưa để sửa ngay | Học viên làm lab | Lội qua hàng chục tin nhắn tìm kiếm trong luồng chat lộn xộn (10') | "Discord search có sẵn rồi, liệu semantic search của AI có thực sự tốt hơn khi từ khóa lỗi code rất cụ thể?" (Minh Đức hỏi) |
| 9 | Nguyễn Ngọc Quang | Khi nhóm cần họp, muốn tìm được khung giờ mọi người đều rảnh để chốt lịch mà không phải nhắn tin qua lại cả ngày | Trưởng nhóm đồ án | Chờ mọi người check lịch cá nhân và phản hồi trong chat (2–3 giờ) | "Mọi người không công khai lịch cá nhân thì bot làm sao đọc được lịch để xếp?" (Đăng Quang hỏi) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | #1 (Git+Chat sync), #7 (Deadline rải rác), #9 (Chốt lịch họp), #8 (Search hỏi đáp cũ), #2 (Bắt lịch dời trên lớp) | **Phối hợp & Quản lý thông tin trong nhóm công nghệ:** Đều giải quyết sự phân mảnh thông tin giữa các kênh chat phi cấu trúc (Discord/Zalo) và công cụ làm việc thực tế (Git, Calendar). Nỗi đau chung của sinh viên/dev khi làm project nhóm. |
| B | #4 (Soạn đề thi), #6 (Tách câu hỏi PDF) | **Soạn và xử lý tài liệu giảng dạy:** người dạy mất thời gian tìm, chọn và chuyển câu hỏi từ nhiều nguồn (đề trên mạng, PDF, đề cũ) thành đề dùng được. |
| C | #3 (Nguyên liệu tủ lạnh), #5 (Ghi chép chi tiêu) | **Tối ưu hoá sinh hoạt cá nhân:** Quản lý tài nguyên cá nhân (tiền bạc, thực phẩm), thường bị tắc ở khâu lười nhập liệu đầu vào. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian người dạy và người học mất cho việc tìm, lọc và tổng hợp thông tin rải rác
├── Opportunity A: Gia sư/giáo viên mất 30'–2h mỗi đề để tìm và chọn câu hỏi hợp bài học (#4, #6)
│     └── Sub: khi gấp thì dùng lại đề cũ, học sinh có thể đã làm rồi
├── Opportunity B: Trưởng nhóm không biết tiến độ thật của thành viên, phải tự đối chiếu Git với chat (#1)
└── Opportunity C: Học viên bỏ sót thông tin (deadline, câu trả lời cũ) vì nằm lẫn trong nhiều kênh chat (#7, #8, #2)
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ~~Trợ lý AI tự sinh đề thi toán~~: là giải pháp, nhu cầu thật là "tìm và chọn câu hợp bài học nhanh hơn" (đã đưa vào Opportunity A).
- ~~Bot Discord tự trả lời bài lab~~: là giải pháp, nhu cầu thật là "tìm được câu trả lời đã có" (Opportunity C).
- ~~App nhắn tin riêng cho dev~~: là giải pháp, nhu cầu thật là "nắm tiến độ thật mà dev không phải tự báo cáo" (Opportunity B).
- ~~Camera AI trong tủ lạnh~~: giải pháp phần cứng, loại cùng cluster C.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#4. Soạn đề ôn tập (Minh Đức)** | 5 | 5 | 4 | 5 | 4 | 5 | 3 | **31** |
| #1. Đối chiếu Git + chat cho Tech Lead (Đăng Quang) | 4 | 4 | 2 | 3 | 4 | 4 | 5 | **26** |
| #7. Theo dõi deadline rải rác (Ngọc Quang) | 4 | 4 | 2 | 3 | 5 | 2 | 5 | **25** |

**Candidate được chọn:** #4 — Soạn đề ôn tập cho gia sư/giáo viên.

**Vì sao chọn:**
1. **Pain có bằng chứng ngoài nhóm:** bấm giờ thật một quy trình (63–75'/đề) và có survey 10 giáo viên/gia sư (mục 3.2). Hai candidate còn lại mới có số ước tính của chính người trong nhóm. Chấm 4 chứ không 5 vì chưa có phỏng vấn sâu.
2. **Actor nằm ngoài nhóm, impact lớn:** 10 người trả lời soạn tổng cộng 101 đề trong tháng, nhân với 30'–2h mỗi đề.
3. **So sánh 4 mức có ý nghĩa thật:** có phương án No AI mạnh (ngân hàng câu hỏi, SmartTest, template Word) để đặt AI cạnh tranh, nên lập luận "vì sao không chọn mức đơn giản hơn" không bị hiển nhiên.

**Vì sao loại các candidate còn lại:**
- **#7 (deadline rải rác):** phương án No AI (Google Calendar chung + quy ước `[DEADLINE]`) gần như giải quyết hết; actor chủ yếu là người trong nhóm; số liệu là ước tính.
- **#1 (Git + chat):** pain dựa trên trải nghiệm trong nhóm, chưa có bằng chứng đo được từ người ngoài; rủi ro thành công cụ giám sát (micromanagement) cao; Rule (GitHub webhook vào Discord) đã che phần lớn nhu cầu "ai commit gì".
- **#8, #9, #2, #3, #5, #6:** điểm thấp hơn ở "Pain có bằng chứng" hoặc có giải pháp sẵn (Discord search, When2meet). #6 (tách câu từ PDF) gộp vào #4 vì cùng actor và cùng opportunity A.

**Xử lý bất đồng (nếu có):**
- Nhánh làm việc ban đầu của Đăng Quang chọn #1. Trưởng nhóm (Ngọc Quang) chốt lại #4 vì đây là candidate duy nhất có bằng chứng từ người ngoài nhóm (survey thật). Điểm "Nhóm hiểu domain" của #4 thấp (3) vì chỉ Minh Đức làm gia sư; nhóm bù lại bằng cách kiểm chứng với giáo viên/gia sư bên ngoài ở CP4.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Giáo viên/gia sư khác cũng mất khoảng một giờ cho mỗi đề, không riêng Minh Đức | Value | 5 | 1 | **Có** (survey) |
| 2 | Bước tốn thời gian nhất là tìm và chọn câu, không phải gõ lại hay kiểm tra đáp án | Value | 5 | 2 | **Có** (survey) |
| 3 | Khi gấp, người soạn dùng lại đề cũ (hậu quả của pain) | Value | 4 | 2 | **Có** (survey) |
| 4 | Người dùng chưa có công cụ/ngân hàng câu hỏi đủ tốt để tự giải quyết | Value | 5 | 1 | **Có** (survey, câu 6) |
| 5 | Có nguồn câu hỏi hợp pháp, đủ nhãn để làm ngân hàng | Feasibility | 4 | 1 | Không (để sau) |
| 6 | Gia sư chịu duyệt từng câu và đáp án do AI đưa ra | Usability | 4 | 1 | Không (cần phỏng vấn) |

Giả định nhóm kiểm chứng trong buổi này: 1, 2, 3, 4 (quan trọng cao, bằng chứng thấp).

### 3.2. Kiểm chứng

Cách đã dùng: **Survey** (Google Form 7 câu, hỏi hành vi trong tháng vừa rồi, không hỏi "bạn có muốn…"). Bộ câu hỏi: [`report/assets/cp4-interview-guide.md`](../assets/cp4-interview-guide.md). Ảnh form: [`cp4-survey-form.png`](../assets/cp4-survey-form.png). Ảnh kết quả: [`cp4-survey-responses.png`](../assets/cp4-survey-responses.png).

Kết quả (10 người trả lời, 09/11/2026; Toán 3, Lý 2, Hóa 2, Anh 1, Văn 1, Sinh 1):

| Câu hỏi | Kết quả |
|---|---|
| Số đề tự soạn tháng vừa rồi | Tổng 101 đề; trung vị 9 đề/người (4–20) |
| Thời gian mỗi đề | Dưới 30' **2** · 30–60' **4** · 1–2 giờ **3** · Trên 2 giờ **1** |
| Bước tốn thời gian nhất | Tìm và chọn câu **5** · Kiểm tra đáp án **2** · Gõ lại/dựng đề **2** · Đưa lên hệ thống/in **1** |
| Lần gần nhất phải dùng lại đề cũ vì không kịp | Tuần này **2** · Tháng này **4** · Lâu hơn **2** · Chưa bao giờ **2** |
| Công cụ đang dùng | Phần lớn là Word (kèm MathType, đề cũ, sách tham khảo); 2 người có ngân hàng câu hỏi; 1 người đã dùng AI; 1 người dùng LaTeX/GeoGebra |

Phỏng vấn: **chưa thực hiện**. Nhóm đã chọn 3 người từ danh sách trả lời survey và viết sẵn giả thuyết cần kiểm cho từng người (xem [`report/assets/cp4-interview-snapshots.md`](../assets/cp4-interview-snapshots.md)):

| Người | Vì sao chọn | Giả thuyết chính cần kiểm |
|---|---|---|
| GV Toán trực tiếp, 20 đề/tháng, 30–60'/đề | Đúng actor chính, soạn nhiều đề nhất | Chọn câu là bottleneck; dùng lại đề cũ là hậu quả của pain |
| GV Vật lý có ngân hàng câu hỏi, dưới 30'/đề | Tín hiệu phản bác mạnh nhất | Ngân hàng câu hỏi (No AI) đã đủ giải bottleneck? |
| Gia sư Toán online, trên 2 giờ/đề, tốn nhất là dựng đề | Cùng actor gốc nhưng bottleneck khác | Bottleneck thật có thể là dựng đề (LaTeX, hình vẽ) chứ không phải chọn câu |

Snapshot sẽ được điền nguyên văn ngay sau từng buổi phỏng vấn thật.

Bằng chứng thứ cấp (desk research, không phải phỏng vấn): [`report/assets/cp4-desk-research.md`](../assets/cp4-desk-research.md).

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Survey Google Form | 10 | 4/10 mất từ 1 giờ trở lên mỗi đề; 5/10 nói bước tìm và chọn câu tốn nhất; 6/10 đã phải dùng lại đề cũ trong tháng này | 6/10 mất dưới 1 giờ, nên baseline 63–75' của Minh Đức cao hơn số đông; 5/10 có bottleneck khác (kiểm tra đáp án, gõ lại, đưa lên hệ thống); **3 người có ngân hàng câu hỏi: 2 người dưới 30', 1 người 30–60', không ai mất từ 1 giờ trở lên** (so với 4/7 người chưa có ngân hàng), gợi ý phương án No AI (ngân hàng câu hỏi) có thể đã đủ; gia sư Toán online duy nhất mất trên 2 giờ nhưng bottleneck là gõ lại/dựng đề chứ không phải chọn câu; 1 người đã tự dùng AI |
| Desk research (khảo sát Tennessee 2019, 3 bài Giáo dục Việt Nam, RMIT/Elkins 2024, Chartered College, arXiv Quiz Design Task) | 7 nguồn | ~70% giáo viên dành >4 giờ/tuần tạo/tìm tài liệu; báo VN: ra đề tốn công, ngân hàng câu hỏi còn ít | Elkins 2024: thời gian viết quiz bằng AI ≈ tự viết vì phải duyệt; báo VN: nguyên nhân gốc là thiếu ngân hàng câu hỏi và kỹ năng ra đề (giải được bằng No AI) |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
- Thu hẹp actor: gia sư/giáo viên **chưa có ngân hàng câu hỏi gắn nhãn** và soạn đề theo bài học riêng, vì cả 3 người có ngân hàng câu hỏi đều soạn dưới 1 giờ. Không giới hạn ở môn Toán online nữa (survey có 6 môn).
- Baseline dùng số của survey: trong 7 người chưa có ngân hàng câu hỏi, 3 người 30–60', 3 người 1–2 giờ, 1 người trên 2 giờ (trung vị nằm ở khoảng 1–2 giờ/đề). Quy trình bấm giờ 63–75' của Minh Đức giữ làm ví dụ chi tiết từng bước ở mục 4.1.
- Ghi nhận bottleneck không giống nhau: 4/7 người chưa có ngân hàng nói tốn nhất là tìm và chọn câu, 2/7 là gõ lại/dựng đề. Giải pháp tập trung vào chọn câu; gõ lại/dựng đề xử lý bằng template (No AI).
- Bổ sung "kiểm tra đáp án" là bước phải giữ cho con người (2/10 coi là bước tốn nhất, và đây là chỗ AI dễ sai nhất).
- Success metric phải đo cả **thời gian duyệt** đầu ra AI, không chỉ thời gian tạo đề (theo nghiên cứu Elkins 2024: thời gian tiết kiệm bị dồn sang khâu duyệt).
- Kết quả "người có ngân hàng câu hỏi nhanh hơn" là lý do chính để quyết định **Not Yet**: cần so AI với phương án No AI trước.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| SmartTest | https://smarttest.vn | Bước 1b (chọn câu theo ma trận) và bước 2 (tổ hợp đề, trộn đề) | Có sẵn ngân hàng câu hỏi cho **nhiều môn cấp 3**; tổ hợp đề theo ma trận; **cho phép thay đổi trọng số (điểm) từng câu/phần trong bài thi**; có tính năng "Tạo đề với AI" (trang chủ smarttest.vn; ghi chú trên lớp) | Chưa rõ có chọn câu "hợp bài học" theo yêu cầu tự do của gia sư không, hay chỉ lọc theo nhãn có sẵn; chưa kiểm tra gắn cờ câu đã dùng cho từng nhóm học sinh; nhắm trường cấp 3, có thể không hợp gia sư cá nhân | Đối thủ đã che phần lớn quy trình → phải dùng thử SmartTest với một chủ đề trước khi kết luận có khoảng trống cho AI (lý do Not Yet) |
| Ngân hàng câu hỏi dùng chung (Tạp chí Giáo dục Việt Nam) | https://giaoduc.net.vn/ngan-hang-cau-hoi-dung-chung-cho-kiem-tra-danh-gia-hoc-sinh-can-dam-bao-yeu-to-nao-post263154.gd | Bước 1a–1b (nguồn câu hỏi) | Mô hình ngân hàng câu hỏi dùng chung cho kiểm tra, đánh giá; nêu các yêu cầu để ngân hàng dùng được (chuẩn hóa, gắn với yêu cầu cần đạt) | Xây và duy trì ngân hàng tốn nhiều công; câu hỏi dùng chung dễ bị học sinh biết trước | Ngân hàng câu hỏi gắn nhãn là phương án No AI mạnh nhất và cũng là **input bắt buộc** nếu dùng AI → phải dựng ngân hàng nhỏ trước khi pilot |
| AI tạo câu hỏi quiz — nghiên cứu Elkins et al. 2024 (tóm tắt của RMIT) | https://www.rmit.edu.au/about/educational-ai/blog/can-gen-ai-create-learning-questions-better-than-a-human | Bước 1b (chọn/soạn câu) | Câu do AI tạo được đánh giá tốt hơn khi prompt có cấu trúc sư phạm (thang Bloom) | Thời gian viết quiz bằng AI gần như bằng tự viết, vì thời gian chuyển sang khâu duyệt | Metric phải đo **cả thời gian duyệt**; AI chỉ có giá trị nếu tổng thời gian (tạo + duyệt) giảm rõ |
| Aila — công cụ AI soạn tài liệu có bước "AI judge" (Chartered College) | https://my.chartered.college/?p=37752 | Bước kiểm tra chất lượng trước khi giáo viên duyệt | Thêm bước tự chấm chất lượng quiz, kết quả sát hơn với đánh giá của giáo viên chuyên môn | Vẫn cần giáo viên duyệt cuối; chất lượng phụ thuộc bộ tiêu chí chấm | Đưa 5 tiêu chí đánh giá ở mục 7 thành bước tự kiểm của AI trước khi trình gia sư |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — ví dụ bấm giờ thật của 1 gia sư Toán: 63–75 phút/đề (3–5 đề/tuần)
(survey 7 người chưa có ngân hàng câu hỏi: 30'–2h+/đề, trung vị khoảng 1–2 giờ)

[1a Tìm đề trên mạng: 15']  ┐ ← BOTTLENECK (1a + 1b = 30')
→ [1b Chọn câu hợp bài học: 15'] ┘
→ [2 Tổng hợp thành đề, gõ lại trên Word: 30']
→ [3a Nhập đề lên trang online: 15']   hoặc   [3b In phiếu cho học sinh: 3–5']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1a | Gia sư/giáo viên | Chủ đề bài học cần ôn | Các đề tìm được trên mạng | 15' / đề | Nguồn rải rác, chất lượng không đều |
| 1b | Gia sư | Các đề tìm được | Danh sách câu hỏi hợp bài học | 15' / đề | **Bottleneck:** phải đánh giá từng câu có hợp bài học, độ khó hay không, template không làm thay được |
| 2 | Gia sư | Danh sách câu hỏi | Đề hoàn chỉnh trên Word | 30' / đề | Copy và gõ lại tay, kể cả công thức toán |
| 3a | Gia sư | Đề trên Word | Đề trên trang online | 15' / đề | Nhánh dùng khi học sinh làm bài online |
| 3b | Gia sư | Đề trên Word | Phiếu in cho học sinh | 3–5' / đề | Nhánh dùng khi học sinh làm bài trên giấy |

Tổng 75' (nhánh 3a) hoặc 63–65' (nhánh 3b); tần suất 3–5 đề/tuần. Số phút từng bước là bấm giờ của Minh Đức; tổng thời gian khớp với nhóm 1–2 giờ/đề trong survey.

**Bottleneck chính:** Bước 1 (1a + 1b, 30'/đề). Bước 2 cũng mất 30' nhưng chỉ cần giải bằng template. Bước 1b khó vì phải đánh giá câu có hợp bài học hay không, và khi không kịp thì gia sư dùng lại đề cũ nên học sinh có thể đã làm đề đó.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — Workflow, khoảng 11–19 phút/đề (kỳ vọng, chưa đo; target ≤ 30' tính cả duyệt)

[1 Con người] Gia sư nhập yêu cầu bằng ngôn ngữ tự nhiên: chủ đề, độ khó, cấu trúc đề (2')
   ↓
[2 Rule] Loại câu đã gắn cờ "đã dùng cho nhóm học sinh này", áp template cấu trúc đề (< 1')
   ↓
[3 AI] Đề xuất câu từ ngân hàng câu hỏi theo yêu cầu, kèm nguồn và đáp án (3–5')
   ├─ Nhánh 3a: ngân hàng thiếu câu đúng dạng → AI soạn câu mới, gắn nhãn "AI soạn"
   └─ Nhánh 3b: tự kiểm theo 5 tiêu chí mục 7 (đáp án, chủ đề/độ khó, trùng, công thức) → câu
      không đạt bị loại và đề xuất câu thay
   ↓
[4 Con người, HITL] Gia sư duyệt từng câu và đáp án, kiểm kỹ câu "AI soạn"; sửa/thay câu (5–8')
   │   Gia sư đổi yêu cầu → quay lại bước 1 (chỉ chạy lại phần bị đổi)
   ↓
[5 Rule] Xuất đề để in hoặc nhập lên trang online, gắn cờ các câu đã dùng (1–3')

* Boundary: AI không tự đưa đề cho học sinh; không đưa các câu của đề đang giao; không dùng lại câu đã gắn cờ cho cùng nhóm.
* Phương án quay về: nếu AI sai hoặc đáp án không đáng tin, gia sư chọn tay từ ngân hàng câu hỏi và template Word như hiện tại.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 (1a, 1b, 2, 3a hoặc 3b) | 5 (nhập yêu cầu, Rule lọc, AI đề xuất, duyệt, xuất) | Số bước không đổi, nhưng 3 bước chuyển từ làm tay sang Rule hoặc AI |
| Tổng thời gian | 63–75 phút/đề (ví dụ bấm giờ); survey: trung vị 1–2 giờ/đề | 11–19 phút/đề | Số "sau" là kỳ vọng; target ≤ 30' tính cả thời gian duyệt |
| Số bước thủ công | 5 | 2 (nhập yêu cầu, duyệt) | Gia sư vẫn quyết định cuối |
| Bottleneck chính | Bước 1: tìm và chọn câu (30') | Bước duyệt của gia sư (5–8') | Chuyển từ tìm kiếm sang kiểm tra |
| Rủi ro mới phát sinh | Dùng lại đề cũ khi không kịp | Đáp án sai hoặc câu không hợp bài học lọt ra; học sinh hỏi lộ câu của đề đang giao | Giảm bằng bước duyệt, cờ câu đã dùng và khóa câu trong đề đang giao |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Gia sư toán dạy online, tự soạn đề ôn tập cho học sinh. Dữ liệu thật hiện chỉ là của một gia sư; việc giáo viên ở trường có quy trình tương tự là giả định cần kiểm chứng |
| **Quy trình** | Trước mỗi buổi cần ôn tập: 1a. Tìm đề thi trên mạng (15') → 1b. Chọn câu hỏi hợp bài học (15') → 2. Tổng hợp thành đề, gõ lại trên Word (30') → 3a. Nhập lên trang online (15') hoặc 3b. In phiếu cho học sinh (3–5') |
| **Bottleneck** | Bước 1 (1a + 1b, 30'/đề): phải tìm và đánh giá từng câu có hợp bài học hay không, việc này không làm máy móc bằng template được. Bước 2 cũng mất 30' nhưng có thể giảm bằng template |
| **Impact** | 63–75 phút/đề; 3–5 đề/tuần, khoảng 3–6 giờ/tuần. Khi không kịp, gia sư dùng lại đề cũ có sẵn trên mạng, nên học sinh đã làm đề đó rồi và đề không sát bài học |
| **Success Metric** (baseline → target, cách đo) | Baseline: 63–75 phút/đề. Target: 15–20 phút/đề. Cách đo: bấm giờ từng bước mỗi lần soạn đề trong 4 tuần, tách nhánh 3a (75') và 3b (63–65'). |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không tự đưa đề cho học sinh; không đưa ra các câu thuộc đề đang được giao hoặc đang làm bài; không dùng lại câu đã gắn cờ (nhóm học sinh, ngày dùng, loại đề) cho cùng nhóm học sinh. Gia sư duyệt từng câu và đáp án trước khi in hoặc upload (HITL) và là người chịu trách nhiệm cuối cùng về nội dung đề. Nếu AI sai, gia sư chọn tay từ ngân hàng câu hỏi và template |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- Câu hỏi từ bạn trong nhóm: nếu cùng một ngân hàng câu hỏi được nhiều người dùng, học sinh có thể biết trước đề. Nhóm đã bổ sung vào Boundary: khóa câu trong đề đang giao và gắn cờ câu đã dùng cho từng nhóm học sinh.
- AI chỉ ra: dữ liệu baseline mới là của một gia sư nên Actor quá rộng nếu ghi cả giáo viên trường. Nhóm đồng ý và thu hẹp Actor về gia sư toán dạy online, giáo viên trường để kiểm chứng sau.
- AI chỉ ra: baseline 63–75' ghép hai nhánh loại trừ nhau (3a nhập online, 3b in phiếu). Nhóm đồng ý và tách thành 75' và 63–65' ở mục 4.
- AI chỉ ra: Boundary chưa nêu ai chịu trách nhiệm về đáp án sai. Nhóm đồng ý: gia sư là người duyệt và chịu trách nhiệm cuối cùng, ghi vào Boundary và mục 7.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **độ mơ hồ trung bình đến cao × độ phức tạp trung bình** → vùng **Workflow** (các bước biết trước, AI xử lý phần cần hiểu ngôn ngữ).

Vì sao:
- **Độ mơ hồ cao ở bước chọn câu:** yêu cầu của gia sư viết bằng ngôn ngữ tự nhiên ("ôn chương này, độ khó vừa, cấu trúc như đề cũ") và "hợp bài học" không quy được hoàn toàn thành tag hay điều kiện lọc.
- **Độ phức tạp trung bình:** quy trình rõ và lặp lại (nhập yêu cầu → lọc → chọn câu → duyệt → xuất đề). Các tình huống khác nhau (ngân hàng thiếu câu, câu trùng, gia sư đổi yêu cầu) đều biết trước nên viết được thành nhánh rẽ cố định, không cần AI tự quyết bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Dùng công cụ có sẵn như SmartTest (ngân hàng câu hỏi, tổ hợp đề theo ma trận, nhập câu từ Word), hoặc tự làm template Word theo cấu trúc đề cố định cộng ngân hàng câu hỏi phân loại theo chủ đề; mỗi lần chỉ chọn câu bỏ vào template | Khi ngân hàng câu hỏi đã có sẵn và gắn nhãn đủ, và việc chọn câu hợp bài học chủ yếu là lọc theo chủ đề/độ khó. Giảm được bước 2 (gõ lại, 30') | Chi phí dựng ngân hàng ban đầu lớn so với 63–75' mỗi đề; ngân hàng không có sẵn câu hợp bài học thì bước 1b vẫn thủ công; bản quyền đề trên mạng | ⚠️ Chưa biết, phải kiểm chứng trước: survey cho thấy 3 người có ngân hàng câu hỏi đều soạn dưới 1 giờ, nên No AI có thể đã đủ cho người có ngân hàng. Với người chưa có ngân hàng, bước chọn câu hợp bài học vẫn thủ công. Đây là lý do quyết định Not Yet |
| **Rule** | Quy tắc cố định: lọc câu theo tag (chủ đề, độ khó, dạng bài), chọn theo ma trận đề, loại câu đã gắn cờ "đã dùng cho nhóm học sinh này" | Khi câu hỏi đã được gắn nhãn đúng và yêu cầu của gia sư chuyển được thành điều kiện lọc rõ ràng. Giải quyết được 1a và một phần 1b, và xử lý việc trùng đề | Chỉ chọn được câu đã có trong ngân hàng và đã gắn nhãn; không hiểu ngữ cảnh "hợp bài học" nằm ngoài tag; cần công sức gắn nhãn ban đầu | ➕ Dùng làm một phần của Workflow (lọc câu đã gắn cờ, template, xuất đề), không thay được việc chọn câu theo ngữ cảnh |
| **Workflow** | Các bước định sẵn, AI làm một phần: gia sư nhập yêu cầu (chủ đề, độ khó, cấu trúc đề) → AI đề xuất các câu phù hợp từ ngân hàng hoặc nguồn có sẵn → gia sư duyệt câu và đáp án → xuất đề để in hoặc upload | Khi tag và điều kiện lọc không đủ để chọn câu hợp bài học, hoặc ngân hàng thiếu câu đúng dạng, và gia sư vẫn kiểm tra được đầu ra | Đáp án hoặc câu sai lọt ra cho học sinh; câu không hợp bài học; trùng đề; công thức toán hiển thị lỗi; chi phí vận hành. Giảm bằng bước gia sư duyệt và cờ câu đã dùng | ✅ Chọn: thứ tự bước cố định; các tình huống ngân hàng thiếu câu, câu trùng, đổi yêu cầu xử lý bằng nhánh rẽ định sẵn (mục 4.2) |
| **Agent** (có giám sát) | Gia sư nhập yêu cầu bằng ngôn ngữ tự nhiên; AI tự quyết bước tiếp theo: tìm nguồn, chọn câu, soạn thêm khi thiếu, tự kiểm tra độ phủ chủ đề, độ khó, trùng câu và đáp án, rồi trình bản nháp. Gia sư duyệt trước khi in hoặc upload; AI không trực tiếp làm việc với học sinh | Khi yêu cầu thay đổi theo từng lần, số bước không định sẵn được, và gia sư vẫn duyệt được đầu ra | Đáp án sai hoặc câu không hợp bài học lọt ra; AI tự quyết sai bước; chi phí và độ trễ cao hơn; khó kiểm tra và khó tái hiện lỗi; lộ câu của đề đang giao | ❌ Không chọn: mọi nhánh đều biết trước nên không cần AI tự quyết bước; thêm quyền tự quyết chỉ thêm rủi ro mà không thêm giá trị |

**Mức chọn:** **Workflow** có người duyệt (human-in-the-loop). Rule lo phần lọc, template và xuất đề; AI chỉ làm bước đề xuất/soạn câu và tự kiểm theo tiêu chí; gia sư duyệt và chịu trách nhiệm cuối cùng.

**Vì sao không chọn mức đơn giản hơn:**
- **So với No AI (SmartTest, template):** các công cụ này đã có ngân hàng câu hỏi, tổ hợp đề theo ma trận và trộn đề, nhưng đều yêu cầu gia sư tự chọn câu hoặc điền điều kiện lọc. Khoảng trống còn lại là bước 1b (chọn câu hợp bài học) và việc tự đánh giá lại đề trước khi duyệt.
- **So với Rule:** tag và điều kiện lọc chỉ chọn được câu đã gắn nhãn; yêu cầu bằng ngôn ngữ tự nhiên và "hợp bài học" nằm ngoài tag nên Rule không đủ.
- **Vì sao không lên Agent:** bản nháp đầu của nhóm chọn Agent vì nghĩ số bước thay đổi theo từng yêu cầu. Khi phản biện lại (Ngọc Quang), nhóm thấy ba tình huống "ngân hàng thiếu câu", "câu trùng", "gia sư đổi yêu cầu" đều biết trước và viết được thành nhánh rẽ cố định (mục 4.2). Agent chỉ cần khi không biết trước bước tiếp theo; ở đây thêm quyền tự quyết chỉ làm tăng rủi ro đáp án sai, chi phí và độ khó kiểm tra.
- Đây là giả định thiết kế, chưa kiểm chứng bằng người dùng; nếu kiểm chứng cho thấy ngân hàng câu hỏi (No AI) hoặc SmartTest đã đủ thì quay về mức đó (xem ngưỡng dừng ở mục 8).

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Bộ câu hỏi phù hợp với yêu cầu (chủ đề, độ khó, cấu trúc đề), đáp án đi kèm và nhận xét về độ phủ, độ khó, trùng câu |
| **Judgment** — con người cân nhắc, quyết định gì? | Gia sư quyết định câu nào hợp bài học, đáp án đúng hay sai, giữ, thay hay bỏ câu, và có dùng đề này cho nhóm học sinh đó không |
| **Action** — hành động cuối cùng là gì, ai làm? | Gia sư duyệt, xuất đề để in hoặc nhập lên trang online, rồi gắn cờ các câu đã dùng; AI không giao đề cho học sinh |
| **Outcome** — đo kết quả bằng gì? | Tổng thời gian soạn mỗi đề **tính cả thời gian duyệt** (trung vị 1–2 giờ → ≤ 30'); tỉ lệ câu gia sư phải sửa hoặc thay; số lần trùng câu đã dùng |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Yêu cầu của gia sư; ngân hàng câu hỏi có nhãn (chủ đề, độ khó, dạng bài) và đáp án; danh sách câu đã dùng cho từng nhóm học sinh. Hiện chưa có sẵn, phải dựng từ đề cũ và nguồn có sẵn, và cần xử lý bản quyền |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Hành động sửa, thay hoặc bỏ câu của gia sư trên bản nháp; nút báo "đáp án sai" hoặc "không hợp bài"; kết quả bài làm của học sinh |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: **được hỗ trợ**. Trong quy trình hiện tại, gia sư chọn câu vì phải đánh giá câu có hợp bài học hay không (bước 1b), và phải kiểm tra đáp án trước khi cho học sinh làm. Đây là việc cần phán đoán chuyên môn, nên gia sư không giao hẳn. Bằng chứng: quy trình của gia sư trong nhóm; survey 10 người (cả 10 vẫn tự soạn đề; chỉ 1 người có AI trong bộ công cụ, cùng với Word và đề trên mạng); desk research (Elkins 2024, Aila) cho thấy giáo viên vẫn duyệt đầu ra AI. Chưa có phỏng vấn sâu xác nhận (đã lên kế hoạch ở mục 3.2).
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: **báo nhầm tệ hơn**, tức là AI đưa ra câu hoặc đáp án sai nhưng trông đúng. Nếu lọt ra cho học sinh thì học sinh học sai và gia sư mất uy tín. Nếu AI bỏ sót một câu hay thì gia sư chỉ mất thêm vài phút tìm thay. Thiết kế: gia sư duyệt từng câu và đáp án, AI kèm nguồn câu hỏi và cách giải để dễ đối chiếu, có nút báo "đáp án sai", và ưu tiên bỏ câu không chắc thay vì đưa ra.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Gia sư/giáo viên tự soạn đề ôn tập theo bài học riêng, **chưa có ngân hàng câu hỏi gắn nhãn** (survey: 7/10 người) |
| **Quy trình** | Gia sư nhập yêu cầu bằng ngôn ngữ tự nhiên → Rule loại câu đã gắn cờ và áp template cấu trúc đề → AI đề xuất câu từ ngân hàng (thiếu thì soạn thêm, gắn nhãn "AI soạn") và tự kiểm theo 5 tiêu chí → **gia sư duyệt (HITL)** → Rule xuất đề để in hoặc nhập online và gắn cờ câu đã dùng. Thay cho 1a, 1b, 2 và 3 thủ công ở v0 |
| **Bottleneck** | Bước 1 (1a + 1b, 30'/đề trong ví dụ bấm giờ): tìm và đánh giá từng câu có hợp bài học hay không. Survey: 4/7 người chưa có ngân hàng câu hỏi nói đây là bước tốn nhất |
| **Impact** | Survey: 7 người chưa có ngân hàng câu hỏi mỗi người mất khoảng 2 đến hơn 20 giờ/tháng cho việc soạn đề (4–20 đề/tháng × 30'–2h+/đề; trung vị 1–2 giờ/đề); 6/10 người đã phải dùng lại đề cũ trong tháng này vì không kịp |
| **Success Metric** (baseline → target, cách đo) | (1) Tổng thời gian soạn mỗi đề **tính cả thời gian duyệt**: trung vị 1–2 giờ (survey), 63–75' (bấm giờ) → ≤ 30'. (2) Tỉ lệ câu gia sư phải sửa hoặc thay ≤ 30%. (3) Số lần dùng lại đề cũ vì không kịp: 6/10 người trong tháng → giảm một nửa. Cách đo: bấm giờ riêng phần tạo và phần duyệt mỗi đề trong 4 tuần pilot; đếm câu bị sửa/thay; hỏi lại câu 5 của survey sau pilot |
| **Boundary** | AI không tự đưa đề cho học sinh; không dùng lại câu đã gắn cờ cho cùng nhóm học sinh; không đưa đáp án chưa qua kiểm tra; không làm việc trực tiếp với học sinh. Gia sư duyệt từng câu và đáp án trước khi in hoặc upload và chịu trách nhiệm cuối cùng về nội dung đề |
| **AI intervention point** | Chỉ bước chọn câu hợp bài học (1b): AI nhận yêu cầu (chủ đề, độ khó, cấu trúc đề), đề xuất câu từ ngân hàng, soạn thêm khi thiếu, tự kiểm theo 5 tiêu chí rồi trình bản nháp. Lọc, template và xuất đề do Rule làm |
| **Mức chọn** | **Workflow.** Vì sao không chọn mức đơn giản hơn: Rule chỉ lọc theo nhãn, không hiểu yêu cầu bằng ngôn ngữ tự nhiên và "hợp bài học"; No AI (ngân hàng câu hỏi, SmartTest) có thể đủ cho người đã có ngân hàng nhưng chưa giải được bước chọn câu cho người chưa có — cần kiểm chứng. Vì sao không lên Agent: các nhánh (thiếu câu, trùng câu, đổi yêu cầu) đều biết trước, không cần AI tự quyết bước |
| **Rủi ro & người kiểm tra** | Rủi ro: đáp án sai hoặc câu không hợp bài học lọt ra cho học sinh; trùng đề với đề đã giao. Người kiểm tra: gia sư duyệt từng câu và đáp án trước khi dùng. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Quy trình | 4 bước làm tay (1a, 1b, 2, 3) | Nhập yêu cầu → Rule → AI → gia sư duyệt → xuất đề | Chỉ ra bước nào Rule, AI hoặc con người làm, để thấy AI chen vào đâu |
| AI intervention point | Chưa có | AI tìm, chọn, soạn thêm và tự kiểm tra câu ở bước 1b | v1 là phiên bản có AI; cần nêu rõ điểm can thiệp |
| Actor | Gia sư toán dạy online (dữ liệu của 1 người) | Gia sư/giáo viên chưa có ngân hàng câu hỏi gắn nhãn, nhiều môn | Survey: 3 người có ngân hàng câu hỏi đều soạn dưới 1 giờ; 4/7 người chưa có mất từ 1 giờ trở lên; survey có 6 môn chứ không riêng Toán |
| Success Metric | Baseline 63–75' → 15–20', chỉ đo thời gian soạn | Baseline trung vị 1–2 giờ (survey) → ≤ 30' **tính cả duyệt**; thêm tỉ lệ câu phải sửa và số lần dùng lại đề cũ | Baseline của 1 người cao hơn đa số; Elkins 2024: thời gian tiết kiệm bị dồn sang khâu duyệt nên phải đo cả duyệt |
| Mức chọn | Chưa chọn (bản nháp đầu: Agent) | Workflow | So sánh 4 mức ở mục 6: các nhánh đều biết trước, viết được thành Workflow; Agent chỉ thêm rủi ro |
| Boundary | AI không tự đưa đề, không dùng lại câu gắn cờ, gia sư duyệt | Thêm: AI không làm việc trực tiếp với học sinh; câu "AI soạn" phải gắn nhãn và được duyệt kỹ; gia sư chịu trách nhiệm cuối cùng | Desk research: câu do AI soạn dễ sai đáp án; 2/10 người trong survey coi kiểm tra đáp án là bước tốn nhất |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đáp án đúng | Đáp án của mọi câu được gia sư đối chiếu đều đúng; tối thiểu 95% câu có đáp án đúng ngay từ bản nháp của AI (kiểm trên 10 đề) | Có đáp án sai lọt qua bước duyệt, hoặc dưới 95% câu đúng ngay từ bản nháp |
| 2 | Hợp yêu cầu | Tối thiểu 90% câu đúng chủ đề và độ khó gia sư yêu cầu; đúng cấu trúc đề (đủ số câu mỗi phần) | Có câu lạc chủ đề, sai độ khó nghiêm trọng, hoặc thiếu phần của cấu trúc đề |
| 3 | Không trùng đề | 0 câu trùng với câu đã gắn cờ cho cùng nhóm học sinh | Có câu trùng với đề đã giao cho cùng nhóm |
| 4 | Công thức hiển thị đúng | Công thức toán hiển thị đúng ở cả bản in và bản online | Công thức bị lỗi, mất ký hiệu hoặc phải gõ lại |
| 5 | Tiết kiệm thời gian, tính cả duyệt | Tổng thời gian soạn mỗi đề (tạo + duyệt) ≤ 30 phút; gia sư phải sửa hoặc thay không quá 30% số câu | Tổng thời gian trên 30 phút, hoặc gia sư phải sửa hoặc thay hơn 30% số câu |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Trung bình** | Survey 10 người: 4/10 mất từ 1 giờ trở lên mỗi đề, 6/10 đã phải dùng lại đề cũ trong tháng này → pain có thật. Nhưng 3 người có ngân hàng câu hỏi đều soạn dưới 1 giờ, SmartTest đã có ngân hàng câu hỏi, tổ hợp đề theo ma trận và "Tạo đề với AI", và chưa có phỏng vấn sâu → chưa chắc AI hơn phương án No AI |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Thấp** | Gia sư là chuyên gia môn học và tự duyệt từng câu và đáp án; yêu cầu nhập bằng ngôn ngữ tự nhiên nên không phải học giao diện mới. Rủi ro nhỏ: duyệt tốn thời gian nếu AI sai nhiều |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Cao** | Cần ngân hàng câu hỏi có nhãn và đáp án (chưa có sẵn, phải dựng từ đề cũ và nguồn mở); cần hiển thị công thức toán; AI có thể sai đáp án toán; cần xử lý bản quyền đề trên mạng. Input chính của AI (ngân hàng câu hỏi gắn nhãn) **hiện chưa có** (mục 6.3) |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **Trung bình** | Chi phí gọi AI cho vài đề mỗi tuần thấp, nhưng bản quyền nội dung đề, công sức dựng và duy trì ngân hàng, và người vận hành (gia sư tự làm hay có đơn vị hỗ trợ) chưa rõ |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:**
- **Feasibility ở mức Cao:** input bắt buộc của AI là ngân hàng câu hỏi gắn nhãn kèm đáp án, hiện chưa có và phải dựng từ đầu, kèm vấn đề bản quyền.
- **Value ở mức Trung bình:** survey xác nhận pain, nhưng cũng cho thấy người có ngân hàng câu hỏi (No AI) đã nhanh; chưa so với SmartTest và chưa phỏng vấn sâu.
- Vì một rủi ro Cao có thể giảm bằng kiểm chứng và một bước chuẩn bị nhỏ (dựng ngân hàng cho 1 chủ đề), quyết định là Not Yet chứ không phải No-Go.
- Chi phí kiểm chứng thấp hơn nhiều so với chi phí xây.

**Nếu Go — pilot nhỏ nhất:** một gia sư chưa có ngân hàng câu hỏi dùng Workflow chạy bằng prompt thủ công trên ngân hàng nhỏ (1 chủ đề, ~50 câu gắn nhãn), 5 đề liên tiếp; gia sư duyệt từng câu và đáp án, bấm giờ riêng phần tạo và phần duyệt, đếm số câu phải sửa.

**Nếu Not Yet — cần kiểm chứng gì trước:**
1. Phỏng vấn 3 người đã chọn ở mục 3.2 (rồi mở rộng lên 5) theo bộ câu hỏi CP4, đặc biệt người có ngân hàng câu hỏi, để biết phương án No AI có đủ không.
2. Thử SmartTest thật với một chủ đề và ghi bước nào vẫn phải làm tay, để xác định khoảng trống.
3. Kiểm tra nguồn câu hỏi hợp pháp và công thức toán có hiển thị được không.

**Nếu No-Go — nên làm gì thay AI:** dùng template Word cộng ngân hàng câu hỏi gắn nhãn, hoặc dùng SmartTest cho phần ma trận và trộn đề, và thêm cờ câu đã dùng bằng bảng tính.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): nếu sau 4 tuần pilot tổng thời gian soạn mỗi đề (tính cả duyệt) vẫn trên 30 phút (baseline trung vị 1–2 giờ), hoặc gia sư phải sửa hoặc thay hơn 30% số câu, hoặc có đáp án sai lọt qua bước duyệt, thì dừng phần AI và quay về template Word cộng ngân hàng câu hỏi gắn nhãn (hoặc SmartTest). Ngoài ra, nếu phỏng vấn cho thấy người có ngân hàng câu hỏi không còn bước chọn câu tốn thời gian thì chuyển sang No-Go và hướng dẫn dựng ngân hàng câu hỏi thay vì làm AI.

---

## 9. Hạn chế và hướng tiếp theo

- **Hạn chế:** quy trình chi tiết từng bước là bấm giờ của một gia sư; survey chỉ có 10 người, câu thời gian là khoảng (30–60', 1–2 giờ…) chứ không phải số phút; chưa có phỏng vấn sâu; các số "sau" ở mục 4 là kỳ vọng, chưa đo; ngân hàng câu hỏi, bản quyền đề và hiển thị công thức toán chưa được giải quyết.
- **Hướng tiếp theo:** phỏng vấn 3 người đã chọn ở mục 3.2; thử SmartTest với một chủ đề; dựng ngân hàng câu hỏi nhỏ cho một chủ đề rồi chạy pilot 5 đề với bước duyệt của gia sư.

## 10. Tài liệu tham khảo

1. SmartTest: https://smarttest.vn
2. Tạp chí Giáo dục Việt Nam, "Ngân hàng câu hỏi dùng chung cho kiểm tra, đánh giá học sinh cần đảm bảo yếu tố nào?": https://giaoduc.net.vn/ngan-hang-cau-hoi-dung-chung-cho-kiem-tra-danh-gia-hoc-sinh-can-dam-bao-yeu-to-nao-post263154.gd
3. Tennessee Department of Education, Educator Survey 2019 (infographic): https://www.tn.gov/content/dam/tn/education/data/2019-survey/Lessons_District_Leaders_Infographic.pdf
4. Giáo dục Việt Nam, "Đề kiểm tra học kỳ II năm nay rất khác với những năm trước đây": https://giaoduc.net.vn/de-kiem-tra-hoc-ky-ii-nam-nay-rat-khac-voi-nhung-nam-truoc-day-post209834.gd
5. Giáo dục Việt Nam, "Một số khó khăn cần khắc phục trong khâu ra đề, coi thi với các môn trắc nghiệm": https://giaoduc.net.vn/ban-in/post173487.gd
6. Giáo dục Việt Nam, "Giáo viên không có năng lực ra đề kiểm tra còn có nguyên nhân nào khác?": https://giaoduc.net.vn/gdvn-post205560.gd
7. RMIT, "Can Gen AI create learning questions better than a human?" (tóm tắt Elkins et al., 2024): https://www.rmit.edu.au/about/educational-ai/blog/can-gen-ai-create-learning-questions-better-than-a-human
8. Chartered College of Teaching, "How can we drive up quality standards in AI-generated teaching resources?": https://my.chartered.college/?p=37752
9. "Quiz Design Task: Helping Teachers Create Quizzes with Automated Question Generation" (arXiv 2205.01730): https://arxiv.org/pdf/2205.01730
10. Google PAIR, *People + AI Guidebook*, "User Needs + Defining Success": https://pair.withgoogle.com/chapter/user-needs/
11. Anthropic, "Building effective agents": https://www.anthropic.com/research/building-effective-agents
12. Marty Cagan, "The Four Big Risks": https://www.svpg.com/four-big-risks/
13. Rob Fitzpatrick, *The Mom Test*: https://www.momtestbook.com/
