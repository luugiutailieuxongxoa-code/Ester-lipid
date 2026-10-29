# Ghi chú sư phạm — Game Ester – Lipid (15 phút)

## Vị trí đề xuất trong kế hoạch bài dạy
Dùng một phần trong hoạt động Khám phá hoặc Luyện tập; không thay thế toàn bộ bài học. Dự kiến 15 phút, điều chỉnh theo tiến độ lớp.

## Kịch bản 15 phút
- 1 phút: GV giới thiệu nhiệm vụ, chia nhóm/thiết bị.
- 2 phút: HS đọc hướng dẫn, quan sát mô hình 3D và trao đổi dự đoán.
- 8 phút: HS làm 5 câu hỏi (có thể tổ chức theo nhóm; 20 điểm/câu).
- 3 phút: GV yêu cầu HS giải thích các câu về thủy phân ester và cấu tạo chất béo.
- 1 phút: Chốt kiến thức và yêu cầu HS nêu một điều cần kiểm chứng khi dùng AI.

## Ánh xạ năng lực
- Năng lực hóa học: trả lời câu hỏi về nhóm chức, danh pháp, thủy phân ester và chất béo; minh chứng là câu trả lời và phần giải thích.
- Năng lực số: thao tác mô hình số và tương tác với giao diện; chỉ ghi nhận chỉ báo cụ thể sau khi đối chiếu bảng mã năng lực số được cung cấp.
- Năng lực AI: câu hỏi cuối mô phỏng tình huống kiểm chứng thông tin AI. Có thể liên hệ NLc (kỹ thuật và ứng dụng AI) và NLa (con người giữ vai trò đánh giá), nhưng chưa gán mã chỉ báo cụ thể vì cần đối chiếu nguyên văn cột THPT trong bảng tài liệu.
- Game không tự đo lường toàn bộ năng lực AI và không nên dùng điểm trò chơi làm kết luận năng lực.

## Đánh giá nhanh
Có thể quan sát theo 3 tiêu chí, mỗi tiêu chí 0–2 điểm:
1. Trả lời đúng và giải thích đúng kiến thức hóa học.
2. Hợp tác, nêu lý do và phản biện dựa trên kiến thức.
3. Biết kiểm chứng thông tin AI thay vì chấp nhận ngay.

Rubric gợi ý:
- 0: Chưa thể hiện được minh chứng.
- 1: Có câu trả lời nhưng giải thích chưa đầy đủ hoặc cần gợi ý.
- 2: Trả lời/giải thích phù hợp, có căn cứ.

Đây là phiếu đánh giá gợi ý, không phải rubric bắt buộc của chương trình.

## Giới hạn cần nói rõ
- Mô hình 3D là hình minh họa, không phải cấu trúc hình học chính xác hay mô phỏng phản ứng thực nghiệm.
- Bản mẫu chưa có ảnh/video 360° hoặc chức năng kính VR.
- Báo cáo JSON được tải xuống trên thiết bị; không có hệ thống thu bài trực tuyến.
- Cần kiểm thử build và chạy trên các thiết bị thực tế trước khi dùng chính thức.


## Cập nhật lớp học
- Chế độ trình chiếu nằm ở thanh trên; có thể bật toàn màn hình và hiển thị QR của URL đang mở. Điện thoại chỉ vào được URL nếu URL đó có thể truy cập từ mạng của học sinh (nên dùng URL Vercel đã triển khai).
- Nút “Kết quả” mở bảng thống kê cục bộ và tải CSV. Đây không phải bảng điểm trực tuyến toàn lớp: trình duyệt giáo viên không tự nhận kết quả từ các thiết bị khác. Muốn đồng bộ thật cần backend/database, quy tắc định danh học sinh và cơ chế gửi kết quả có xác thực.
- Mô hình ethyl acetate dùng khung CH₃–C(=O)–O–CH₂–CH₃; liên kết C=O được vẽ đôi. Mô hình triacylglycerol là sơ đồ khung triester, không nên dùng để đo góc/liên kết hoặc xem là cấu trúc không gian định lượng. Đối chiếu SGK trước khi dạy.
- Việc cài dependency/build chưa được xác minh thành công trong môi trường tạo gói; sau khi tải lên GitHub, kiểm tra log Vercel để xác nhận `npm install` và `npm run build`.
