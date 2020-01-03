**Bộ Giao Thức TCP/IP** (Transmission Control Protocol/ Internet Protocol) là một bộ giao thức trao đổi thông tin được sử dụng để truyền tải và kết nối các thiết bị trong mạng internet. TCP/IP được phát triển để mạng được tin cậy hơn cùng với khả năng tự động phục hồi

Các tầng trong mô hình OSI:

<img src="https://www.totolink.vn/public/uploads/img_article/mohinhtcpiplagichucnangcuacactangtrongmohinhtcpip.png">

- Tầng 1: Tầng vật lý (Physical) tầng này chịu trách nhiệm truyền dữ liệu giữa hai thiết bị trong cùng môt mạng. Tại đây các gói giữ liệu được đóng gói vào khung(frame)và được định tuyến đi đến đích được chỉ định ban đầu.
- Tầng 2: Tầng mạng (internet) là môtj giao thức trịu trách nhiệm truyền tải dữ liệu một cách logic trong mạng. Các phân đoạn dữ liệu sẽ được đóng gói (Packets) với kích thước phù hợp với mạng chuyển mạch mà nó dùng để truyền dữ liệu.
- Tầng 3: Tầng giao vận (tranport) xử lý các vấn đề giao tiếp  giữa các mày chủ trong cùng một mạng hoặc khác mạng được kết nối với nhau thông qua bộ định tuyến.
- Tầng 4: Tầng ứng dụng (Application) đảm nhận vai trò giao tiếp giữa hai máy khác nhau thông qua các dịch vụ khác nhau, dữ liệu khi đến đây sẽ được định dạng theo kiểu byte nối byte cùng với đó là thông tin định tuyến giúp xác định đường đi đúng của một gói tin.
