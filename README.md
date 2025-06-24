# 📊 HomeMart Retail Analytics
Cuộc thi Data Science Talent Competition của trường Đại học FTU 
## 🛒 Giới thiệu dự án
Dự án này nhằm trực quan hóa và phân tích hành vi mua sắm của khách hàng tại hệ thống bán lẻ **HomeMart**, dựa trên dữ liệu hành vi khách hàng và sản phẩm từ ngày **01/07/2024 đến 08/07/2024**.  
Chúng tôi sử dụng các công cụ như **Python, Tableau, Power BI, Looker Studio** và **BigQuery** để phân tích và xây dựng dashboard.  
> **Mục tiêu chính**: Hiểu rõ hơn về xu hướng tiêu dùng, thời điểm mua sắm cao điểm, quầy hàng sinh lời cao và nhóm khách hàng trọng điểm để tối ưu hoạt động kinh doanh.
---
## 🧾 Dữ liệu sử dụng
Dữ liệu gồm 3 bảng chính:
- `Customer Behavior`: 15.395 dòng – thông tin hành vi mua sắm của khách.
- `Item Information`: 135 dòng – thông tin sản phẩm.
- `Shelf Information`: 9 dòng – thông tin các quầy hàng.
---
## 📈 Một số insight chính
### 🗓️ Doanh thu theo ngày
- **Doanh thu cao nhất vào Thứ Bảy (417 triệu)** và **Chủ Nhật (379 triệu)**.
- **Doanh thu thấp nhất vào Thứ Hai (46 triệu)** – cho thấy hành vi mua sắm tăng mạnh vào cuối tuần.
📌 **Đề xuất**: Tập trung khuyến mãi, marketing mạnh vào cuối tuần. Triển khai chương trình “Monday Deals” để kích cầu đầu tuần.

---
### 🕒 Doanh thu theo giờ
- **Khung giờ cao điểm**: từ **11h đến 15h59** và **20h đến 22h59** – lượng giao dịch lớn.
- **Khung giờ thấp điểm**: 6h–10h – nên cân nhắc cắt giảm nhân lực hoặc tạo chương trình kích cầu mini.
📌 **Đề xuất**: Tăng cường nhân sự, khuyến mãi và hoạt động trải nghiệm sản phẩm vào các khung giờ cao điểm.

---
### 🛍️ Doanh thu theo quầy hàng
- **3 quầy dẫn đầu**: Gia dụng, Sữa, Hóa mỹ phẩm – chiếm **trên 71% tổng doanh thu**.
- **Quầy thực phẩm, gia vị, bánh kẹo** có đóng góp thấp – cần đánh giá lại hiệu quả kinh doanh.
📌 **Đề xuất**: Tái cấu trúc không gian trưng bày, tập trung nhiều hơn vào các quầy sinh lời cao.
---
### 🧴 Doanh thu theo sản phẩm
- Top 20 sản phẩm chiếm > 80% doanh thu (hiệu ứng **Pareto** rõ rệt).
- Các sản phẩm chủ lực: **Sữa Ensure**, **Nồi cơm điện Lock&Lock**, **Tã Merries**, **Máy xay sinh tố**…
📌 **Đề xuất**: Tập trung tồn kho, marketing cho nhóm sản phẩm chủ lực. Xem xét loại bỏ các mặt hàng đóng góp <1% doanh thu.
---
### 👥 Doanh thu theo khách hàng
- Nhóm top 20% khách hàng mang lại gần 80% doanh thu.
- Khách hàng chủ lực chỉ chiếm số ít nhưng ảnh hưởng lớn đến hiệu quả kinh doanh.
📌 **Đề xuất**: Chăm sóc đặc biệt cho nhóm khách hàng VIP (ưu đãi thành viên, cá nhân hóa khuyến mãi).
---
## 👨‍💻 Thành viên nhóm

| Họ tên            | Vai trò chính                     |
|------------------|-----------------------------------|
| Bảo Phương       | Phân tích doanh thu, LookerStudio |
| Hải Anh          | Phân tích sản phẩm, Python        |
| Phương Anh       | Phân tích kệ hàng, Power BI       |

