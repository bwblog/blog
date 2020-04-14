---
layout: post
title: Giới thiệu AutoTouch
date: 2020-04-12 23:38:53 +0700
categories: null
---

# AutoTouch là ứng dụng giúp ace giả lập thao tác trên iPhone/iPad nhằm mục đích tự động lặp đi lặp lại một quá trình nào đó. Ví dụ auto cầy game online, lead offer, nuôi mail, autolike facebook, cầy view YouTube, vân vân mây mây...

<br/>

{:#table-of-contents}
- [I> Làm thế nào để record?](#how-to-record)
- [II> Làm thế nào để chạy script?](#how-to-play-script)
- [III> Làm thế nào để chụp ảnh màn hình?](#how-to-take-screenshot)
- [IV> Làm thế nào để viết script?](#how-to-write-a-script)
- [V> Một vài Function trong script](#how-to-use-the-function-helper-while-script-coding)
- [VI> Làm thế nào để quản lý script trên PC?](#how-to-write-and-manage-scripts-on-the-computer)

<br/><br/><br/><br/>

## I> Làm thế nào để record?
{:#how-to-record}
> - Để record ace cần chạy app trước sau đó giữ phím giảm âm lượng một lúc sẽ nhìn thấy cửa sổ AutoTouch như hình.
  
> ![](https://i.imgur.com/D0HSfOP.jpg){:width="80%"}
> - Chọn biểu tượng REC màu đỏ để tiến hành record.
> - AutoTouch sẽ ghi lại mọi hành vi ace thao tác trên màn hình iphone cho đến khi dừng record.
> - Giữ phím giảm âm lượng một lúc một lần nữa để dừng việc record.
> - File script sẽ được lưu trong thư mục Records có dạng "năm-tháng-ngày giờ:phút:giây.lua".

> ![](https://i.imgur.com/mzi91vS.jpg){:width="80%"}

[Top](autotouch-introduce.html#table-of-contents)
<br /><br /><br /><br />

## II> Làm thế nào để chạy script?
{:#how-to-play-script}
> - Giũ phím giảm âm lượng một lúc sẽ nhìn thấy cửa sổ AutoTouch.
> - Chọn script ace muốn chạy.
> - Chọn biểu tượng options (bên cạnh nút REC) để thiết lập cấu hình chạy script. Bấm thêm lần nữa để tắt option nếu ace không muốn thiết lập cấu hình.
> - Chú ý AutoTouch sẽ thông báo options được bật hay không như hình sau

> ![alt Play Script](https://i.imgur.com/hmdpjVz.jpg){:width="30%"}![alt Play Script](https://i.imgur.com/NkOvtWY.jpg){:width="30%"}
> - Biểu tượng chữ H là chế độ chờ, khi nào ace bấm nút giảm âm lượng scipt sẽ chạy.
> - Giữ phím tăng âm lượng để dừng script.

[Top](autotouch-introduce.html#table-of-contents)
<br /><br /><br /><br />

## III> Làm thế nào để chụp màn hình?
{:#how-to-take-screenshot}
> - Chọn biểu tượng hình máy ảnh bên cạnh chữ H của cửa sổ AutoTouch để chụp ảnh.
> - Ảnh sẽ lưu trong ứng dụng Photos của iPhone.

[Top](autotouch-introduce.html#table-of-contents)
<br /><br /><br /><br />

## IV> Làm thế nào để viết script?
{:#how-to-write-a-script}
> - Mở app AutoTouch chọn Local sau đó dọn dấu + sau đó chọn "New Script" để viết script.

> ![alt Write Script](https://i.imgur.com/FzPHQ6S.jpg){:width="30%"}![alt Write Script](https://i.imgur.com/M6BfAjk.jpg){:width="30%"}
> - Viết xong chọn "Save" để lưu script.

[Top](autotouch-introduce.html#table-of-contents)
<br /><br /><br /><br />

## V> Một vài Function trong script
{:#how-to-use-the-function-helper-while-script-coding}
> - ACE chọn nút "Extensions", "Indent" and "Statements", sau đó chọn lệnh hoặc khối lệnh để viết script một cách đơn giản và tránh bị sai cú pháp.

> ![](https://i.imgur.com/fD9dX7q.jpg){:width="30%"}
> - Nút "HELPER" trong "Extensions" sẽ giúp ace căn toạ độ, kích thước, màu, phím cần bấm nhanh chóng.

> ![](https://i.imgur.com/ng2QWrz.png){:width="30%"}

[Top](autotouch-introduce.html#table-of-contents)
<br /><br /><br /><br />

## VI> Làm thế nào để quản lý script trên PC?
{:#how-to-write-and-manage-scripts-on-the-computer}
> - Cách 1: Bật Web Server trong Settings để quản lý script bằng trình duyệt web trên PC bằng cách truy cập http://ip-của-iphone:8080. VD trong ảnh http://192.168.1.113:8080

> ![](https://i.imgur.com/pCHlZQV.jpg){:width="30%"}
> - Cách 2: Bật WebDAV Server và quản lí bằng ứng dụng WebDav ace cài đặt trên PC (Cách này hơi khó với ace mới dùng em khuyên nên dùng Cách 1 dễ dàng hơn).

[Top](autotouch-introduce.html#table-of-contents)
<br /><br /><br /><br />

### Phần tiếp theo mình sẽ giúp ace làm quen với một số lệnh thường xuyên sử dụng trong script AutoTouch. Mời ace đón đọc!