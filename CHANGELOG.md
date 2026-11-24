# Lịch sử cập nhật

## 1.2.4 — 24/11/2026

[Ghi chú phát hành](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.2.4) · [Bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.4/LaTeXStudio-Setup-1.2.4.exe) · [Tệp SHA-256](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.4/SHA256SUMS-1.2.4.txt)

### Soạn thảo & Gợi ý lệnh

- Gợi ý lệnh phân biệt lệnh LaTeX, lệnh package và macro/môi trường tự định nghĩa trong project (hỗ trợ cả `\NewDocumentCommand`, `\DeclarePairedDelimiter` và các thay đổi chưa lưu trong tab đang mở).
- **Enter** sau `\\` giữ nguyên lệnh xuống dòng; **Enter** sau `\begin` tạo cặp môi trường đổi tên đồng thời; gõ `\{` tự chèn `\}`.
- Tối ưu độ mượt khi gõ trên tài liệu dài (không dựng lại toàn bộ cây file/tab/outline ở mỗi phím), chuyển tab tức thì không rơi ký tự và giữ nguyên lịch sử hoàn tác (**Ctrl + Z**) khi tệp thay đổi từ ngoài đĩa.

### Xem PDF, Biên dịch & Hiệu năng

- Giảm 75% bộ nhớ dựng trang PDF mặc định và tải kính lúp độ nét cao 2× theo nhu cầu; hiển thị trang đích nhanh hơn với PDF nhiều trang.
- Giữ cache `.aux` khi chỉnh sửa tệp `.tex` con được `\input`, giảm thời gian biên dịch lại cho project nhiều chương.
- Tách cảnh báo BibTeX khỏi lỗi biên dịch, sửa phân tích log với tên tệp/nhãn có dấu chấm, tăng cường sandbox TeX (`openin_any=p`/`openout_any=p`), bỏ qua proxy hệ thống khi kiểm tra máy chủ cục bộ và hỗ trợ đổi tên chỉ khác hoa/thường trên Windows.
- Thu gọn khoảng 2,5 MiB dung lượng bộ cài (chuyển nền mờ sang WebP, bỏ font `.woff`/`.ttf` thừa trên WebView2 và loại bỏ trang thử nghiệm cũ).

### Google Drive & Giao diện

- Thêm **Share PDF…** trong menu trạng thái Google Drive để bật/tắt quyền xem qua liên kết, sao chép liên kết và gửi lời mời qua email với quyền **Viewer**, **Commenter** hoặc **Editor**.
- Tối ưu đồng bộ Google Drive (giảm các lượt gọi API dư thừa và tái sử dụng phiên kết nối), giữ các project đã ghim luôn ở đầu danh sách, đồng bộ hộp thoại xác nhận theo giao diện sáng/tối và dọn sạch dữ liệu thừa khi xóa project.

## 1.2.2 — 21/11/2026

[Ghi chú phát hành](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.2.2) · [Bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.2/LaTeXStudio-Setup-1.2.2.exe) · [Tệp SHA-256](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.2/SHA256SUMS-1.2.2.txt)

### Soạn thảo

- Thêm **Find and Replace** cho file đang mở. Dùng **Ctrl + F** để tìm và **Ctrl + H** để chuyển tới ô thay thế.
- Hỗ trợ phân biệt hoa thường, khớp nguyên từ và biểu thức chính quy. Hiển thị số kết quả, cho phép đi tới kết quả trước hoặc sau, chọn tất cả kết quả, thay từng chỗ hoặc thay tất cả. Có thể hoàn tác bằng **Ctrl + Z**.

### Xem PDF

- Giữ **Ctrl** và lăn chuột trong khung PDF để thu phóng quanh vị trí con trỏ. Dùng **−** và **+** trên thanh dưới khung PDF, hoặc bấm mức phần trăm để trở về chế độ vừa chiều rộng.
- Giữ nút chuột trái trên trang PDF để soi 2×. Kính lúp nằm trong khung xem và tự tắt khi thả chuột hoặc kéo ra khỏi khung. Bấm biểu tượng kính lúp trên thanh PDF để bật hoặc tắt thao tác giữ chuột.

