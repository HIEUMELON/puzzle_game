# Game puzzle 216 mảnh (HTML + JS)

## Cấu trúc

- `index.html` — file game, mở bằng trình duyệt (Chrome, Edge, Firefox...)
- `puzzle.jpg` — ảnh gốc dùng làm puzzle
- `README.md` — file hướng dẫn này

## Cách chạy

1. Giải nén file ZIP.
2. Đảm bảo trong thư mục có đủ 3 file: `index.html`, `puzzle.jpg`, `README.md`.
3. Nháy đúp `index.html` để mở bằng trình duyệt.
4. Game sẽ chia ảnh thành 216 mảnh (12 x 18). Click chọn 2 mảnh để hoán đổi.
5. Khi tất cả mảnh về đúng vị trí, trò chơi sẽ hiện thông báo **"Hoàn thành!"**.

## Tùy chỉnh

- Muốn đổi ảnh khác: thay file `puzzle.jpg` bằng ảnh mới (giữ nguyên tên file).
- Muốn thay số mảnh:
  - Mở `index.html` =>
  - Tìm đoạn:

    ```js
    const ROWS = 12;
    const COLS = 18;
    ```

  - Sửa `ROWS` và `COLS` sao cho `ROWS * COLS` là số mảnh bạn muốn.
