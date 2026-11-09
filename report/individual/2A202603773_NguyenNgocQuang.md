# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Ngọc Quang
- MSSV: 2A202603773
- Email trường (không bắt buộc, repo có thể để public): 26ai.quangnn3@vinuni.edu.vn
- Tên nhóm: B2
- Link repo nhóm: https://github.com/shoxieje/K5-L3B-DAY02-B2-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi gặp vướng mắc trong lab, tôi muốn tìm xem câu hỏi tương tự đã được hỏi và trả lời trên Discord của lớp chưa, để có câu trả lời ngay mà không phải đăng hỏi lại rồi chờ. | Tôi; học viên lớp L3B | Ước tính: ~10–15 phút mỗi lần tìm; 2–3 lần/tuần; khoảng một nửa số lần không tìm thấy dù câu hỏi đã có người hỏi trước |
| 2 | Pain từ người khác | Khi trả lời câu hỏi trên kênh Q&A Discord, coach/TA muốn biết câu nào đã được trả lời trước đó, để không phải trả lời lại cùng một câu nhiều lần. | Coach/TA của lớp | Ước tính từ quan sát kênh Q&A: ~15–20 câu hỏi/ngày trong ngày lab, khoảng 30% là câu lặp lại (cần hỏi coach/TA để xác nhận) |
| 3 | Lặp lại | Khi phải theo dõi bài tập và thông báo nằm rải rác ở LMS, Discord, email và GitHub, tôi muốn thấy hết deadline và việc cần làm ở một chỗ, để không bỏ sót bài và không phải mở từng app mỗi ngày. | Tôi; học viên lớp L3B | Ước tính: 4 app phải kiểm tra mỗi ngày; ~15 phút/ngày; 1–2 lần suýt trễ deadline trong tháng qua |
| 4 | Lặp lại | Khi nhóm cần họp, tôi muốn tìm được khung giờ mọi người đều rảnh, để chốt lịch mà không phải nhắn qua lại cả ngày. | Tôi; các thành viên nhóm | Ước tính: ~20–30 tin nhắn và 3–4 giờ để chốt một buổi họp; 1–2 lần/tuần |
| 5 | | | | |
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Dòng 1 và 3 là ý của tôi. Dòng 2 và 4 là ý AI (Claude) gợi ý thêm; tôi giữ lại vì đã thực sự gặp. Số liệu ở cột dấu hiệu hiện là ước tính, sẽ thay bằng số đo thật.
- Ý bị bỏ: lỗi môi trường/thư viện khi code, vì mỗi lỗi một kiểu, khó vẽ thành quy trình cố định.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi phải theo dõi bài tập và thông báo nằm rải rác ở LMS, Discord, email, Phoenix và GitHub, tôi muốn thấy hết deadline và việc cần làm ở một chỗ, để không bỏ sót bài và không phải mở từng app mỗi ngày. |
| Actor | Học viên lớp L3B (tôi và các bạn cùng lớp) |
| Thời điểm / bối cảnh | Mỗi tối sau giờ học, và dày hơn vào ngày trước deadline hoặc khi coach thông báo gia hạn/đổi lịch |
| Quy trình hiện tại (3–7 bước) | 1. Mở LMS xem bài tập và hạn nộp (~3') → 2. Lướt kênh thông báo và kênh chat lớp trên Discord tìm deadline mới, gia hạn, đổi lịch (~7') → 3. Kiểm tra email trường (~3') → 4. Ghi deadline vào note/lịch cá nhân (~2') → 5. Khi có thay đổi, sửa lại note/lịch (~2', vài lần/tuần) |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 (~7 phút/ngày): thông báo về deadline, gia hạn, đổi lịch nằm lẫn trong rất nhiều tin nhắn thường trên Discord, phải đọc gần hết mới chắc không sót. Đây cũng là bước gây ra các lần suýt trễ |
| Impact (nếu không giải thì sao) | Mất ~15 phút/ngày (~1,5 giờ/tuần) chỉ để kiểm tra; 1–2 lần suýt trễ deadline trong tháng qua; luôn có cảm giác "chắc còn sót gì đó" trước mỗi hạn nộp |
| Success metric (baseline → target) | (1) Thời gian kiểm tra deadline mỗi ngày: ~15 phút → ≤ 5 phút. (2) Số deadline bị bỏ sót hoặc suýt trễ: 1–2 lần/tháng → 0. Cách đo: tự ghi log thời gian và số deadline phát hiện muộn trong 2 tuần, so sánh trước/sau |
| Phương án không dùng AI | Một Google Calendar chung của lớp, lớp trưởng hoặc coach thêm sự kiện mỗi khi có deadline/gia hạn; Discord chỉ bật thông báo cho kênh announcements; quy ước mọi thông báo deadline có tiền tố `[DEADLINE]` để search được |
| Giả thuyết về AI (nếu có) | Đọc tin nhắn mới ở các kênh, nhận ra tin nào có deadline/gia hạn (kể cả khi viết không theo mẫu), trích ra môn, bài, ngày giờ, link thành sự kiện lịch nháp; người dùng xác nhận trước khi lưu |
| Cảm nhận nhanh | Rule (nếu lớp chịu dùng quy ước `[DEADLINE]` + lịch chung); Workflow nếu thông báo vẫn viết tự do |

Số phút ở từng bước là ước tính, sẽ thay bằng số đo thật sau khi tự ghi log.

Quy trình nháp hiện tại:

```text
[1] Mở LMS xem bài tập, hạn nộp            ~3'
      ↓
[2] Lướt Discord: kênh thông báo + chat lớp ~7'   ⛔ BOTTLENECK
      ↓                                         (deadline lẫn trong tin nhắn thường)
[3] Kiểm tra email trường                   ~3'
      ↓
[4] Ghi deadline vào note/lịch cá nhân      ~2'
      ↓
[5] Có thay đổi (gia hạn, đổi giờ)? → sửa note/lịch  ~2', vài lần/tuần
                                     Tổng: ~15'/ngày
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

```text

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