## 1.2.1 — 18/11/2026

[Ghi chú phát hành](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.2.1) · [Bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.1/LaTeXStudio-Setup-1.2.1.exe) · [Tệp SHA-256](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.1/SHA256SUMS-1.2.1.txt)

- Khôi phục hàng đợi đồng bộ nếu bản PDF cũ không còn nhưng đã có bản mới hợp lệ. Ứng dụng tiếp tục trên cùng file Drive và báo xung đột nếu file trên Drive đã được chỉnh sửa.
- Biểu tượng Drive cho biết bản PDF đang chờ, lần tải lên gần nhất và lịch thử lại. Khi cần, ứng dụng hiện thao tác **Retry** hoặc **Reconnect**.
- Settings giữ bốn mục ở sidebar. Các thẻ bên phải cân đối trên cửa sổ rộng, xếp dọc khi thiếu chỗ và hiển thị lưu ý cạnh thao tác liên quan.
- **Settings → About → LaTeX environment → Run check** thử biên dịch một mẫu nhỏ. Phép thử không sửa project, tự cài gói hay tải mẫu lên Drive.

## 1.2.0 — 18/11/2026

[Ghi chú phát hành](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.2.0) · [Bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.0/LaTeXStudio-Setup-1.2.0.exe) · [Tệp SHA-256](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.0/SHA256SUMS-1.2.0.txt)

- Đồng bộ PDF lên Google Drive theo từng project. Chỉ bản biên dịch thành công được tải lên; hàng đợi có thể tiếp tục sau khi mở lại ứng dụng và cập nhật cùng file Drive.
- Settings thêm tùy chỉnh màu HEX, Light/Dark/Auto và độ hạt, đồng thời cho phép xem và chuyển workspace mà không di chuyển các file nguồn.
- Files và Outline cuộn riêng, có thể kéo thanh chia để điều chỉnh chiều cao.
- Tự thử lại khi lỗi làm mới phiên đăng nhập tạm thời và xử lý phiên tải lên hết hạn giữa chừng.

## 1.1.6

### Cài đặt và lưu project

- Thêm bước chọn workspace; tự tạo thư mục Latex Compiler khi cài đặt.
- Mặc định dùng Documents trên máy mới, nhận diện workspace cũ khi nâng cấp.
- Lưu project, bản nháp và dữ liệu ứng dụng trong workspace; giữ dữ liệu khi gỡ cài đặt.
- Thay ô tick shortcut bằng checkbox chuẩn để tránh bị cắt ở mức scale cao.

### Import và giao diện

- Bật xử lý DPI cho cửa sổ chọn thư mục và xuất PDF để tránh Windows phóng mờ.
- Import tài nguyên trên Windows không còn phụ thuộc vào hard link.
- Recompile và Export PDF cùng hàng với PDF Preview; Recompile có màu indigo.
- Thanh tiêu đề dùng gradient trắng xám với hiệu ứng hạt nhẹ.
- Thêm menu dấu chấm Rename/Delete cho từng file và bỏ Find file.
- Ẩn dòng All changes saved; vẫn hiển thị trạng thái cần chú ý khi lưu.

### Bộ phát hành

- README dành cho người sử dụng, danh sách phiên bản và bộ cài tương ứng.
- Loại bỏ tài nguyên font cũ không còn dùng khỏi bộ cài.
- Kèm mã SHA-256 để kiểm tra tính toàn vẹn của bộ cài.

## 1.1.5 — Bản lưu trữ

[Xem Release v1.1.5](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.1.5) · [Tải bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.5/LaTeXStudio-Setup-1.1.5.exe) · [SHA256SUMS.txt](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.5/SHA256SUMS.txt)

Bộ cài gốc **24,98 MB**, số ProductVersion đã được đối chiếu với tên phiên bản. Đây là bản lưu trữ được đăng bổ sung, không phải bản build lại từ mã nguồn hiện tại.

