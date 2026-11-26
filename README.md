# LaTeX Studio

Soạn thảo LaTeX và xem PDF ngay trong một cửa sổ Windows.

## Tải về

**Bản mới nhất 1.2.4 · Windows x64 · Cập nhật ngày 26/11/2026**

[Tải LaTeXStudio-Setup-1.2.4.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.4/LaTeXStudio-Setup-1.2.4.exe) · [Ghi chú phát hành](https://github.com/tomsuhapbia/latex-studio/releases/tag/v1.2.4) · [Tệp SHA-256](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.4/SHA256SUMS-1.2.4.txt) · [Tất cả phiên bản](https://github.com/tomsuhapbia/latex-studio/releases) · [Lịch sử cập nhật](CHANGELOG.md)

Bộ cài khoảng 23,4 MiB. SHA-256 `25a3d80c81ec0aab72d532e9bc42e6cf294763831199899de920a6e47ed6274b`

| Phiên bản | Bộ cài Windows | Trạng thái |
| --- | --- | --- |
| **1.2.4** | [LaTeXStudio-Setup-1.2.4.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.4/LaTeXStudio-Setup-1.2.4.exe) | Bản mới nhất |
| 1.2.2 | [LaTeXStudio-Setup-1.2.2.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.2/LaTeXStudio-Setup-1.2.2.exe) | Đã phát hành |
| 1.2.1 | [LaTeXStudio-Setup-1.2.1.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.1/LaTeXStudio-Setup-1.2.1.exe) | Đã phát hành |
| 1.2.0 | [LaTeXStudio-Setup-1.2.0.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.2.0/LaTeXStudio-Setup-1.2.0.exe) | Đã phát hành |
| 1.1.6 | [LaTeXStudio-Setup-1.1.6.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.6/LaTeXStudio-Setup-1.1.6.exe) | Đã phát hành |
| 1.1.5 | [LaTeXStudio-Setup-1.1.5.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.5/LaTeXStudio-Setup-1.1.5.exe) | Đã phát hành · Bản lưu trữ |
| 1.1.4 | [LaTeXStudio-Setup-1.1.4.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.4/LaTeXStudio-Setup-1.1.4.exe) | Đã phát hành · Bản lưu trữ |
| 1.1.3 | [LaTeXStudio-Setup-1.1.3.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.3/LaTeXStudio-Setup-1.1.3.exe) | Đã phát hành · Bản lưu trữ |
| 1.1.2 | [LaTeXStudio-Setup-1.1.2.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.2/LaTeXStudio-Setup-1.1.2.exe) | Đã phát hành · Bản lưu trữ |
| 1.1.1 | [LaTeXStudio-Setup-1.1.1.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.1/LaTeXStudio-Setup-1.1.1.exe) | Đã phát hành · Bản lưu trữ |
| 1.1.0 | [LaTeXStudio-Setup-1.1.0.exe](https://github.com/tomsuhapbia/latex-studio/releases/download/v1.1.0/LaTeXStudio-Setup-1.1.0.exe) | Đã phát hành · Bản lưu trữ |

Các bản 1.1.0–1.1.5 giữ nguyên bộ cài gốc để lưu trữ. Nếu không cần một phiên bản cụ thể, hãy dùng [bản mới nhất](https://github.com/tomsuhapbia/latex-studio/releases/latest). Mỗi bản phát hành có bộ cài, tệp kiểm tra SHA-256 và hướng dẫn cài đặt. Xem [SHA256SUMS.txt](SHA256SUMS.txt) để đối chiếu mã băm của mọi bộ cài đã phát hành.

## Có gì mới trong 1.2.4?

- **Bộ đếm trang PDF** hiển thị trang hiện tại / tổng số trang, ví dụ **2 / 8**, ngay cạnh kính lúp. Bộ đếm cập nhật khi cuộn, thu phóng hoặc chuyển tài liệu.
- **Bản PDF riêng cho từng tài liệu**. **Recompile** biên dịch file `.tex` độc lập đang mở. Bản PDF thành công gần nhất của mỗi file xuất hiện khi chuyển tab. Google Drive đồng bộ từng PDF theo tên file nguồn.
- Nhấn **Enter** để xác nhận tên khi tạo file hoặc project. Bấm **×** để đóng tab.
- **Gợi ý lệnh thông minh hơn**: nhận diện macro và môi trường tự định nghĩa trong toàn bộ project (kể cả `\NewDocumentCommand`, `\DeclarePairedDelimiter` và thay đổi chưa lưu); **Enter** sau `\begin` tạo cặp môi trường đổi tên đồng thời, **Enter** sau `\\` giữ nguyên xuống dòng, gõ `\{` tự đóng `\}`.
- **Share PDF… trên Google Drive**: bật/tắt quyền xem qua liên kết, sao chép liên kết và gửi lời mời qua email (**Viewer**, **Commenter**, **Editor**) ngay trong ứng dụng.
- **Nhanh và nhẹ hơn rõ rệt**: tối ưu gõ văn bản trên tài liệu dài, chuyển tab tức thì, giảm 75% bộ nhớ dựng trang PDF mặc định, giữ cache `.aux` khi sửa file `\input` con, giảm số lượt gọi API Drive và thu gọn bộ cài còn khoảng 23,4 MiB.
- **Ổn định & bảo mật hơn**: tách cảnh báo BibTeX khỏi lỗi biên dịch, sửa log parser với tên file có dấu chấm, tăng cường sandbox TeX, giữ lịch sử hoàn tác khi file đổi từ ngoài đĩa, giữ project đã ghim ở đầu danh sách và hỗ trợ đổi tên chỉ khác hoa/thường trên Windows.

## Tính năng

- Editor và PDF Preview cạnh nhau, kéo để điều chỉnh kích thước. Thu phóng PDF bằng **Ctrl + lăn chuột** hoặc giữ chuột trái để soi **2×**. Xem số trang ngay cạnh kính lúp.
- Find and Replace hỗ trợ phân biệt hoa thường, khớp nguyên từ, regex và hoàn tác.
- Chọn pdfLaTeX, XeLaTeX hoặc LuaLaTeX trong menu **Recompile**. Ứng dụng giữ PDF thành công gần nhất riêng cho mỗi tài liệu khi lần biên dịch mới gặp lỗi.
- Tự lưu bản nháp, khôi phục phiên làm việc, gợi ý lệnh thông minh, file outline và xem trước công thức.
- Quản lý nhiều project; tìm kiếm, sắp xếp, ghim, đổi tên, đưa vào thùng rác và import thư mục.
- Tải hình ảnh/PDF vào project, tạo file/thư mục, menu Rename/Delete cho từng file và xuất PDF.
- Settings với bảng màu theo HEX, Light/Dark/Auto, hiệu ứng grain và kiểm tra môi trường LaTeX.
- Đồng bộ & chia sẻ PDF theo project qua Google Drive và tùy chọn hiển thị hoạt động qua Discord Rich Presence.

## Cài đặt

1. Tải và mở bộ cài `.exe` của phiên bản mong muốn.
2. Chọn thư mục workspace. Với máy mới, mặc định là **Documents\Latex Compiler**; setup sẽ tự tạo thư mục này.
3. Chọn tạo shortcut Desktop nếu cần, rồi hoàn tất cài đặt.
4. Mở LaTeX Studio từ Start Menu hoặc shortcut.
5. Chọn **New project** để bắt đầu, hoặc **Import folder** để đưa project có sẵn vào workspace.

Ứng dụng cần Windows 10 (1809 trở lên) hoặc Windows 11 x64, Microsoft WebView2 Runtime và một bộ TeX có compiler phù hợp, chẳng hạn MiKTeX hoặc TeX Live. Setup kiểm tra WebView2 và hỗ trợ cài nếu thiếu; bước này cần Internet. Bộ TeX và các gói LaTeX được cài riêng. Sau khi có đủ các thành phần này, bạn có thể soạn và biên dịch offline.

## Đồng bộ & chia sẻ PDF trên Google Drive

1. Mở **Settings → Integrations → Connect Google Drive** và đăng nhập.
2. Mở project, bật **Auto-sync PDF** ở cụm Google Drive rồi biên dịch thành công. PDF được đặt tên theo tài liệu, ví dụ `main2.tex` tạo `main2.pdf`.
3. Bấm biểu tượng trạng thái để xem bản đang chờ, lần tải lên gần nhất, lịch thử lại hoặc chọn **Share PDF…** để chia sẻ liên kết/mời qua email. Bấm chữ **Google Drive** để mở bản PDF đã đồng bộ.

Ứng dụng tải PDF sau khi biên dịch thành công. Khi mất mạng, ứng dụng giữ hàng đợi để thử lại. Trên máy chưa có cấu hình OAuth Desktop, đặt tệp client tại `%LOCALAPPDATA%\LaTeXStudio\google-oauth-client.json` để kết nối Google Drive.

## Project được lưu ở đâu?

Project mới nằm ngay trong workspace đã chọn: ví dụ `Documents\Latex Compiler\Bao-cao\main.tex`. Import tạo một bản sao trong workspace và giữ nguyên thư mục gốc. Bản nháp, danh mục project và dữ liệu ứng dụng nằm trong thư mục `.studio` bên trong workspace.

Khi nâng cấp, setup ưu tiên workspace đã dùng. Các bản cũ lưu ở `D:\Latex Compiler` tiếp tục được nhận diện. Gỡ ứng dụng không xóa workspace và tài liệu của bạn.

## Phím tắt

| Phím | Thao tác |
| --- | --- |
| Ctrl + S | Lưu |
| Ctrl + Enter | Biên dịch |
| Ctrl + F / Ctrl + H | Tìm / thay thế trong file đang mở |
| Ctrl + lăn chuột trong PDF | Thu phóng quanh con trỏ |
| Giữ chuột trái trên trang PDF | Soi 2× khi kính lúp được bật |
| Ctrl + P | Mở nhanh file |
| Ctrl + Space | Gợi ý lệnh |
| Ctrl + B / Ctrl + I | Đậm / nghiêng |
| Ctrl + T / Ctrl + U | Thêm / bỏ chú thích dòng |
| Ctrl + Shift + P | Xem trước tại con trỏ |
| Ctrl + Shift + S | Xuất PDF |
| Ctrl + , | Mở Settings |
| F2 | Đổi tên file |

## Hỗ trợ

Nếu biên dịch thất bại, dùng **Settings → About → LaTeX environment → Run check** để kiểm tra compiler. Nếu mẫu chạy được nhưng project vẫn lỗi, xem log biên dịch để xác định gói, font hoặc dòng LaTeX cần sửa. Khi báo lỗi trong [Issues](https://github.com/tomsuhapbia/latex-studio/issues), hãy ghi phiên bản ứng dụng, các bước tái hiện và ảnh thông báo lỗi; bỏ thông tin riêng tư trước khi gửi.

Repository này dành cho tài liệu sử dụng và các bản phát hành. Mã nguồn phát triển không được phân phối tại đây. [Thông báo giấy phép của các thành phần bên thứ ba](THIRD_PARTY_NOTICES.txt) cũng đi kèm bộ cài.
