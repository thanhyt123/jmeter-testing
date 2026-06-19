# JMeter Performance Testing Lab

## Thông tin sinh viên

* Họ và tên: Nguyễn Văn Thành
* GitHub: thanhyt123

## Mục tiêu

Tìm hiểu và thực hành công cụ kiểm thử hiệu năng Apache JMeter.

## Công cụ sử dụng

* Apache JMeter
* Java JDK 11
* Windows 11

## Kịch bản kiểm thử

Website được kiểm thử:

https://httpbin.org/get

Thông số:

* Number of Threads (Users): 10
* Ramp-Up Period: 5 giây
* Loop Count: 10

Tổng số request:

100 requests

## Các bước thực hiện

### Bước 1: Tạo Test Plan

Tạo một Test Plan mới trong JMeter.

### Bước 2: Tạo Thread Group

Thiết lập:

* Users: 10
* Ramp-Up: 5
* Loop Count: 10

### Bước 3: Thêm HTTP Request

Method: GET

URL: https://httpbin.org/get

### Bước 4: Thêm View Results Tree

Theo dõi Request và Response.

### Bước 5: Thêm Summary Report

Thu thập số liệu kiểm thử.

## Kết quả

* Success Rate: 100%
* Error Rate: 0%
* Các request được xử lý thành công.

## Nhận xét

JMeter là công cụ hữu ích để kiểm thử hiệu năng và tải hệ thống. Qua bài thực hành đã hiểu được cách tạo Test Plan, gửi HTTP Request và phân tích kết quả.

## Kết luận

JMeter hỗ trợ đánh giá hiệu năng ứng dụng hiệu quả và dễ sử dụng cho các bài thực hành kiểm thử phần mềm.
