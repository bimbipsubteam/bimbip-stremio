---
layout: guide
title: "🔰 Bí Sử Khởi Nguyên"
---

# 🔰 KHÁI NIỆM CƠ BẢN CHO NGƯỜI MỚI

Cẩm nang này giả định bạn đang hướng tới việc thiết lập Stremio ***<mark>gọn gàng, tiện lợi và nhất quán</mark>*** trên tất cả các thiết bị. Các khái niệm dưới đây giải thích **<mark2>chức năng</mark2>** của từng thành phần, lý do nó **<mark2>quan trọng</mark2>** và tại sao **<mark2>sự kết hợp</mark2>** như hướng dẫn sẽ hoạt động tốt hơn so với thêm "add-on đơn lẻ".

## **Stremio là gì?**
> * Stremio là ***<mark>một trung tâm giải trí</mark>*** hợp nhất việc khám phá và phát nội dung dưới một giao diện duy nhất. Bạn chọn phim theo poster và Stremio hiển thị thông tin và nguồn video thông qua add-on.
> * Điểm quan trọng là Stremio **<mark2>không lưu trữ video.</mark2>** Hãy hình dung nó như **<mark2>một cái hộp rỗng,</mark2>** danh sách, thông tin phim và video sẽ là **<mark2>những món đồ</mark2>** mà bạn cho vào từ **<mark2>các add-on</mark2>** mà bạn cài đặt.
> * Stremio hoạt động dựa trên **<mark2>tài khoản.</mark2>** Khi bạn hoàn thành thiết lập rồi đăng nhập trên một thiết bị khác, **<mark2>toàn bộ add-on và trạng thái thư viện</mark2>** cũng sẽ có sẵn ở đó. Vậy nên bình thường chỉ cần thiết lập **<mark2>một lần</mark2>** và sử dụng lại ở **<mark2>mọi nơi.</mark2>**

## **Stremio hỗ trợ những nền tảng/thiết bị nào?**
> * **<mark>Máy Tính & Laptop:</mark>** Windows, macOS, Linux
> * **<mark>Điện Thoại Thông Minh & Máy Tính Bảng:</mark>** Android, iOS, iPadOS
> * **<mark>TV:</mark>** Android TV, Google TV, Android TV Box, Android Box, Fire TV Stick, Samsung TV, LG TV, Sony TV, Philips TV, Hisense TV
> * **<mark>VR:</mark>** Meta Quest, Pico
> * **<mark>Thiết bị khác:</mark>** Steam Deck, Raspberry Pi, Máy chiếu & các thiết bị chạy hệ điều hành Android, Trình duyệt web

## **Stremio hoạt động như thế nào?**
> Stremio gồm 4 thành phần cơ bản nhất:
  > * **<mark>Giao diện:</mark>** Tìm kiếm, thư viện, lịch chiếu, thông tin, tiếp tục xem,...
  > * **<mark>Add-on:</mark>** Công cụ liên kết nguồn phát và mở rộng thêm các chức năng khác
  > * **<mark>Luồng phát:</mark>** Các *"link phim"* được cung cấp cho Stremio
  > * **<mark>Trình phát:</mark>** Công cụ giải mã video thành hình ảnh, âm thanh, phụ đề

* Giao diện tương tác giữa người dùng và Stremio luôn giống nhau và hiện tại không thể chỉnh sửa. 
* Thư viện phim và luồng phát được tạo ra từ add-on (ví dụ: Cinemeta là add-on mặc định giúp cung cấp thông tin phim từ IMDb do Stremio phát triển và tích hợp ngay trong phần mềm). 
* Add-on chính là thứ khiến cho hai người cùng sử dụng Stremio nhưng có thể có những trải nghiệm hoàn toàn khác nhau.

## **"Đồng bộ mọi nơi" trong Stremio nghĩa là gì?**
> **<mark2>Tài khoản Stremio là "trạm điều khiển" trung tâm.</mark2>** Mọi thiết lập cốt lõi và trạng thái sử dụng của bạn đều được lưu vào đó. Khi đăng nhập trên thiết bị mới, bạn sẽ nhận lại toàn bộ:
   > * **<mark2>Các add-on đã cài đặt</mark2>**
   > * **<mark2>Thư viện và danh sách phim muốn xem</mark2>**
   > * **<mark2>Lịch sử xem tiếp</mark2>**
* Tuy nhiên, hãy lưu ý: "Đồng bộ" không có nghĩa là mọi thiết bị sẽ phát phim giống hệt nhau. Khả năng phần cứng và nền tảng của từng thiết bị vẫn đóng vai trò quan trọng trong việc phát video.

