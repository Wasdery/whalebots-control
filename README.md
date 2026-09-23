# Whalebots Control

**Phần mềm cho thuê máy đào Rise of Kingdoms** — điều khiển nhiều giả lập chạy
WhaleBots qua Discord, kèm giao diện quản trị trên máy tính.

<sub>by **Wasdery**</sub>

---

## Tải về

👉 **[Tải bản mới nhất](../../releases/latest)**

Giải nén, chạy `WhalebotsControl.exe`. Lần đầu sẽ hiện cửa sổ nhập token bot
Discord, ID server, ID admin và đường dẫn WhaleBots — mất khoảng 1 phút.

---

## Làm được gì

**Người thuê máy** gõ thẳng trong kênh Discord, không có dấu `/`:

| Lệnh | Chức năng |
|---|---|
| `start` | Bật máy đào |
| `stop` | Tắt hẳn giả lập |
| `status` | Xem trạng thái máy |
| `view` | Tự chụp màn hình máy của mình |
| `help` | Xem hướng dẫn |

**Chủ máy** có 26 lệnh quản trị trên Discord, và một giao diện trên máy tính
làm được gần hết mà không cần vào Discord:

- **Người dùng** — gia hạn, cấp quyền, gắn/gỡ giả lập, bật/tắt máy, xem màn hình
- **Giả lập** — danh sách máy, xem từng máy hoặc xem tất cả cùng lúc
- **Bảo trì** — cộng ngày hàng loạt, đồng bộ trạng thái, dọn người đã rời Discord
- **Nhật ký** — toàn bộ hoạt động, tô màu theo mức độ

---

## Cảnh báo tự động cho người thuê máy

Phần mềm tự theo dõi và **nhắn tin riêng** cho người thuê khi máy của họ có vấn
đề — chủ máy không phải ngồi canh.

| Loại lỗi | Cách phát hiện |
|---|---|
| Không hiển thị game | Màn hình trắng trơn — báo ngay, vẫn trắng sau 5 phút thì **tự tắt/bật lại** giúp khách |
| Bot bị treo | Chụp màn hình định kỳ, hai lần liên tiếp giống nhau |
| Lệnh không có hiệu lực | Gõ `start` mà máy vẫn chưa chạy sau vài phút, vẫn chưa chạy sau 5 phút tiếp thì **tự bật lại** giúp khách |

---

## Yêu cầu

- Windows 10/11
- WhaleBots đã cài và chạy được
- Giả lập (BlueStacks) đã tạo sẵn các instance
- Máy bật liên tục khi muốn bot hoạt động
- Bot Discord đã bật **MESSAGE CONTENT INTENT**

Không cần cài Python — mọi thứ nằm trong file `.exe`.

---

## Bản quyền

Phần mềm cần **mã license** để bật máy. Các lệnh xem trạng thái, chụp màn hình,
tắt máy vẫn dùng được bình thường khi chưa kích hoạt.

Một mã dùng cho **một máy tại một thời điểm**. Đổi máy thoải mái — tắt phần mềm
ở máy cũ rồi mở ở máy mới là chạy được ngay.

Liên hệ **Wasdery** để mua mã.

---

## Hỗ trợ

Hướng dẫn cài đặt đầy đủ nằm trong file `HUONG DAN SU DUNG.md` kèm theo bản tải về.

Giao diện hiện tại bằng **tiếng Việt**.
