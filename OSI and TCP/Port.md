Port là giao thức bit 16 đứng đầu mỗi tập tin được truyền và nhận thông qua giao thức TCP, UDP. Port mạng cũng được gọi là cổng quy định các tệp dữ liệu riêng biệt. Mỗi port mạng được định danh bởi một số nguyên từ 0 đến 65535. Trong đó:

Các port từ 0 đến 1023 được xem như là các port cố định, được sử dụng cho các dịch vụ mạng chuẩn như HTTP (port 80), FTP (port 21), Telnet (port 23), và SSH (port 22). 
Các port từ 1024 đến 49151 là các port được sử dụng cho các ứng dụng và dịch vụ tùy chỉnh. 
Các port từ 49152 đến 65535 được sử dụng cho các kết nối tạm thời hoặc các kết nối ngẫu nhiên giữa các thiết bị.

Port 20 - 21 - TPC - File Transfer - FTP data: Port 20 là một trong số các cổng được sử dụng trong giao thức truyền tải tệp tin FTP (File Transfer Protocol). Khi một máy tính muốn truyền tệp tin đến một máy tính khác thông qua giao thức FTP, nó sẽ thiết lập kết nối với máy tính đó thông qua Port 20.

Port 22 - TCP /UDP - SSH Remote Login Protocol: Port 22 là một trong những cổng mạng được sử dụng trong giao thức truyền tải dữ liệu SSH (Secure Shell). SSH là một giao thức mạng được sử dụng để truyền tải dữ liệu an toàn giữa các thiết bị mạng, giúp ngăn chặn các cuộc tấn công giả mạo, đánh cắp thông tin hoặc thay đổi dữ liệu trong quá trình truyền tải. 

Port 23 - TCP - Telnet: Port 23 là một trong những cổng mạng được sử dụng để truy cập vào máy chủ thông qua giao thức Telnet. 

Port 25 - TCP - Simple Mail Transfer Protocol (SMTP): Port 25 là một trong những cổng mạng được sử dụng để gửi và nhận email qua giao thức SMTP (Simple Mail Transfer Protocol). Tuy nhiên, để ngăn chặn spam và các cuộc tấn công email, nhiều nhà cung cấp dịch vụ Internet đã chặn cổng 25 và yêu cầu người dùng sử dụng cổng khác để gửi email.

Port 53 - DNS: Port 53 là một trong những cổng mạng được sử dụng trong giao thức DNS (Domain Name System). Giao thức DNS là một trong những giao thức quan trọng nhất trong mạng internet được sử dụng để dịch địa chỉ IP thành tên miền và ngược lại.

Port 67 - DHCP/BOOTP: Port 67 là một trong hai cổng mạng được sử dụng trong giao thức DHCP (Dynamic Host Configuration Protocol). Giao thức DHCP được sử dụng để cấu hình địa chỉ IP tự động cho các thiết bị trong mạng. Khi một thiết bị mới kết nối đến mạng, nó sẽ gửi yêu cầu DHCP trên cổng 67 để yêu cầu một địa chỉ IP và các thông tin khác như subnet mask, gateway mặc định và DNS server. 

Port 102 - RPC: Port 102 được sử dụng trong giao thức RPC (Remote Procedure Call), một giao thức cho phép các tiến trình trong một mạng thực hiện các thủ tục từ xa. Port 102 thường được sử dụng bởi các máy chủ RPC và các máy khách để truy cập các dịch vụ RPC trên mạng.

Port 143: IMAP (Internet Message Access Protocol) - Sử dụng để nhận email, cho phép truy cập email từ nhiều thiết bị.


Port 691- MS Exchange: Port 691 được sử dụng trong giao thức MS Exchange Routing, một giao thức được sử dụng bởi Microsoft Exchange Server để định tuyến thư điện tử giữa các máy chủ Exchange trên mạng.

Port 110 - POP3: Port 110 là một trong những cổng mạng được sử dụng trong giao thức truyền thư (POP3 - Post Office Protocol version 3). Thiết bị sẽ kết nối đến máy chủ thông qua port 110, sau đó sử dụng các lệnh POP3 để yêu cầu máy chủ gửi thư đến

Port 443- HTTPS: sử dụng trong giao thức HTTPS (Hypertext Transfer Protocol Secure). Giao thức HTTPS được sử dụng để truyền tải dữ liệu an toàn trên Internet bằng cách sử dụng một lớp mã hóa SSL/TLS.

Port Port 445 SMB (Server Message Block) - Sử dụng cho chia sẻ tệp trên mạng cục bộ.

Port 465 - SMTPS: Được sử dụng trong giao thức SMTPS (Simple Mail Transfer Protocol Secure). Giao thức SMTPS được sử dụng để gửi thư điện tử an toàn trên Internet bằng cách sử dụng SSL/TLS để mã hóa dữ liệu.

Port 554 - RTSP: được sử dụng trong giao thức RTSP (Real-Time Streaming Protocol)

Port 8080: HTTP Alternate (HTTP trên port không chuẩn) - Thường dùng cho các dịch vụ web không chạy trên port 80.

Port 546-547 DHCPv6: Được sử dụng trong giao thức DHCPv6 (Dynamic Host Configuration Protocol version 6)

Port 989-990 - FTPS: được sử dụng trong giao thức FTPS (File Transfer Protocol Secure). Giao thức FTPS được sử dụng để truyền tải dữ liệu an toàn trên mạng bằng cách sử dụng SSL/TLS. 

Port 1433-1434 - Microsoft SQL: Được sử dụng trong giao thức Microsoft SQL Server. Giao thức Microsoft SQL Server được sử dụng để kết nối và truy cập cơ sở dữ liệu Microsoft SQL Server từ các ứng dụng khác.

Port 3306 - MySQL: được sử dụng trong giao thức MySQL. Giao thức MySQL được sử dụng để kết nối và truy cập cơ sở dữ liệu MySQL từ các ứng dụng khác.
Port 3389:

Port 3389: RDP (Remote Desktop Protocol) - Sử dụng để điều khiển máy tính từ xa.










![image](https://github.com/DiWien/Traning-Networking/assets/88604764/5efc1209-ced7-4fe7-aade-145b050d9b7e)
