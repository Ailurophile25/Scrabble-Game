# GAME SCRABBLE 

Một trò chơi Scrabble trên desktop được phát triển bằng C++ và thư viện SDL2.  
Project mô phỏng các cơ chế cơ bản của Scrabble như quản lý bàn cờ, đặt chữ, kiểm tra từ hợp lệ, tính điểm và xử lý kết thúc trò chơi.

## Thực hiện bới nhóm sinh viên
1. Nguyễn Bình An
2. Lê Minh Anh
3. Trần Lê Cương
4. Đỗ Thị Thu Hà
5. Nguyễn Minh Phúc

## Công nghệ sử dụng
- C++
- SDL2
- SDL2_image
- SDL2_ttf
- CodeBlocks

## Cấu trúc project

```text
Scrabble/
│
├── src/                # File source (.cpp)
├── include/            # File header (.h)
├── PNGs/             # Hình ảnh chữ cái
├── libs/               # SDL2 DLL
│
├── scrabble.cbp        # File project CodeBlocks
└── README.md
```

---

## Luật Chơi Scrabble (Đơn Giản)
1. Mỗi người chơi bắt đầu với 7 quân chữ.
2. Người chơi lần lượt đặt các quân chữ lên bàn cờ để tạo thành từ có nghĩa.
3. Từ đầu tiên phải đi qua ô trung tâm của bàn cờ.
4. Các từ mới được tạo phải liên kết với những từ đã có trên bàn cờ.
5. Điểm số được tính dựa trên giá trị của từng chữ cái và các ô thưởng đặc biệt trên bàn cờ.
6. Nếu sử dụng hết toàn bộ 7 quân chữ trong một lượt, người chơi sẽ nhận thêm điểm thưởng (Bingo).
7. Trò chơi kết thúc khi túi chữ không còn quân nào và một người chơi đã sử dụng hết toàn bộ quân chữ trên tay.
