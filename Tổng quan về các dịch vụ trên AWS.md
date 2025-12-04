- Các dịch vụ trong danh sách được sắp xếp theo 2 tiêu chí
+ Mức độ phổ biến trong các dự án thực tế (Service nào hay dùng được đưa lên đầu tiên)
+ Độ khó tăng dần
* Đây chỉ là một phần nhỏ, không phải là tất cả dịch vụ của AWS

- Computing & Container ( tạo ra các máy chủ)
+ EC2 (Elastic Compute Cloud)
+ ECR (Elastic Container Registry) chứa các docker image
+ ECS (Elastic Container Service) chạy các service chạy bằng docker
+ EKS (Elastic Kubernetes Service) Cluster của AWS giúp triển khai K8S

- Storage
+ S3
+ EBS
+ AWS Backup

- Networking
+ VPC (mạng ảo riêng của trong AWS)
+ CloudFront (Tạo và quản lý những network ảo trên AWS)
+ Cloud Map (Dành cho các service nội bộ)
+ Route 53 (Quản lý DNS)
+ Load Balancing (Cân bằng tải)

- Database
+ Amazon Aurora (Tương thích MySQL và PostgreSQL)
+ Amazon ElastiCache (dùng để caching data, tăng tốc độ truy vấn)
+ Amazon DynamoDB (Công nghệ SQL độc quyền của AWS)
+ Amazon RDS (Relational Database Service hỗ trợ: MySQL, PostgreSQL, MariaDB, Oracle, SQL Server) 
+ Amazon DocumentDB (Hỗ trợ cho MongoDB)

- Security & Identity
+ IAM (Quản lý người dùng và phân quyền trong AWS)
+ KMS (Quản lý mã hóa dữ liệu bằng key)
+ AWS Secrets Manager (Quản lý user, pass)
+ AWS WAF (Web Application Firewall) (Tường lửa chặn tấn công)
+ AWS Certificate Manager (ACM) (Quản lý và cung cấp SSL/TLS certificate miễn phí)

- Management & Governance
+ AWS Config
+ AWS Console
+ AWS CloudTrail
+ AWS Resource Explorer 

+ Monitoring
- CloudWatch
- AWS CloudTrail

- Deployment & Automation
+ AWS Cloud9 (Dùng để lập trình trực tiếp trên AWS)
+ AWS CodeBuild (Step “Build” trong pipeline CI/CD)
+ AWS CodeCommit (Giống như github và gitlab nhưng chạy trong AWS, lưu code an toàn trong AWS)
+ AWS CodeDeploy (Dịch vụ triển khai ứng dụng tự động lên: EC2, Lambda,.....)
+ AWS CodePipeline (Công cụ tạo pipeline CI/CD đầy đủ các bước: Source → Build → Test → Deploy)

- Migration
+ AWS Database Migration Service (AWS DMS) (Dịch vụ di chuyển database từ on-premise hoặc cloud khác sang AWS)
+ AWS Server Migration Service (AWS SMS) (Dịch vụ di chuyển máy chủ vật lý hoặc VM lên AWS) (Hỗ trợ VMware, Hyper-V, Azure VMs)