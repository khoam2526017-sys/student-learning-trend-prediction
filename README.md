# ỨNG DỤNG HỌC MÁY TRONG DỰ ĐOÁN XU HƯỚNG HỌC TẬP TRỰC TUYẾN CỦA SINH VIÊN

## 1. Giới thiệu đề tài
Các hệ thống quản lý học tập (LMS) lưu trữ lượng lớn dữ liệu tương tác của sinh viên như thời gian truy cập, tiến độ nộp bài và điểm kiểm tra. Dự án này ứng dụng các thuật toán Học máy (Machine Learning) để phân tích hành vi học tập trực tuyến và dự đoán sớm nguy cơ rớt môn hoặc giảm sút kết quả học tập.

## 2. Mục tiêu nghiên cứu
* Khai thác và tiền xử lý dữ liệu nhật ký học tập (log data) từ hệ thống học trực tuyến.
* So sánh độ chính xác giữa các mô hình phân loại phổ biến gồm **Decision Tree**, **Random Forest** và **Logistic Regression**.

## 3. Phương pháp thực hiện
* **Tập dữ liệu:** Dữ liệu tương tác học tập trực tuyến gồm 3.000 hồ sơ sinh viên, chia tỷ lệ 80% huấn luyện – 20% kiểm thử.
* **Quy trình:** Làm sạch dữ liệu & chuẩn hóa đặc trưng (*Pandas, Scikit-learn*) $\rightarrow$ Huấn luyện mô hình phân loại $\rightarrow$ Đánh giá qua *Accuracy, Precision, Recall* và *F1-score*.

## 4. Kết quả chính
* Mô hình **Random Forest** cho kết quả dự đoán tốt nhất với **Accuracy đạt 91.4%** và **F1-Score đạt 90.8%**, vượt trội hơn Decision Tree (86.2%) và Logistic Regression (84.5%).

## 5. Cấu trúc thư mục
* `data/`: Dữ liệu hành vi học tập thô và dữ liệu đã làm sạch.
* `src/`: Mã nguồn huấn luyện mô hình dự đoán.
* `docs/`: Tài liệu báo cáo thực hành.
* `results/`: Bảng số liệu và biểu đồ đánh giá mô hình.

## 6. Giấy phép sử dụng (License)
Dự án này được phát hành theo giấy phép **GNU General Public License v3.0 (GPLv3)**. Xem chi tiết tại tệp [LICENSE](./LICENSE).# student-learning-trend-prediction
