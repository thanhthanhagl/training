# Chapter 01
Báo cáo về cơ chế hoạt động của website
## 1. Cơ chế hoạt động của internet
Internet là một mạng lưới cáp vật lý toàn cầu, có thể bao gồm dây đồng điện thoại, cáp TV và cáp quang. Ngay cả các kết nối không dây như Wi-Fi và 3G / 4G cũng dựa vào các loại cáp vật lý này để truy cập Internet. Khi bạn truy cập một trang web, máy tính của bạn sẽ gửi một yêu cầu qua các dây này tới một máy chủ. Máy chủ là nơi lưu trữ các trang web và nó hoạt động giống như ổ cứng máy tính của bạn. Khi yêu cầu đến, máy chủ sẽ truy xuất trang web và gửi dữ liệu chính xác trở lại máy tính của bạn. 
## 2. Giải thích về protocol của HTTP/HTTPS
### **HTTP (Hypertext Transfer Protocol)** <br/>
HTTP là giao thức truyền tải siêu văn bản. Đây là giao thức tiêu chuẩn cho World Wide Web (www) để truyền tải dữ liệu dưới dạng văn bản, âm thanh, hình ảnh, video từ Web Server tới trình duyệt web của người dùng và ngược lại.<br/>
HTTP là một giao thức ứng dụng của bộ giao thức **TCP/IP (các giao thức nền tảng cho Internet)**. Bộ giao thức TCP/IP là một bộ các giao thức truyền thông cài đặt chồng giao thức mà Internet và hầu hết các mạng máy tính thương mại đang chạy trên đó. Bộ giao thức này được đặt theo tên hai giao thức chính là TCP *(Transmission Control Protocol – Giao thức điều khiển truyền vận)* và IP *(Internet Protocol – Giao thức Internet)*.<br/>
HTTP hoạt động theo mô hình Client (máy khách) – Server (máy chủ). Việc truy cập website được tiến hành dựa trên các giao tiếp giữa 2 đối tượng trên. Khi bạn truy cập một trang web qua giao thức HTTP, trình duyệt sẽ thực hiện các phiên kết nối đến server của trang web đó thông qua địa chỉ IP do hệ thống phân giải tên miền DNS cung cấp. Máy chủ sau khi nhận lệnh, sẽ trả về lệnh tương ứng giúp hiển thị website, bao gồm các nội dung như: văn bản, ảnh, video, âm thanh,…
### **HTTPS (Hypertext Transfer Protocol Secure)**<br/>
HTTPS là giao thức truyền tải siêu văn bản an toàn. Thực chất, đây chính là giao thức HTTP nhưng tích hợp thêm Chứng chỉ bảo mật SSL nhằm mã hóa các thông điệp giao tiếp để tăng tính bảo mật. Có thể hiểu, HTTPS là phiên bản HTTP an toàn, bảo mật hơn.<br/>
HTTPS hoạt động tương tự như HTTP, tuy nhiên được bổ sung thêm chứng chỉ ***SSL (Secure Sockets Layer – tầng ổ bảo mật)*** hoặc ***TLS (Transport Layer Security – bảo mật tầng truyền tải)***.
## 3. Cơ chế hoạt động của browser và sự khác nhau giữa các browser
### **Cơ chế hoạt động của browser**<br/>
Browser hoạt động dựa trên 4 bước:<br/>
**Bước 1:** Thu thập dữ liệu từ các website<br/>
Công việc này được thực hiện tự động dựa trên các thuật toán và hệ thống máy chủ tương đối phức tạp bởi mỗi ngày có đến hàng tỷ nội dung/ hàng trăm triệu website trên Internet.<br/>
**Bước 2:** Đánh giá, phân loại dữ liệu<br/>
Mỗi loại trình duyệt sẽ có quá trình phân tích, phân loại nội dung dữ liệu khác nhau và sẽ trả về kết quả tìm kiếm khác nhau.<br/>
**Bước 3:** Truy xuất dữ liệu<br/>
Nhiệm vụ của các trình duyệt web là đưa ra gợi ý gần nhất với từ khóa tìm kiếm của người dùng. Nó phụ thuộc vào 2 yếu tố chính: Hành vi của người dùng và sự liên quan của từ khóa.<br/>
**Bước 4:** Hiển thị nội dung người dùng cần tìm kiếm<br/>
Sau khi đã thu thập, phân tích hành vi người sử dụng, trình duyệt web sẽ tối ưu nội dung/ hình ảnh để tương thích nhất với các thiết bị của bạn.<br/>
### **Sự khác nhau giữa các browser**
* **Google Chrome** là trình duyệt được đánh giá cao về tính bảo mật, tốc độ và khả năng tùy biến cao nhờ kho tiện ích mở rộng (Extensions) phong phú. Những phiên bản trước của trình duyệt Chrome bị người dùng đánh giá là gây hao tốn bộ nhớ RAM trên máy tính nhưng với tốc độ, tính bảo mật cùng một số tiện ích nâng cao giúp cho Google Chrome vẫn là trình duyệt được ưa thích với số lượng cài đặt hàng triệu lượt mỗi ngày. Những phiên bản Chrome hiện nay được cải thiện và nâng cao hơn về tính năng bảo mật và lỗi tràn bộ RAM cũng được cải thiện đáng kể.<br/>
* **Mozilla Firefox** lần đầu ra mắt người dùng vào năm 2002 khi đó Internet đang phát triển. Cho tới năm 2012 thì Mozilla Firefox vươn lên vị trí thứ 2 sau trình duyệt mặc định của Windows là Internet Explorer trong cuộc đua các trình duyệt phổ biến nhất. Trình duyệt Firefox được đánh giá cao về tính ổn định và không bị tràn bộ nhớ RAM như trình duyệt Chrome. Nhược điểm của Mozilla Firefox có lẽ là tốc độ tải trang không nhanh và kho tiện ích mở rộng không phong phú. <br/>
* **Opera** một trong những trình duyệt có mặt từ lâu đời nhất từng được ra mắt vào năm 1995 khi mà Internet vẫn còn chưa được phổ biến rộng rãi. Trình duyệt Opera với ưu điểm gọn nhẹ, tích hợp nhiều tính năng hữu ích như bộ lọc quảng cáo Ad-block, mạng riêng ảo VPN…<br/>
* **Cốc Cốc** được mệnh danh là một trình duyệt web phổ biến dành thị phần trình duyệt web tại Việt Nam. Sở hữu những chức năng phục vụ cho nhu cầu người dùng Việt Nam như: Chỉnh sửa chính tả, truy cập Facebook, tải video từ bất kỳ trang web nào,… Cốc Cốc có tốc độ tải video cực nhanh và có nhiều tiện ích cá nhân tiện lợi tuy nhiên nó lại tiêu tốn khá nhiều tài nguyên hệ thống.<br/>
* **Microsoft Edge** là trình duyệt web phổ biến mặc định trên hệ điều hành Windows 10. Edge ghi điểm bởi khả năng lướt web cực nhanh và độ tương tác với Cortana khá tốt. Đặc biệt, đây là công cụ thay thế cho các trình đọc file i pdf. <br/>
* **Safari** là một trình duyệt website mặc định trên các thiết bị của Apple. Safari phân phối cho người dùng tốc độ duyệt web khá tốt. Đi kèm là giao diện mới lạ và các tiện ích riêng biệt. 
## 4. Cơ chế hoạt động của DNS và domain
### Cơ chế hoạt động của DNS
DNS là ký hiệu viết tắt của **Domain Name System**, nghĩa tiếng Việt là hệ thống phân giải tên miền.<br/>
![DNS](https://bizflyportal.mediacdn.vn/thumb_wm/1000,100/bizflyportal/images/dns16154343449688.jpeg)<br/>
Với cấu trúc như hình, máy chủ DNS sẽ tự động tìm kiếm thông tin đã phân giải tại file hosts của hệ điều hành. Việc tìm kiếm có thể dẫn tới một trong hai kết quả:<br/>
* Không thấy thông tin -> DNS tiếp tục tìm kiếm tại bộ nhớ cache
* Không nhận được bất cứ thông tin nào -> DNS hiển thị mã lỗi. 
### Cơ chế hoạt động của domain
Domain chính là địa chỉ đại diện cho website của bạn. Một domain name chỉ tồn tại cho một website. <br/>
Khi bạn nhập một domain name vào thanh URL của trình duyệt web, lúc này nó sẽ gửi yêu cầu truy cập đến một mạng lưới máy chủ toàn cầu hình thành nên hệ thống domain (DNS). Sau đó các máy chủ toàn cầu này sẽ tìm kiếm các máy chủ có tên được liên kết với domain và chuyển tiếp yêu cầu đến các máy chủ tên đó.
## 5. Giải thích về hosting server
**Hosting** là dịch vụ lưu trữ dữ liệu và chia sẻ liệu trực tuyến, là không gian trên máy chủ có cài đặt các dịch vụ Internet như world wide web (www), truyền file (FTP), Mail…, bạn có thể chứa nội dung trang web hay dữ liệu trên không gian đó. <br/>
**Server** (Máy chủ) là một máy tính được kết nối với mạng máy tính hoặc Internet, có IP tĩnh, có năng lực xử lý cao. Trên đó người ta cài đặt các phần mềm để phục vụ cho các máy tính khác truy cập để yêu cầu cung cấp các dịch vụ và tài nguyên.



