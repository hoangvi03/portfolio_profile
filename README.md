# Portfolio Website - Trần Hoàng Vĩ

Website portfolio tĩnh của lập trình viên Python Trần Hoàng Vĩ, sinh viên năm cuối ngành CNTT tại Đại học Công nghiệp Thực phẩm TP.HCM, chuyên ngành Kỹ thuật Phần mềm.

## 🎓 Thông tin cá nhân

**Trần Hoàng Vĩ** - Lập trình viên Python
- 📧 Email: tranhoangvi210720003@gmail.com
- 📱 Phone: +84889424240
- 📍 Địa chỉ: Tân Phú, Thành phố Hồ Chí Minh
- 🎓 Học vấn: Đại học Công nghiệp Thực phẩm TP.HCM (2021-2025), GPA: 3.12
- 💼 LinkedIn: [linkedin.com/in/hoang-vi-860254323](https://www.linkedin.com/in/hoang-vi-860254323)

## 📁 Dự án nổi bật

### 1. Phân loại bệnh tiểu đường qua trên phương pháp học máy (03/2025 - 06/2025)
- **Mô tả**: Xây dựng hệ thống dự đoán nguy cơ mắc bệnh tiểu đường sử dụng Pima Indians Diabetes dataset
- **Tech Stack**: Python, Scikit-learn, SMOTE, RandomUnderSampler, Flask
- **Kết quả**: F1-score đạt 0.78, 4 thuật toán ML được tối ưu thành 5 mô hình
- **GitHub**: [diabetes_classification](https://github.com/hoangvi03/diabetes_classification.git)

### 2. Phân tích và dự đoán môi quan tâm người dùng trên Twitter (04/2025 - 05/2025)  
- **Mô tả**: Hệ thống phân tích và dự đoán chủ đề quan tâm của người dùng trên Twitter
- **Tech Stack**: Python, SVD, K-Means, LDA, Cosine Similarity
- **Kết quả**: Silhouette Score 0.42, độ chính xác phân cụm 80%
- **GitHub**: [Social_Network_Analytics](https://github.com/hoangvi03/Social_Network_Analytics.git)

### 3. Trang web quản lý trung tâm mỹ thuật sáng tạo (12/2024 - 02/2025)
- **Mô tả**: Website quản lý hoạt động trung tâm mỹ thuật với đầy đủ tính năng CRUD
- **Tech Stack**: Python, Django, PostgreSQL (Aiven Cloud), REST API, PgAdmin 4
- **Kết quả**: Hoàn thành trong 2 tháng, tối ưu hiệu năng và khả năng mở rộng
- **GitHub**: [Website_QuanLyTrungTamMyThuat](https://github.com/WebsiteTrungTamMyThuat/Website_QuanLyTrungTamMyThuat.git)

## 💼 Kinh nghiệm làm việc

### Thực tập sinh Phát triển Phần mềm - BEEMART SOLUTIONS (18/04/2025 - 25/07/2025)
- Phát triển công cụ crawl dữ liệu (>10,000 bản ghi), triển khai trên VPS Ubuntu Compose
- Xây dựng, quản lý và triển khai các module Odoo; quản lý mã nguồn với GitLab, GitHub  
- Tạo môi và tối ưu module Odoo với GitHub Copilot, triển khai Odoo App Store
- **Tech Stack**: Python, Django, Scrapy, SQLite, Odoo, PostgreSQL, Docker Compose, GitLab, GitHub, Linux VPS

### Thực tập sinh Lập trình - Công ty Cổ phần Tập đoàn Bất động sản Thắng Lợi (15/08/2024 - 25/10/2024)
- Thiết kế và xây dựng Vietnamese Spell-Checking System
- Tạo và quản lý từ điển tiếng Việt để tra cứu hiệu quả
- Phát triển thuật toán sửa lỗi chính tả phù hợp với ngôn ngữ tiếng Việt
- **Tech Stack**: Python, Flask, REST API, Levenshtein Distance, N-grams

## 🚀 Cấu trúc dự án

```
website/
├── index.html                 # Trang chính (single-page)
├── project-diabetes.html      # Chi tiết dự án Diabetes Classification
├── project-twitter.html       # Chi tiết dự án Social Network Analytics  
├── project-art-center.html    # Chi tiết dự án Art Center Management
├── css/
│   ├── style.css             # CSS chính cho trang index
│   └── project-detail.css    # CSS cho các trang chi tiết dự án
├── js/
│   └── main.js              # JavaScript cho tương tác
└── images/                  # Thư mục chứa hình ảnh
    ├── profile.jpg          # Ảnh profile (cần thêm)
    ├── diabetes-project.jpg # Ảnh dự án diabetes (cần thêm)
    ├── social-network-project.jpg # Ảnh dự án social network (cần thêm)
    └── art-center-project.jpg # Ảnh dự án art center (cần thêm)
```

## 🎨 Tính năng chính

### Trang chính (index.html)
- **Header & Navigation**: Logo + menu điều hướng smooth scroll
- **Hero Section**: Ảnh profile + giới thiệu + CTA button
- **About Me**: Thông tin cá nhân + học vấn + kỹ năng + tech stack
- **Experience**: Timeline 2 kỳ thực tập với animation
- **Projects**: Grid 3 dự án với preview + link chi tiết
- **Contact**: Form liên hệ + thông tin social links
- **Footer**: Bản quyền + social icons

### Trang chi tiết dự án
- **Project Hero**: Breadcrumb + title + metadata
- **Demo Section**: Ảnh chính với play button overlay
- **Overview**: Mô tả + mục tiêu + vai trò + tech stack
- **Process Timeline**: 4 bước quy trình thực hiện
- **Results**: Metrics + thành tựu cụ thể
- **Gallery**: Screenshots giao diện
- **Next Project**: Navigation đến dự án tiếp theo

## 🎨 Thiết kế

### Màu sắc
- **Chính**: Xanh dương (#3498db) + Trắng (#fff)
- **Phụ**: Xám nhạt (#f8f9fa), Cam CTA (#e74c3c)
- **Text**: Dark (#2c3e50), Medium (#555), Light (#7f8c8d)

### Typography
- **Headers**: Poppins (Google Fonts)
- **Body**: Open Sans (Google Fonts)
- **Icons**: Font Awesome 6

### Responsive
- **Desktop**: Grid layout, hover effects
- **Tablet**: Adjusted grid, collapsed navigation
- **Mobile**: Single column, touch-friendly buttons

## 🚀 Hướng dẫn Deploy lên GitHub Pages

### Bước 1: Chuẩn bị GitHub Repository
```bash
# Tạo repo mới trên GitHub với tên: username.github.io
# Hoặc tên khác và enable GitHub Pages từ Settings
```

### Bước 2: Upload files
```bash
# Upload tất cả files trong thư mục website/ lên repo
# Đảm bảo index.html ở root level
```

### Bước 3: Enable GitHub Pages
1. Vào Settings của repository
2. Scroll xuống GitHub Pages section
3. Chọn Source: Deploy from a branch
4. Chọn Branch: main (hoặc master)
5. Folder: / (root)
6. Click Save

### Bước 4: Truy cập website
- URL sẽ là: `https://username.github.io` hoặc `https://username.github.io/repository-name`

## 📸 Thêm hình ảnh

Bạn cần thêm các hình ảnh sau vào thư mục `images/`:

### Ảnh chính
- `profile.jpg` - Ảnh chân dung chuyên nghiệp (300x300px)
- `diabetes-project.jpg` - Screenshot dự án diabetes
- `social-network-project.jpg` - Screenshot dự án social network
- `art-center-project.jpg` - Screenshot dự án art center

### Ảnh chi tiết cho từng dự án
**Diabetes Project:**
- `diabetes-project-main.jpg` - Hero image
- `diabetes-ui-1.jpg` đến `diabetes-ui-4.jpg` - Screenshots giao diện

**Social Network Project:**
- `social-network-main.jpg` - Hero image  
- `twitter-dashboard.jpg` - Dashboard screenshot
- `twitter-sentiment.jpg` - Sentiment analysis
- `twitter-network.jpg` - Network visualization
- `twitter-trends.jpg` - Trending topics

**Art Center Project:**
- `art-center-main.jpg` - Hero image
- `art-admin-dashboard.jpg` - Admin dashboard
- `art-course-management.jpg` - Course management
- `art-student-portal.jpg` - Student portal
- `art-payment-system.jpg` - Payment system

## 🔧 Tùy chỉnh

### Thay đổi thông tin cá nhân
1. Mở `index.html`
2. Tìm các phần cần sửa:
   - Tên trong `.hero-title`
   - Mô tả trong `.hero-description`
   - Thông tin About Me
   - Links social media
   - Email contact

### Thay đổi màu sắc
1. Mở `css/style.css`
2. Tìm CSS variables hoặc màu hex values
3. Thay đổi theo ý muốn

### Thêm/sửa dự án
1. Sửa thông tin trong `index.html` phần projects
2. Tạo file HTML mới cho dự án hoặc sửa existing files
3. Update navigation links

## 📱 Tính năng JavaScript

- **Smooth scrolling** cho navigation
- **Mobile menu** toggle
- **Active section** highlighting khi scroll
- **Contact form** validation
- **Typing animation** cho hero text
- **Scroll reveal** animation
- **Back to top** button
- **Loading states** cho form submission

## 🔍 SEO & Performance

- **Meta tags** đầy đủ
- **Semantic HTML** structure  
- **Alt text** cho images
- **Optimized CSS** với classes có ý nghĩa
- **Mobile-first** responsive design
- **Fast loading** với CDN fonts và icons

## 📞 Hỗ trợ

Nếu bạn cần hỗ trợ hoặc có thắc mắc về website, vui lòng liên hệ qua:
- Email: tranhoangvi@email.com
- GitHub: github.com/tranhoangvi

---

**Lưu ý**: Đây là template hoàn chỉnh theo yêu cầu của bạn. Bạn chỉ cần thêm hình ảnh thực tế và cập nhật thông tin cá nhân để có website portfolio hoàn chỉnh!
