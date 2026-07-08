# Game 2048

Game 2048 cổ điển chạy hoàn toàn trên trình duyệt, gói gọn trong **một file HTML duy nhất** (`index.html`) — không cần cài đặt, không cần server, không cần thư viện ngoài.

## Cách chạy

1. Mở link: [https://buivantri8433.github.io/2048/](https://buivantri8433.github.io/2048/)
2. Hoặc tải file `index.html` về máy và mở bằng trình duyệt.

## Tính năng

| Tính năng | Mô tả |
|---|---|
| Điều khiển | Phím mũi tên / WASD trên máy tính, vuốt trên màn hình cảm ứng |
| Điểm & kỷ lục | Điểm cộng hiện hiệu ứng "+n" bay lên; kỷ lục lưu vĩnh viễn |
| Giao diện sáng / tối | Nút 🌙/☀️ để chuyển; mỗi giao diện có bảng màu ô riêng |
| Tự động lưu | Ván đang chơi lưu sau mỗi nước đi — đóng trình duyệt mở lại vẫn chơi tiếp |
| Hiệu ứng | Ô trượt mượt, nảy khi ghép, ô giá trị cao phát sáng |
| Hỗ trợ tiếp cận | Tôn trọng `prefers-reduced-motion`, có focus ring cho bàn phím |

## Dữ liệu lưu ở đâu?

Game dùng `localStorage` của trình duyệt với 3 khóa:

- `game2048` — trạng thái bàn cờ hiện tại
- `best2048` — điểm kỷ lục
- `theme2048` — giao diện đang chọn (`dark` / `light`)

Xóa dữ liệu duyệt web sẽ xóa luôn tiến trình.

---

**Chơi ngay:** [https://buivantri8433.github.io/2048/](https://buivantri8433.github.io/2048/)
