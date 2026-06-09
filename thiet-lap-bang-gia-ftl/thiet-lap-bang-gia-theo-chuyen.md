# Bảng giá theo chuyến

**Theo chuyến** — Giá được tính cố định cho cả chuyến xe, dựa trên tuyến đường từ điểm lấy đến điểm giao. Không tính thêm dù chuyến đó có nhiều điểm giao.

### Cần lưu ý:

* Đảm bảo khách hàng đã được tạo trên hệ thống.&#x20;
* Chọn đúng loại địa chỉ trước khi tải file mẫu.
* Tải file địa chỉ mẫu `.xlsx` để import dữ liệu giá.

### Tạo bảng giá mới

1.  Vào **Quản lý khách hàng**.

    <figure><img src="../.gitbook/assets/Quản lý KH.png" alt=""><figcaption></figcaption></figure>


2.  Tìm khách hàng theo tên hoặc mã khách hàng. Nếu chưa có khách hàng, vui lòng chọn **Thêm khách hàng** để tạo thông tin khách hàng.

    <figure><img src="../.gitbook/assets/Danh sách KH.png" alt=""><figcaption></figcaption></figure>


3.  Nhấn **Xem chi tiết**.

    <figure><img src="../.gitbook/assets/Xem chi tiết.png" alt=""><figcaption></figcaption></figure>


4.  Kéo xuống mục **Danh sách bảng giá FTL**.

    <figure><img src="../.gitbook/assets/Danh sách BG.png" alt=""><figcaption></figcaption></figure>


5.  Nhấn **+ Tạo bảng giá mới**.

    <figure><img src="../.gitbook/assets/Tạo BG.png" alt=""><figcaption></figcaption></figure>


6.  Hệ thống mở trang **Tạo bảng giá mới** với hai phần: **1. Thông tin chung** và **2. Thiết lập giá tuyến**.

    <figure><img src="../.gitbook/assets/Chi tiết bảng giá mới.png" alt=""><figcaption></figcaption></figure>

### Thiết lập thông tin chung

1.  Nhập **Tên bảng giá**.

    * Đây là trường bắt buộc.
    * Ví dụ: `Bảng giá Q1-2026 - KH Wilmar`&#x20;

    <figure><img src="../.gitbook/assets/Nhập tên BG.png" alt=""><figcaption></figcaption></figure>


2.  Chọn **Loại địa chỉ**.

    * **Địa chỉ cũ** gồm 3 cấp: Tỉnh/TP, Quận/Huyện, Phường/Xã.
    * **Địa chỉ mới** gồm 2 cấp: Tỉnh/TP, Phường/Xã.
    * <mark style="color:$danger;">**Lưu ý: Chọn đúng loại địa chỉ sử dụng trước khi tải file mẫu.**</mark>

    <figure><img src="../.gitbook/assets/Địa chỉ sử dụng.png" alt=""><figcaption></figcaption></figure>


3.  Chọn **Theo chuyến** tại phần **Cách tính giá**.

    <figure><img src="../.gitbook/assets/Chọn theo chuyến.png" alt=""><figcaption></figcaption></figure>

### Tải và điền file mẫu

Nhấn **File mẫu** để tải file đúng với loại địa chỉ đã chọn.

<figure><img src="../.gitbook/assets/Tải file mẫu .png" alt=""><figcaption></figcaption></figure>

File mẫu gồm các cột sau:

* **Điểm đi** — bắt buộc
* **Điểm đến** — bắt buộc
* **Giá theo từng loại xe** — điển ít nhất 1 giá cho 1 loại xe.

Khi điền file, lưu ý:

* Tỉnh/TP đi và đến là bắt buộc.
* Quận/Huyện và Phường/Xã không bắt buộc.
* Mỗi tuyến phải có ít nhất một giá tu.
* Không thêm, xóa, hoặc đổi tên cột tiêu đề.
* Chỉ hỗ trợ định dạng `.xlsx`.

Các loại xe hỗ trợ: `1T · 1.25T · 1.5T · 1.9T · 2T · 2.5T · 3T · 3.5T · 4T · 5T · 6T · 7T · 8T · 9T · 10T · 11T · 12T · 15T · 20HC · 40HC · 45HC`

Lưu lại điền file trước khi upload.

### Upload file

1.  Kéo file `.xlsx` vào vùng upload hoặc nhấn **Tải lên file Excel** để chọn file.<br>

    <figure><img src="../.gitbook/assets/Upload file excel.png" alt=""><figcaption></figcaption></figure>


2.  Nhấn **Tạo bảng giá**.

    <figure><img src="../.gitbook/assets/Nút TBG.png" alt=""><figcaption></figcaption></figure>

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
*   Sau khi xác nhận, bảng giá mới có hiệu lực ngay.

    <figure><img src="../.gitbook/assets/Bật HĐ (1).png" alt=""><figcaption></figcaption></figure>

#### Lên lịch hoạt động

Nhấn **Lên lịch hoạt động** → chọn ngày → nhấn **Áp dụng**.

* Ngày áp dụng phải lớn hơn hôm nay.
* Ngày đã được bảng giá khác sử dụng sẽ bị mờ.
* Trạng thái chuyển thành **Hoạt động từ \[ngày]**.
* Hệ thống tự kích hoạt đúng ngày đã chọn.
* Có thể chỉnh lại bằng **Sửa lịch hoạt động**.

Mỗi thời điểm chỉ có một bảng giá ở trạng thái **Đang hoạt động**. Bảng giá **Hết hiệu lực** không thể kích hoạt lại.

<figure><img src="../.gitbook/assets/Lên lịch HĐ.png" alt=""><figcaption></figcaption></figure>

### Kết quả

Sau khi hoàn tất, khách hàng có bảng giá **Theo chuyến** ở trạng thái **Đang hoạt động** hoặc **Hoạt động từ \[ngày]** theo cấu hình bạn chọn.

<figure><img src="../.gitbook/assets/Đang HĐ.png" alt=""><figcaption></figcaption></figure>
