# Titanic
Titanic - Machine Learning from Disaster
Dữ liệu đầu vào – input bao gồm: 2 tập dữ liệu gần tương tự nhau có thông tin về hành khách
	- Tập dự liệu “train.csv” và tập “test.csv”
	- Tập train  chứa thông tin chi tiết về một nhóm nhỏ các hành khách trên tàu (chính xác là 	891) và quan trọng là sẽ tiết lộ liệu họ có sống sót hay không
	- Tập test chứa thông tin tương tự nhưng không tiết lộ khả năng sống sót.
Sử dụng các mẫu tìm thấy trong dữ liệu train.csv, dự đoán xem 418 hành khách khác trên tàu (được tìm thấy trong test.csv) có sống sót hay không
Dữ liệu đầu ra – output: Tệp phải có chính xác 2 cột: PassengerId (được sắp xếp theo thứ tự bất kỳ) Survived (chứa các dự đoán nhị phân của bạn: 1 cho người sống sót, 0 cho người chết)
Kết hợp tập dữ liệu train và set ->full
Bổ sung các giá trị còn thiếu và cũng tìm kiếm các mối tương quan và tính năng có thể ảnh hưởng đến sự sống còn của hành khách.
Biến name có thể chia nhỏ ra thành name (tên) và Title (Chức danh)
Tạo biến family từ SibSp + Parch và có phải độc thân hay không
Xử lý các giá trị bị thiếu trong fare, Embarked và quan trọng là Age
Khi có biến Age , có thể tạo ra biến phụ thuộc mới: Child và Mother
Các Child và Mother ở các class khác nhau có khả năng sống sót khác nhau
Tập dữ liệu full có các biến cũ và thêm các biến đã được xữ lý
Lựa chọn và sàng lọc lại các biến cần thiết và không bị thiếu giá trị

