# TTM-64HTTT1
ỨNG DỤNG MẠNG NƠRON MỜ TRONG DỰ ĐOÁN KHÁCH HÀNG TRUNG THÀNH DỰA TRÊN ĐẶC ĐIỂM NHÂN KHẨU HỌC VÀ HÀNH VI
------
- Giảng viên hướng dẫn: TS. Trần Mạnh Tuấn
- Sinh viên: Nguyễn Thị Phương Anh, Nguyễn Thị Thanh Hải
- Lớp: 64HTTT4
---
Trong những năm gần đây, với sự phát triển nhanh chóng của thương mại điện tử và chuyển đổi số, nhu cầu nghiên cứu hành vi tiêu dùng và duy trì khách hàng trung thành trở nên ngày càng cấp thiết đối với doanh nghiệp. Khách hàng trung thành không chỉ giúp giảm chi phí marketing, duy trì doanh thu ổn định mà còn là nguồn lan tỏa thương hiệu hiệu quả thông qua các kênh truyền miệng và mua lại thường xuyên.
Tuy nhiên, việc nhận diện và dự đoán khách hàng trung thành không phải là bài toán đơn giản, bởi nó chịu ảnh hưởng từ nhiều yếu tố như độ tuổi, giới tính, thu nhập, lịch sử mua sắm, hành vi phản hồi, mức độ tương tác,... Các mô hình phân tích truyền thống gặp hạn chế trong việc xử lý các dữ liệu phi tuyến tính, không đầy đủ hoặc có tính mơ hồ. Do đó, cần thiết phải có các phương pháp học máy linh hoạt và có khả năng thích ứng cao. 
Mạng nơ ron mờ (Fuzzy Neural Network - FNN), là sự kết hợp giữa mạng nơ ron nhân tạo và logic mờ, được xem là một trong những hướng tiếp cận hiệu quả trong bài toán dự đoán hành vi và phân loại khách hàng. Nghiên cứu của Wang và cộng sự cho thấy rằng FNN có khả năng mô hình hóa hành vi tiêu dùng và cải thiện độ chính xác trong dự đoán khách hàng trung thành lên đến 92% trong môi trường thương mại điện tử [1]. Tại Việt Nam, các nghiên cứu cũng chỉ ra rằng việc ứng dụng mô hình dự đoán dựa trên hành vi và nhân khẩu học giúp doanh nghiệp hiểu rõ hơn về nhu cầu khách hàng và nâng cao hiệu quả chiến lược tiếp thị 
---
Bộ dữ liệu được công bố trong DAZONE - Cuộc thi Phân Tích Dữ Liệu, dữ liệu được thu thập gồm hơn 50 triệu bản ghi, từ khoảng 5000 cửa hàng, hơn 200 nghìn khách hàng và hơn 1 triệu sản phẩm. Bộ dữ liệu là thông tin tổng hợp của khách hàng từ một sàn thương mại điện thử trong một khoảng thời gian cố định, bao gồm: Danh sách các gian hàng (merchants), thông tin người dùng, lịch sử hành vi người dùng với các gian hàng như xem sản phẩm, mua hàng,v.v… theo thời gian.
---
- raw data: https://www.kaggle.com/datasets/rmxrmx8112/dazone-2025
- notebook (anfis): https://www.kaggle.com/code/rmxrmx8112/btl-ttm-fuzzy-neuron-network
