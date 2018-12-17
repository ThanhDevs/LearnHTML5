### Chào mừng bạn đến với { HCJ TEAM }

HTML CƠ BẢN
===========

## Nội dung chính 

* DOCTYPE
* html
* head
* body

### DOCTYPE

!Doctype không phải là một tag HTML, !Doctype chỉ cho trình duyệt web biết được phiên bản ngôn ngữ đánh dấu (markup language) nào được sử dụng trong trang web. “Document Type Definition ” (DTD), DTD quy định cụ thể các quy tắc cho các ngôn ngữ đánh dấu, để làm cho các trình duyệt thông dịch thêm chính xác.

**Ví dụ**

html4:
~~~html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
~~~

html5:
~~~html
<!DOCTYPE html>
~~~

### html

HTML là phần tử gốc của một file html 

**Ví dụ**

~~~html
<html thuoctinh="giatri">
〜〜〜
</html>
~~~

**Thuộc tính đặc biệt**

* manifest
 + Thêm vào bộ nhớ đệm, giúp người dùng có thể duyệt web ngay cả khi offline, và giúp người dùng truy cập website nhanh hơn

~~~html
<html manifest="example.appcache"></html>
~~~
* xmlns
 + Thiết lập tên cho một khu vực nội dung html nào đó, tránh bị trùng 

~~~html
<html xmlns="http://www.w3.org/1999/xhtml"></html>
~~~
* lang
 + Thiết lập mô tả ngôn ngữ sử dụng cho website, Ví dụ: Vi (Tiếng việt)
~~~html
<html lang="Vi"></html>
~~~

### head

Khu vực chứa thông tin miêu tả về website, tiêu đề website, mô tả tóm gọi nội dung, từ khóa tìm kiếm, và các nội dung meta khác ...

**Ví dụ**

~~~html
<head>
〜〜〜
</head>
~~~

### body

Chứa nội dung hiển thị khi client yêu cầu ra màn hình, trong file html chỉ có thể có một body 

**Ví dụ**

~~~html
<body>
〜〜〜
</body>
~~~

## Ví dụ tổng hợp

~~~html
<!DOCTYPE html>
<html lang="Vi">
    <head>
        <meta charset="utf-8">
        <title>Tiêu đề website (Chỉ hiện thị trên trình duyệt)</title>
        <meta name="description" content="Miêu tả đơn giản về website">
        <meta name="keywords" content="Từ khóa tìm kiếm liên quan (Được phân cách bởi dấu phẩy)">
        <link rel="/css/style.css">
        <script src="/js/myscript.js"></script>
    </head>
    <body>
        <header>Hiển thị nội dung Đầu trang </header>
        <main>Hiển thị nội dung chính </main>
        <nav>Hiển thị nội dung Thanh điều hướng (Menu)...</nav>
        <footer>Hiển thị nội dung chân trang (Thông tin, copyright)...</footer>
    </body>
</html>
~~~

## Kênh Youtube & Codes

* Mỗi một video chỉ bao gồm một nội dung chính, và được khống chế trong 5 - 15p 
 - Youtube 
	@https://www.youtube.com/channel/UCj6UHJS3mZzCrrbq1L6AnfQ
* Code sẽ được chia sẻ
 - Github
	@https://github.com/ThanhDevs/LearnHTML5
 - Website cá nhân
	@http://lavanthanh.com
