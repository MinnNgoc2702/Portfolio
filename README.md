# 🌸 Bùi Minh Ngọc — Academic & Professional Portfolio

> **Portfolio cá nhân học thuật và lãnh đạo của Bùi Minh Ngọc**  
> Định hướng chuyên ngành: **Business Analytics, Corporate Finance & Applied AI Innovation**  
> Trường: **THPT Vinschool Smart City (Khóa 2027)**  
> Điểm nổi bật: **SAT 1550 • IELTS 8.0 • GPA 9.7/10 • 2x Huy chương Vàng Sáng chế Quốc tế (SVIIF Thung lũng Silicon & IPITEx Bangkok)**

---

## ✨ Điểm nhấn Thiết kế & Phong cách

* **Phong cách Thẩm mỹ:** Nữ tính, tinh tế, sang trọng và chuẩn mực học thuật (*Modern Executive Feminine*).
* **Bảng màu:** Rose Gold (Vàng hồng), Satin Blush, Warm Champagne Gold phối cùng Dark Velvet Orchid (Tím than nhung) và ngọc trai ngà (*Ivory Silk*).
* **100% Ảnh Thật & Bằng Khen Chính Thức:** Sử dụng ảnh thật của Bùi Minh Ngọc trong trang phục Áo dài nhận cúp/huy chương tại Bangkok và toàn bộ 14 chứng chỉ/bằng khen quốc tế & quốc gia trích xuất từ tệp `Bui Minh Ngoc_ Awards.pdf`.
* **Trải nghiệm tương tác cao cấp:**
  * **Bộ lọc Danh mục:** Lọc giải thưởng theo *Quốc tế, Kinh tế/Kinh doanh, Khoa học & Công nghệ, Hình ảnh sân khấu*.
  * **Modal Lightbox:** Bấm vào bất kỳ bằng khen nào để xem phóng to độ phân giải cao và đọc thông tin chi tiết.
  * **Đổi giao diện Sáng / Tối (Light Blossom / Dark Velvet):** Tự động ghi nhớ theo tùy chọn của người dùng.
  * **Hiệu ứng đếm số mượt mà:** Cho các chỉ số SAT, IELTS, GPA và số học sinh được cố vấn.
  * **Timeline Lãnh đạo Tài chính:** Mô tả chi tiết vai trò Trưởng ban Tài chính MUN, dự án cộng đồng Iron Run, thực tập sinh EdTech Data tại SCONEK JSC và Trợ giảng AI tại RIVA Institute.

---

## 📁 Cấu trúc Thư mục Dự án

```text
├── index.html                 # Cấu trúc HTML5 ngữ nghĩa, tối ưu SEO & Responsive
├── style.css                  # Hệ thống Design Tokens CSS, hiệu ứng kính Glassmorphism
├── app.js                     # Logic tương tác (Lightbox, lọc giải thưởng, đếm số, đổi theme)
├── vercel.json                # Cấu hình Vercel tối ưu Routing và Caching tĩnh
├── README.md                  # Hướng dẫn chi tiết dự án & cách deploy
├── Resume__Bui Minh Ngoc.docx # Bản gốc hồ sơ học thuật
├── Bui Minh Ngoc_ Awards.pdf  # Tệp gốc 14 trang chứng chỉ & giải thưởng
└── assets/
    ├── minh_ngoc_real_avatar.jpg # Ảnh đại diện chân dung cắt từ ảnh sân khấu thật
    └── awards/                   # 14 hình ảnh bằng khen & ảnh chụp sự kiện thật:
        ├── award_page_01.jpg     # HCV IPITEx 2026 (Máy tái chế nước từ không khí)
        ├── award_page_02.jpg     # Ảnh Bùi Minh Ngọc nhận Cúp & HCV tại Bangkok
        ├── award_page_03.jpg     # Đoàn học sinh Việt Nam cầm cờ tại IPITEx
        ├── award_page_04.jpg     # Giải đặc biệt Quốc tế từ Hiệp hội Romania (ARTAS)
        ├── award_page_05.jpg     # Diploma Huy chương Vàng SVIIF Silicon Valley, Mỹ
        ├── award_page_06.jpg     # Giấy khen Giải Khuyến khích Olympic Kinh tế (VEO 2025)
        ├── award_page_07.jpg     # Chứng nhận tham gia VEO 2025
        ├── award_page_08.jpg     # Top 5% Olympic Ngôn ngữ Tính toán Việt Nam (RIVA)
        ├── award_page_09.jpg     # Giải Vận hành Doanh nghiệp SAGE Global 2025
        ├── award_page_10.jpg     # Giải Ba Tiếng Anh Cụm Nam - Bắc Từ Liêm
        ├── award_page_11.jpg     # HCV Quốc gia ASMO Science 2025
        ├── award_page_12.jpg     # Giải Nhì Đồng đội ASMO Quốc tế tại Indonesia
        ├── award_page_13.jpg     # Giải Khuyến khích ASMO Quốc tế
        └── award_page_14.jpg     # Đội tuyển có thành tích tốt nhất ASMO Quốc tế
```

