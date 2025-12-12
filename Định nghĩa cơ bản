1. Chi phí trên AWS
Service: Billing and Cost Management
Month-to-date cost: Chi phí đã sử dụng từ đầu tháng
Total forecasted cost for current month: Tổng chi phí dự kiến cho tháng hiện tại nếu dùng từ giờ đến cuối tháng
Last month's cost for same time period: So sánh chi phí với tháng trước
Last month's total cost: Tổng chi phí tháng trước

Cost breakdown: Các dịch vụ đang được tính chi phí (VD: EC2, S3, Lightsail, RDS, ....)
Bill: Check bill của tháng hiện tại, hoặc các tháng trước

2. Regions
+ Định nghĩa Regions
- Là một khái niệm để mô tả một khu vực địa lý trên thế giới mà AWS cung cấp các dịch vụ điện toán đám mây. Mỗi AWS Region là một khu vực độc lập với cơ sở hạ tầng và các dịch vụ
- Mỗi region sẽ bao gồm nhiều Availability Zone (AZ)
Hiểu đơn giản Regions sẽ là vùng mà AWS cung cấp dịch vụ (Ví dụ: Asia có Singapore và Tokio, Seoul)
+ Lựa chọn region
Việc lựa chọn dựa trên các tiêu chí sau
- Tuân thủ compliance ( tiêu chuẩn ngành, luật pháp,v.v)
- Ưu tiên gần người dùng để mang lại trải nghiệm tốt nhất ( giảm độ trễ) (Ví dụ: Dịch vụ người dùng đa số ở VN, thì nên đặt ở bên SGP)
- Dịch vụ cần sử dụng có ở region đấy không
- Giá cả của dịch vụ
* Lưu ý:
- Luôn phải chọn region trước khi thực hiện bất kỳ thao tác nào.

3. Availability Zone - AZ
- Mội Availability Zone (AZ) là một trung tâm dữ liệu hoặc một nhóm các trung tâm dữ liệu nằm trong cùng một khu vực vật lý, nhưng được phân bổ và vận hành hoàn toàn độc lập. Mỗi AZ có thể có các tài nguyên đám mây như máy chủ ảo, ổ cứng. network, security, các dịch vụ khác nhau, cùng với các tài nguyên hỗ trợ khác như hệ thống cấp điện
- Việc sử dụng nhiều AZ, giúp đảm bảo tính khả dụng (HA) cao cho ứng dụng, tăng tính bảo mật và đảm bảo dữ liệu được lưu trữ và xử lý an toàn. Nếu một AZ gặp sự cố hoặc ngừng hoạt động, các tài nguyên đám mây được triển khai tại các AZ khác vẫn có thể hoạt động bình thường, giúp đảm bảo rằng dịch vụ của bạn vẫn hoạt động một cách liên tục và đáng tin cậy.
- Mỗi region của AWS thường có ít nhất 3 AZs
Ví dụ: Ở region Singapore(ap-southeast) sẽ có các zone:
ap-southeast-1a
ap-southeast-1b
ap-southeast-1c
- Hầu hết các service của AWS đều hỗ trợ triển khai trên Multi-AZ để đảm bảo nâng cao High Avalibility của hệ thống

4. Local Zone
Enable local zone trên console
* Chỉ bật khi thật sự có nhu cầu
