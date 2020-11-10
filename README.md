# Jbdc-java-demo
Jbdc java demo
------------------------------------
1 - Chuẩn bị.
MySQL server (có thể dùng XAMPP).
JDBC Driver: Mỗi loại server sẽ cần một driver riêng để thực hiện. Demo sẽ thực hiện
trên MySQL nên ta sẽ dùng MySQL Connector Platform Independent. (link tải:
https://dev.mysql.com/downloads/connector/j/)
IDE: IntelliJ

2 - Thực hiện.
Bước 1: Mở ứng dụng XAMPP, kết nối đến MySQL qua PHPmyadmin.
Bước 2: Tạo Project mới, đặt tên chương trình là JBDC_demo.
Bước 3: Vào “View > Tool > Database” để mở cửa sổ quản lý kết nối database
Bước 4: Nhấn vào nút “ + > Data Source > MySQL” để tạo kết nối đến database
Bước 5: Bảng data source hiện ra, chọn “Driver > Go to Driver”
Bước 6: Ở tab Driver File, chọn Custom JARs, chọn thư mục chứa driver đã chuẩn bị, sau đó
nhấn apply.
Bước 7: Quay về trang đầu, nhấn nút “Test Connection” để kiểm tra kết nối thành công hay
chưa, nếu thành công sẽ thông báo như trong hình dưới.
Bước 8: Sau khi nhấn “OK” sẽ hiện ra tab “console” để thực hiện các lệnh trên database, thực
hiện tạo database bằng code.
Bước 9: Chuột phải vào jbdc_demo, chọn “new > table” để tạo table mới, sau đó nhập tên
table là person, table này sẽ chứa 3 cột là id (khoá chính), name và age, nhấn nút add bên phải
để thêm và quy định thuộc tính cho các cột này.
Bước 10: Sau khi nhấn “Execute”, bảng sẽ được tạo như hình dưới, nhấn nút “+” để thêm dữ
liệu vào bảng, sau đó nhấn run để thực hiện.
Bước 11: để thực hiện đưa dữ liệu vào database, nhấn tổ hợp phím “ctrl + enter”, vào
phpMyAdmin để kiểm tra dữ liệu.
Bước 12: Sau khi hoàn tất khởi tạo dữ liệu và kết nối với database, thực hiện đoạn code sau
trong demo.
Bước 13: Thực hiện chạy chương trình và xuất kết quả.
