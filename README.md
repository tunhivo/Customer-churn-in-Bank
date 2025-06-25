# 📉 Dự Án Phân Tích Khách Hàng Rời Bỏ Ngân Hàng (Customer Churn in Bank)

## 📌 Mục tiêu
Dự án nhằm **phân tích và dự đoán khả năng rời bỏ của khách hàng** trong lĩnh vực ngân hàng, từ đó đề xuất các chiến lược giữ chân khách hàng hiệu quả.

---

## 🧾 Nội dung chính

### 1. 📂 Dữ liệu sử dụng
- **Nguồn**: Bộ dữ liệu mô phỏng từ Kaggle / ngân hàng giả định
- **Tên file**: `Churn_Modelling.csv`
- **Số lượng dòng**: ~10.000
- **Các cột quan trọng**:
  - `CustomerId`, `Surname`, `Geography`, `Gender`, `Age`, `Balance`
  - `NumOfProducts`, `IsActiveMember`, `Exited` (biến mục tiêu)

---

## 🧾 Cấu trúc thư mục
```toml
Customer-churn-in-Bank/
│
├── Customer churn in bank.ipynb       # Notebook chính
├── Churn_Modelling.csv                # File dữ liệu
├── README.md                          # Tệp mô tả (bạn đang đọc đây)

---

### 2. 🧪 Quy trình xử lý
#### 🔍 Khám phá dữ liệu (EDA)
- Thống kê số lượng khách hàng đã rời đi
- Phân tích mối quan hệ giữa churn và:
  - Giới tính
  - Độ tuổi
  - Quốc gia
  - Số lượng sản phẩm sử dụng
  - Mức độ hoạt động của tài khoản

#### 📊 Trực quan hóa
- Biểu đồ cột, histogram, heatmap
- Highlight insight: **Khách hàng không hoạt động có tỷ lệ rời đi cao gấp 2 lần bình thường**

#### 🧠 Mô hình dự đoán
> *(Chưa có trong file hiện tại, sẽ bổ sung nếu được cập nhật)*

---

## 💡 Một số insight quan trọng

### 📌 Tỷ lệ rời bỏ
- **Tổng tỷ lệ churn**: khoảng `20%`
- **Khách hàng lớn tuổi có xu hướng rời bỏ cao hơn**
- **Khách hàng không hoạt động (inactive)** dễ churn hơn gấp **2 lần**

### 🧠 Đề xuất giữ chân
- Cải thiện trải nghiệm người dùng trên app ngân hàng
- Tạo ưu đãi cho khách hàng có nguy cơ churn
- Tăng tương tác với khách hàng ít hoạt động

---

## 💼 Công cụ & thư viện
- Python, Pandas, Matplotlib, Seaborn
- Môi trường phát triển: VS Code / Jupyter Notebook

---


**Người thực hiện:**  
[Tu Nhi Vo] – Dự án phân tích vận hành, 2025