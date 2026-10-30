## hiusuy Pro 2.4.0

- Render tự đo trên source và sub thực tế; dùng CPU/GPU phù hợp, chuyển CPU khi GPU lỗi. Không thay file xuất cũ nếu tác vụ lỗi hoặc bị hủy.
- Nhập source mặc định ở 00; kéo thả vào timeline đặt đúng vị trí thả, kể cả khi đang cuộn.
- Tự tìm voice để khớp TXT/SRT/VTT giữa nhiều đoạn audio, có tính vị trí, phần cắt và tốc độ. Chờ khi tác vụ nhận diện đang bận; giữ sub khi chưa đủ độ chắc chắn.
- Thêm **Công cụ dựng**: bản xem nhẹ 640/960 pixel, xem trước và dồn khoảng trống chung, giữ tối đa 40 phiên bản dự án.
- Bản xem nhẹ chỉ dùng trong Program. Xuất video, âm thanh và nhận diện vẫn dùng source gốc.
- Mã nhận diện đi cùng bản cập nhật, giữ model và cài đặt đang có.

### Tải gói phù hợp

- **Windows-portable.zip**: app đầy đủ cho máy mới.
- **Cap-nhat-lan-dau.zip**: thêm cập nhật online cho bản cũ. Giải nén toàn bộ và mở Cap_nhat.cmd.
- Máy đã có cập nhật online: mở nút **Cập nhật**, chờ tải, lưu dự án và khởi động lại.

### Kiểm tra

Đã kiểm tra proxy, cache hỏng, hủy tác vụ, dồn video/voice/sub cùng nhau, hoàn tác, track khóa, mở bản lưu, kéo thả, dựng tự động, hàng đợi và render dự phòng CPU.

Video thử 30 phút, 1080p/30fps, 360 câu sub: **3 phút 42 giây** trên i5-12400F và RTX 2060 SUPER. Đây là số đo của máy thử, không bảo đảm thời gian trên máy khác. Chưa kiểm tra trực tiếp GPU AMD/Intel hoặc máy RAM thấp. Bộ nhận diện cần model cài trong Preferences.
