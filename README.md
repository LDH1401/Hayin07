# Web tỏ tình — Trái Tim Đếm Ngược

Trang tỏ tình một file: mưa chữ nền, đếm ngược 15 giây, ba lời nhắn hiện lần lượt,
rồi trái tim vẽ ra từ chính những ký tự đang rơi với câu cuối nằm bên trong.

Không cần build, không phụ thuộc thư viện. Mở `index.html` bằng trình duyệt là chạy.

## Tuỳ chỉnh bằng địa chỉ

Gắn thêm vào sau đường dẫn, ví dụ `?to=Hà&dem=10`:

| Tham số | Ý nghĩa | Mặc định |
|---|---|---|
| `to` | Tên người nhận, hiện ở màn chào | `Em` |
| `bg` | Câu nền tạo mưa chữ và các ký tự đắp nên trái tim | `Anh thích em` |
| `l1` `l2` `l3` | Ba câu hiện sau khi đếm xong | xem trong `index.html` |
| `f` | Câu cuối nằm trong trái tim | `Làm bạn gái anh nhé` |
| `dem` | Số giây đếm ngược, từ 1 đến 60 | `15` |
| `mp3` | Tên file nhạc nền; để trống thì dùng nhạc tổng hợp | `nhac.mp3` |
| `s` | Phát nhạc từ giây thứ mấy | `0` |

Hoặc xem hết một lượt rồi bấm **Tự tạo lời nhắn** ở cuối trang: điền form, bấm
Tạo link là có sẵn đường dẫn kèm mã QR.

## Nhạc nền

Đặt file `nhac.mp3` cạnh `index.html`. Thiếu file thì trang tự chuyển sang bản
nhạc tổng hợp bằng Web Audio, không báo lỗi.
