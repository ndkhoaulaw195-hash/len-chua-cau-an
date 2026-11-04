# Lên Chùa Cầu An - Chùa An Lạc (3D Web Game)

> Game web 3D thanh tịnh, tái hiện không gian ngôi chùa Việt cổ kính lúc hoàng hôn chuyển đêm với đầy đủ nghi thức tâm linh nhẹ nhàng: Thắp hương, Thỉnh chuông, Gõ mõ tụng kinh, Treo dải lụa cầu an lên Cây Bồ Đề / Thả đèn hoa đăng Hồ Sen, Xin quẻ đầu năm và Quản lý hồ sơ Phật tử.

---

## 🌟 Điểm nổi bật & Tính năng chính

1. **MỘT FILE DUY NHẤT (`index.html`)**:
   - Mở thẳng bằng trình duyệt là chơi được ngay, không cần máy chủ (serverless), không cần cài đặt dependencies hay npm.
   - 100% tài nguyên đồ họa và âm thanh được sinh bằng mã lập trình:
     - Dựng 3D Low-Poly ấm áp qua Three.js (ES Module CDN).
     - Âm thanh thuần Web Audio API: Tiếng chuông đồng ngân vang nhiều âm bội, mõ gỗ trầm ấm, tiếng om drone tụng kinh rì rầm, gió thoảng, chim hót ngẫu nhiên, tiếng lắc ống xăm tre.
2. **Bối cảnh chùa Việt cổ kính**:
   - Cổng Tam Quan với biển đề chữ Quốc Ngữ **"Chùa An Lạc"**.
   - Sân chùa lát gạch Bát Tràng đỏ nung, lư hương đồng ba chân quỳ giữa sân với khói trầm nghi ngút.
   - Chính điện 2 tầng mái ngói cong đầu đao, tượng Phật Thích Ca Mâu Ni ngồi kiết già trang nghiêm với vòng hào quang phát sáng dịu nhẹ.
   - Cây bồ đề cổ thụ treo rủ dải lụa đỏ, hồ sen với hoa sen hồng, lá sen xanh và đèn hoa đăng lung linh dập dềnh sóng nước.
   - Gác chuông với quả Đại Hồng Chung bằng đồng hun và chày gỗ đánh chuông.
   - Ánh đèn lồng đỏ chớp tắt nhẹ, đom đóm vàng xanh lập lòe, cánh hoa bồ đề bay nhẹ trong gió chiều hoàng hôn.
3. **Nhân vật chibi áo lam & Điều khiển linh hoạt**:
   - Nhân vật mặc áo lam truyền thống, tóc búi, dáng đi mềm mại, khi đứng yên thì chắp tay trang nghiêm.
   - **Điện thoại di động (Màn dọc)**: Cần điều khiển ảo (Virtual Joystick) góc trái mượt mà, vuốt màn hình để xoay camera 360 độ.
   - **Máy tính (PC/Laptop)**: Phím W-A-S-D hoặc phím Mũi tên, giữ rê chuột để xoay góc nhìn.
   - Hệ thống chống đi xuyên tường, cột chùa, lư hương, hồ sen, gác chuông.
4. **5 Hoạt động tâm linh thanh tịnh**:
   - **Thắp Hương**: Chọn 1 nén (nhất tâm hướng thiện) hoặc 3 nén (Tam Bảo: Phật - Pháp - Tăng), cắm vào lư hương, khói bay, đầu nhang đỏ rực.
   - **Thỉnh Chuông**: Minigame bắt nhịp (Timing QTE) chạm chuông khi vòng hào quang co khớp tâm chuông, tiếng chuông "Boong..." rền rĩ trầm ấm, rung nhẹ màn hình.
   - **Gõ Mõ Tụng Kinh**: Minigame nhịp điệu 25 giây, tiếng mõ ấm vang, chấm điểm "Tâm An" (0-100) kèm lời khen tịnh tâm, an lạc.
   - **Viết Lời Cầu An**: Nhập tối đa 120 ký tự, có các gợi ý nhanh (gia đình, thi cử, sức khỏe, công việc), lọc từ thô tục, chọn treo dải lụa đỏ lên Cây Bồ Đề hoặc thả đèn hoa đăng xuống Hồ Sen.
   - **Xin Quẻ Đầu Năm**: Lắc ống xăm tre lách cách, rút ngẫu nhiên trong 40 câu quẻ cát tường giàu ý nghĩa đối nhân xử thế, hướng thiện, tích phúc, có ghi chú "Mang tính giải trí và an lạc tâm hồn".
5. **Khách hành hương AI đông vui, ấm áp**:
   - 42 khách AI mặc nhiều màu áo (lam, nâu sòng, vàng kem...) đi dạo, đứng chắp tay vái trước điện, quỳ lễ lư hương.
   - Hiện bong bóng suy nghĩ/cầu nguyện trên đầu khách AI: "Cầu cho mẹ mau khỏe...", "Mong thi đậu...", "Nam mô A Di Đà Phật...", v.v.
   - Định kỳ xuất hiện "Đoàn khách" 8-12 người cùng bước vào từ cổng Tam Quan.
   - Bộ đếm khách viếng chùa trong ngày tự động cập nhật tự nhiên.
6. **Quản lý tài khoản Phật tử (Local Multi-Profile)**:
   - Cho phép tạo và chuyển đổi nhiều tài khoản cho các thành viên trong gia đình (Bố, Mẹ, Con, Bạn bè...).
   - Lưu trữ riêng biệt từng sổ cầu an cho mỗi tài khoản.
   - Hỗ trợ đổi tên, xóa hồ sơ, sao lưu dữ liệu (Export JSON) và khôi phục (Import JSON).
