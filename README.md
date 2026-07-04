# ⚡ Azota Quiz Formatter

<p align="center">
  <img src="https://img.shields.io/badge/Release-v1.0.0-indigo?style=for-the-badge&logo=github" alt="Release Version">
  <img src="https://img.shields.io/badge/Platform-Windows_x64-blue?style=for-the-badge&logo=windows" alt="Platform">
  <img src="https://img.shields.io/badge/Framework-.NET_10.0-green?style=for-the-badge&logo=.net" alt="Framework">
  <img src="https://img.shields.io/badge/Architecture-Native_AOT-orange?style=for-the-badge&logo=c-sharp" alt="Architecture">
</p>

---

## 🌟 Giới Thiệu
**Azota Quiz Formatter** là công cụ tối ưu hóa và chuẩn hóa định dạng tài liệu câu hỏi trắc nghiệm (PDF/DOCX) để copy trực tiếp vào hệ thống Azota mà không lo lỗi font, sai định dạng hay lệch số thứ tự. 

Ứng dụng được thiết kế trên nền tảng **C# .NET 10.0** kết hợp công nghệ **Native AOT** cho tốc độ khởi động tức thì, hiệu năng vượt trội và giao diện **Chromeless Dark Mode** cực kỳ hiện đại.

---

## ✨ Tính Năng Nổi Bật
* ⚡ **Siêu Hiệu Năng (Native AOT)**: Biên dịch trực tiếp thành mã máy, ứng dụng siêu nhẹ, chạy không cần cài đặt .NET Runtime.
* 🔗 **Đa Luồng Song Song (Parallel API Processing)**: Tự động chia nhỏ tài liệu lớn thành các phần nhỏ (tối đa 80 câu hoặc 24.000 ký tự) để gửi song song lên AI qua giao thức **HTTP/2**.
* 🧠 **Bộ Não AI Tối Ưu**: Tích hợp các chỉ thị an toàn chống ảo giác dữ liệu (Anti-Hallucination), đảm bảo bảo toàn 100% nội dung câu hỏi và các phương án nhiễu (A, B, C, D) không bị nuốt chữ hay mất câu.
* 📝 **Hỗ trợ PDF & Word (DOCX)**: Trích xuất thông minh, tự động loại bỏ số trang tự động của file PDF.
* 🔄 **Đánh Số Thứ Tự Liên Tục**: Tự động phát hiện và re-index lại thứ tự câu hỏi từ 1 đến N sau khi gộp các phân đoạn dữ liệu.
* 🖥️ **Console Log GDI+**: Trình hiển thị tiến trình dạng terminal giả lập hiện đại, trực quan, theo dõi ping và trạng thái hệ thống trong thời gian thực.

---

## 🚀 Hướng Dẫn Sử Dụng
1. Tải bản phát hành mới nhất (.exe) từ mục [Releases](../../releases).
2. Chạy ứng dụng **AzotaQuizFormatter.exe** (không cần cài đặt).
3. Chọn file đề thi cần xử lý (PDF hoặc DOCX).
4. Cấu hình các tùy chọn (Tự sắp xếp số thứ tự, Cách đánh dấu đáp án đúng).
5. Bấm **Bắt Đầu Chuyển Đổi** và copy kết quả đã được chuẩn hóa để dán vào Azota!

---

## 🛠️ Tác Giả & Liên Hệ

Ứng dụng được phát triển và duy trì bởi **FuyukoUxU**.

* 🐙 **GitHub Profile**: [github.com/FuyukoUxU](https://github.com/FuyukoUxU)
* 🔵 **Facebook**: [fb.com/xyt712114](https://facebook.com/xyt712114)
* 📧 **Email Liên Hệ**: [fuyukouxu@gmail.com](mailto:fuyukouxu@gmail.com)

Nếu bạn gặp lỗi hoặc có đóng góp ý kiến để cải thiện phần mềm, vui lòng gửi phản hồi qua các kênh liên lạc trên hoặc tạo [Issue](../../issues). Thank you! 🎉