## **Hệ sinh thái add-on là gì và mang lại điều gì?**
> Add-on chính là **<mark2>"phụ kiện"</mark2>** mở rộng sức mạnh cho Stremio. Mỗi add-on có thể đảm nhận **<mark2>một hoặc nhiều vai trò sau:</mark2>**
   > * **<mark2>Danh mục:</mark2>** Các hàng phim trên màn hình chính và danh sách được tuyển chọn.
   > * **<mark2>Dữ liệu:</mark2>** Chi tiết phim, ảnh bìa, xếp hạng, danh sách tập phim.
   > * **<mark2>Nguồn phát:</mark2>** Các đường link để bạn có thể nhấn "Play" và xem phim.

## **"Addon instance" nghĩa là gì?**
* Hãy hình dung đơn giản add-on là một bịch kẹo, còn instance là nhà máy sản xuất ra cục kẹo đó và giao cho Stremio phát từng viên kẹo cho bạn.
* Khi cài đặt một add-on, thực chất là bạn đang đăng ký **<mark2>địa chỉ của nó</mark2>** vào tài khoản Stremio. Khi bạn lướt xem phim, Stremio sẽ "hỏi" máy chủ đó để lấy thông tin.
* Có thể có nhiều instance của cùng một add-on do các bên khác nhau vận hành. Chúng giống nhau về tính năng nhưng khác nhau về "sức khỏe":
   * **<mark2>Độ ổn định và tốc độ phản hồi khác nhau.</mark2>**
   * **<mark2>Giới hạn lượt truy cập khác nhau.</mark2>**
   * **<mark2>Chính sách bảo trì riêng biệt.</mark2>**
* **<mark>Lưu ý quan trọng:</mark>** Tinh chỉnh không dùng chung giữa các instance. Nếu bạn muốn đổi máy chủ, bạn thường phải thiết lập lại từ đầu nếu add-on đó yêu cầu tinh chỉnh trước khi sử dụng.

## **Nên chọn máy chủ (instance) nào?**
* Hãy ưu tiên **<mark2>độ ổn định</mark2>** trước, sau đó mới đến tốc độ. Nếu máy chủ chập chờn, trải nghiệm của bạn sẽ cực kỳ ức chế.
* Sử dụng **[link này](https://status.stremio-status.com/)** hoặc **[link này](https://status.dinsden.top/status/stremio-addons)** để kiểm tra nhanh xem máy chủ nào đang "sống" hay "ngỏm" để chọn giải pháp thay thế.
* Trong hướng dẫn của anh bạn mình có cung cấp các địa chỉ máy chủ rất tốt, nhưng hãy coi đó là "gợi ý hàng đầu" chứ không phải là lựa chọn duy nhất mãi mãi.

## **Tạm kết: Từ lý thuyết đến "Rạp phim tại gia" hoàn hảo**

Đến đây, chắc hẳn bạn đã nắm trong tay "bản đồ kiến thức" về hệ sinh thái Stremio. Có thể lúc mới đọc, bạn sẽ thấy hơi choáng ngợp vì "xem phim thôi mà, sao phải rắc rối thế", nhưng đừng quá lo lắng! Hãy coi đây là một khoản "đầu tư" nhỏ về thời gian để đổi lấy một trải nghiệm giải trí không giới hạn về sau.

> **<mark>Tại sao việc thiết lập kỹ lưỡng lại xứng đáng?</mark>**
> * **<mark2>Chỉ cần làm một lần:</mark2>** Khi đã cấu hình xong theo đúng ý muốn, mọi chức năng chính sẽ tự động vận hành trơn tru trên tất cả thiết bị của bạn (ngoại trừ phần trình phát nhé).
> * **<mark2>Sự tự do tuyệt đối:</mark2>** Bạn không còn bị phụ thuộc vào việc phim này có trên app đó hay phim nọ có trên web kia hay không. Cả thế giới điện ảnh giờ đây nằm gọn trong một ứng dụng duy nhất.
> * **<mark2>Chất lượng đỉnh cao:</mark2>** Thay vì xem những bản nén mờ nhạt, bạn sẽ được thưởng thức những khung hình sắc nét với âm thanh vòm sống động nhất (nếu thiết bị của bạn hỗ trợ đầy đủ nhé).

Lý thuyết đã xong, giờ là lúc biến những dòng chữ này thành thực tế. Hãy đọc tiếp để bắt đầu xây dựng "đế chế" giải trí của riêng bạn. Một chân trời điện ảnh mượt mà, chuyên nghiệp và "đáng mồ hôi công sức" đang chờ đón bạn phía trước!

**<mark>Chúc bạn có được những giờ phút xem phim thật bùng nổ 🤩</mark>**
