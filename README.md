# Game puzzle (HTML + JS)

## Cấu trúc

- `index.html` — file game, mở bằng trình duyệt (Chrome, Edge, Firefox...)
- `puzzle.jpg` — ảnh gốc dùng làm puzzle
- `README.md` — file hướng dẫn này



- Muốn đổi ảnh khác: thay file `puzzle.jpg` bằng ảnh mới (giữ nguyên tên file).
- Muốn thay số mảnh:
  - Mở `index.html` =>
  - Tìm đoạn:

    ```js
    const ROWS = 12;
    const COLS = 18;
    ```

  - Sửa `ROWS` và `COLS` sao cho `ROWS * COLS` là số mảnh bạn muốn.
