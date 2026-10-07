lỗi `pop()` lấy phần tử cuối mảng nên xe đến sau lại được sạc trước. Sửa thành `shift()` để lấy xe đầu tiên trong hàng đợi FIFO

Trường hợp kiểm thử      | Dữ liệu đầu vào                              | Kết quả sai thực tế         | Kết quả đúng mong đợi 
Điều phối xe             | `['29A-112.33', '30E-889.12', '51K-678.99']` | `pop()` trả về `51K-678.99` | `shift()` trả về `29A-112.33` 
Tính tổng và doanh thu   | `[45.2, 30.5, 62.8, 28.0]`, giá `4500`       | Tổng và doanh thu bị `NaN`  | Tổng `166.5 kWh`, doanh thu `749250 VNĐ