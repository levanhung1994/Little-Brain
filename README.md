
    Sau khi giải nén ZIP, thực hiện theo thứ tự:
1

Cài thành phần EmulatorJS
Chạy file scripts\install-emulator.bat khi máy có Internet.


2

Chép ROM và BIOS vào thư mục
games/
├── arcade/
│   ├── mslug.zip
│   ├── killbld.zip
│   └── kof97.zip
├── nes/
│   └── contra.nes
└── bios/
    ├── neogeo.zip
    └── pgm.zip




3

Khởi động website
Chạy start-local.bat, sau đó mở http://127.0.0.1:8000.


4

Nhấn REFRESH LIBRARY
Game hợp lệ sẽ được thêm vào thư viện. Chọn PLAY để bắt đầu nạp bằng emulator.


Lưu ý:
- Metal Slug cần BIOS Neo Geo tương thích.
- The Killing Blade cần BIOS PGM tương thích và có thể cần thêm ROM parent tùy phiên bản.
- Contra NES thông thường chỉ cần contra.nes.
- Một BIOS có thể dùng chung cho nhiều game cùng hệ máy.
- Các file giả lập trong emulator/data/ chỉ cần cài một lần, không cần cài riêng cho từng game.
Ví dụ: Nếu bạn tải 10 game Metal Slug hoặc King of Fighters chạy trên Neo Geo thì thường chỉ cần một bộ BIOS neogeo.zip dùng chung, không cần 10 bản BIOS.
Sau khi chép ROM, bạn chỉ cần vào website nhấn Refresh Library để nhận diện game.
