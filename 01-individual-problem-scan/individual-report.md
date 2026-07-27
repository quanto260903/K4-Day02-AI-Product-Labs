| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
| 1 | Tốn thời gian | Không truy xuất được nhanh nội dung cũ trong group Messenger; phải scroll thủ công nhiều lần để tìm lại kỉ niệm. |Người dùng app |mất khoảng 30p/1lần để tìm, phải cuộn chat lên theo tháng, năm |
| 2 | Lặp lại| Mỗi tuần phải tổng hợp báo cáo từ nhiều file Excel rồi gửi cho quản lý.|Nhân viên, quản lý | Thực hiện 1–2 lần/tuần, mất khoảng 1–2 giờ/lần.|
| 3 | AI có thể hỗ trợ tốt hơn|Viết email, biên bản họp hoặc tóm tắt tài liệu vẫn làm thủ công. |Nhân viên văn phòng |Mỗi email mất 10–15 phút; nhiều nội dung lặp lại. |
| 4 | Lặp lại + AI hỗ trợ| Nhập dữ liệu từ biểu mẫu giấy vào Excel bằng tay.|Nhân viên nhập liệu | Hàng chục đến hàng trăm bản ghi mỗi ngày; dễ sai sót|
| 5 | Lặp lại | Giảng viên ngữ văn chấm bài tập tự luận|

Problem Card #1 — Tìm ảnh/video cũ trong chat Messenger
Problem 1 câu: Không thể nhanh chóng tìm lại ảnh/video cũ trong group chat Messenger khi có người nhắc đến kỷ niệm cũ.

Actor: Tôi (và nhiều người dùng Messenger có group chat lưu trữ lâu năm nói chung)

Thời điểm / bối cảnh: Khi có ai đó trong nhóm nhắc lại một kỷ niệm cũ và muốn xem lại ảnh/video liên quan

Current workflow 3-7 bước:
1. Nhớ mốc thời gian gần đúng của sự kiện
2. Mở group chat, cuộn tay theo tháng/năm
3. Thử search từ khóa liên quan (nếu nhớ được)
4. Không tìm thấy kết quả mong muốn
5. Bỏ cuộc

Bottleneck: Không có cách tìm theo ngữ cảnh (ai, sự kiện gì, khoảng thời gian nào) — chỉ có scroll tay hoặc search từ khóa chính xác, mà thường không nhớ chính xác từ khóa

Impact: Mất ~30 phút/lần, không tìm ra thì mất thời gian và gây khó chịu, bỏ lỡ việc ôn lại kỷ niệm

Success metric: Thời gian tìm giảm từ ~30 phút xuống dưới 5 phút; tỷ lệ tìm ra thành công tăng

Non-AI alternative: (bạn tự nghĩ — ví dụ: tự đặt tên/gắn thẻ ảnh khi gửi, tạo album riêng lưu ảnh quan trọng thủ công)

AI hypothesis: (bạn tự nghĩ — ví dụ: AI hiểu mô tả ngữ cảnh "ảnh đi Đà Lạt năm ngoái" rồi search ra đúng đoạn chat)

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[x] Chưa biết


Problem Card #2 — Tổng hợp báo cáo từ nhiều file Excel

Problem 1 câu: Mỗi tuần phải tổng hợp báo cáo từ nhiều file Excel rồi gửi cho quản lý, tốn nhiều thời gian.

Actor: Nhân viên phụ trách tổng hợp báo cáo (và quản lý là người nhận/sử dụng báo cáo)

Thời điểm / bối cảnh: Định kỳ 1–2 lần/tuần, thường vào cuối tuần hoặc trước buổi họp báo cáo

Current workflow 3-7 bước:
1. Mở từng file Excel từ các nguồn/bộ phận khác nhau
2. Kiểm tra và đối chiếu số liệu giữa các file
3. Copy/tổng hợp dữ liệu vào 1 file báo cáo chung
4. Định dạng lại bảng biểu cho dễ đọc
5. Kiểm tra lại số liệu trước khi gửi
6. Gửi báo cáo cho quản lý

Bottleneck: Bước tổng hợp và đối chiếu số liệu từ nhiều file (thủ công, dễ sai sót)

Impact: Mất 1–2 giờ/lần, 1–2 lần/tuần → tốn nhiều thời gian, dễ sai sót khi làm tay

Success metric: Giảm thời gian tổng hợp từ 1–2 giờ xuống dưới 30 phút/lần

Non-AI alternative: Chuẩn hóa template file Excel đầu vào để dễ tổng hợp hơn, dùng công thức Excel/pivot table có sẵn

AI hypothesis: AI/tool tự động đọc và gộp dữ liệu từ nhiều file Excel theo cấu trúc định sẵn, tạo báo cáo nháp

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết


Problem Card #4 — Nhập dữ liệu từ biểu mẫu giấy vào Excel

Problem 1 câu: Phải nhập dữ liệu từ biểu mẫu giấy vào Excel bằng tay, khối lượng lớn và dễ sai sót.

Actor: Nhân viên phụ trách nhập liệu

Thời điểm / bối cảnh: Diễn ra hàng ngày, khi có biểu mẫu giấy được thu thập về

Current workflow 3-7 bước:
1. Nhận biểu mẫu giấy đã điền
2. Đọc từng trường thông tin trên biểu mẫu
3. Gõ tay dữ liệu vào Excel theo đúng cột
4. Kiểm tra lại để phát hiện lỗi gõ sai
5. Lưu file

Bottleneck: Gõ tay từng bản ghi (chậm, dễ sai khi số lượng lớn)

Impact: Hàng chục đến hàng trăm bản ghi mỗi ngày, dễ sai sót, không có thời gian cụ thể được ghi nhận

Success metric: Giảm thời gian nhập liệu trên mỗi bản ghi và giảm tỷ lệ sai sót

Non-AI alternative: Thiết kế lại biểu mẫu giấy chuẩn hóa hơn, hoặc chuyển sang form nhập liệu điện tử trực tiếp

AI hypothesis: AI/OCR đọc biểu mẫu giấy và tự động điền vào Excel, người kiểm tra lại

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết