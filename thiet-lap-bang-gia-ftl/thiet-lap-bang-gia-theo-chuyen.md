# Bảng giá theo chuyến

**Theo chuyến** — Giá được tính cố định cho cả chuyến xe, dựa trên tuyến đường từ điểm lấy đến điểm giao. Không tính thêm dù chuyến đó có nhiều điểm giao.

### Trước khi bắt đầu

* Đảm bảo khách hàng đã được tạo trên hệ thống.&#x20;
* Chọn đúng loại địa chỉ trước khi tải file mẫu.
* Chuẩn bị file `.xlsx` để import dữ liệu giá.

### Tạo bảng giá mới

1.  Vào **Quản lý khách hàng**.

    <figure><img src="../.gitbook/assets/Quản lý KH.png" alt=""><figcaption></figcaption></figure>
2.  Tìm khách hàng theo tên hoặc mã khách hàng. Nếu chưa có khách hàng, vui lòng chọn **Thêm khách hàng** để tạo thông tin khách hàng.<br>

    <figure><img src="../.gitbook/assets/Danh sách KH.png" alt=""><figcaption></figcaption></figure>


3. Nhấn **Xem chi tiết**.<br>
4. Kéo xuống mục **4. Danh sách bảng giá FTL**.
5. Nhấn **+ Tạo bảng giá mới**.

Hệ thống mở trang **Tạo bảng giá mới** với hai phần: **1. Thông tin chung** và **2. Thiết lập giá tuyến**.

### Thiết lập thông tin chung

1. Nhập **Tên bảng giá**.
   * Đây là trường bắt buộc.
   * Ví dụ: `Bảng giá Q1-2026 - KH Wilmar`
2. Chọn **Loại địa chỉ**.
   * **Địa chỉ cũ** gồm 3 cấp: Tỉnh/TP, Quận/Huyện, Phường/Xã.
   * **Địa chỉ mới** gồm 2 cấp: Tỉnh/TP, Phường/Xã.
   * Lưu ý: Chọn đúng template địa c
3. Chọn **Theo chuyến** tại phần **Cách tính giá**.

Sau khi chọn, vùng tải file Excel sẽ xuất hiện bên dưới.

### Tải và điền file mẫu

Nhấn **File mẫu** để tải file đúng với loại địa chỉ đã chọn.

File mẫu gồm các cột sau:

* **Điểm đi** — bắt buộc
* **Điểm đến** — bắt buộc
* **Giá theo từng loại xe** — điền ít nhất một loại

Khi điền file, lưu ý:

* Tỉnh/TP đi và đến là bắt buộc.
* Quận/Huyện và Phường/Xã không bắt buộc.
* Mỗi dòng tuyến phải có ít nhất một cột giá.
* Không thêm, xóa, hoặc đổi tên cột tiêu đề.
* Chỉ hỗ trợ định dạng `.xlsx`.

Các loại xe hỗ trợ: `1T · 1.25T · 1.5T · 1.9T · 2T · 2.5T · 3T · 3.5T · 4T · 5T · 6T · 7T · 8T · 9T · 10T · 11T · 12T · 15T · 20HC · 40HC · 45HC`

Lưu file bằng `Ctrl+S` hoặc `Cmd+S` trước khi upload.

### Upload file

1. Kéo file `.xlsx` vào vùng upload hoặc nhấn để chọn file.
2. Nhấn **Tạo bảng giá**.

Bạn có thể gặp một trong các kết quả sau:

* **Thành công** — popup **Xử lí thành công**. Nhấn **Xác nhận**.
* **Lỗi một phần** — popup **Xem kết quả xử lí**. Tải file xử lý, sửa lỗi, rồi upload lại.
* **File rỗng** — popup **Xử lí thất bại**. Kiểm tra lại file rồi thử lại.
* **Lỗi hệ thống** — nhấn **Xác nhận** và thực hiện lại thao tác.

Sau khi tạo thành công, bảng giá được lưu ở trạng thái **Lưu nháp**.

### Bật hoạt động bảng giá

Bạn có thể đưa bảng giá từ **Lưu nháp** sang hoạt động theo một trong hai cách.

#### Bật hoạt động ngay

Nhấn **Bật hoạt động** ở cột **Thao tác**.

* Nếu đã có bảng giá khác đang hoạt động, hệ thống sẽ yêu cầu xác nhận.
* Sau khi xác nhận, bảng giá mới có hiệu lực ngay.

#### Lên lịch hoạt động

Nhấn **Lên lịch hoạt động** → chọn ngày → nhấn **Áp dụng**.

* Ngày áp dụng phải lớn hơn hôm nay.
* Ngày đã được bảng giá khác sử dụng sẽ bị mờ.
* Trạng thái chuyển thành **Hoạt động từ \[ngày]**.
* Hệ thống tự kích hoạt đúng ngày đã chọn.
* Có thể chỉnh lại bằng **Sửa lịch hoạt động**.

Mỗi thời điểm chỉ có một bảng giá ở trạng thái **Đang hoạt động**. Bảng giá **Hết hiệu lực** không thể kích hoạt lại.

### Kết quả

Sau khi hoàn tất, khách hàng có bảng giá **Theo chuyến** ở trạng thái **Đang hoạt động** hoặc **Hoạt động từ \[ngày]** theo cấu hình bạn chọn.
