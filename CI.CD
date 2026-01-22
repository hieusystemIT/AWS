CodeCommit
+ Là một dịch vụ được quản lý bởi AWS, giúp lưu trữ và quản lý source code, cấu hình và các tài liệu liên quan trong một kho lưu trữ Git an toàn, riêng tư và có thể mở rộng
- Một số tính năng bao gồm:
  + Quản lý mã nguồn: Code Commit cung cấp 1 kho lưu trữ Git, cho phép lưu trữ và quản lý mã nguồn, cấu hình và tài liệu
  + Bảo mật: CodeCommit mã hóa các tệp và metadata của bạn tại atres và trong quá trình transfer
  + Tích với với các dịch vụ AWS khác: CodeCommit có thể tích hợp với các dịch vụ AWS khác như CodeBuild, CodeDeploy và CodePipelive để tự động hóa quy trình phát triển phần mềm
  + Có thể mở rộng: CodeCommit có thể mở rộng để hỗ trợ dự án từ nhỏ đến lớn, từ 1 vài người đến hàng trăm người dùng
  + Quản lý truy cập: Tích hợp trực tiếp với IAM để quản lý truy cập, setting các policy

CodeBuld
+ CodeBuild là một dịch vụ xây dựng và kiểm thử từ AWS giúp bạn biên dịch mã nguồn, chạy kiểm thử và tạo ra các software package mà có thể được triển khai
+ Dịch vụ này hoạt động dựa trên cấu hình mà bạn cung cấp dưới dạng file 'buildspec' hoặc thông qua một Dockerfile từ source code.
- Một số tính năng bao gồm:
  • Tự động hóa
  • Có thể mở rộng: CodeBuild có thể mở rộng để xử lý các công việc xây dựng lớn và đồng thời xử lý nhiều công việc xây dựng cùng một lúc.
  • Tích hợp với các dịch vụ AWS khác như CodeCommit, CodeDeploy và CodePipeline để tự động hóa quy trình phát triển phần mềm.
  • Bảo mật: CodeBuild chạy trong một VPC riêng, giúp bảo vệ môi trường build của bạn.
  • Hiệu quả chi phí: Với CodeBuild, bạn chỉ phải trả cho thời gian build thực tế mà bạn sử dụng

CodeDeploy
+ CodeDeploy là một dịch vụ triển khai tự động từ AWS giúp bạn tự động hóa việc triển khai ứng dụng vào các môi trường dịch vụ như EC2, ECS, AWS Lambda, và cả máy chủ vật lý của bạn.
- Một số tính năng chính của CodeDeploy bao gồm:
  • Triển khai tự động: giúp giảm thời gian downtime và tăng tốc độ triển khai.
  • Triển khai môi trường phức tạp: CodeDeploy hỗ trợ triển khai vào các môi trường dịch vụ phức tạp và cung cấp khả năng quản lý cấu hình, điều khiển phiên bản và quản lý trạng thái ứng dụng.
  • Tích hợp với các dịch vụ AWS khác: như CodeCommit, CodeBuild và AWS CodePipeline để tự động hóa quy trình phát triển phần mềm.
  • Quản lý chi phí: Với CodeDeploy, bạn chỉ phải trả cho những gì bạn sử dụng. Không cần trả trước và bạn có thể bắt đầu sử dụng CodeDeploy miễn phí.
  • Cập nhật liên tục: CodeDeploy hỗ trợ cập nhật liên tục, giúp bạn triển khai các phiên bản mới của ứng dụng một cách nhanh chóng và dễ dàng.

  CodePipeline
+ CodePipeline là một dịch vụ triển khai tự động từ Amazon Web Services giúp bạn tự động hóa các bước trong quy trình phát triển phần mềm. Nó cho phép bạn xác định một chuỗi các bước, gọi là "pipeline", mà mỗi bước sẽ được thực hiện mỗi khi có thay đổi code.
Các bước này có thể bao gồm việc build code, kiểm tra và triển khai ứng dụng.
Ví dụ, bạn có thể thiết lập một pipeline với các bước sau:
  • Khi có thay đổi code trong kho lưu trữ Git, AWS CodePipeline sẽ tự động chạy.
  • Code sẽ được build bằng cách sử dụng một công cụ build như AWS CodeBuild.
  • Sau khi build thành công, các kiểm tra tự động sẽ được chạy để đảm bảo chất lượng code.
  • Nếu tất cả các kiểm tra đều thành công, code sẽ được triển khai lên một môi trường như Elastic Beanstalk hoặc Fargate (ECS).
  • Với CodePipeline, bạn có thể tự động hóa quy trình phát triển phần mềm, giúp giảm thời gian triển khai và tăng cường chất lượng sản phẩm
