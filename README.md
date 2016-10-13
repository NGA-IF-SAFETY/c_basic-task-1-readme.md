I: Markdown là 1 ngôn ngữ đánh dấu cú pháp văn bản thô dễ viết dễ đọc dễ dàng chuyển thành HTML và nhiều định dạng khác sử dụng một công cụ cùng tên 
II:Markdowm thường được sử dụng trong file readme.me ( file dùng để mô tả ngắn project hoặc sản phẩm) hoặc viết các tin nhắn trong các diễm đàn thảo luận và dùng để tạo ra các đoạn văn bản có câu trúc phức tạp chỉ bằng một công cụ xử lý văn bản thô.
III. Cú pháp
1.TẠO TIÊU ĐỀ 
# tiêu đề 1(h1)
## tiêu đề 2(h2)
### tiêu đề 3(h3)
để tạo tiêu đề trong markdown chỉ cần chèn ký tự # ngay phía trước. số lượng kí tự # sẽ xác định độ sâu của tiêu đề (tương đương từ h1-h6 trong mã HTML)
2.ĐỊNH DẠNG CHỮ 
**In đậm** hoặc __In đậm__ 
-ví dụ (<**họ**>)
*In nghiêng* hoặc _In nghiêng_ 
-ví dụ <*tên*>
~~Chữ gạch ngang~~ 
-ví dụ ~~nga~~
3.Phân đoạn một đoạn văn bản bằng cách chèn một dòng trắng ở giữa các đoạn văn bản.
4.Xuống dòng bằng cách thêm 2 khoảng trắng ngay phía sau dòng văn bản  
5.Tạo Danh Sách
a)Tạo danh sách dạng số:
1. danh sách 1
2. danh sách 2
3. danh sách 3
b)Tạo danh sách dạng bullet:
- danh sách 1
- danh sách 2- danh sách 3
6.Tạo Liên Kết
![Tên link](đường dẫn) ![facebook](https://www.facebook.com/)
![Tên link với chú thích](đường dẫn "chú thích") 
a)Tạo liên kết tự động
Chỉ cần gõ đường link tuyệt đối (có HTTP hoặc HTTPS) Markdown sẽ tạo liên kết tự động
http://example.com ví dụ http://www.google.com
b)Tạo Hình Ảnh
![](đường dẫn) ![facebook]<https://www.facebook.com/photo.php?fbid=144703055988630&set=pb.100013468090295.-2207520000.1476377409.&type=3&theater/>
![](đường dẫn "title") 
c)Tạo Trích Dẫn (Blockquotes)
Để tạo trích dẫn bạn chèn > ngay phía trước 
> câu trích dẫn
7.Tạo Đường Kẻ Gạch Ngang
Bạn gõ --- hoặc *** hoặc ___ 
---
***
___
8.Tạo Điểm Nhấn (highlight)
==text==
Inline Code
`inline code`
9.Tạo chú thích cuối trang
Chú thích[^1] chú thích[^2].  

- [^1]: chú thích 1 
- [^2]: chú thích 2
10.tạo bảng 
Các cột được tách nhau bằng dấu ngăn thẳng đứng | và header được tách với content bằng dấu gạch ngang -.
ví dụ: 
          |   A   |   B   |   C   |
          |------:|:-----:|:-----:|
          |   1   |   3   |    5  |
    hết.
  
          
          
