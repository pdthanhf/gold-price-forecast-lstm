# Dự báo giá vàng sử dụng LSTM

## 1. Giới thiệu
Đề tài tập trung vào việc ứng dụng khoa học dữ liệu để dự báo giá vàng trong ngắn hạn dựa trên dữ liệu lịch sử.

## 2. Dữ liệu
- Nguồn: Yahoo Finance (GC=F)
- Thời gian: 2000 – 2025
- Biến sử dụng: Giá đóng cửa (Close)

## 3. Phương pháp
- Chuẩn hóa dữ liệu bằng MinMaxScaler
- Sử dụng mô hình LSTM để học chuỗi thời gian
- Dự báo giá vàng trong 30 ngày tương lai

## 4. Kết quả
- Mô hình LSTM cho kết quả RMSE và MAE ở mức chấp nhận được
- Dự báo cho thấy xu hướng tăng nhẹ trong ngắn hạn

## 5. Hạn chế
- Chỉ sử dụng dữ liệu đơn biến
- Chưa kết hợp yếu tố kinh tế vĩ mô

## 6. Hướng phát triển
- Mở rộng sang mô hình đa biến
- Áp dụng Transformer cho chuỗi thời gian

## 7. Hướng dẫn chạy
1. Mở notebook
2. Chọn Runtime → Run all
3. Quan sát kết quả dự báo

## Tác giả
Sinh viên Công nghệ Thông tin 
