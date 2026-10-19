# BÀI THỰC HÀNH 2: TỔ CHỨC SPRINT RETROSPECTIVE CHO NỀN TẢNG RIKKEIRETECH

> 👤 **Học viên:** Hoàng Công Dũng | **Mã SV:** PTIT-HCM-009
> 🏫 **Môn học:** it206-k25-HoangCongDung

---

## Nhiệm vụ 1: Chọn kỹ thuật và xếp thẻ ý kiến

(a) Kỹ thuật chọn và giải thích:

Tôi chọn kỹ thuật 4Ls (Liked, Learned, Lacked, Longed For) vì Sprint chỉ kéo dài 45 phút, vấn đề trong nhật ký đã rất cụ thể và nhóm cần định hướng ngay các giải pháp hành động rõ ràng mà không mất thời gian tranh cãi.

(b) Xếp thẻ T2 đến T5 vào cột tương ứng:

- Thẻ T1 (Đã làm mẫu): Continue (Liked). Cách làm này hiệu quả, nên giữ.
- Thẻ T2: Xếp vào cột Lacked. Lý do: Kiểm thử bị dồn việc đến ngày 9 là lỗ hổng quy trình cần bổ sung thêm nguồn lực hoặc phân rã tác vụ nhỏ hơn.
- Thẻ T3: Thẻ đổ lỗi cá nhân (Hải báo lỗi muộn...). Viết lại thành 'Việc phát hiện và thông báo lỗi kỹ thuật còn chậm trễ', sau đó xếp vào cột Lacked.
- Thẻ T4: Thẻ không thuộc phạm vi Sprint Retrospective nội bộ nhóm phát triển (liên quan đến nghiệp vụ Product Backlog và trải nghiệm người dùng ngoài Sprint). Chuyển thẻ này cho Product Owner Thảo đưa vào buổi Product Backlog Refinement tiếp theo.
- Thẻ T5: Xếp vào cột Lacked. Lý do: Định nghĩa hoàn thành DoD chưa bao phủ toàn diện các thiết bị thực tế, cần cập nhật ngay.

## Nhiệm vụ 2: Từ Data đến Improvement

Tôi chọn sự việc DT-01 trong nhật ký (Ngày 9 mới bắt đầu kiểm thử chức năng đặt giữ máy, lỗi phát hiện muộn nên chưa Done) để phân tích nguyên nhân gốc rễ và xây dựng hành động cải tiến.

Bảng phân tích Data và Insight:

- Bảng hành động cải tiến theo chuẩn SMART:

| Data đã chọn | Khía cạnh | Insight (vì sao xảy ra) |
| --- | --- | --- |
| DT-01: Kiểm thử dồn đến ngày 9, trễ hạn DoD | Quy trình | Nhóm Developers có thói quen làm xong toàn bộ code mới đưa sang kiểm thử (Waterfall trá hình trong Scrum), thiếu bước viết kiểm thử và kiểm tra từng phần nhỏ liên tục trong Sprint. |

## Hành động cải tiến chi tiết (Improvement)

Chi tiết kế hoạch hành động khắc phục lỗi DT-01:

| Hành động cụ thể | Người/nhóm theo dõi | Khi kiểm tra lại | Bằng chứng |
| --- | --- | --- | --- |
| Áp dụng TDD (Test-Driven Development) và review chéo mã nguồn ngay khi hoàn thành từng User Story nhỏ, không đợi dồn cuối Sprint. | Scrum Master Duy và Developer Linh | Giữa Sprint tiếp theo (Ngày 5) | Biên bản Daily Scrum ghi nhận các PBI được kiểm thử cuốn chiếu hàng ngày. |

## Nhiệm vụ 3: Sắp xếp và mở đầu buổi Retrospective

(a) Thứ tự 5 bước của buổi Retrospective:

H3 -> H2 -> H5 -> H1 -> H6

Hoạt động bị loại và lý do:

Loại hoạt động H4 vì Scrum Master không được phép tự áp đặt giải pháp và giao việc cho nhóm theo ý chủ quan, vi phạm nguyên tắc tự tổ chức (self-organizing) của Scrum.

(b) Lời mở đầu của Scrum Master Duy:

Chào mọi người, cảm ơn anh em đã nỗ lực hết mình trong Sprint vừa qua. Hôm nay chúng ta ngồi lại trong 45 phút để nhìn nhận thẳng thắn những điểm chưa tốt trên tinh thần xây dựng, tuyệt đối không chỉ trích cá nhân ai cả. Mục tiêu của chúng ta là tìm ra nguyên nhân và chốt 1 hành động cải tiến thiết thực nhất để Sprint sau chạy mượt hơn.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt2.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
