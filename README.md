# Platformer-Game
## Sơ lược về đồ án:  
Đồ án cuối kì môn Lập trình hướng đối tượng (OOP) với đề tài "ỨNG DỤNG PYGAME LÀM GAME PLATFORMER" nhằm mục tiêu áp dụng những kiến thức đã học trong môn IT002.O21 tại trường Đại học Công nghệ Thông tin - Đại học Quốc gia Hồ Chí Minh vào việc xây dựng một trò chơi điện tử hoàn chỉnh. Trò chơi Mario được phát triển bằng thư viện Pygame, một thư viện phổ biến dành cho lập trình game trong Python. Đồ án này không chỉ nhằm giúp sinh viên củng cố và nâng cao kỹ năng lập trình hướng đối tượng mà còn phát triển khả năng tư duy logic và sáng tạo :smiley:.

## Nội dung
- [Cài đặt](#Cài-đặt)
- [Cách sử dụng](#Cách-sử-dụng)
- [Cơ chế hoạt động](#Cơ-chế-hoạt-động)
- [Tham khảo](#Tham-khảo)


## Cài đặt 

Để có được một bản sao của dự án này và chạy nó trên máy tính của bạn, hãy làm theo các bước đơn giản sau.

### Yêu Cầu

Đảm bảo rằng bạn đã cài đặt Git trên hệ thống của mình. Bạn có thể tải xuống từ [git-scm.com](https://git-scm.com/).

### Các bước để cài đặt đồ án về máy

1. Mở terminal của bạn.
2. Điều hướng đến thư mục nơi bạn muốn nhân bản kho lưu trữ.
3. Sử dụng lệnh sau để nhân bản kho lưu trữ:

```bash
git clone git@github.com:Ryaniac/PlatFormer-Game.git
```
Để trải nghiệm trò chơi, thực hiện các bước sau:

```bash
cd PlatFormer-Game
```
Nếu bạn sử dụng Windows
```bash
py game.py
```
Nếu bạn sụng Linux
```bash
python3 game.py
```
Ngoài ra, nếu bạn chưa download thư viện pygame
```bash
pip install pygame
```
## Cách sử dụng

### A. Cấu trúc của đồ án 
#### Cấu trúc thư mục của dự án:

```plaintext
PlatFormer-Game/
├── README.md
├── game.py
├── editor.py
├── tutorial.json
│
├── data/
│   ├── images/
│   │   ├── background
│   │   ├── clouds
│   │   ├── enemy
│   │   ├── entities
│   │   ├── final_form
│   │   ├── menu
│   │   ├── monsters
│   │   ├── particles
│   │   └── tiles
│   ├── maps/
│   │   ├── 0.json
│   │   ├── 1.json
│   │   └── 2.json
│   ├── sfx
│   └── menu
│
└── scripts/
    ├── clouds.py
    ├── entities.py
    ├── tilemap.py
    ├── utils.py
    ├── particles.py
    └── menu.py

```
### B. Demo Video
#### Dưới đây là video chơi thử game Godthic Adventure
[Watch the video](https://drive.google.com/file/d/1IDn6WXkr_PW0bfk6Ue7wof7ouP5RS8OX/view?usp=sharing)


