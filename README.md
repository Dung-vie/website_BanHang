# Website Thương Mại Điện Tử (ReactJS + Python + AWS)

##  Giới thiệu
Ứng dụng web hỗ trợ quản lý và hiển thị sản phẩm, cho phép quản trị viên thao tác với dữ liệu thông qua giao diện trực quan.  
Hệ thống được xây dựng theo mô hình client–server và triển khai trên nền tảng cloud.

---

##  Mục đích
- Xây dựng hệ thống quản lý sản phẩm cơ bản  
- Tổ chức và lưu trữ dữ liệu trên nền tảng cloud  
- Áp dụng kiến trúc serverless để tăng khả năng mở rộng  
- Tối ưu việc trao đổi dữ liệu giữa frontend và backend  

---

## Chức năng tổng quát
- Quản trị viên đăng nhập và quản lý sản phẩm  
- Frontend giao tiếp với backend thông qua REST API  
- Dữ liệu được lưu trữ trên cloud database (DynamoDB)  
- Xử lý và validate dữ liệu trước khi gửi lên server  

---

## Chức năng chính
- Thêm, sửa, xoá và hiển thị danh sách sản phẩm  
- Kiểm tra và validate dữ liệu đầu vào  
- Giao tiếp frontend – backend thông qua REST API  
- Lưu trữ dữ liệu trên DynamoDB  
- Triển khai backend serverless với AWS Lambda  

---

## Công nghệ sử dụng
### Frontend
- ReactJS  
- HTML, CSS, JavaScript  

### Backend
- Python  

### Cloud & Deploy
- AWS Lambda  
- AWS API Gateway  

### Database
- DynamoDB  

---

## Cách chạy dự án
```bash
1. git clone dự án
2. cd website_BanHang
3. npm install
4. npm run dev
