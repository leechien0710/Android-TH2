# Bài tập HTML và CSS:
## Bài 1:
### Thẻ inline
Các thẻ inline là những thẻ không tạo ra dòng mới nghĩa là nội dung của thẻ bến dưới chúng sẽ ngang hàng với nội dung thẻ inline chứ chúng không xuống dòng. 
* 10 thẻ inline:
1. \<a\>:: Liên kết đến một trang web hoặc một tài liệu khác.
2. \<i\>: in ra chữ nghiêng.
3. \<span\>: không có ý nghĩa ngữ pháp riêng mà thường được dùng để in ra một phần văn bản.
4. \<em\>: làm nổi bật nội dung văn bản, mặc định sẽ in ra chữ nghiêng giống thẻ <i> nhưng thẻ <i> không có ý nghĩa cụ thể nào cả.
5. \<input\>: tạo phần tử để người dùng nhập dữ liệu.
6. \<button\>: tạo nút kích hoạt một hành động.
7. \<label\>: gắn nhãn cho một trường nhập liệu.
8. \<select\>: tạo một danh sách thả xuống.
9. \<b\>: in đậm văn bản.
10. \<img\>: hiển thị hình ảnh.
### Thẻ block:
Thẻ block là các thẻ chiếm một dòng riêng, thường được sử dụng để tạo các phần tử bố cục lớn, chẳng hạn như đoạn văn, tiêu đề, và hình ảnh.
* 10 thẻ block:
1. \<h1\>-\<h6\>: Thẻ tiêu đề
2. \<p\: Thẻ đoạn văn
3. \<div\>: Thẻ tạo khối, chia bố cục.
4. \<ul\>: tạo danh sách không có thứ tự.
5. \<ol\>: tạo danh sách có thứ tự.
6. \<li\>: Được sử dụng để tạo các mục trong danh sách (<ul> hoặc <ol>).
6. \<table\>: tạo bảng.
7. \<form\> : tạo biểu mẫu.
8. \<video\> : hiển thị video.
9. \<address\>: Được sử dụng để đánh dấu thông tin liên hệ của tác giả hoặc chủ sở hữu của tài liệu.
10. \<fieldset\>: Được sử dụng để tạo một nhóm các phần tử <input> trong một biểu mẫu HTML và tạo ra một khung xung quanh chúng.
### Thẻ semantic:
Thẻ semantic là các thẻ HTML có ý nghĩa ngữ nghĩa rõ ràng, giúp cho trình duyệt và các công cụ hỗ trợ truy cập có thể hiểu được nội dung của trang web một cách chính xác hơn.
* Các thẻ semantic:
1. \<header\>: Được sử dụng để đánh dấu phần tiêu đề hoặc phần đầu của một phần tử hoặc trang web.
2. \<nav\>: Được sử dụng để đánh dấu các liên kết điều hướng, thường xuất hiện ở đầu trang web.
3. \<main\>: Được sử dụng để đánh dấu phần nội dung chính của trang web.
4. \<article\>: Được sử dụng để đánh dấu một phần tử độc lập và tự đủ, chẳng hạn như một bài viết hoặc một phần nội dung khác có thể tồn tại độc lập với trang web.
5. \<section\>: Được sử dụng để đánh dấu một phần độc lập và có ý nghĩa ngữ pháp riêng biệt trong một tài liệu HTML.
6. \<aside\>: Được sử dụng để đánh dấu một phần nội dung bên cạnh nội dung chính và thường chứa thông tin phụ thuộc vào nội dung chính.
7. \<footer\>: Được sử dụng để đánh dấu phần cuối của một phần tử hoặc trang web, thường chứa thông tin về bản quyền hoặc thông tin liên hệ.
8. \<figure\> và \<figcaption\>: Được sử dụng để nhúng hình ảnh hoặc đồ họa cùng với một chú thích, giúp gắn kết nội dung mô tả với hình ảnh.
9. \<summary\>: được sử dụng để hiển thị một đoạn văn bản ngắn gọn tóm tắt nội dung của thẻ <details>.
10. Thẻ \<details\>: được sử dụng để xác định nội dung chi tiết hơn về nội dung chính của trang web. Nội dung chi tiết sẽ được ẩn đi cho đến khi người dùng nhấp vào thẻ <summary> để mở rộng nó ra.
11. \<time\>: được sử dụng để xác định thời gian hoặc ngày tháng.
## Bài 2:
BEM (Block, Element, Modifier) là một phương pháp đặt tên lớp CSS có cấu trúc và có mục đích để tạo ra mã CSS dễ đọc, dễ bảo trì và tái sử dụng. Trong BEM, một phần tử giao diện được chia thành các khối (block), các phần tử (element), và các bổ sung (modifier).
Ví dụ về BEM:
...html
    <div class="boy">Boy</div>
    <div class="boy boy__button">Boy Image</div>
    <div class="boy boy__button boy__button--highlighted">Boy Button</div>
## Bài 3