Chưa có nhật ký thay đổi riêng đã được xác nhận cho bản này. Ghi chú Release có hướng dẫn cài đặt, yêu cầu bộ TeX và cách kiểm tra SHA-256; không gán ngược các thay đổi của bản mới hơn.

## 1.1.4 — Bản lưu trữ

[Xem Release v1.1.4](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.1.4) · [Tải bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.4/LaTeXStudio-Setup-1.1.4.exe) · [SHA256SUMS.txt](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.4/SHA256SUMS.txt)

Bộ cài gốc **24,97 MB**, số ProductVersion đã được đối chiếu với tên phiên bản. Đây là bản lưu trữ được đăng bổ sung, không phải bản build lại từ mã nguồn hiện tại.

Chưa có nhật ký thay đổi riêng đã được xác nhận cho bản này. Ghi chú Release có hướng dẫn cài đặt, yêu cầu bộ TeX và cách kiểm tra SHA-256; không gán ngược các thay đổi của bản mới hơn.

## 1.1.3 — Bản lưu trữ

[Xem Release v1.1.3](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.1.3) · [Tải bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.3/LaTeXStudio-Setup-1.1.3.exe) · [SHA256SUMS.txt](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.3/SHA256SUMS.txt)

Bộ cài gốc **24,97 MB**, số ProductVersion đã được đối chiếu với tên phiên bản. Đây là bản lưu trữ được đăng bổ sung, không phải bản build lại từ mã nguồn hiện tại.

Chưa có nhật ký thay đổi riêng đã được xác nhận cho bản này. Ghi chú Release có hướng dẫn cài đặt, yêu cầu bộ TeX và cách kiểm tra SHA-256; không gán ngược các thay đổi của bản mới hơn.

## 1.1.2 — Bản lưu trữ

[Xem Release v1.1.2](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.1.2) · [Tải bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.2/LaTeXStudio-Setup-1.1.2.exe) · [SHA256SUMS.txt](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.2/SHA256SUMS.txt)

Bộ cài gốc **24,97 MB**, số ProductVersion đã được đối chiếu với tên phiên bản. Đây là bản lưu trữ được đăng bổ sung, không phải bản build lại từ mã nguồn hiện tại.

Chưa có nhật ký thay đổi riêng đã được xác nhận cho bản này. Ghi chú Release có hướng dẫn cài đặt, yêu cầu bộ TeX và cách kiểm tra SHA-256; không gán ngược các thay đổi của bản mới hơn.

## 1.1.1 — Bản lưu trữ

[Xem Release v1.1.1](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.1.1) · [Tải bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.1/LaTeXStudio-Setup-1.1.1.exe) · [SHA256SUMS.txt](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.1/SHA256SUMS.txt)

Bộ cài gốc **24,97 MB**, số ProductVersion đã được đối chiếu với tên phiên bản. Đây là bản lưu trữ được đăng bổ sung, không phải bản build lại từ mã nguồn hiện tại.

Chưa có nhật ký thay đổi riêng đã được xác nhận cho bản này. Ghi chú Release có hướng dẫn cài đặt, yêu cầu bộ TeX và cách kiểm tra SHA-256; không gán ngược các thay đổi của bản mới hơn.

## 1.1.0 — Bản lưu trữ

[Xem Release v1.1.0](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.1.0) · [Tải bộ cài Windows x64](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.0/LaTeXStudio-Setup-1.1.0.exe) · [SHA256SUMS.txt](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.0/SHA256SUMS.txt)

Bộ cài gốc **22,46 MB**, số ProductVersion đã được đối chiếu với tên phiên bản. Đây là bản lưu trữ được đăng bổ sung, không phải bản build lại từ mã nguồn hiện tại.

Chưa có nhật ký thay đổi riêng đã được xác nhận cho bản này. Ghi chú Release có hướng dẫn cài đặt, yêu cầu bộ TeX và cách kiểm tra SHA-256; không gán ngược các thay đổi của bản mới hơn.
