# alpha_base_busd_charts# 📊 Alpha base BUSD - Interactive Reports

Repository này là nơi lưu trữ và host các báo cáo phân tích chiến lược **Alpha base BUSD** dưới dạng biểu đồ 3D tương tác.



## 🎯 Mục tiêu
Cung cấp cái nhìn trực quan về hiệu suất của các thế hệ Alpha thông qua chỉ số Sharpe Ratio trên không gian 3 chiều (Frequency & Threshold).

## 🚀 Tính năng chính
- **3D Interactive Charts:** Biểu đồ xoay 360 độ, zoom-in/out để soi các vùng dữ liệu.
- **Auto-Sync:** Dữ liệu được cập nhật tự động từ hệ thống Backtest thông qua Git.
- **Performance Table:** Tích hợp bảng thông số (Metrics) và chú thích (Legend) ngay trên báo cáo.

## 🔗 Truy cập nhanh
- **Link Reports:** `https://thanhnt15.github.io/alpha_base_busd_charts/`
- **Cấu trúc URL:** `.../alpha_{ID}_gen_{ID}_year_{YYYY}.html`

## 🛠 Quy trình vận hành (Workflow)
1. **Backtest:** Hệ thống Python tính toán và xuất file HTML.
2. **Push:** File được tự động đẩy lên Repo này với Timestamp Việt Nam.
3. **Deploy:** GitHub Pages tự động host file thành link web tĩnh.
4. **Link:** URL được cập nhật trực tiếp vào Google Sheets quản lý.

## 📂 Cấu trúc Repo
```text
.
├── reports/                    # Thư mục chứa các file báo cáo (nếu có)
├── alpha_01_gen_1_year_2024.html
├── alpha_02_gen_1_year_2024.html
└── README.md