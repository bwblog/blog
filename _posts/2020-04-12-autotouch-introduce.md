---
layout: post
title: Giới thiệu AutoTouch
categories: null
---

# AutoTouch là ứng dụng giúp ace giả lập thao tác trên iPhone/iPad nhằm mục đích tự động lặp đi lặp lại một quá trình nào đó. Ví dụ auto cầy game online, lead offer, nuôi mail, autolike facebook, cầy view YouTube, vân vân mây mây...

<br/>

<ul id="table-of-contents">
  <li><a href="#how-to-record">I> Làm thế nào để record?</a>></li>
  <li><a href="#how-to-play-script">II> Làm thế nào để chạy script?</a></li>
  <li><a href="#how-to-take-screenshot">III> Làm thế nào để chụp ảnh màn hình?</a></li>
  <li><a href="#how-to-write-a-script">IV> Làm thế nào để viết script?</a></li>
  <li><a href="#how-to-use-the-function-helper-while-script-coding">V> Một vài Function trong script</a></li>
  <li><a href="#how-to-write-and-manage-scripts-on-the-computer">VI> Làm thế nào để quản lý script trên PC?</a></li>      
</ul>



<h2 id="how-to-record">I> Làm thế nào để record?</h2>
<blockquote>
  <ul>
    <li>Để record ace cần chạy app trước sau đó giữ phím giảm âm lượng một lúc sẽ nhìn thấy cửa sổ AutoTouch như hình.</li>
    <img src="https://i.imgur.com/D0HSfOP.jpg" class="img-fluid" style="width:80%">
    <li>Chọn biểu tượng REC màu đỏ để tiến hành record.</li>
    <li>AutoTouch sẽ ghi lại mọi hành vi ace thao tác trên màn hình iphone cho đến khi dừng record.</li>
    <li>Giữ phím giảm âm lượng một lúc một lần nữa để dừng việc record.</li>
    <li>File script sẽ được lưu trong thư mục Records có dạng "năm-tháng-ngày giờ:phút:giây.lua".</li>
    <img src="https://i.imgur.com/mzi91vS.jpg" class="img-fluid" style="width:80%">
  </ul>
</blockquote>
<p><a href="#table-of-contents">Top</a></p>
<br />

<h2 id="how-to-play-script">II> Làm thế nào để chạy script?</h2>
<blockquote>
  <ul>
    <li>Giũ phím giảm âm lượng một lúc sẽ nhìn thấy cửa sổ AutoTouch.</li>
    <li>Chọn script ace muốn chạy.</li>
    <li>Chọn biểu tượng options (bên cạnh nút REC) để thiết lập cấu hình chạy script. Bấm thêm lần nữa để tắt option nếu ace không muốn thiết lập cấu hình.</li>
    <li>Chú ý AutoTouch sẽ thông báo options được bật hay không như hình sau</li>
    <img src="https://i.imgur.com/hmdpjVz.jpg" class="img-fluid" style="width:30%" alt="Play Script">
    <img src="https://i.imgur.com/NkOvtWY.jpg" class="img-fluid" style="width:30%" alt="Play Script">
    <li>Biểu tượng chữ H là chế độ chờ, khi nào ace bấm nút giảm âm lượng scipt sẽ chạy.</li>
    <li>Giữ phím tăng âm lượng để dừng script.</li>
  </ul>
</blockquote>
<p><a href="#table-of-contents">Top</a></p>
<br />

<h2 id="how-to-take-screenshot">III> Làm thế nào để chụp màn hình?</h2>
<blockquote>
  <ul>
    <li>Chọn biểu tượng hình máy ảnh bên cạnh chữ H của cửa sổ AutoTouch để chụp ảnh.</li>
    <li>Ảnh sẽ lưu trong ứng dụng Photos của iPhone.</li>
  </ul>
</blockquote>
<p><a href="#table-of-contents">Top</a></p>
<br />

<h2 id="how-to-write-a-script">IV> Làm thế nào để viết script?</h2>
<blockquote>
  <ul>
    <li>Mở app AutoTouch chọn Local sau đó dọn dấu + sau đó chọn "New Script" để viết script.</li>
    <img src="https://i.imgur.com/FzPHQ6S.jpg" class="img-fluid" style="width:30%" alt="Write Script">
    <img src="https://i.imgur.com/M6BfAjk.jpg" class="img-fluid" style="width:30%" alt="Write Script">
    
    <li>Viết xong chọn "Save" để lưu script.</li>
  </ul>
</blockquote>
<p><a href="#table-of-contents">Top</a></p>
<br />

<h2 id="how-to-use-the-function-helper-while-script-coding">V> Một vài Function trong script</h2>
<blockquote>
  <ul>
    <li>ACE chọn nút "Extensions", "Indent" and "Statements", sau đó chọn lệnh hoặc khối lệnh để viết script một cách đơn giản và tránh bị sai cú pháp.</li>
    <img src="https://i.imgur.com/fD9dX7q.jpg" class="img-fluid" style="width:30%">
    <li>
      <p>Nút "HELPER" trong "Extensions" sẽ giúp ace căn toạ độ, kích thước, màu, phím cần bấm nhanh chóng.</p>
      <p><img src="https://i.imgur.com/ng2QWrz.png" alt="Function Helper" /></p>
    </li>
  </ul>
</blockquote>
<p><a href="#table-of-contents">Top</a></p>
<br />

<h2 id="how-to-write-and-manage-scripts-on-the-computer">VI> Làm thế nào để quản lý script trên PC?</h2>
<blockquote>
  <ul>
    <li>Cách 1: Bật Web Server trong Settings để quản lý script bằng trình duyệt web trên PC bằng cách truy cập http://ip-của-iphone:8080. VD trong ảnh http://192.168.1.113:8080</li>
    <img src="https://i.imgur.com/pCHlZQV.jpg" class="img-fluid" style="width:30%">
    <li>Cách 2: Bật WebDAV Server và quản lí bằng ứng dụng WebDav ace cài đặt trên PC (Cách này hơi khó với ace mới dùng em khuyên nên dùng Cách 1 dễ dàng hơn).</li>
  </ul>
</blockquote>
<p><a href="#table-of-contents">Top</a></p>
<br />
<br />
### Phần tiếp theo mình sẽ giúp ace làm quen với một số lệnh thường xuyên sử dụng trong script AutoTouch. Mời ace đón đọc!