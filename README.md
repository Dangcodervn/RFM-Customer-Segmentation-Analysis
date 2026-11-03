# RFM Customer Segmentation Analysis

Phân tích và phân khúc khách hàng theo phương pháp **RFM (Recency – Frequency – Monetary)**, thực hiện trong khuôn khổ khóa học Data Analyst.

## Mục tiêu

Dựa trên lịch sử giao dịch của khách hàng, tính toán 3 chỉ số:

- **Recency (R):** số ngày kể từ lần mua gần nhất
- **Frequency (F):** tần suất mua hàng
- **Monetary (M):** tổng giá trị chi tiêu

Từ đó chấm điểm (rank) từng chỉ số và phân khách hàng vào các nhóm để hỗ trợ ra quyết định marketing/chăm sóc khách hàng.

## Phân khúc khách hàng

Dữ liệu sau phân tích được chia thành 5 nhóm:

| Nhóm | Ý nghĩa |
|---|---|
| VIP | Khách hàng giá trị cao nhất, mua thường xuyên và gần đây |
| Loyal | Khách hàng trung thành |
| Potential | Khách hàng tiềm năng |
| Vang lai | Khách hàng vãng lai |
| Sap mat | Khách hàng có nguy cơ rời bỏ |

## Nội dung repo

| File | Mô tả |
|---|---|
| `RFMdata.csv` | Dữ liệu khách hàng đã tính điểm RFM (~114,000 dòng): `CustomerID`, `recency`, `frequency`, `monetary`, rank tương ứng (`rn_recency`, `rn_frequency`, `rn_monetary`), điểm `R`/`F`/`M` và nhãn phân khúc `RFM` |
| `RFMreport.pbix` | Báo cáo trực quan hóa (Power BI) |
| `RFM analytical report.docx` / `.pdf` | Báo cáo phân tích chi tiết |

## Công cụ sử dụng

- Power BI (dựng dashboard, DAX)
- Excel/SQL cho xử lý và tính toán dữ liệu
