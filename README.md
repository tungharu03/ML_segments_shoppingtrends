# Customer Shopping Trends
## Mô tả dữ liệu
Bộ dữ liệu này bao gồm các đặc điểm liên quan đến sở thích mua sắm của khách hàng, thu thập thông tin cần thiết cho các doanh nghiệp mong muốn nâng cao sự hiểu biết về cơ sở khách hàng của họ. Với một bộ dữ liệu gồm 3900 bản ghi, bộ dữ liệu này là nền tảng cho các doanh nghiệp mong muốn áp dụng những hiểu biết dựa trên dữ liệu để ra quyết định tốt hơn và chiến lược tập trung vào khách hàng.

Customer ID: Định danh duy nhất cho mỗi khách hàng.
Age: Tuổi của khách hàng.
Gender: Giới tính của khách hàng (Nam/Nữ).
Item Purchased: Mặt hàng được mua bởi khách hàng.
Category: Danh mục của mặt hàng đã mua.
Purchase Amount (USD): Số tiền của giao dịch mua hàng
Location: Địa điểm mà giao dịch mua hàng được thực hiện.
Size: Kích cỡ của mặt hàng đã mua.
Color: Màu sắc của mặt hàng đã mua.
Season: Mùa trong đó giao dịch mua hàng được thực hiện.
Review Rating: Điểm đánh giá từ khách hàng cho mặt hàng đã mua.
Subscription Status: Chỉ ra liệu khách hàng có đăng ký (Có/Không).
Payment Method: Phương thức thanh toán của khách hàng.
Shipping Type: Loại vận chuyển được chọn bởi khách hàng.
Discount Applied: Chỉ ra liệu có áp dụng giảm giá cho giao dịch mua hàng hay không (Có/Không).
Promo Code Used: Chỉ ra liệu có sử dụng mã khuyến mãi cho giao dịch mua hàng hay không (Có/Không).
Previous Purchases: Số lần mua hàng trước đó của khách hàng.
Preferred Payment Method: Phương thức thanh toán ưa thích của khách hàng.
Frequency of Purchases: Tần suất mà khách hàng thực hiện các giao dịch mua hàng (ví dụ: Hàng tuần, Hàng hai tuần, Hàng tháng).

# Các kỹ thuật phân tích hành vi khách hàng
## Phân khúc khách hàng 
Phân khúc khách hàng là kỹ thuật chia khách hàng thành các nhóm nhỏ dựa trên các đặc điểm chung như độ tuổi, giới tính, sở thích, hành vi mua sắm, v.v. 

## Học máy
Sử dụng các mô hình học máy:Random Forestm, Extreme Gradient Boosting để dự đoán tần suất mua hàng của khách hàng từ bộ dữ liệu đã có 

# Tạo thêm mẫu dữ liệu bằng Generative Adversarial Networks (GANs)

Do độ tương quan giữa các thuộc tính với Frequency of Purchases thấp và bộ dữ liệu chưa đủ nhiều do đó sử dụng GANs để gia tăng dữ liệu để tăng độ chính xác của mô hình, sau đó có thể xây dựng models để dự đoán
