# TELEHEALTH_COMPREHENSIVE_PLATFORM
Business Analysis artifacts for Telehealth Comprehensive Platform project.
ĐỀ BÀI DỰ ÁN: XÂY DỰNG HỆ THỐNG ĐẶT LỊCH VÀ KHÁM BỆNH TỪ XA 
1. Bối cảnh dự án
Một chuỗi phòng khám đa khoa quốc tế muốn chuyển đổi số bằng cách xây dựng hệ thống Telehealth (gồm Mobile App cho bệnh nhân và Web Portal cho bác sĩ/quản trị viên). Mục tiêu nhằm giảm tải thời gian chờ đợi tại phòng khám, kết nối bác sĩ với bệnh nhân từ xa qua cuộc gọi video, và quản lý hồ sơ bệnh án điện tử tập trung.
2. Các yêu cầu nghiệp vụ chính 
Bệnh nhân: Đăng ký tài khoản, tìm kiếm bác sĩ theo chuyên khoa/mức giá, đặt lịch khám, thanh toán trực tuyến, tham gia cuộc gọi video với bác sĩ, và xem đơn thuốc điện tử.
Bác sĩ: Quản lý lịch hẹn trống, nhận cuộc gọi khám từ xa, ghi chú bệnh án (EMR), và kê đơn thuốc số.
Quản trị viên (Admin): Quản lý danh mục bác sĩ, phê duyệt lịch làm việc, xem báo cáo doanh thu và quản lý cấu hình hệ thống.
KẾT QUẢ MONG ĐỢI
1. Requirement Artifacts
Tài liệu BRD (Business Requirements Document): Xác định rõ mục tiêu chiến lược, phạm vi dự án (In-scope/Out-of-scope), và các chỉ số đo lường thành công (KPIs).
Tài liệu SRS (Software Requirement Specification): Mô tả chi tiết các yêu cầu chức năng (Functional) và phi chức năng (Non-functional như bảo mật dữ liệu y tế, hiệu năng video call).
Ma trận truy vết yêu cầu (Requirement Traceability Matrix - RTM): Bảng liên kết từ mục tiêu kinh doanh đến các tính năng cụ thể để đảm bảo không bỏ sót yêu cầu.
2. Mô hình hóa quy trình 
Sơ đồ luồng công việc (As-is & To-be Process Map): Vẽ sơ đồ quy trình khám bệnh thủ công hiện tại và quy trình khám bệnh từ xa mới bằng chuẩn BPMN 2.0.
Sơ đồ Use Case (Use Case Diagram): Phân định rõ vai trò và quyền hạn của 3 nhóm đối tượng: Bệnh nhân, Bác sĩ, và Quản trị viên.
3. Functional Analysis
Tài liệu mô tả Use Case (Use Case Specifications): Viết chi tiết cho tính năng cốt lõi là "Đặt lịch khám và thanh toán", bao gồm luồng đi chính (Main flow), luồng rẽ nhánh (Alternative flow), và luồng ngoại lệ (Exception flow - ví dụ: Thanh toán thất bại).
Danh sách Product Backlog & User Stories: Bộ danh sách các câu chuyện người dùng viết theo chuẩn As a... I want to... So that... kèm tiêu chí nghiệm thu (Acceptance Criteria) rõ ràng cho đội lập trình.
4. Wireframes & Data
Wireframe/Mockup mức thấp (Low-fidelity Wireframe): Bản phác thảo giao diện luồng đặt lịch trên Mobile App nhằm làm việc với UI/UX designer.
Từ điển dữ liệu (Data Dictionary) hoặc Sơ đồ ERD: Định nghĩa các trường thông tin bắt buộc phải lưu trữ (Ví dụ: Thông tin Bác sĩ gồm Tên, Chuyên khoa, Số năm kinh nghiệm, Giá khám).


