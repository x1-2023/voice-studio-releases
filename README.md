# Voice Studio cho Windows

[**Tải VoiceStudio.exe mới nhất**](https://github.com/x1-2023/voice-studio-releases/releases/latest/download/VoiceStudio.exe) · [Các phiên bản](https://github.com/x1-2023/voice-studio-releases/releases)

Ứng dụng TTS và clone giọng với VieNeu-TTS v3 Turbo, OmniVoice và thư viện 362 giọng. Có nhập SRT/VTT theo thời gian phụ đề, ghi mẫu micro và công cụ xử lý audio.

## Cách dùng

1. Tải EXE, đặt trong thư mục cá nhân như Desktop rồi mở.
2. Lần đầu giữ kết nối Internet để app tự tải Python riêng, thư viện AI và model. Cần ít nhất 25 GB trống.
3. Chọn giọng trong thư viện hoặc tạo giọng tại tab Clone giọng, nhập văn bản rồi chuyển đổi.
4. Mở Lịch sử và bấm nút mở thư mục cạnh bản thu để lấy WAV/SRT.

Không cần cài Python, pip hay CUDA Toolkit. App ưu tiên GPU NVIDIA, có cấu hình riêng cho RTX 3060 12 GB và GTX 1070 Ti 8 GB. Driver không phù hợp hoặc GPU không qua kiểm tra thì app thông báo dùng CPU cho engine tương ứng. Không tự thay driver của máy.

## Cập nhật

App tự kiểm tra bản mới khi mở, tối đa một lần/ngày. Vào **Cài đặt → Cập nhật ứng dụng** để tải và khởi động lại. Bản tải được kiểm SHA256; EXE cũ giữ cạnh app với đuôi `.previous`. Dữ liệu giọng riêng, model và lịch sử ở `%LOCALAPPDATA%/VoiceStudio`, được giữ khi cập nhật.

Repo này chỉ dùng để cung cấp bản phát hành và hướng dẫn. Đây là bản đầu để dùng thử; đã kiểm tra trên RTX 2070 SUPER, chưa kiểm tra trực tiếp trên RTX 3060 và GTX 1070 Ti. EXE chưa ký mã, mở trực tiếp và chưa có trình cài đặt MSI.