---

## 🚀 Hướng dẫn Deploy lên Vercel App (Miễn phí 100%)

Trang web đã được cấu hình sẵn tệp `vercel.json` chuẩn tĩnh, không cần cài đặt build phức tạp. Bạn có thể triển khai lên Vercel theo 2 cách dưới đây:

### Cách 1: Deploy qua GitHub (Khuyên dùng — Chỉ 1 Click & Tự động cập nhật)

Vì tài khoản GitHub trên máy của bạn đã được kết nối với tài khoản **`MinnNgoc2702`**, đây là cách chuyên nghiệp và dễ nhất:

1. **Khởi tạo và đẩy code lên GitHub:**
   Chạy các lệnh sau trong Terminal của Antigravity IDE:
   ```powershell
   git init
   git add .
   git commit -m "feat: complete professional portfolio for Bui Minh Ngoc"
   git branch -M main
   gh repo create minh-ngoc-portfolio --public --source=. --remote=origin --push
   ```
   *(Lệnh trên sẽ tự động tạo một repository mới tên là `minh-ngoc-portfolio` trên GitHub của bạn và đẩy toàn bộ source code lên).*

2. **Kết nối với Vercel:**
   - Truy cập vào [vercel.com](https://vercel.com) và đăng nhập bằng tài khoản GitHub **MinnNgoc2702**.
   - Bấm vào nút **"Add New..."** ➔ Chọn **"Project"**.
   - Bạn sẽ thấy repository `minh-ngoc-portfolio` xuất hiện trong danh sách ➔ Bấm nút **"Import"**.
   - Mục **Framework Preset**: Chọn **Other** (hoặc để mặc định).
   - Bấm nút **"Deploy"**.

3. **Hoàn tất:**
   - Trong vòng chưa đầy 15 giây, website sẽ được xuất bản trực tuyến tại địa chỉ dạng:
     `https://minh-ngoc-portfolio.vercel.app` (hoặc tên miền tùy chỉnh bạn chọn).
   - Mỗi lần bạn sửa code và gõ `git push`, Vercel sẽ tự động cập nhật phiên bản mới nhất!

---

### Cách 2: Deploy trực tiếp bằng Vercel CLI (Không qua Web)

1. Mở Terminal trong Antigravity, gõ lệnh:
   ```powershell
   npx vercel
   ```
2. Terminal sẽ hỏi:
   * *`Set up and deploy?`* ➔ Gõ **`y`** rồi nhấn Enter.
   * *`Which scope do you want to deploy to?`* ➔ Nhấn Enter (chọn tài khoản của bạn).
   * *`Link to existing project?`* ➔ Gõ **`n`** rồi nhấn Enter.
   * *`What's your project's name?`* ➔ Nhấn Enter (mặc định lấy tên thư mục).
   * *`In which directory is your code located?`* ➔ Nhấn Enter (`./`).
3. Chờ vài giây, bạn sẽ nhận được đường link website `https://...vercel.app` xem được ngay trên điện thoại và máy tính!

---

## 👩‍🎓 Thông tin Liên hệ trong Hồ sơ

* **Ứng viên:** Bùi Minh Ngọc (Bui Minh Ngoc)
* **Email:** [minhngocbui2702@gmail.com](mailto:minhngocbui2702@gmail.com)
* **Điện thoại:** (+84) 931-796-269
* **Địa chỉ:** Hà Nội, Việt Nam
* **GitHub:** [github.com/MinnNgoc2702](https://github.com/MinnNgoc2702)
