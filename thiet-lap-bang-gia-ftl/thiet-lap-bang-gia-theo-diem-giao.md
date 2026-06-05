# Thiết lập bảng giá — Theo điểm giao

{% hint style="info" %}
Áp dụng cho khách hàng có nhiều điểm giao trên mỗi chuyến. Giá = tổng giá tất cả tuyến giao. Mỗi điểm giao = 1 tuyến A→B (A = điểm lấy đầu tiên, B = điểm giao tương ứng).
{% endhint %}

{% hint style="warning" %}
Kích hoạt bảng giá Theo điểm giao sẽ tự động vô hiệu hóa phụ phí rải điểm (nếu có). Đọc kỹ popup trước khi xác nhận.
{% endhint %}

---

## Bước 01 — Truy cập trang Chi tiết khách hàng

**1. Mở Quản lý khách hàng**

- Nhấn mục "Quản lý khách hàng" ở thanh điều hướng bên trái.
- Hoặc tìm "Quản lý khách hàng" trong ô tìm kiếm dịch vụ ở trang chủ.

**2. Tìm khách hàng cần thiết lập**

- Gõ tên hoặc mã KH → nhấn "Xem chi tiết" ở cột Thao tác.
- KH chưa có: nhấn "Thêm khách hàng" → tạo thông tin trước rồi quay lại.

**3. Nhấn "+ Tạo bảng giá mới"**

- Kéo xuống mục "4. Danh sách bảng giá FTL" — nằm dưới phần Thông tin vận hành.
- Nhấn nút "+ Tạo bảng giá mới" ở góc trên bên phải.

{% hint style="success" %}
Hệ thống chuyển sang trang "Tạo bảng giá mới" gồm 2 mục: "1. Thông tin chung" và "2. Thiết lập giá tuyến".
{% endhint %}

---

## Bước 02 — Thiết lập thông tin chung

**1. Nhập tên bảng giá**

- Nhập vào ô "Tên bảng giá" (bắt buộc). Ví dụ: "BG Q2-2026 - Pepsi - Per stop".

**2. Chọn loại địa chỉ**

- Địa chỉ cũ — 3 cấp: Tỉnh/TP · Quận/Huyện · Phường/Xã.
- Địa chỉ mới — 2 cấp: Tỉnh/TP · Phường/Xã (không có Quận/Huyện).

**3. Chọn "Theo điểm giao" tại phần Cách tính giá**

- Giá = tổng giá các tuyến giao. Mỗi điểm giao thuộc tuyến A–B xác định bằng điểm lấy hàng đầu tiên (A) và điểm giao tương ứng (B).
- Vùng upload file Excel xuất hiện bên dưới sau khi chọn.

{% hint style="warning" %}
Chọn đúng loại địa chỉ TRƯỚC khi tải file mẫu. Nếu chọn sai và đã điền dữ liệu, bạn phải làm lại từ đầu.
{% endhint %}

---

## Bước 03 — Tải file mẫu Excel và điền dữ liệu

Cấu trúc file mẫu gồm các cột:

- Điểm đi (bắt buộc)
- Điểm đến (bắt buộc)
- Giá theo từng loại xe — điền ít nhất 1 loại

**21 loại xe hỗ trợ:**

`1T · 1.25T · 1.5T · 1.9T · 2T · 2.5T · 3T · 3.5T · 4T · 5T · 6T · 7T · 8T · 9T · 10T · 11T · 12T · 15T · 20HC · 40HC · 45HC`

**1. Tải file mẫu về máy**

- Nhấn nút "File mẫu" — file tự thay đổi theo loại địa chỉ đã chọn.

**2. Điền dữ liệu vào file**

- Tỉnh/TP đi và đến: bắt buộc. Quận/Huyện, Phường/Xã: không bắt buộc.
- Điền ít nhất 1 cột giá xe cho mỗi dòng tuyến.
- Mỗi dòng tuyến = 1 điểm giao trong booking. Đảm bảo file bao phủ tất cả tuyến KH có thể yêu cầu.

**3. Lưu file (Ctrl+S / Cmd+S)**

{% hint style="warning" %}
Không thêm, xóa hoặc đổi tên cột tiêu đề. Định dạng phải là .xlsx.
{% endhint %}

---

## Bước 04 — Upload file và xử lý kết quả

**1. Upload file và nhấn "Tạo bảng giá"**

- Kéo file .xlsx vào vùng upload, hoặc nhấn để chọn file từ máy.
- Nhấn nút "Tạo bảng giá" ở góc dưới bên phải.

**2. Xử lý theo kết quả hệ thống trả về**

- **Thành công** — Popup "Xử lí thành công" → nhấn "Xác nhận". BG lưu ở trạng thái Lưu nháp.
- **Lỗi một phần** — Popup "Xem kết quả xử lí" → nhấn "Tải file xử lý" → sửa lỗi → upload lại.
- **File rỗng** — Popup "Xử lí thất bại" → kiểm tra lại file rồi upload lại.
- **Lỗi hệ thống** — Nhấn "Xác nhận" và thử lại.

{% hint style="success" %}
Bảng giá lưu ở trạng thái Lưu nháp — chưa có hiệu lực. Cần bật hoạt động ở bước tiếp theo.
{% endhint %}

---

## Bước 05 — Bật hoạt động bảng giá

Bảng giá mới tạo mặc định ở trạng thái Lưu nháp. Có 2 cách đưa vào hoạt động:

### Cách 1 — Bật hoạt động ngay

**Nhấn "Bật hoạt động" ở cột Thao tác.**

- Popup có thể kèm cảnh báo phụ phí rải điểm sẽ bị vô hiệu hóa — đọc kỹ trước khi xác nhận.
- Sau xác nhận: BG chuyển sang Đang hoạt động ngay lập tức.

### Cách 2 — Lên lịch hoạt động

**Nhấn "Lên lịch hoạt động" → chọn ngày → nhấn "Áp dụng".**

- Ngày phải lớn hơn hôm nay. Ngày đã đặt bởi BG khác sẽ bị mờ.
- Trạng thái → "Hoạt động từ [ngày]". Hệ thống tự kích hoạt đúng ngày.
- Sửa lịch: nhấn "Sửa lịch hoạt động" ở cột Thao tác.

{% hint style="warning" %}
Tối đa 1 bảng giá Đang hoạt động tại mỗi thời điểm. Bảng giá Hết hiệu lực không thể kích hoạt lại.
{% endhint %}
