# doan
do an tot nghiep luan van thac si


1. thanhhai_00_test
Dùng hàm sample lấy 10% mẫu đối với tập dataset.

2. thanhhai_01_preprocessing
- Xử lí lỗi kĩ tự “-” Unicode 8211 và thay đôi thành ‘”-”, unicode 45.
- Tạo ra file all_date.csv để gọp tất cả các ngày vào cung 1 file để thao tác tập dataset.
- Total operation time: = 115.90s

3. thanhhai_02_statistics
- Mục đích của chương trình này là cung cấp số liệu thống kê về dữ liệu có trong bộ dữ
liệu.
- Xem xét rằng một số dữ liệu rất lớn và một số trong số chúng rất nhỏ, đồ họa được tạo
thành ba nhóm riêng biệt, để có thể nhìn thấy tất cả dữ liệu:
  o big: nhãn có nhiều hơn 11000 số.
  o medium: nhãn nằm giữa 600 và 11000 số.
  o small: nhãn ít hơn 600 số.
- Trong đồ họa cuối cùng, tỷ lệ của tất cả các cuộc tấn công và hành vi bình thường được
đưa ra.
4. thanhhai_03_attack
- Mục đích của chương trình này là tạo ra các tệp CSV chỉ bao gồm một loại luồng tấn
công và luồng không phải tấn công.
- Tạo ra thư mục “attacks” chứa phân loại.
- These files contain all attack flow and some benign data flow. The rate : (attack= 30% ,
benign=70%)
5. thanhhai_04_1_feature_selection_for_attack_files
- Mục đích của mã này là xác định các tính năng sẽ sử dụng trong giai đoạn học máy.
- Tạo ra thư mục feature_pics.
- Cho mục đích này, trọng số của các cuộc tấn công được tính toán, được thực hiện bằng
cách sử dụng sklearn-RandomForestRegressor.
6. thanhhai_04_2_feature_selection_for_all_data
- Mục đích của mã này là xác định các tính năng sẽ sử dụng trong giai đoạn học máy.
- Chọn feature qayn trọng đối với tập all_data.
7.
Mục đích của chương trình này là áp dụng các thuật toán học máy vào bộ dữ liệu và quan
sát hiệu suất của các thuật toán.
- Các thuật toán được sử dụng là: Naive Bayes, QDA, Random Forest, ID3, AdaBoost,
MLP, Nearest Neighbors.
- Như chương trình hiển thị dữ liệu đầu ra bao gồm: file name, machine learning algorithm
name, accuracy,Precision, Recall, F1-score,Time.
- chương trình sẽ tạo một tệp CSV in kết quả và thư mục chứa graph.

