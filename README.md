## Giới thiệu về HTML

`HTML` là viết tắt của **Hyper Text Markup Language** (ngôn ngữ đánh dấu siêu văn bản).

`HTML` cho *phép người dùng tạo và cấu trúc hóa các thành phần* trên một trang web như đoạn văn, tiêu đề, liên kết, trích dẫn, bảng biểu…

### Chương trình đầu tiên

> Tạo file index.html có nội dung như sau

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
    <h1>About page</h1>
    <!-- Làm menu giữa các trang -->
    <a href="./index.html">Trang chủ</a>
    <a href="./shop.html">Shop</a>
    <a href="./about.html">Liên hệ</a>
</body>

</html>
```

Nội dung file `style.css` như sau

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
}
```

**Kết quả:**

![Ảnh con sóc](./day_01/image/image-01.jpeg)

### Tài liệu

- https://topdev.vn/blog/markdown-la-gi-cach-su-dung-markdown/
- https://www.w3schools.com/html/default.asp
- https://www.w3schools.com/html/html_intro.asp

### Code tham khảo

- [Buổi học số 1](./day_01/index.html)
- [Buổi học số 2](./day_02/)