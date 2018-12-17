### Chào mừng bạn đến với { HCJ TEAM }

Thẻ meta trong HTML5 
====================

## Nội dung chính（thẻ meta）

* name
* http-equiv
* content
* charset

### meta.name

Chỉ định tên meta cho thông tin, ví dụ: keywords,author... sau đó kết hợp với thuộc tính content để miêu tả cho nội dung website

~~~html
<meta name="author" content="LA VĂN THANH">
<meta name="description" content="Webstie hướng dẫn học HTML5 cơ bản, Hướng dẫn sử dụng thẻ meta trong HTML5">
<meta name="keywords" content="html,html5,meta,seo">
~~~


### meta.http-equiv

Thiết lập thông tin cho website, thông qua giao thức http để chuyển giao thông tin, và cũng để thiết lập hành vi cho website

~~~html
<!-- Sau 30s website tự động làm mới trang (Load lại trang) -->
<meta http-equiv="refresh" content="300">
<!-- Sau 30s website tự động chuyển hướng qua link other.html -->
<meta http-equiv="refresh" content="30;URL=other.html">
~~~

### meta.content

name, http-equiv kết hợp với content để truyền tải thông tin miêu tả cho nội dung web

**Một số thuộc tính**

* content-type
* default-style
* refresh
* set-cookie

|  Tên thuộc tính | Miêu tả thuộc tính                                                    |
|:----------------|:----------------------------------------------------------------------|
| content-type    | Chỉ định mã hóa nội dung văn bản hiển thị                             |
| default-style   | Chỉ định file style mặc định được sử dụng                              |
| refresh         | Dùng để tự động làm mới hoặc chuyển trang                             |
| set-cookie      | Dùng để thiết lập cookie cho website, nhưng không khuyến khích sử dụng |

### meta.charset

Chỉ định kiểu mã hóa văn bản, khuyên dùng kiểu mã hóa utf8 

~~~html
<meta charset="utf-8">
~~~

## Ví dụ tổng hợp

Chuẩn bị một số thông tin cho con robots tìm kiếm 

~~~html
<!-- Đoạn mã này có thể ngăn chặn bộ máy tìm kiếm lưu vào bộ nhớ Cache, và theo dõi trang web của chúng ta -->
<meta name="robots" content="noindex,nofollow">
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
