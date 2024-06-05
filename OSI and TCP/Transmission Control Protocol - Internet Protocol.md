
Mô HÌNH TCP/IP (Transmission Control Protocol/Internet Protocol) là một tập hợp các giao thức được sử dụng để truyền dữ liệu qua mạng Internet. Mô hình TCP/IP gồm bốn tầng, khác với mô hình OSI bảy tầng, nhưng chúng có một số điểm tương đồng về chức năng. Dưới đây là mô tả của từng tầng trong mô hình TCP/IP:

4 Layer : Application - Transport - Network - Network Interface / Link

--------------------------------------------------------------------------------------------
Network Applications 

DHCP Client: Tự động gán địa chỉ IP.

Máy khách DNS: Phân giải tên miền thành địa chỉ IP.

Máy khách/Máy chủ FTP: Xử lý việc truyền tệp giữa máy khách và máy chủ.

Máy khách/Máy chủ HTTP: Quản lý các yêu cầu và phản hồi trên web.

Máy khách MQTT: Giao thức truyền thông IoT.

Máy khách SMTP: Quản lý việc gửi email.

SNMP Agent: Được sử dụng để quản lý mạng.

SNTP Client: Đồng bộ hóa thời gian trên các mạng.

Máy chủ TELNET: Cung cấp khả năng đăng nhập từ xa.

Máy khách/Máy chủ TFTP: Giao thức truyền tệp đơn giản được sử dụng chủ yếu cho các tệp nhỏ.
--------------------------------------------------------------------------------------------
Lõi TCP/IP (Core TCP/IP)

Cốt lõi của ngăn xếp bao gồm nhiều lớp và thành phần, mỗi lớp chịu trách nhiệm về các chức năng cụ thể:

Ngăn xếp SSL: Cung cấp các tính năng bảo mật cho giao tiếp được mã hóa.

Cổng bảo mật (SSL): Giao diện để liên lạc an toàn qua SSL.

API ổ cắm: Giao diện cho giao tiếp mạng.
--------------------------------------------------------------------------------------------
Lớp vận chuyển (Transport Layer)

TCP (Giao thức điều khiển truyền): Đảm bảo việc phân phối dữ liệu đáng tin cậy, có trật tự và được kiểm tra lỗi.

UDP (Giao thức gói dữ liệu người dùng): Cung cấp mô hình truyền thông không kết nối với các cơ chế giao thức tối thiểu.
--------------------------------------------------------------------------------------------
Internet Layer
Internet Protocol (IP): Xử lý việc đánh địa chỉ và định tuyến các gói trên mạng.

IGMP (Internet Group Management Protocol): Quản lý tư cách thành viên nhóm multicast.

ICMP (Internet Control Message Protocol): Được sử dụng cho các thông báo lỗi và thông tin vận hành.

ARP (Address Resolution Protocol): Phân giải địa chỉ IP thành địa chỉ MAC (vật lý).

--------------------------------------------------------------------------------------------
Network Interface Layer
Ethernet: A common wired networking technology.

Wi-Fi: Wireless networking technology.

PPP (Point-to-Point Protocol): Encapsulation protocol for point-to-point connections.

--------------------------------------------------------------------------------------------
Data Flow
Network applications communicate through the SSL Stack for secure communication or directly through the TCP/IP Core for standard communication.

The core components (TCP, UDP, IP, etc.) manage the flow of data from applications to the network interface (Ethernet, Wi-Fi, PPP) and vice versa.

--------------------------------------------------------------------------------------------

![image](https://github.com/DiWien/Traning-Networking/assets/88604764/a43e1273-d47c-4ec0-8ce7-e677047aecab)

![image](https://github.com/DiWien/Traning-Networking/assets/88604764/2acf737a-2293-4a68-9c14-3e4722b5d21d)

