> Đây là một chương trình blog hoạt động trên Cloudflare Workers, sử dụng Cloudflare KV làm cơ sở dữ liệu và không phụ thuộc vào bất kỳ công cụ nào khác. Nó kết hợp tốc độ của blog tĩnh với sự linh hoạt của blog động, dễ dàng thiết lập mà không cần quá nhiều thao tác.
>
> Địa chỉ trình diễn: [https://blog.gezhong.vip](https://blog.gezhong.vip "cf-blog演示站点")

### Nhóm thảo luận TG: [@CloudflareBlog](https://t.me/cloudflareblog "")

# Các tính năng chính
* Sử dụng KV do Workers cung cấp làm cơ sở dữ liệu.
* Sử dụng bộ nhớ đệm của Cloudflare để giảm thiểu việc đọc và ghi KV.
* Tất cả các trang HTML đều được lưu vào bộ nhớ đệm, đạt được tốc độ của blog tĩnh.
* Sử dụng KV làm cơ sở dữ liệu, đạt được sự linh hoạt tương đương với WordPress.
* Hỗ trợ cú pháp Markdown trong phần quản trị, nhanh chóng và thuận tiện.
* Phát hành chỉ bằng một cú nhấp chuột (tái cấu trúc trang + xóa bộ nhớ đệm).

# Khả năng chịu tải
* KV gần như không có điểm nghẽn vì sử dụng bộ nhớ đệm, việc đọc và ghi rất ít.
* Điểm nghẽn duy nhất là số lượng truy cập hàng ngày của Workers là 100.000, có thể chịu được khoảng 20.000 IP/ngày.
* Số lượng bài viết: 1GB dung lượng lưu trữ, có thể chứa vài chục nghìn bài viết mà không gặp vấn đề gì.

# Hướng dẫn triển khai
  Đây không có chế độ xem trước thời gian thực thật là khó chịu, các vấn đề sẽ dần được cập nhật trên blog, xin vui lòng theo dõi tại [https://blog.gezhong.vip](https://blog.gezhong.vip "")

# Nhật ký cập nhật

> [Địa chỉ cập nhật liên tục: https://blog.gezhong.vip/article/009000/update-log.html](https://blog.gezhong.vip/article/009000/update-log.html "Nhật ký cập nhật")

## Cập nhật gần đây (2020-12-31)
* 2020-12-31: Thêm sitemap.xml.
* 2020-12-24: Cập nhật lần này chủ yếu tập trung vào SEO, số lượt đọc, và nhiều chi tiết tối ưu khác.

### Trình diễn giao diện trước: [https://blog.gezhong.vip](https://blog.gezhong.vip "Trình diễn trang web")
![](https://s3.ax1x.com/2020/12/22/rrP81S.png)

### Trình diễn giao diện sau:
![](https://s3.ax1x.com/2020/12/22/rrAWrD.png)

## Đóng góp

Nếu bạn thấy dự án này hữu ích, xin hãy ủng hộ tác giả:

* [Đóng góp](https://afdian.net/@zhaopp "Ủng hộ")
