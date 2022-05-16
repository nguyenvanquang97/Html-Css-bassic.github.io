## Bài học đầu tiên về html
Mục lục nội dung
`Markdown` là gì?
**Trả** lời câu hỏi ‘tại sao nên sử dụng Markdown?’

Cách sử dụng Markdown
Dùng cho Heading
Hiển thị: Heading 1

Hiển thị: Heading 2

Hiển thị: Heading 3
Dùng cho Bold và Italic
Dùng cho Strikethrough
Dùng cho chèn Link

<!-- tạo file index.html có nội dung như sau -->
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <!-- Thẻ tiêu đề -->
    <h1 style="color: red">Đây là thẻ h1</h1>
    <div style="color: green;background-color: antiquewhite;">
        <h2>Đây là thẻ h2</h2>
    <h3>Đây là thẻ h3</h3>
    <h4>Đây là thẻ h4</h4>
    <h5>Đây là thẻ h5</h5>
    <h6 style="text-align: center;" >Đây là thẻ h6</h6>
    </div>
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <!-- Đây là thẻ link -->
    <a href="https://www.google.com/" target="_blank" style="text-decoration:--thẻ ;">Đi đến trang tìm kiếm</a><br>
    <!-- Làm  menu giữa các trang -->
     <!-- Tìm link cùng cấp:./ -->
    <a href="./index.html">Trang chủ</a>
    <a href="./Shop.html">Shop</a>
    <a href="./about.html">Liên hệ</a><br>
<!-- thẻ ảnh -->
<img src="https://images.unsplash.com/photo-1644982648791-a010e61aa845?ixlib=rb-1.2.1&ixid=MnwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHwxfHx8ZW58MHx8fHw%3D&auto=format&fit=crop&w=500&q=60" alt="ảnh điện thoại" width="500">

<img src="" alt="">
<!--thẻ danh sách không thứ tự-->
<h3>Thông tin nhân viên</h3>
<ul>
    <li>Nguyễn Văn Quang</li>
    <li>11/11/1997</li>
</ul>
<!-- thẻ danh sách không thứ tự -->
<h3>Danh sách người đẹp zai nhất công ty</h3>
<ol>
    <li>Quang</li>
    <li>Aquang</li>
</ol>
<!-- cấu trúc gõ nhanh :ul>li*5 -->
<!-- Thẻ button -->
<button>Đăng nhập</button>
<button>Đăng xuất</button>
</body>

</html>
```
<!-- Nội dung file style.css như sau -->
```css
.text {
    background-color: bisque;
}
.text1{
    font-size: 30px;
}
/* chọn thẻ vừa có class là text vừa có class là .text1 */
.text.text1{
    font-size: 20px;
}
.text1{
    font-size: 26px;
}
```
### Tài liệu
-https://www.w3schools.com/js/default.asp

### code tham khảo
[ Buoi hoc so 1](https://www.w3schools.com/js/default.asp)

![ảnh con sóc](link)