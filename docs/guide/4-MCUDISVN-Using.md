---
layout: guide
title: "🔎 4. Quả Cầu Thấu Thị"
---

# 🔎 4. VẬN HÀNH "CỖ MÁY" MCUDISVN ADDON

Chào mừng trở lại với ***<mark>Dòng Thời Gian Thiêng Liêng MCUDISVN</mark>***. Để bạn không bị "lạc lối" trong thực tại này, đây là bản hướng dẫn chi tiết về cách thức vận hành, các tính năng thông minh và cách xử lý sự cố của **<mark>ADDON MCUDISVN</mark>**

## I. 🗺️ TÌM PHIM

>* Xem phim với Stremio vô cùng đơn giản, bạn chỉ cần **<mark2>bấm vào poster</mark2>** của phim bạn muốn xem, hệ thống sẽ tự động tìm file trong Drive và gửi về cho bạn.
>* Trên màn hình chính của Stremio luôn có sẵn poster của phim trong các danh mục mặc định hoặc cài đặt thêm cho bạn lựa chọn ngay.

### Cách A: Tìm kiếm qua thanh Search
1. Gõ tên phim bạn muốn xem vào thanh tìm kiếm của Stremio (VD: *Avengers: Endgame*).
2. Chọn phim từ kết quả của các danh mục. *Khi bạn cài đặt nhiều danh mục, tất cả đều sẽ hiện ra nếu tìm thấy phim, bạn chọn cái nào cũng được.*
4. Đợi vài giây để "cỗ máy" quét sạch Drive và hiện danh sách luồng phát của **<mark2>MCUDISVN</mark2>**. *Khi bạn cài đặt nhiều addon tạo luồng phát, hãy chọn cái có tên MCUDISVN.*

### Cách B: Duyệt qua "Danh mục phim" (Catalogs)
Nếu bạn chưa biết xem gì, hãy vào mục **<mark2>Discover</mark2>** (Khám phá) trong Stremio:
*   **<mark2>Chọn loại Movie</mark2>**
*   **<mark2>Chọn danh mục Google Drive:</mark2>** Hiện các file vừa mới thêm vào Drive.
*   **<mark2>Cách trên cũng áp dụng cho các danh mục khác, mời bạn tự khám phá</mark2>**

### Cách C: Tìm file cụ thể trong Drive (không qua poster)
Nếu bạn bấm vào một phim nào đó nhưng hiện dòng chữ **<mark2>No streams found</mark2>** thì có 2 nguyên nhân: **<mark2>Tên file không khớp với hệ thống lọc</mark2>** hoặc/và **<mark2>phim không có trong Drive.</mark2>** *Đây là lỗi thường gặp với Anime*, khi đó hãy thử các cách sau:
*   **<mark2>Gõ tên phim,</mark2>** sau đó lướt xuống tìm danh mục **<mark2>Google Drive Search</mark2>**
*   **<mark2>Bấm See All</mark2>** và tìm file bạn cần. *Bấm vào từng file để hiện đầy đủ tên.*
*   **<mark2>Mẹo nhỏ:</mark2>** Tên càng chi tiết thì tìm càng nhanh.

## II. 🎞️ Đọc thông số Luồng phát
Khi danh sách luồng phát hiện ra, mỗi "ô phim" sẽ chứa các thông tin quan trọng. Hãy đọc kỹ trước khi nhấn Play:

### 1. Thông tin chung (bên phải)
>*   **<mark>MCUDISVN:</mark>** Tên của addon tạo luồng phát.
>*   **<mark>🚀 Direct:</mark>** Lấy file trực tiếp từ Google. Dành cho Windows, macOS, TV có hỗ trợ.
>*   **<mark>📱 Proxy:</mark>** Dành cho iPhone, iPad, TV kén định dạng. Video đi qua "cổng phụ" để đảm bảo phát được.
>*   **<mark>2160p, 1080p, 720p, 480p, Unknown:</mark>** Độ phân giải của video (2160p là 4KKKK). Unknown là khi tên file không ghi độ phân giải.

### 2. Mô tả kỹ thuật (bên trái)
>*   **<mark>🎥 Chất Lượng:</mark>** BluRay (lấy từ đĩa phim), WEB-DL (lấy từ nền tảng trực tuyến). Thường thì BluRay>WEB-DL
>*   **<mark>📺 Hình Ảnh:</mark>** DV, HDR (Chỉ dành cho thiết bị "xịn"); AI (thường gặp với Anime, nâng độ phân giải bằng AI)
>*   **<mark>🎧 Âm Thanh:</mark>** Định dạng âm thanh và cấu hình kênh. Nếu thấy E-AC3, DTS, TrueHD hoặc 5.1, 7.1, thì một số thiết bị sẽ không có tiếng.
>*   **<mark>📦 Dung Lượng:</mark>** Càng nặng load càng lâu, 4K nên có mạng mạnh, 1080p phù hợp tốc độ mạng bình thường.
>*   **<mark>📄 Tên File:</mark>** Rê chuột vào sẽ hiện tên đầy đủ.

## III. 🍿 Chọn phim
* Hệ thống tự động xếp thứ tự chất lượng từ cao xuống thấp.
* Hệ thống tự động hiện link Direct và Proxy tùy thiết bị, vẫn là 1 file đó, chỉ khác cách phân phối.
* Nếu thiết bị của bạn có phần cứng tốt, mạng nhanh, màn to, loa xịn thì cứ chọn bất cứ gì bạn thích.
* Nếu xem trên màn hình nhỏ hoặc mạng yếu/chậm/cà giựt thì 1080p là đủ.
* **<mark2>Lưu ý 1:</mark2>** Độ phân giải không tỷ lệ thuận với chất lượng hình ảnh. Bitrate mới là yếu tố then chốt quyết định chất lượng. Hiểu nôm na thì bitrate cao = video đẹp hơn = file nặng hơn. Vậy nên nếu gặp các file có cùng độ phân giải thì file có dung lượng cao hơn *thường* sẽ đẹp hơn.
* **<mark2>Lưu ý 2:</mark2>** Còn nhiều thứ để nói về cái này nữa nhưng để ở đây thì dài dòng, mời bạn ghé qua [🧿 Điện Thờ Hiền Triết](https://bimbipsubteam.github.io/bimbip-stremio/guide/7-Additional-Stuff/)

## IV. 💬 Chọn Phụ Đề
Sau khi phim đã chạy, nếu không có phụ đề tiếng Việt tự động:
1. Nhấn vào biểu tượng **<mark2>Phụ đề (CC)</mark2>** trên trình phát Stremio.
2. Tìm các nhãn có chữ:
    *   **`[Vie]`** hoặc **`[Tiếng Việt]`**: Phụ đề tiếng Việt có tag "vie" trong tên file.
    *   **`[V1E]`** hoặc **`[MCUDISVN]`**: Phụ đề tiếng Việt chưa có tag "vie" trong tên file.
3. **<mark2>Mẹo nhỏ:</mark2>** Bạn có thể cài đặt thêm addon phụ đề được giới thiệu trong [💎 5. Thần Chú Sung Túc](https://bimbipsubteam.github.io/bimbip-stremio/guide/5-Addon-Expanding/)

**<mark>MCUDISVN FOREVER! 🛡️🍿</mark>**

