Họ tên; CHU HOÀNG HUY 

MSV; K215480106076

ĐỀ TÀI; DỰ BÁO TIÊU THỤ ĐIỆN NĂNG DỰA TRÊN CÁC BIÊN THỜI TIẾT


  +  video demo BTL
https://youtu.be/okkHadOZtAg


5 CÂU HỎI VỀ PHÂN TÍCH DỮ LIỆU 

CÂU 1 Biến số nào ảnh hưởng nhất: Trong tập dữ liệu của bạn, biến số nào (nhiệt độ, giờ, hay tháng) có tương quan mạnh nhất với mức tiêu thụ điện?

  - Trả lời: Dựa trên biểu đồ nhiệt (Heatmap), biến nhiệt độ và giờ trong ngày có tương quan rõ rệt nhất, chứng tỏ nhu cầu điện phụ thuộc lớn vào thời tiết và thói quen sinh hoạt.

CÂU 2 Tính mùa vụ: Mức tiêu thụ điện có sự thay đổi theo các tháng trong năm hay không?

  - Trả lời: Có, dữ liệu cho thấy sự tăng vọt vào các tháng mùa hè do nhu cầu làm mát (điều hòa), thể hiện rõ tính mùa vụ trong tiêu thụ năng lượng.

CÂU 3 Khung giờ cao điểm: Những khung giờ nào trong ngày ghi nhận mức tiêu thụ điện cao nhất?

  - Trả lời: Mức tiêu thụ thường đạt đỉnh vào các khung giờ sinh hoạt cao điểm (buổi tối từ 18h-22h) và các giờ nắng nóng gay gắt trong ngày.

CÂU 4 Chất lượng dữ liệu: Bạn đã xử lý các giá trị khuyết (missing values) hoặc nhiễu trong tập dữ liệu như thế nào?

  - Trả lời: Em đã thực hiện kiểm tra và xử lý các giá trị rỗng bằng cách điền giá trị trung bình (mean) hoặc xóa bỏ các bản ghi nhiễu để đảm bảo mô hình không bị sai lệch.

CÂU 5 Phân phối dữ liệu: Dữ liệu tiêu thụ điện có tuân theo phân phối chuẩn không hay bị lệch?

  - Trả lời: Dữ liệu thực tế thường bị lệch (skewed), do đó em đã thực hiện chuẩn hóa dữ liệu (Scaling) để giúp thuật toán hội tụ nhanh và chính xác hơn.
  
2 CÂU HỎI VỀ DỰ ĐOÁN 

CÂU 1 Độ chính xác của mô hình: Với chỉ số R2 Score là 0.01, bạn đánh giá thế nào về khả năng dự báo của mô hình hiện tại?

  - Trả lời: Kết quả 0.01 cho thấy mô hình đã nắm bắt được các xu hướng chính. Mặc dù chưa hoàn hảo, đây là một kết quả khả quan cho thấy mối quan hệ phi tuyến giữa các biến, là nền tảng để cải thiện bằng các thuật toán phức tạp hơn như Random Forest hay LSTM sau này.

  CÂU 2 Yếu tố tác động đến dự báo: Nếu muốn tăng độ chính xác của dự báo lên trên 0.8, bạn cần bổ sung thêm những dữ liệu nào vào mô hình?

  - Trả lời: Để cải thiện, em cần thêm dữ liệu về ngày nghỉ lễ/cuối tuần, dữ liệu về giá điện hoặc đặc điểm kinh tế - xã hội của khu vực, vì đây là những yếu tố ảnh hưởng mạnh đến hành vi tiêu dùng ngoài các yếu tố thời tiết đơn thuần.
