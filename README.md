# Cảm biến siêu âm MKE-S01 Ultrasonic Distance Sensor
## Giới thiệu
Cảm biến siêu âm MKE-S01 Ultrasonic Distance Sensor sử dụng sóng siêu âm để đo khoảng cách đến vật cản từ 3~200cm, cảm biến sử dụng IC xử lý, thạch anh chất lượng tốt cho độ bền, độ ổn định và độ chính xác cao, thích hợp để làm các loại robot tránh vật cản, chống trộm, đo khoảng cách,...

Cảm biến siêu âm MKE-S01 Ultrasonic Distance Sensor thuộc hệ sinh thái phần cứng Robotics MakerEdu nên có thể sử dụng trực tiếp an toàn với các mạch điều khiển trung tâm ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....với chuẩn kết nối Connector XH2.54 thông dụng.
Cảm biến siêu âm đo khoảng cách đến vật cản bằng cách phát sóng siêu âm từ mắt phát T (Transmitter) đến vật cản, sóng siêu âm khi đó sẽ bị phản xạ lại và truyền tới mắt thu R (Receiver), ghi nhận khoảng thời gian t quá trình này xảy ra bằng mạch xử lý kết hợp với vận tốc xác định của sóng siêu âm ta có thể tính được khoảng cách tương đối chính xác đến vật cản theo công thức:
## Nguyên lý hoạt động
Khoảng cách đến vật cản L = (khoảng thời gian t * vận tốc sóng siêu âm) / 2
Minh họa sóng siêu âm từ phát phát T (Transmitter) đến vật cản bị phản xạ lại và truyền tới mắt thu R (Receiver).
Minh họa sóng siêu âm từ phát phát T (Transmitter) đến vật cản bị phản xạ lại và truyền tới mắt thu R (Receiver).

Để tăng độ chính xác và giảm nhiễu, sóng siêu âm sẽ được mắt phát T (Transmitter) phát ra theo tần số chuyên biệt để không bị nhiễu với các loại sóng khác của môi trường, phương pháp đo khoảng cách bằng cảm biến siêu âm tương đối chính xác và ổn định, tuy nhiên vẫn có một nhược điểm của phương pháp này là phụ thuộc vào hình dạng của vật thể phản xạ, vật thể có bề mặt không phẳng sẽ làm ảnh hưởng đến độ phản xạ của sóng siêu âm dẫn đến kết quả đo kém chính xác. 

## Thông số kỹ thuật
- Điện áp hoạt động: 5VDC
- Chuẩn giao tiếp: Digital
- Điện áp giao tiếp: TTL 3.3VDC / 5VDC
    Dòng điện hoạt động: 65mA
    Tần số hoạt động: 40Khz
    Khoảng cách đo được: 3-200cm
    Góc quét: 15°
    Tín hiệu ngõ vào Trigger: 10μs TTL pulse
    Sử dụng trực tiếp an toàn với các board mạch giao tiếp ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....
    Bổ sung thêm các thiết kế ổn định, chống nhiễu.
    Chuẩn kết nối: connector XH2.54 4Pins
    Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các mạch điều khiển trung tâm của MakerEdu và MakerEdu Shield.
## Hình ảnh bộ kit
![ciaobot main](/image/ciaobot1.png)
## Các thành phần có trong bộ kit
![ciaobot inside](/image/ciaobot2.png)
## Hướng dẫn sử dụng
### Giới thiệu
[![Ciaobot introduce](/image/introduce.png)](https://www.youtube.com/watch?v=pvLTHNnOPeM)
### Hướng dẫn lắp ráp
[![Ciaobot assembly](/image/assembly.png)](https://www.youtube.com/watch?v=QY7m3F5WTkc)
### Cài đặt Driver
Mạch điều khiển trung tâm MakerEdu Creator sử dụng Driver giao tiếp máy tính CH340 sẽ tự động nhận Driver trên các hệ điều hành Windows / MacOS / Linux, tuy nhiên nếu không nhận cổng COM của mạch bạn vẫn có thể [tải và cài đặt Driver cho CH340 tại đây.](https://www.mediafire.com/file/fsem9mtf5yl56q6/[MakerLab.vn]+CH340+Driver+WinMacLinux.zip/file)
### Hướng dẫn lập trình với mBlock (kéo thả khối)
>- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
>- Thêm Device "MakerEdu Creator" by MakerEduVN
>- Thêm Extension "Upload Mode Broadcast" by mBlock Official
>- Thêm Extension "MakerEdu Hardware" by MakerEduVN
>- Mở [chương trình mẫu tại đây](/mBlock5), kết nối mạch và nạp chương trình.
## Hỗ trợ và liên hệ:
- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)
## Nhà phân phối
- Các bạn có thể mua sản phẩm tại các [nhà phân phối của MakerLab](https://www.makerlab.vn/nha-phan-phoi/).
