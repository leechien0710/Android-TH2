# Bài tập HTML và CSS:
## Bài 1
### Thẻ inline
Các thẻ inline là những thẻ không tạo ra dòng mới nghĩa là nội dung của thẻ bến dưới chúng sẽ ngang hàng với nội dung thẻ inline chứ chúng không xuống dòng. 
* 10 thẻ inline:
1. \<a\>:: Liên kết đến một trang web hoặc một tài liệu khác.
2. \<i\>: in ra chữ nghiêng.
3. \<span\>: không có ý nghĩa ngữ pháp riêng mà thường được dùng để in ra một phần văn bản.
4. \<em\>: làm nổi bật nội dung văn bản, mặc định sẽ in ra chữ nghiêng giống thẻ \<i\> nhưng thẻ \<i\> không có ý nghĩa cụ thể nào cả.
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
6. \<li\>: Được sử dụng để tạo các mục trong danh sách (\<ul\> hoặc \<ol\>).
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
9. \<summary\>: được sử dụng để hiển thị một đoạn văn bản ngắn gọn tóm tắt nội dung của thẻ \<details\>.
10. Thẻ \<details\>: được sử dụng để xác định nội dung chi tiết hơn về nội dung chính của trang web. Nội dung chi tiết sẽ được ẩn đi cho đến khi người dùng nhấp vào thẻ \<summary\> để mở rộng nó ra.
11. \<time\>: được sử dụng để xác định thời gian hoặc ngày tháng.
## Bài 2
BEM (Block, Element, Modifier) là một phương pháp đặt tên lớp CSS có cấu trúc và có mục đích để tạo ra mã CSS dễ đọc, dễ bảo trì và tái sử dụng. Trong BEM, một phần tử giao diện được chia thành các khối (block), các phần tử (element), và các bổ sung (modifier).
Ví dụ về BEM:
```html
    <div class="boy">Boy</div>
    <div class="boy boy__button">Boy Image</div>
    <div class="boy boy__button boy__button--highlighted">Boy Button</div>
```
## Bài 3
```html
    <div class="dropdown">
        <div class="dropdown__item">Call To Action</div>
        <div class="dropdown__item">New Project</div>
        <div class="dropdown__item dropdown__item--bolded">View Profile</div>
        <div class="dropdown__item">Setting</div>
        <div class="dropdown__item">Logout</div>
    </div>
```
## Bài 4
```html
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;600&display=swap">
```
## Bài 5
```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <style>
            .btn{
                width: 150px;
                height: 50px;
                background-color: blueviolet;
                color: white;
                font-weight: bold;
                margin: 0 40px;
            }
            .btn__rounded{
                border-radius: 5px;
            }
            .btn__round{
                border-radius: 20px;
            }
        </style>
    </head>
    <body>
        <button class="btn btn__square">Button</button>
        <button class="btn btn__rounded">Button</button>
        <button class="btn btn__round">Button</button>
    </body>
    </html>
```
## Bài 6
```html
    .btn:hover{
            background-color: blue;
            color: red;
    }
```
## Bài 7
```html
    <!DOCTYPE html>
    <html>
    <head>
    <style>
        .color__item{
            width: 100px;
            height: 100px;
            margin: 20px 20px;
            display: inline-block;
        }
        .color__item:first-child{
            background-color: #A24BF0;
        }
        .color__item:nth-child(2){
            background-color: #38DBB2;
        }
        .color__item:nth-child(3){
            background-color: #25C2E3;
        }
        .color__item:nth-child(4){
            background-color: red;
        }
        .color__item:nth-child(4){
            background-color: red;
        }
        .color__item:nth-child(5){
            background-color: #DD44A7;
        }
        .color__item:nth-child(6){
            background-color: #F7AC2A;
        }
        .color__item:nth-last-child(6){
            background-color: #000000;
        }
        .color__item:nth-last-child(5){
            background-color: #555555;
        }
        .color__item:nth-last-child(4){
            background-color: #888888;
        }
        .color__item:nth-last-child(3){
            background-color: #D2D2D2;
        }
        .color__item:nth-last-child(2){
            background-color: #e8e8e8;
        }
        .color__item:last-child{
            background-color: #fcfcfc;
        }
    </style>
    </head>
    <body>
        <div class="color">
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div><br>
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div>
            <div class="color__item"></div>
        </div>
    </body>
    </html>
```
## Bài 8
- Chọn các thẻ div có data-link bắt đầu bằng https:
     ```html
    `     div[data-link^="https"]{
        background-color: lightgreen;
         color: black;
          }
     ```
- Chọn ra các thẻ div có data-link kết thúc bằng .vn:
      ```html
          div[data-link$=".vn"] {
            background-color: blueviolet;
          }
      ```
- Chọn ra các thẻ div có data-name có chứa chữ hello:
      ```html
          div[data-name*="hello"] {
              background-color: yellow;
              color: black;
            }
      ```
- Chọn ra input có type là email:
      ```html
          input[type="email"] {
              border: 1px solid blue;
              color: black;
            }
      ```
- Chọn ra input có name là fullname:
     ```html
          input[name="fullname"] {
              border: 1px solid green;
              background-color: lightgray;
            }
     ```

  
