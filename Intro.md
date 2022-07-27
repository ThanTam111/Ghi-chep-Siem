# 1. Tổng quan
Hệ thống SIEM (Security Information and Event Management) là hệ thống quản lý nhật ký và sự kiện tập trung, có nhiệm vụ thu thập thông tin nhật ký, sự kiện trong toàn hệ thống doanh nghiệp và tổng hợp tất cả trên một giao diện duy nhất thay vì phải làm thủ công từng cái một.
[anh1]()
# 2. Kiến trúc hệ thống SIEM
# 2.1. Thành phần trong hệ thống SIEM
[anh]()
Hệ thống SIEM thường bao gồm 3 bộ phận chính. Đó là bộ phận thu thập nhật ký ATTT, phân tích và lưu trữ, quản trị tập trung.
-	Thu thập nhật ký ATTT có chức năng thu thập nhật ký từ các thiết bị hoạt động. Sau khi dữ liệu được tập hợp sẽ được gửi toàn bộ về bộ phận phân tích và lưu trữ.
-	Phân tích và lưu trữ có nhiệm vụ tiếp cận, tổng hợp, phân tích và lưu trữ dữ liệu. Các thuật toán so sánh sau quá trình phân tích sẽ đưa ra cảnh báo (nếu có).
-	Quản trị tập trung cung cấp giao diện quản lý tập trung cho toàn bộ hệ thống giám sát an ninh. Hàng ngàn mẫu báo được tập hợp sẵn có thể sử dụng được ngay trong mọi trường hợp.
-	Mỗi bộ phận đều có chức năng và nhiệm vụ riêng biệt. Khi kết hợp hoạt động cùng lúc sẽ tạo nên giải pháp SIEM hoàn chỉnh, làm việc hiệu quả.
# 2.2 Chức năng hệ thống SIEM
-	Quản lý tập trung: Thu thập, lưu trữ tập trung nhật ký và sự kiện từ tất cả các thiết bị trên 1 giao diện giúp quản trị viên có được cái nhìn toàn diện về những gì đang xảy ra trong hệ thống
-	Giám sát an toàn mạng: Phân tích thông tin qua các thật toán, dự đoán các sự cố bảo mật giúp các bộ phận liên quan chủ động hơn trong công việc.
-	Xử lý sự cố hiệu quả: Đưa ra cảnh báo khi có xâm nhập trái phép để kịp thời xử lý và khắc phục sự cố nhanh nhất.
# 2.3. Quy trình SIEM
[anh3]()
-	Data Collection: Giai đoạn đầu tiên là thu thập và tổng hợp một lượng lớn dữ liệu từ nhật ký dữ liệu trong mạng bằng cách triển khai các nhánh thu thập trên thiết bị người dùng, máy trạm, máy chủ, thiết bị mạng như thiết bị chuyển mạch, bộ định tuyến và các hệ thống bảo mật như antivirus, IDS/IPS, tường lửa,… Các giải pháp SIEM hiện đại có thể có được nhật ký dữ liệu của các ứng dụng đám mây bằng cách triển khai bộ thu thập trên cơ sở hạ tầng đám mây
-	Data Storage: Kết hợp tất cả dữ liệu được thu thập đó, Các hệ thống SIEM hiện đại được xây dựng trên công nghệ hiện đại như Amazon S3 hoặc Hadoop cho phép lưu trữ không giới hạn với khả năng mở rộng với chi phí thấp và cho phép lưu giữ và phân tích nhật ký dữ liệu từ các nguồn nền tảng và hệ thống rời rạc
-	Policies and Rules: SIEM cho phép nhân viên bảo mật xác định các chính sách và ngưỡng giúp tổng hợp nhật ký và phân loại các sự kiện bảo mật như đăng nhập thành công và thất bại, nỗ lực khai thác, hoạt động phần mềm độc hại và quét các port.
-	Data Correlation and Reporting: Tập hợp nhật ký dữ liệu và hợp nhất một cách tổng quát các nhật ký và sự kiện thành các sự cố bảo mật có ý nghĩa, cảnh bảo các tổ chức về các mối đe dọa đó.


