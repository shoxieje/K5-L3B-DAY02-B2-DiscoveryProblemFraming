# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — 63–75 phút/đề (3–5 đề/tuần)

[1a Tìm đề trên mạng: 15']  ┐ ← BOTTLENECK (1a + 1b = 30')
→ [1b Chọn câu hợp bài học: 15'] ┘
→ [2 Tổng hợp thành đề, gõ lại trên Word: 30']
→ [3a Nhập đề lên trang online: 15']   hoặc   [3b In phiếu cho học sinh: 3–5']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1a | Gia sư | Chủ đề bài học cần ôn | Các đề tìm được trên mạng | 15' / đề | Nguồn rải rác, chất lượng không đều |
| 1b | Gia sư | Các đề tìm được | Danh sách câu hỏi hợp bài học | 15' / đề | **Bottleneck:** phải đánh giá từng câu có hợp bài học, độ khó hay không, template không làm thay được |
| 2 | Gia sư | Danh sách câu hỏi | Đề hoàn chỉnh trên Word | 30' / đề | Copy và gõ lại tay, kể cả công thức toán |
| 3a | Gia sư | Đề trên Word | Đề trên trang online | 15' / đề | Nhánh dùng khi học sinh làm bài online |
| 3b | Gia sư | Đề trên Word | Phiếu in cho học sinh | 3–5' / đề | Nhánh dùng khi học sinh làm bài trên giấy |

Tổng 75' (nhánh 3a) hoặc 63–65' (nhánh 3b); tần suất 3–5 đề/tuần.

**Bottleneck chính:** Bước 1 (1a + 1b, 30'/đề). Bước 2 cũng mất 30' nhưng chỉ cần giải bằng template. Bước 1b khó vì phải đánh giá câu có hợp bài học hay không, và khi không kịp thì gia sư dùng lại đề cũ nên học sinh có thể đã làm đề đó.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — khoảng 11–18 phút/đề (kỳ vọng, chưa đo)

[Con người] Gia sư nhập yêu cầu bằng ngôn ngữ tự nhiên: chủ đề, độ khó, cấu trúc đề (2')
   ↓
[Rule] Loại các câu đã gắn cờ "đã dùng cho nhóm học sinh này" và áp template cấu trúc đề
   ↓
[AI, mức Agent có giám sát] Tìm và chọn câu từ ngân hàng/nguồn có sẵn, soạn thêm khi thiếu,
   tự kiểm tra độ phủ chủ đề, độ khó, trùng câu, đáp án (3–5')
   ↓
[Con người, HITL] Gia sư duyệt từng câu và đáp án, sửa hoặc thay câu (5–8')
   ↓
[Rule] Xuất đề theo định dạng in hoặc nhập sẵn lên trang online và gắn cờ các câu đã dùng (1–3')

* Boundary: AI không tự đưa đề cho học sinh; không đưa các câu của đề đang giao; không dùng lại câu đã gắn cờ cho cùng nhóm.
* Phương án quay về: nếu AI sai hoặc đáp án không đáng tin, gia sư chọn tay từ ngân hàng câu hỏi và template Word như hiện tại.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 4 (1a, 1b, 2, 3) | 4 (nhập yêu cầu, AI chọn, duyệt, xuất) | Số bước không đổi, nhưng 3 bước chuyển từ làm tay sang Rule hoặc AI |
| Tổng thời gian | 63–75 phút/đề | 11–18 phút/đề | Số "sau" là kỳ vọng, mục tiêu 15–20' |
| Số bước thủ công | 4 | 2 (nhập yêu cầu, duyệt) | Gia sư vẫn quyết định cuối |
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

Bài của nhóm nằm ở ô: **độ mơ hồ trung bình đến cao × độ phức tạp trung bình**.

Vì sao:
- **Độ mơ hồ cao ở bước chọn câu:** yêu cầu của gia sư viết bằng ngôn ngữ tự nhiên ("ôn chương này, độ khó vừa, cấu trúc như đề cũ") và "hợp bài học" không quy được hoàn toàn thành tag hay điều kiện lọc.
- **Độ phức tạp trung bình:** quy trình khá rõ (nhập yêu cầu → chọn câu → duyệt → xuất đề), nhưng số bước thực tế thay đổi theo từng yêu cầu: có lần ngân hàng đủ câu, có lần phải tìm thêm hoặc soạn thêm, có lần phải thay câu trùng.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Dùng công cụ có sẵn như SmartTest (ngân hàng câu hỏi, tổ hợp đề theo ma trận, nhập câu từ Word), hoặc tự làm template Word theo cấu trúc đề cố định cộng ngân hàng câu hỏi phân loại theo chủ đề; mỗi lần chỉ chọn câu bỏ vào template | Khi ngân hàng câu hỏi đã có sẵn và gắn nhãn đủ, và việc chọn câu hợp bài học chủ yếu là lọc theo chủ đề/độ khó. Giảm được bước 2 (gõ lại, 30') | Chi phí dựng ngân hàng ban đầu lớn so với 63–75' mỗi đề; ngân hàng không có sẵn câu hợp bài học thì bước 1b vẫn thủ công; bản quyền đề trên mạng | ❌ Không đủ: chỉ thay được bước gõ lại, bước chọn câu hợp bài học vẫn thủ công |
| **Rule** | Quy tắc cố định: lọc câu theo tag (chủ đề, độ khó, dạng bài), chọn theo ma trận đề, loại câu đã gắn cờ "đã dùng cho nhóm học sinh này" | Khi câu hỏi đã được gắn nhãn đúng và yêu cầu của gia sư chuyển được thành điều kiện lọc rõ ràng. Giải quyết được 1a và một phần 1b, và xử lý việc trùng đề | Chỉ chọn được câu đã có trong ngân hàng và đã gắn nhãn; không hiểu ngữ cảnh "hợp bài học" nằm ngoài tag; cần công sức gắn nhãn ban đầu | ❌ Không đủ: dùng làm một phần của giải pháp (cờ câu đã dùng, template), không thay được việc chọn câu theo ngữ cảnh |
| **Workflow** | Các bước định sẵn, AI làm một phần: gia sư nhập yêu cầu (chủ đề, độ khó, cấu trúc đề) → AI đề xuất các câu phù hợp từ ngân hàng hoặc nguồn có sẵn → gia sư duyệt câu và đáp án → xuất đề để in hoặc upload | Khi tag và điều kiện lọc không đủ để chọn câu hợp bài học, hoặc ngân hàng thiếu câu đúng dạng, và gia sư vẫn kiểm tra được đầu ra | Đáp án hoặc câu sai lọt ra cho học sinh; câu không hợp bài học; trùng đề; công thức toán hiển thị lỗi; chi phí vận hành. Giảm bằng bước gia sư duyệt và cờ câu đã dùng | ❌ Chưa chọn: thứ tự các bước cố định, nên khó xử lý khi ngân hàng thiếu câu, phải soạn thêm hoặc đổi yêu cầu giữa chừng |
| **Agent** (có giám sát) | Gia sư nhập yêu cầu bằng ngôn ngữ tự nhiên; AI tự quyết bước tiếp theo: tìm nguồn, chọn câu, soạn thêm khi thiếu, tự kiểm tra độ phủ chủ đề, độ khó, trùng câu và đáp án, rồi trình bản nháp. Gia sư duyệt trước khi in hoặc upload; AI không trực tiếp làm việc với học sinh | Khi yêu cầu thay đổi theo từng lần, số bước không định sẵn được, và gia sư vẫn duyệt được đầu ra | Đáp án sai hoặc câu không hợp bài học lọt ra; AI tự quyết sai bước; chi phí và độ trễ cao hơn; lộ câu của đề đang giao. Giảm bằng Boundary (AI không tiếp xúc học sinh), cờ câu đã dùng và bước duyệt bắt buộc | ✅ Chọn |

**Mức chọn:** Agent có giám sát (human-in-the-loop). AI tự quyết cách tìm, chọn và kiểm tra câu trong phạm vi yêu cầu của gia sư; gia sư là người duyệt và chịu trách nhiệm cuối cùng.

**Vì sao không chọn mức đơn giản hơn:**
- **So với No AI (SmartTest, template):** các công cụ này đã có ngân hàng câu hỏi, tổ hợp đề theo ma trận và trộn đề, nhưng đều yêu cầu gia sư tự chọn câu hoặc điền điều kiện lọc. Khoảng trống còn lại là bước 1b (chọn câu hợp bài học) và việc tự đánh giá lại đề trước khi duyệt.
- **So với Rule:** tag và điều kiện lọc chỉ chọn được câu đã gắn nhãn; yêu cầu bằng ngôn ngữ tự nhiên và "hợp bài học" nằm ngoài tag nên Rule không đủ.
- **So với Workflow:** Workflow cần thứ tự bước cố định. Bài này không cố định được: khi ngân hàng thiếu câu thì phải tìm thêm hoặc soạn thêm, khi phát hiện trùng thì phải thay, khi gia sư đổi yêu cầu thì phải làm lại một phần. AI cần tự quyết bước tiếp theo trong từng trường hợp, nên chọn Agent, nhưng giới hạn quyền bằng Boundary và bước duyệt của gia sư.
- Đây là giả định thiết kế, chưa được kiểm chứng bằng người dùng; nếu kiểm chứng cho thấy Rule hoặc SmartTest đã đủ thì quay về mức đó (xem ngưỡng dừng ở mục 8).

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Bộ câu hỏi phù hợp với yêu cầu (chủ đề, độ khó, cấu trúc đề), đáp án đi kèm và nhận xét về độ phủ, độ khó, trùng câu |
| **Judgment** — con người cân nhắc, quyết định gì? | Gia sư quyết định câu nào hợp bài học, đáp án đúng hay sai, giữ, thay hay bỏ câu, và có dùng đề này cho nhóm học sinh đó không |
| **Action** — hành động cuối cùng là gì, ai làm? | Gia sư duyệt, xuất đề để in hoặc nhập lên trang online, rồi gắn cờ các câu đã dùng; AI không giao đề cho học sinh |
| **Outcome** — đo kết quả bằng gì? | Thời gian soạn mỗi đề (63–75' → 15–20'); tỉ lệ câu gia sư phải sửa hoặc thay; số lần trùng câu đã dùng |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Yêu cầu của gia sư; ngân hàng câu hỏi có nhãn (chủ đề, độ khó, dạng bài) và đáp án; danh sách câu đã dùng cho từng nhóm học sinh. Hiện chưa có sẵn, phải dựng từ đề cũ và nguồn có sẵn, và cần xử lý bản quyền |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Hành động sửa, thay hoặc bỏ câu của gia sư trên bản nháp; nút báo "đáp án sai" hoặc "không hợp bài"; kết quả bài làm của học sinh |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: **được hỗ trợ**. Trong quy trình hiện tại, gia sư chọn câu vì phải đánh giá câu có hợp bài học hay không (bước 1b), và phải kiểm tra đáp án trước khi cho học sinh làm. Đây là việc cần phán đoán chuyên môn, nên gia sư không giao hẳn. Bằng chứng này đến từ quy trình của chính gia sư trong nhóm, chưa có phỏng vấn người thứ hai xác nhận.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: **báo nhầm tệ hơn**, tức là AI đưa ra câu hoặc đáp án sai nhưng trông đúng. Nếu lọt ra cho học sinh thì học sinh học sai và gia sư mất uy tín. Nếu AI bỏ sót một câu hay thì gia sư chỉ mất thêm vài phút tìm thay. Thiết kế: gia sư duyệt từng câu và đáp án, AI kèm nguồn câu hỏi và cách giải để dễ đối chiếu, có nút báo "đáp án sai", và ưu tiên bỏ câu không chắc thay vì đưa ra.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Gia sư toán dạy online, tự soạn đề ôn tập cho học sinh |
| **Quy trình** | Gia sư nhập yêu cầu bằng ngôn ngữ tự nhiên → Rule loại câu đã gắn cờ và áp template cấu trúc đề → AI tìm, chọn, soạn thêm và tự kiểm tra câu và đáp án → **gia sư duyệt (HITL)** → Rule xuất đề để in hoặc nhập online và gắn cờ câu đã dùng. Thay cho 1a, 1b, 2 và 3 thủ công ở v0 |
| **Bottleneck** | Bước 1 (1a + 1b, 30'/đề): tìm và đánh giá từng câu có hợp bài học hay không |
| **Impact** | 63–75 phút/đề; 3–5 đề/tuần, khoảng 3–6 giờ/tuần; dùng lại đề cũ khi không kịp |
| **Success Metric** (baseline → target, cách đo) | Baseline 63–75 phút/đề → target 15–20 phút/đề; bấm giờ mỗi lần soạn đề trong 4 tuần. |
| **Boundary** | AI không tự đưa đề cho học sinh; không dùng lại câu đã gắn cờ cho cùng nhóm học sinh; không đưa đáp án chưa qua kiểm tra; không làm việc trực tiếp với học sinh. Gia sư duyệt từng câu và đáp án trước khi in hoặc upload và chịu trách nhiệm cuối cùng về nội dung đề |
| **AI intervention point** | Bước chọn câu hợp bài học (1b): AI nhận yêu cầu của gia sư (chủ đề, độ khó, cấu trúc đề), tìm và chọn câu từ ngân hàng hoặc nguồn có sẵn, soạn thêm khi thiếu, và tự kiểm tra độ phủ, độ khó, trùng câu và đáp án trước khi trình bản nháp cho gia sư |
| **Mức chọn** | **Agent có giám sát.** Vì sao không chọn mức đơn giản hơn: SmartTest hoặc template (No AI) và Rule chỉ lọc theo nhãn, không chọn được câu hợp bài học theo yêu cầu bằng ngôn ngữ tự nhiên; Workflow cần thứ tự bước cố định nhưng bài này thay đổi theo từng yêu cầu (thiếu câu thì tìm hoặc soạn thêm, trùng thì thay, đổi yêu cầu thì làm lại một phần). Quyền của AI được giới hạn bằng Boundary và bước duyệt của gia sư |
| **Rủi ro & người kiểm tra** | Rủi ro: đáp án sai hoặc câu không hợp bài học lọt ra cho học sinh; trùng đề với đề đã giao. Người kiểm tra: gia sư duyệt từng câu và đáp án trước khi dùng. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Quy trình | 4 bước làm tay (1a, 1b, 2, 3) | Nhập yêu cầu → Rule → AI → gia sư duyệt → xuất đề | Chỉ ra bước nào Rule, AI hoặc con người làm, để thấy AI chen vào đâu |
| AI intervention point | Chưa có | AI tìm, chọn, soạn thêm và tự kiểm tra câu ở bước 1b | v1 là phiên bản có AI; cần nêu rõ điểm can thiệp |
| Mức chọn | Chưa chọn | Agent có giám sát | Sau khi so sánh 4 mức ở mục 6: Rule và Workflow không đủ vì yêu cầu thay đổi theo từng lần |
| Boundary | AI không tự đưa đề, không dùng lại câu gắn cờ, gia sư duyệt | Thêm: AI không làm việc trực tiếp với học sinh; gia sư chịu trách nhiệm cuối cùng | Mức Agent cần giới hạn quyền tự quyết chặt hơn |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đáp án đúng | Đáp án của mọi câu được gia sư đối chiếu đều đúng; tối thiểu 95% câu có đáp án đúng ngay từ bản nháp của AI (kiểm trên 10 đề) | Có đáp án sai lọt qua bước duyệt, hoặc dưới 95% câu đúng ngay từ bản nháp |
| 2 | Hợp yêu cầu | Tối thiểu 90% câu đúng chủ đề và độ khó gia sư yêu cầu; đúng cấu trúc đề (đủ số câu mỗi phần) | Có câu lạc chủ đề, sai độ khó nghiêm trọng, hoặc thiếu phần của cấu trúc đề |
| 3 | Không trùng đề | 0 câu trùng với câu đã gắn cờ cho cùng nhóm học sinh | Có câu trùng với đề đã giao cho cùng nhóm |
| 4 | Công thức hiển thị đúng | Công thức toán hiển thị đúng ở cả bản in và bản online | Công thức bị lỗi, mất ký hiệu hoặc phải gõ lại |
| 5 | Tiết kiệm thời gian và công sức duyệt | Tổng thời gian soạn mỗi đề từ 15–20 phút; gia sư phải sửa hoặc thay không quá 30% số câu | Tổng thời gian trên 30 phút, hoặc gia sư phải sửa hoặc thay hơn 30% số câu |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Trung bình** | Pain có thật với một gia sư (63–75 phút/đề, 3–5 đề/tuần), và các nguồn research cho thấy giáo viên nói chung tốn thời gian soạn đề. Nhưng chưa có kiểm chứng đủ tin cậy từ người thứ hai về bài toán này, và SmartTest đã có ngân hàng câu hỏi, tổ hợp đề theo ma trận và tính năng AI tạo câu hỏi nên khoảng trống thật còn cần xác nhận |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Thấp** | Gia sư là chuyên gia môn học và tự duyệt từng câu và đáp án; yêu cầu nhập bằng ngôn ngữ tự nhiên nên không phải học giao diện mới. Rủi ro nhỏ: duyệt tốn thời gian nếu AI sai nhiều |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Trung bình đến cao** | Cần ngân hàng câu hỏi có nhãn và đáp án (chưa có sẵn, phải dựng từ đề cũ và nguồn mở); cần hiển thị công thức toán; AI có thể sai đáp án toán; cần xử lý bản quyền đề trên mạng |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **Trung bình** | Chi phí gọi AI cho vài đề mỗi tuần thấp, nhưng bản quyền nội dung đề, công sức dựng và duy trì ngân hàng, và người vận hành (gia sư tự làm hay có đơn vị hỗ trợ) chưa rõ |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:**
- Không có rủi ro nào ở mức Cao, nhưng Value và Feasibility ở mức trung bình đến cao và đều dựa trên bằng chứng còn mỏng (chủ yếu từ một gia sư, chưa phỏng vấn đủ người, chưa so sát với SmartTest).
- Mức Agent mạnh hơn mức cần thiết nếu Rule hoặc SmartTest đã đủ; cần bằng chứng trước khi chấp nhận độ phức tạp và rủi ro đáp án sai.
- Chi phí kiểm chứng thấp hơn nhiều so với chi phí xây.

**Nếu Go — pilot nhỏ nhất:** một gia sư dùng bản nháp chạy bằng prompt thủ công cho một chủ đề toán, 5 đề liên tiếp, gia sư duyệt từng câu và đáp án, ghi thời gian và số câu phải sửa.

**Nếu Not Yet — cần kiểm chứng gì trước:**
1. Phỏng vấn ít nhất 5 gia sư hoặc giáo viên theo bộ câu hỏi CP4 (hỏi hành vi đã xảy ra) để xác nhận pain và so thời gian với 63–75 phút/đề.
2. Thử SmartTest thật với một chủ đề và ghi bước nào vẫn phải làm tay, để xác định khoảng trống.
3. Kiểm tra nguồn câu hỏi hợp pháp và công thức toán có hiển thị được không.

**Nếu No-Go — nên làm gì thay AI:** dùng template Word cộng ngân hàng câu hỏi gắn nhãn, hoặc dùng SmartTest cho phần ma trận và trộn đề, và thêm cờ câu đã dùng bằng bảng tính.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): nếu sau 4 tuần pilot thời gian soạn mỗi đề vẫn trên 30 phút (baseline 63–75'), hoặc gia sư phải sửa hoặc thay hơn 30% số câu, hoặc có đáp án sai lọt qua bước duyệt, thì dừng Agent và quay về template Word cộng ngân hàng gắn nhãn (hoặc SmartTest).

---

## 9. Hạn chế và hướng tiếp theo

- **Hạn chế:** baseline 63–75 phút/đề và quy trình chủ yếu là của một gia sư toán dạy online, chưa có kết quả phỏng vấn đủ tin cậy từ người khác; các số "sau" ở mục 4 là kỳ vọng, chưa đo; ngân hàng câu hỏi, bản quyền đề và hiển thị công thức toán chưa được giải quyết.
- **Hướng tiếp theo:** phỏng vấn thêm gia sư và giáo viên theo bộ câu hỏi CP4; thử SmartTest để xác định khoảng trống thật; dựng ngân hàng câu hỏi nhỏ cho một chủ đề toán rồi chạy pilot 5 đề với bước duyệt của gia sư.

## 10. Tài liệu tham khảo

1. SmartTest: https://smarttest.vn
2. Tạp chí Giáo dục Việt Nam, "Ngân hàng câu hỏi dùng chung cho kiểm tra, đánh giá học sinh cần đảm bảo yếu tố nào?": https://giaoduc.net.vn/ngan-hang-cau-hoi-dung-chung-cho-kiem-tra-danh-gia-hoc-sinh-can-dam-bao-yeu-to-nao-post263154.gd
3. eSchool News, "6 key trends shaping the future of K-12 assessment" (trích báo cáo của Instructure): https://www.eschoolnews.com/district-management/2022/02/15/6-key-assessments-trends/
4. GL Assessment, *Crunched by Numbers*, "Workload: teachers have their say": https://www.gl-assessment.co.uk/reports/workload/yougov-results/
5. Google PAIR, *People + AI Guidebook*, "User Needs + Defining Success": https://pair.withgoogle.com/chapter/user-needs/
6. Anthropic, "Building effective agents": https://www.anthropic.com/research/building-effective-agents
7. Marty Cagan, "The Four Big Risks": https://www.svpg.com/four-big-risks/
8. Rob Fitzpatrick, *The Mom Test*: https://www.momtestbook.com/
