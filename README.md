# 🧪 Ứng Dụng Tính Lượng Nước Pha Cồn $\text{C}_2\text{H}_5\text{OH}$

Ứng dụng web đơn lẻ (**Single Page Application**) giúp tính toán nhanh chóng và chính xác **lượng nước cần thêm** để pha loãng cồn trực tiếp trên trình duyệt.

---

## ✨ Tính Năng Nổi Bật

* **Tính toán hai chiều:** Tự động tính thể tích sau khi pha nếu nhập thể tích ban đầu, hoặc ngược lại.

* **Kiểm tra lỗi thông minh:** Tự động cảnh báo ngay trên màn hình khi nồng độ sau khi pha lớn hơn hoặc bằng nồng độ ban đầu, hoặc khi các giá trị nhập vào không hợp lệ (nhỏ hơn 0).

* **Giao diện trực quan:** Tối ưu hóa không gian hiển thị trên điện thoại, sử dụng tông màu chủ đạo **Đỏ Tím (Magenta) quý phái** và tự động đổi màu khối kết quả khi có lỗi.

* **Hoạt động Offline:** Chỉ gồm một file HTML duy nhất chứa toàn bộ mã nguồn, chạy mượt mà không cần kết nối mạng.

---

## 📐 Thông Số & Công Thức Tích Hợp

| Đại lượng | Ký hiệu | Thuật toán áp dụng |
| --- | --- | --- |
| **Nồng độ ban đầu** | $C_1$ (%) | Nhập số từ $1 \rightarrow 100$<br> |
| **Nồng độ mục tiêu** | $C_2$ (%) | Điều kiện bắt buộc: $C_2 < C_1$<br> |
| **Thể tích ban đầu** | $V_1$ (ml) | $V_1 = \frac{V_2 \times C_2}{C_1}$<br> |
| **Thể tích mục tiêu** | $V_2$ (ml) | $V_2 = \frac{V_1 \times C_1}{C_2}$<br> |
| **Lượng nước cần pha** | $V_3$ (ml) | $V_3 = V_2 - V_1$<br> |

---

## 🛠️ Hướng Dẫn Sử Dụng

1. **Mở tệp tin:** Nhấp đúp để mở trực tiếp file HTML trên bất kỳ trình duyệt web nào (Chrome, Safari, Edge,...).
2. **Khai báo nồng độ:** Điền **Nồng Độ Cồn Ban Đầu** và **Nồng Độ Cồn Sau Khi Pha** (Ứng dụng gợi ý sẵn mức pha tiêu chuẩn từ $96\%$ xuống $70\%$).

3. **Khai báo thể tích:** Chỉ cần điền một trong hai giá trị **Thể Tích Ban Đầu** hoặc **Thể Tích Sau Khi Pha**. Ô còn lại sẽ tự động xoá trống để nhường quyền tính toán.

4. **Nhận kết quả:** Hệ thống sẽ ngay lập tức trả về **Lượng nước cần thêm (ml)** (đã được làm tròn số nguyên) ở khối màu bên dưới cùng.

---

## 📝 Thông Tin Tác Giả & Mã Nguồn

* **Tác giả:** Dương Tấn Chánh

* **Công nghệ:** HTML5, CSS3, JavaScript Thuần (Vanilla JS)
