## Analysis Data of Sales with Python
![Hình minh họa](https://github.com/Bang1710/Analysis_Data_of_Sales_with_Python/blob/main/ImageCover.jpg)
### I. Tóm tắt dự án đầu tiên:
Dữ liệu của dự án bao gồm 11 cột, đại diện cho các thuộc tính liên quan đến việc mua sản phẩm. Các cột chính gồm:

- **Order ID:** Mã đơn hàng duy nhất cho mỗi giao dịch.
- **Product:** Sản phẩm được mua.
- **Quantity Ordered:** Số lượng sản phẩm đã được đặt hàng.
- **Price Each:** Giá của mỗi sản phẩm.
- **Order Date:** Ngày đặt hàng.
- **Purchase Address:** Địa chỉ giao hàng.
- **Month, Sales, City, Hour:** Các thuộc tính bổ sung được tạo từ dữ liệu trên để phục vụ việc phân tích.

### II. Quá trình làm sạch dữ liệu:
Trong quá trình làm sạch, các công việc sau đã được thực hiện:

- Loại bỏ các giá trị NaN (không có dữ liệu).
- Xóa các hàng dữ liệu không hợp lệ dựa trên điều kiện nhất định.
- Chuyển đổi kiểu dữ liệu phù hợp cho các cột (sang kiểu số, ngày tháng, v.v.).

Sau khi dữ liệu đã được làm sạch, các câu hỏi phân tích dữ liệu chính được đặt ra:

### III. Câu hỏi phân tích:

1. **Sản phẩm nào được đặt mua nhiều nhất trong cửa hàng?**
   - Phân tích dữ liệu sẽ trả lời xem sản phẩm nào có số lượng đặt hàng cao nhất.

2. **Mối quan hệ giữa giá bán trung bình của sản phẩm và số lượng đơn hàng?**
   - Xác định liệu sản phẩm có giá cao hơn có bị ảnh hưởng đến số lượng đơn hàng hay không.

3. **5 thành phố có số lượng đơn hàng cao nhất là gì?**
   - Xác định các thành phố nào có số lượng giao dịch mua hàng trực tuyến lớn nhất.

4. **Số lượng sản phẩm được đặt theo từng giờ trong ngày?**
   - Phân tích số lượng đơn hàng theo giờ giúp hiểu rõ thời điểm khách hàng đặt hàng nhiều nhất.

5. **Thời điểm tốt nhất để hiển thị quảng cáo nhằm tối đa hóa khả năng mua hàng của khách hàng?**
   - Sử dụng dữ liệu về thời gian để đưa ra gợi ý cho chiến lược quảng cáo hiệu quả.

6. **Doanh thu tổng thể của cửa hàng trong mỗi tháng là bao nhiêu?**
   - Phân tích doanh thu theo tháng để tìm ra tháng có doanh thu cao nhất.

7. **Sản phẩm nào bán chạy nhất?**
   - Xác định sản phẩm có doanh thu tốt nhất, không chỉ dựa trên số lượng bán mà còn doanh thu.

8. **Giá bán cao nhất cho một sản phẩm là bao nhiêu?**
   - Xác định mức giá cao nhất từng được trả cho một sản phẩm trong cửa hàng.

9. **Có mối tương quan nào giữa giá của sản phẩm và số lượng đơn hàng?**
   - Kiểm tra xem sản phẩm đắt tiền hơn có dẫn đến ít đơn hàng hơn không.

10. **Sự phân bố của giá cả giữa các sản phẩm trong cửa hàng như thế nào?**
    - Kiểm tra xem liệu có sự khác biệt đáng kể giữa giá của các loại sản phẩm khác nhau.

11. **5 thành phố có tỷ lệ đặt hàng trực tuyến cao nhất là gì?**
    - Xác định các thành phố có tỷ lệ mua hàng qua mạng lớn nhất.

### IV. Insight từ dự án:
- **Sản phẩm phổ biến nhất:** Một sản phẩm cụ thể chiếm tỷ lệ lớn đơn hàng, gợi ý rằng cửa hàng có thể tập trung tiếp thị mạnh mẽ hơn cho sản phẩm này.
- **Mối quan hệ giá và số lượng:** Phân tích cho thấy sản phẩm có giá cao thường có số lượng đặt hàng thấp hơn, dẫn đến chiến lược định giá phù hợp là quan trọng.
- **Thành phố dẫn đầu:** Các thành phố với số lượng đơn hàng cao nhất có thể là trọng tâm cho các chiến dịch quảng cáo địa phương.
- **Thời gian đặt hàng:** Thời gian cụ thể trong ngày cho thấy cao điểm mua sắm, là cơ hội cho các chiến dịch quảng cáo.
- **Doanh thu hàng tháng:** Cửa hàng có thể tối ưu hóa chiến lược tiếp thị trong các tháng có doanh thu thấp hơn để tăng cường doanh số.

Dự án này giúp tối ưu hóa chiến lược kinh doanh dựa trên dữ liệu thực tế về sản phẩm, khách hàng và thời gian, nhằm cải thiện doanh thu và hiệu suất tổng thể.
