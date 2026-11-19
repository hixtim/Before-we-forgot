BEFORE WE FORGOT — TRẢI NGHIỆM TẾT

CÁCH MỞ WEBSITE
1. Mở thư mục dự án trong VS Code.
2. Mở `HomePage.html` bằng Live Server (nút “Go Live”), hoặc mở trực tiếp trong trình duyệt.
3. Truy cập địa chỉ localhost mà Live Server hiển thị.

Đây là website tĩnh, không cần cài đặt package hoặc chạy bước build. Có thể mở HomePage.html trực tiếp; Live Server cũng dùng được và tạo địa chỉ lưu trữ ổn định cho localStorage. Toàn bộ ảnh được lưu cục bộ, còn Bootstrap và font chữ được tải từ CDN nên cần mạng để hiển thị đầy đủ.

Toàn bộ ảnh hiển thị được lưu cục bộ trong assets/photo-story và assets/gallery. Website tải Bootstrap 5.3.3 từ jsDelivr và DM Sans, Playfair Display, Special Elite từ Google Fonts. Nếu ảnh của một chương không tải được, trang chương có liên kết tới nguồn ảnh gốc; nguồn các ảnh khác có trong CREDITS.md.

CÁC PHẦN CHÍNH
- Thư viện sáu câu chuyện về Tết miền Bắc.
- Hộp ký ức lưu câu chuyện, tiến độ trải nghiệm và ghi chú trong trình duyệt.
- Hành trình Tết gồm ba câu chuyện ảnh: Ngôi nhà trước Tết, Bánh chưng: từ bàn gói đến nồi bánh, và Một đêm, một mái nhà.
- Mỗi chương có dòng thời gian để xem lại từng phần; tiến độ tự lưu. Ở phần cuối, bạn có thể ghi một lời nhắn riêng và lưu chương vào Hộp ký ức.
- Ba chương ảnh là luồng chính của Hành trình Tết; hoạt động chuẩn bị năm món đồ phiên bản trước vẫn mở được từ trang này.
- Letters to the Future: tạo thư gửi bản thân hoặc người thân, chọn ngày mở, lưu bản nháp, xem trước, niêm phong và xem thư trong My Letters.
- Thư đã niêm phong hiển thị countdown và chỉ chuyển sang trạng thái sẵn sàng khi mở website vào hoặc sau ngày đã chọn. Thư đã mở có thể được hồi âm, in hoặc lưu thành PDF.
- Tìm kiếm ở Khám phá Tết lọc kết quả ngay khi nhập; ảnh so sánh hỗ trợ vuốt/kéo và phím mũi tên.

LƯU DỮ LIỆU
Tiến độ, câu chuyện đã lưu, ghi chú và thư được lưu trong localStorage của trình duyệt theo từng địa chỉ website. Letters to the Future dùng key riêng `before-we-forgot:letters:v1`; dữ liệu không được gửi lên máy chủ, không gửi email và không đồng bộ sang thiết bị khác. Thời điểm mở được kiểm tra khi website đang mở hoặc khi người dùng quay lại; đây không phải dịch vụ gửi thư tự động.

Thư chỉ được lưu trên thiết bị/trình duyệt hiện tại và không được mã hóa. Xóa dữ liệu website của trình duyệt sẽ xóa các thư và kỷ niệm đã lưu. Nếu trình duyệt chặn localStorage, thay đổi chỉ được giữ trong phiên hiện tại và website sẽ báo tình trạng này.

NGUỒN ẢNH VÀ PHẦN MỀM
Xem CREDITS.md để biết nguồn ảnh, tác giả và giấy phép. Các ảnh trong assets/photo-story có ghi nguồn tương ứng trong tài liệu này.