7. **Tạo Thiệp Bình An 1080×1350 & Chia Sẻ**:
   - Xuất thiệp dọc chất lượng cao bằng Canvas 2D: hoa sen, mặt trời hoàng hôn, tên người cầu nguyện, ước nguyện, điểm Tâm An, dấu triện đỏ "Bình An".
   - Tích hợp Web Share API chia sẻ trực tiếp lên Zalo, Facebook, tin nhắn hoặc tải ảnh PNG về máy.

---

## 🚀 Hướng dẫn triển khai lên GitHub & Render

### Bước 1: Khởi tạo và Đẩy lên GitHub

Mở Terminal tại thư mục này và chạy các lệnh sau:

```bash
# 1. Khởi tạo Git repo
git init
git add .
git commit -m "feat: Ra mắt game web 3D Lên Chùa Cầu An - Chùa An Lạc"

# 2. Tạo repository mới trên GitHub (thông qua GitHub CLI hoặc trên web github.com)
# Nếu dùng GitHub CLI:
gh repo create len-chua-cau-an --public --source=. --remote=origin --push

# Hoặc nếu tạo repo thủ công trên github.com:
git remote add origin https://github.com/<tai-khoan-github-cua-ban>/len-chua-cau-an.git
git branch -M main
git push -u origin main
```

### Bước 2: Triển khai trực tiếp lên Render (Hoàn toàn Miễn Phí)

Vì dự án là Static Web (chỉ gồm file `index.html`), triển khai lên Render chỉ mất **30 giây**:

1. Đăng nhập vào [Render Dashboard](https://dashboard.render.com/).
2. Nhấn vào nút **New +** ở góc trên bên phải -> Chọn **Static Site**.
3. Chọn kho lưu trữ GitHub của bạn (`len-chua-cau-an`).
4. Điền các trường cấu hình cực kỳ đơn giản:
   - **Name**: `len-chua-cau-an` (hoặc tên bạn tùy chọn).
   - **Branch**: `main`.
   - **Build Command**: Để trống (không cần build).
   - **Publish Directory**: `.` (hoặc `./`).
5. Nhấn **Create Static Site**.
6. Render sẽ cung cấp ngay cho bạn đường link trực tiếp (ví dụ: `https://len-chua-cau-an.onrender.com`), mở trên bất kỳ điện thoại hay máy tính nào đều chơi mượt mà!

---

## 📋 Danh Sách Tự Kiểm Tra (Self-Check Checklist)

- [x] **File sản phẩm**: Đóng gói hoàn chỉnh trong 01 file duy nhất `index.html`.
- [x] **Three.js & Assets**: Sử dụng Three.js qua Importmap CDN, không tải file ảnh, mô hình 3D hay âm thanh MP3 bên ngoài; toàn bộ dựng bằng code procedural.
- [x] **Giao diện & Ngôn ngữ**: 100% Tiếng Việt, chữ Quốc Ngữ chuẩn mực, tối ưu đặc biệt cho khung hình điện thoại dọc (portrait mode) và chơi tốt trên máy tính.
- [x] **Không thương mại / Không thu thập**: Không đăng nhập bắt buộc, không tracking, không quảng cáo, không quyên góp tiền bạc.
- [x] **Bối cảnh Chùa Việt**: Đầy đủ Cổng Tam Quan, Chính Điện mái cong 2 tầng ngói đỏ, tượng Phật Thích Ca kiết già, Lư hương đồng lớn, Cây Bồ Đề, Hồ sen, Gác chuông, Hàng đèn lồng lung linh, khói hương, đom đóm, cánh hoa rơi.
- [x] **Âm thanh Web Audio**: Tự tổng hợp tiếng chuông đồng nhiều âm bội ngân 7s, tiếng mõ tụng kinh gỗ ấm, tiếng tụng kinh om drone, gió xào xạc, chim hót, có nút Mute/Unmute.
- [x] **Đi lại & Va chạm**: Virtual Joystick mượt trên mobile, WASD trên PC, xoay góc nhìn tự do, không xuyên tường, không xuyên tượng, không xuyên lư hương hay hồ sen.
- [x] **Đủ 5 hoạt động**:
  - [x] 1. Thắp hương (chọn 1 hoặc 3 nén, cắm vào lư, khói bay).
  - [x] 2. Thỉnh chuông (minigame timing co vòng, ngân dài, rung nhẹ màn hình).
  - [x] 3. Gõ mõ tụng kinh (nhịp điệu 25s, phản hồi tức thì, tính điểm Tâm An 0-100).
  - [x] 4. Viết lời cầu an (tối đa 120 ký tự, lọc từ thô tục, chọn treo lụa Bồ Đề hoặc thả hoa đăng Hồ Sen).
  - [x] 5. Xin quẻ đầu năm (lắc ống xăm, 40 câu cát tường tích cực, có dòng chữ giải trí).
- [x] **Khách AI**: 42 khách hành hương nhiều màu áo, đi lại, vái lạy, có bong bóng suy nghĩ trên đầu khách AI, đoàn khách mới từ cổng tam quan, bộ đếm khách viếng chùa trong ngày.
- [x] **Quản lý tài khoản**: Hệ thống Local Multi-profile tạo/đổi nhiều tài khoản, đổi tên, xóa, xuất/nhập file sao lưu JSON.
- [x] **Lưu & Chia sẻ**: Lưu localStorage, trang Sổ Cầu An, xuất ảnh thiệp 1080x1350 bằng Canvas, Web Share API hoặc tải file PNG.
