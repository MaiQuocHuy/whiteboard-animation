# SketchMotion

Biến một tấm ảnh thành video vẽ tay kiểu bảng trắng. Chọn ảnh, bấm Submit,
nhận file `.mp4`.

Toàn bộ việc dựng video chạy ngay trên máy bạn — không upload ảnh đi đâu,
không hàng đợi, không giới hạn độ dài, và không có watermark.

<p align="center">
  <video src="https://github.com/MaiQuocHuy/whiteboard-animation/raw/main/docs/demo.mp4"
         poster="https://github.com/MaiQuocHuy/whiteboard-animation/raw/main/docs/demo-poster.jpg"
         controls muted loop playsinline width="760"></video>
</p>

<p align="center">
  <sub>Video trên do chính app dựng ra từ một tấm ảnh &mdash; 1280&times;720, 10 giây.
  Không xem được ở đây thì
  <a href="https://github.com/MaiQuocHuy/whiteboard-animation/raw/main/docs/demo.mp4">bấm vào đây để tải</a>.</sub>
</p>

---

## Tải về

**[⬇ Tải bản mới nhất](https://github.com/MaiQuocHuy/whiteboard-animation/releases/latest)**
— tải file `SketchMotion-Setup-x.y.z.exe` rồi chạy.

Windows có thể hiện bảng xanh *"Windows protected your PC"* vì bộ cài chưa mua
chứng chỉ ký số. Bấm **More info › Run anyway** để tiếp tục.

Yêu cầu: **Windows 10 hoặc 11, 64-bit**. Không cần cài Python hay thư viện gì
thêm — mọi thứ nằm sẵn trong bộ cài.

## Dùng thế nào

1. **Upload Image** — chọn một ảnh. Bạn cũng có thể kéo thả nhiều ảnh cùng lúc,
   hoặc chọn cả thư mục, để dựng hàng đợi ở tab **Batch**
2. Chỉnh vài thông số nếu muốn
3. **Submit** — xong thì video hiện ngay trong app
4. Mọi video đã dựng nằm ở tab **Library**, mới nhất lên đầu, kèm ảnh gốc và
   thời điểm tạo. Nút **Download** lưu video ra chỗ bạn chọn

### Các thông số

| Thông số | Mặc định | Ý nghĩa |
|---|---|---|
| Drawing time | 8 giây | Bút mất bao lâu để vẽ xong bức tranh. Ảnh nhiều chi tiết nên để dài hơn cho dễ nhìn |
| Frame rate | 25 fps | Số khung hình mỗi giây |
| Hold final image | 2 giây | Giữ bức tranh hoàn chỉnh bao lâu ở cuối video |
| Colour timing | Whole picture | Tô màu cả bức sau khi vẽ xong, hoặc vẽ-và-tô từng nhân vật một |

Trong **Options** còn ba công tắc: hiện ảnh màu ở cuối, hiện bàn tay cầm bút, và
giới hạn độ phân giải ở 1080p. Tắt công tắc 1080p thì video giữ nguyên kích
thước ảnh gốc — nét hơn, nhưng dựng lâu hơn và file nặng hơn.

## Dùng thử và mua bản quyền

Mỗi máy được dựng **3 video miễn phí**, đủ để bạn xem thành phẩm trước khi
quyết định. Sau đó cần mã kích hoạt.

Trạng thái luôn hiện ở góc phải thanh tiêu đề, bấm vào được bất cứ lúc nào:

| Chip hiện | Nghĩa là | Bấm vào thì |
|---|---|---|
| 🎁 Còn 2/3 lượt | Đang dùng thử | Mở bảng giá |
| 🔒 Hết lượt · Nâng cấp | Đã dùng hết 3 lượt | Mở bảng giá kèm lý do |
| 👑 6 tháng | Đã kích hoạt | Xem gói, hạn dùng, mã đã che, mã máy |
| 👑 Còn 5 ngày | Sắp hết hạn | Xem chi tiết, có nút gia hạn |
| 📶 Chưa rõ | Chưa kiểm tra được trạng thái | Thử kết nối lại |

### Bảng giá

| Gói | Thời hạn | Giá |
|---|---|---:|
| 1 tháng | 30 ngày | 49.000đ |
| 3 tháng | 90 ngày | 129.000đ |
| 6 tháng | 180 ngày | 229.000đ |
| **Trọn đời** | không hết hạn | **499.000đ** |

Giá hiển thị trong app là giá đang áp dụng — nếu có khuyến mãi, app hiện luôn
mức đã giảm.

### Mua trong 30 giây

Chọn gói, app hiện mã QR VietQR **đã điền sẵn số tiền và nội dung chuyển
khoản**. Quét bằng app ngân hàng, chuyển tiền, rồi cứ để màn hình đó mở.

App tự hỏi máy chủ 4 giây một lần. Tiền về là mã được cấp và app **tự kích
hoạt** — bạn không phải gõ gì, không phải chờ ai nhắn mã, kể cả lúc 2 giờ sáng.

> ⚠️ **Chuyển đúng số tiền hiển thị** và **giữ nguyên nội dung chuyển khoản**.
> Đoạn `SM…` trong nội dung là thứ nối khoản tiền với đúng máy của bạn; sửa nó
> đi thì hệ thống không biết cấp mã cho ai, còn chuyển sai số tiền thì không
> khớp được với gói nào. Cả hai trường hợp đều vẫn xử lý được, nhưng phải chờ
> người bán làm tay.

Nếu bạn đã có mã sẵn, bấm **Tôi đã có mã** và dán vào. Mã có dạng
`IMGA-XXXXX-XXXXX-XXXXX`, gõ hoa hay thường đều được.

## Câu hỏi thường gặp

**Mua rồi có dùng offline được không?**
Được. Bản quyền chạy offline liên tục 7 ngày. Sau đó chỉ cần vào mạng một lần
để app tự gia hạn, rồi lại offline tiếp. Riêng bản dùng thử thì lần nào cũng
cần mạng, vì số lượt còn lại được đếm trên máy chủ chứ không phải trên máy bạn.

**Đổi máy được không?**
Được, tối đa **2 lần** cho mỗi mã. Ở máy cũ, bấm vào chip trạng thái rồi chọn
*Gỡ khỏi máy này* — thao tác này **không** tốn lượt chuyển máy. Sau đó dùng
chính mã đó kích hoạt ở máy mới.

**Cài lại Windows thì sao?**
Mã máy được tính lại sau khi cài lại hệ điều hành, nên lần kích hoạt sau sẽ
tính là một lần chuyển máy. Nếu đã hết lượt, nhắn cho người bán kèm **mã máy**
hiện trong màn hình chi tiết bản quyền.

**Quên mất mã của mình?**
Bấm vào chip trạng thái, mã hiện ở dạng che bớt như `IMGA-7K2M9-•••••-••18Z`.
Mấy ký tự đó đủ để người bán tra ra mã đầy đủ cho bạn.

**Video lưu ở đâu?**
Trong thư mục dữ liệu của app, xem lại bất cứ lúc nào ở tab **Library**. Nút
**Download** trong Library lưu ra chỗ bạn chọn.

**Dựng một video mất bao lâu?**
Tuỳ máy và tuỳ ảnh. Ảnh thường ở 1080p mất khoảng vài chục giây đến vài phút.
Tắt giới hạn 1080p thì lâu hơn đáng kể.

**Gỡ app có mất bản quyền không?**
Không. Mã vẫn gắn với máy; cài lại app là dùng tiếp.

## Hỗ trợ

Gặp lỗi, chuyển khoản rồi mà chưa được kích hoạt, hay cần thêm lượt đổi máy —
mở một [issue tại đây](https://github.com/MaiQuocHuy/whiteboard-animation/issues)
kèm **mã máy** (xem trong màn hình chi tiết bản quyền).

<!-- Điền kênh liên hệ trực tiếp của bạn vào dòng dưới rồi bỏ dấu chú thích:
Liên hệ nhanh: Zalo 09xxxxxxxx · Email ban@example.com
-->

## Giấy phép

Phần mềm phát hành theo giấy phép [MIT](./LICENSE).
