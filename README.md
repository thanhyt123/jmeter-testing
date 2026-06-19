# JMeter Performance Testing Lab

## Thông tin sinh viên

* Họ và tên: Nguyễn Văn Thành
* Mã sinh viên:23010764
* GitHub: thanhyt123

## Mục tiêu

Tìm hiểu và thực hành công cụ kiểm thử hiệu năng Apache JMeter.

## Công cụ sử dụng

* Apache JMeter (Phiên bản 5.6.3)
* Java JDK 11
* Windows 11

## Kịch bản kiểm thử

Website được kiểm thử:
https://google.com

Thông số cấu hình tải:
* Number of Threads (Users): 10
* Ramp-Up Period: 5 giây
* Loop Count: 1

Tổng số request thực hiện:
10 requests

## Các bước thực hiện

### Bước 1: Tạo Test Plan
Tạo một Test Plan mới trong giao diện đồ họa của JMeter.

### Bước 2: Tạo Thread Group
Thiết lập giả lập người dùng với các thông số: Users = 10, Ramp-Up = 5, Loop Count = 1.

### Bước 3: Thêm HTTP Request
Cấu hình giao thức gửi yêu cầu đến địa chỉ máy chủ Server Name: `google.com`.

### Bước 4: Thêm Summary Report
Thêm Listener Summary Report để thu thập và tổng hợp các số liệu kiểm thử hiệu năng.

## Kết quả thu được

Dựa trên kết quả chạy thực tế thu được từ bảng **Summary Report**:
* **Tổng số requests (Samples):** 10
* **Thời gian phản hồi trung bình (Average):** 300 ms
* **Thời gian phản hồi nhỏ nhất (Min):** 281 ms
* **Thời gian phản hồi lớn nhất (Max):** 348 ms
* **Tỷ lệ lỗi (Error %):** 0.00% (Success Rate đạt 100%)
* **Tốc độ xử lý (Throughput):** 2.1 requests/giây

### Hình ảnh minh họa kết quả:
<img width="1917" height="1036" alt="image" src="https://github.com/user-attachments/assets/98715ec2-5316-4b39-9400-e4683cd914bf" />

## Nhận xét

JMeter là công cụ hữu ích để kiểm thử hiệu năng và tải hệ thống. Qua bài thực hành đã hiểu được cách tạo Test Plan, cấu hình Thread Group, gửi HTTP Request và đọc/phân tích các chỉ số cơ bản trong bảng kết quả.

## Kết luận

JMeter hỗ trợ đánh giá hiệu năng ứng dụng hiệu quả, trực quan và dễ sử dụng cho các bài thực hành kiểm thử phần mềm của sinh viên.
