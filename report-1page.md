# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- 
- 

**CIA mapping:**
- Sự cố A -> Confidentiality (Lộ dữ liệu người dùng)
- Sự cố B -> Integrity (Dữ liệu bị sửa đổi trái phép)
- Sự cố C -> Availability (Hệ thống bị sập / không truy cập được)

**Phân tích sự cố B:**
- Threat: Hacker tấn công và thay đổi dữ liệu (SQL Injection, tấn công nội bộ, v.v.)
- Vulnerability: Không kiểm tra input, thiếu validation, phân quyền kém
- Mitigation: Sử dụng prepared statements (chống SQL Injection)
Kiểm tra và validate dữ liệu đầu vào
Phân quyền người dùng rõ ràng
Log và giám sát hệ thống

### 4. Kết luận ngắn
(4-6 dòng: em học được gì từ bài lab này, phần nào khó nhất, điều gì cần chú ý khi phân tích một sự cố an toàn thông tin.)
Qua bài này, em hiểu rõ hơn về tầm quan trọng của bảo mật trong hệ thống thông tin. Ba yếu tố CIA (Confidentiality, Integrity, Availability) giúp đánh giá và phân loại các rủi ro một cách rõ ràng. Việc xác định assets giúp biết được cái gì cần bảo vệ trước tiên. Ngoài ra, phân tích threat và vulnerability giúp tìm ra nguyên nhân gốc rễ của sự cố. Từ đó, có thể đề xuất các biện pháp mitigation phù hợp để giảm thiểu rủi ro. Đây là kiến thức quan trọng khi thiết kế và vận hành hệ thống phần mềm.
