# Bảng giá FTL

{% hint style="info" %}
Tính năng quản lý bảng giá cho đơn hàng Full Truck Load (FTL). Cho phép BD/CS thiết lập mức giá riêng cho từng khách hàng.
{% endhint %}

## Tổng quan

Hệ thống hỗ trợ 2 cách tính giá:

- **Theo chuyến** — Tổng giá dựa trên 1 tuyến cố định, không phụ thuộc vào số điểm giao.
- **Theo điểm giao** — Giá = tổng giá của tất cả tuyến giao. Mỗi điểm giao = 1 tuyến A→B.

## Khi nào dùng loại nào?

| Mô hình | Cách tính | Dùng khi |
|---|---|---|
| Theo chuyến | 1 tuyến cố định | KH thuê nguyên chuyến A→B |
| Theo điểm giao | Tổng các tuyến giao | KH có nhiều điểm giao/chuyến |
