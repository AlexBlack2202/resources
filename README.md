# Vietnamese 

Dự án xây dựng tài nguyên cho các bài toán NLP tiếng Việt 🇻🇳

Ý tưởng: 

* Cho mô hình chạy gán nhãn tự động các câu thú vị nhất  
* Ít nhất 3 người gán nhãn lại 
* Ít nhất 3 người reviews 
* Tất cả qua giao diện text 
* Luồng phát triển qua git
* Cập nhật dữ liệu từ wikipedia, baomoi
* Chương trình hoàn toàn tự động thông qua các bot 
* Cập nhật dữ liệu HÀNG TUẦN

Mô hình cải tiến

```
+----------------+    +----------------+     +----------------+
|                |    |                |     |                |
|    Đề Xuất     + -> |    Xem Xét     +  -> |   Cập Nhật     +
|                |    |                |     |                |
+-------+--------+    +-------+--------+     +-------+--------+
```

* Bước 1: Đưa các các đề xuất
* Bước 2: Các đề xuất được xem xét 
* Bước 3: Các đề xuất đúng sau khi được xem xét sẽ được cập nhật vào dữ liệu

**Câu hỏi 1**: Làm sao các mô hình luôn cải tiến chất lượng

- Cần chạy mô hình liên tục
- Cần có người để sửa sai cho mô hình
- Sau đó cập nhật lại mô hình với dữ liệu đã sửa sai 



