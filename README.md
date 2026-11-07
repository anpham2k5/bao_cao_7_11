# Báo cáo tiến độ nghiên cứu ngày 07/11/2026
## A. Công việc đã làm
- Đo giá trị khi không tác động với nhiều môi trường và với 2 máy
- Hàn thêm linh kiện vào 1 mạch mới
## B. Khó Khăn
## C. Báo cáo chi tiết 
### 1. Code chi tiết

### 2. Tiến hành đo ở nhiều môi trường và nhiều máy khác nhau
- Mạch hàn lần 1(chip được lấy ra từ mạch cũ) gọi là mạch 1
- Mạch hàn lần 2(chip và linh kiện hoàn toàn mới) gọi là mạch 2
- Tất cả lần đo đều rút sạc máy tính, rút những dây không dùng và đã khắc phục lỗi GND
#### Với môi trường 1
- Hình ảnh lúc đo

| | Mạch 1 | Mạch 2 |
| :---: | :---: | :---: |
| Máy 1 | ![](image/old_may1_mt1.jpg) | ![](image/new_may1_mt1.jpg) |
| Máy 2 | ![](image/old_may2_mt1.jpg) | ![](image/new_may2_mt1.jpg) |
- So sánh mạch 1 ở hai máy khác nhau
<div align="center">

![](image/old_mt1.jpg)

</div>

- So sánh mạch 2 ở hai máy khác nhau
<div align="center">

![](image/new_mt1.jpg)

</div>

#### Với môi trường 2 
- Hình ảnh lúc đo

| | Mạch 1 | Mạch 2 |
| :---: | :---: | :---: |
| Máy 1 | ![](image/old_may1_mt2.jpg) | ![](image/new_may1_mt2.jpg) |
| Máy 2 | ![](image/old_may2_mt2.jpg) | ![](image/new_may2_mt2.jpg) |

- So sánh mạch 1 ở hai máy khác nhau
<div align="center">

![](image/old_mt2.jpg)

</div>

- So sánh mạch 2 ở hai máy khác nhau
<div align="center">

![](image/new_mt2.jpg)

</div>

#### Với môi trường 3
- Hình ảnh lúc đo

| | Mạch 1 | Mạch 2 |
| :---: | :---: | :---: |
| Máy 1 | ![](image/old_may1_mt3.jpg) | ![](image/new_may1_mt3.jpg) |
| Máy 2 | ![](image/old_may2_mt3.jpg) | ![](image/new_may2_mt3.jpg) |

- So sánh mạch 1 ở hai máy khác nhau
<div align="center">

![](image/old_mt3.jpg)

</div>

- So sánh mạch 2 ở hai máy khác nhau
<div align="center">

![](image/new_mt3.jpg)

</div>

#### Nhận xét:
- Ở mạch 1 với nhiều môi trường và nhiều máy khác nhau thì giá trị đo từ mạch luôn cho ra một kết quả thiếu ổn định

### 3. Hàn thêm mạch mới 
#### Tình hình linh kiện
- Tất cả linh kiện là mới hoàn toàn
- Được mua tại linh kiện chất lượng(Ngõ 116 đường Nguyễn Xiển)
#### Hàn mạch
- Được hàn bởi một anh D22DT 
- Trong quá trình hàn, nhóm em quan sát và đưa từng linh kiện để hàn
#### Kiểm tra mạch
- Đã kiểm tra thông các chân 3v3, gnd, chân swdio, chân swclk, chân rx, tx
- Kiểm tra 2 chân 3v3 và gnd không bị chập vào nhau
- Cấp nguồn vào đo các chân 3v3 có lên điện áp
- Vẫn bị lỗi pad GND bottom không thông với đất
#### Khắc phục mạch
- Tiến hành câu dây từ pad gnd top xuống gnd bottom
#### Hình ảnh mạch sau hàn
<div align="center">

![](image/mach3_anh.jpg)

</div>

#### Đồ thị giá trị ADC khi không có tác động
<div align="center">

![](image/mach3.jpg)

</div>

### 4. Đồ thị các mức lực
- Đồ thị các mức lực của mạch mới hàn
<div align="center">

![](image/mucluc.jpg)

</div>

#### Nhận xét: Phát hiện chân PA6 đang không có tín hiệu
#### So sánh đồ thị mức lực mạch 2 và mạch 3 sau khi đã sửa lỗi PA6

| Mạch 2 | Mạch 3 |
| :---: | :---: |
| ![](image/mucluc_mach2.jpg) | ![](image/mucluc_1.jpg) |
