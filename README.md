# LaTeX Studio

Soạn thảo LaTeX và xem PDF ngay trong một cửa sổ Windows.

## Tải về

**Bản 1.1.6 cho Windows x64 đang chờ đăng bộ cài. Hiện chưa có bản tải về trên GitHub Releases.**

Các bộ cài sẽ được đăng tại [Releases](https://github.com/tomsuhapbia/latex-studio/releases). Xem [lịch sử cập nhật](CHANGELOG.md) để biết các thay đổi.

| Phiên bản | Tên bộ cài | Trạng thái |
| --- | --- | --- |
| **1.1.6** | `LaTeXStudio-Setup-1.1.6.exe` | Chờ đăng |
| 1.1.5 | `LaTeXStudio-Setup-1.1.5.exe` | Chưa đăng |
| 1.1.4 | `LaTeXStudio-Setup-1.1.4.exe` | Chưa đăng |
| 1.1.3 | `LaTeXStudio-Setup-1.1.3.exe` | Chưa đăng |
| 1.1.2 | `LaTeXStudio-Setup-1.1.2.exe` | Chưa đăng |
| 1.1.1 | `LaTeXStudio-Setup-1.1.1.exe` | Chưa đăng |
| 1.1.0 | `LaTeXStudio-Setup-1.1.0.exe` | Chưa đăng |
| 1.0.0 | `LaTeXStudio-Setup-1.0.0.exe` | Chưa đăng |

## Tính năng

- Editor và PDF Preview cạnh nhau, có thể kéo để đổi kích thước.
- Chọn pdfLaTeX, XeLaTeX hoặc LuaLaTeX trong menu Recompile.
- Tự lưu, tự biên dịch và khôi phục bản nháp.
- Quản lý nhiều project; tìm kiếm, ghim và mở lại project gần đây.
- Import thư mục, tải hình ảnh/PDF vào project, tạo file và thư mục.
- Menu dấu chấm ở từng file để Rename hoặc Delete.
- Gợi ý lệnh LaTeX, outline và xem trước công thức.
- Xuất PDF bằng nút Export PDF.

## Cài đặt

1. Tải và mở bộ cài `.exe` của phiên bản mong muốn.
2. Chọn thư mục workspace. Với máy mới, mặc định là **Documents\Latex Compiler**; setup sẽ tự tạo thư mục này.
3. Chọn tạo shortcut Desktop nếu cần, rồi hoàn tất cài đặt.
4. Mở LaTeX Studio từ Start Menu hoặc shortcut.
5. Chọn **New project** để bắt đầu, hoặc **Import folder** để đưa project có sẵn vào workspace.

Ứng dụng cần Windows 10 (1809 trở lên) hoặc Windows 11 x64, Microsoft WebView2 Runtime và một bộ TeX có compiler phù hợp, chẳng hạn MiKTeX. Setup kiểm tra WebView2 và hỗ trợ cài nếu thiếu; bước này cần Internet. Bộ TeX và các gói LaTeX được cài riêng. Sau khi có đủ các thành phần này, bạn có thể soạn và biên dịch offline.

## Project được lưu ở đâu?

Project mới nằm ngay trong workspace đã chọn: ví dụ `Documents\Latex Compiler\Bao-cao\main.tex`. Import tạo một bản sao trong workspace và giữ nguyên thư mục gốc. Bản nháp, danh mục project và dữ liệu ứng dụng nằm trong thư mục `.studio` bên trong workspace.

Khi nâng cấp, setup ưu tiên workspace đã dùng. Các bản cũ lưu ở `D:\Latex Compiler` tiếp tục được nhận diện. Gỡ ứng dụng không xóa workspace và tài liệu của bạn.

## Phím tắt

| Phím | Thao tác |
| --- | --- |
| Ctrl + S | Lưu |
| Ctrl + Enter | Biên dịch |
| Ctrl + F | Tìm trong file đang mở |
| Ctrl + Space | Gợi ý lệnh |
| Ctrl + B / Ctrl + I | Đậm / nghiêng |
| Ctrl + T / Ctrl + U | Thêm / bỏ chú thích dòng |
| Ctrl + Shift + P | Xem trước tại con trỏ |
| F2 | Đổi tên file |

## Hỗ trợ

Nếu biên dịch thất bại, kiểm tra compiler đang chọn, bộ TeX và các package mà tài liệu sử dụng. Khi báo lỗi trong [Issues](https://github.com/tomsuhapbia/latex-studio/issues), hãy ghi phiên bản ứng dụng, các bước tái hiện và ảnh thông báo lỗi; bỏ thông tin riêng tư trước khi gửi.

Repository này dành cho tài liệu sử dụng và các bản phát hành. Mã nguồn phát triển không được phân phối tại đây. Thông báo giấy phép của các thành phần bên thứ ba đi kèm bộ cài.
