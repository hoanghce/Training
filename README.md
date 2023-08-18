# Chapter 1: GIỚI THIỆU VỀ DAX
## 1.1. Ngôn ngữ DAX là gì ?
- DAX – Data Analysis Expressions là ngôn ngữ chính được sử dụng trong Power BI Desktop, Power Pivot cho Excel, SSAS Tabular models trong Microsoft SQL Server
- DAX là một ngôn ngữ dùng để giao tiếp với Semantic Model hay Data Model. Để tính toán các KPI hay dùng cho phân tích thống kê các chỉ số.
- Bởi vì là ngôn ngữ dùng để phân tích dữ liệu. Do đó DAX không nên được sử dụng cho mục đích processing data mặc dù có thể ứng dụng tạo các Table trong Power Pivot/ Power BI….


## 1.2. Những môi trường có thể ứng dụng DAX
![image](https://github.com/hoanghce/Training_DKSH/assets/87324837/e4d3f8e4-96fd-4333-af04-0f208371d359)

## 1.3. Từ business logic đến systax trong DAX 
![image](https://github.com/hoanghce/Training_DKSH/assets/87324837/0755ada6-1266-439a-85bc-2c97f4a5cbfa)

## 1.4. Sự tương đồng giữa DAX và SQL

# Chapter 2: NGỮ CẢNH TRONG DAX
## 2.1. Row Context
## 2.2. Evaluation Context
## 2.3. Filter Context

# Chapter 3: CÁC HÀM BỎ BỘ LỌC TRONG DAX
## 3.1. Các loại Filter
## 3.2. Các hàm bỏ bộ lọc
- ALL, ALLSELECTED, REMOVEFILTERS, ALLEXCEPT
# Chapter 4: CÁC LOẠI HÀM BẢNG TRONG DAX
## 4.1. Các hàm tạo bảng ảo
 - SUMMARIZE, ADDCOLUMNS, SELECTCOLUMNS, FILTER, GROUPBY
## 4.2. Các hàm liên quan đến bộ lọc

# BÀI TẬP:
<strong> 1. Trong mỗi năm xem mỗi category đóng góp bao nhiêu % doanh thu? ? </strong>
   - Doanh Thu = Sales[Net Price] * Sales[Quantity]

 ![image](https://github.com/hoanghce/Training_DKSH/assets/87324837/801f9b88-41c9-4001-a8af-454eb84b5598)

<strong> 2. Tính toán như câu 1 nhưng bây giờ kéo thêm cột Promotion Category trong bảng Promotion (Lưu ý không chia theo Promotion Category và kết quả vẫn như câu 1) ? </strong>


   ![image](https://github.com/hoanghce/Training_DKSH/assets/87324837/a7b51f9a-659a-499f-a6d6-4bcde9177676)




