# CHEMQUEST — Mật mã phân tử: Ester – Lipid

Bản mẫu game giáo dục Hóa học 12 dùng React + TypeScript + Three.js.

## Chức năng hiện có trong mã nguồn
- Giao diện responsive cho máy tính, máy chiếu và điện thoại.
- Mô hình nguyên tử/liên kết 3D tạo bằng Three.js; tự xoay nhẹ, kéo để xoay, cuộn để phóng to/thu nhỏ.
- 5 câu hỏi trắc nghiệm, phản hồi và giải thích sau khi nộp câu trả lời.
- Tính điểm 20 điểm/câu; thanh tiến độ và đồng hồ đếm ngược 15 phút.
- Màn hình kết quả, chơi lại và tải báo cáo JSON cục bộ.
- Không cần tài khoản, không có backend và không gửi câu trả lời lên máy chủ.

## Chạy trên máy tính
Yêu cầu Node.js 20+.

```bash
npm install
npm run dev
```
Mở URL mà Vite in ra. Để kiểm tra bản build:

```bash
npm run build
npm run preview
```

## Triển khai Vercel
1. Đưa thư mục dự án lên GitHub.
2. Import repository trong Vercel.
3. Build command: `npm run build`.
4. Output directory: `dist`.
5. Không cần biến môi trường cho bản mẫu này.

## Lưu ý
- Cảnh hiện tại là mô hình 3D tương tác minh họa, không phải mô phỏng phản ứng phân tử động học.
- Chưa có cảnh ảnh/video 360° thật, kính VR, lưu điểm trực tuyến, bảng xếp hạng lớp hay tài khoản giáo viên.
- Tải báo cáo JSON là chức năng cục bộ trên trình duyệt; dữ liệu không được gửi tới giáo viên tự động.
- Nguồn font chữ Google Fonts cần Internet; khi ngoại tuyến, trình duyệt dùng font dự phòng.
- Nội dung câu hỏi được xây dựng làm bản mẫu bám chủ đề Ester – Lipid; giáo viên cần đối chiếu cách trình bày, danh pháp và yêu cầu cần đạt với bản SGK đang sử dụng trước khi dạy chính thức.
