# Dự án Đảm bảo Chất lượng (QA) - Hệ thống Quản lý Chuỗi Cafe (SaaS)


## Giới thiệu dự án

Đây là dự án cá nhân nhằm áp dụng các kỹ năng kiểm thử phần mềm (Software Testing) vào một hệ thống giả định: Hệ thống quản lý chuỗi quán Cafe theo mô hình Multi-Tenant SaaS. 



Dự án bao phủ toàn bộ vòng đời kiểm thử (STLC) từ việc phân tích tài liệu Đặc tả yêu cầu (SRS), thiết kế Test Case, cho đến kiểm thử giao diện (UI) và kiểm thử API.



## Mục tiêu kiểm thử (Testing Objectives)

**Manual Testing:** Đảm bảo tính logic của nghiệp vụ bán hàng, trừ kho tự động và phân quyền RBAC.

**API Testing:** Xác thực tính toàn vẹn của dữ liệu và các status code trả về từ hệ thống backend.

**Security Testing:** Kiểm tra rủi ro truy cập chéo dữ liệu giữa các Chi nhánh (Tenants).



## Công cụ sử dụng (Tools \& Technologies)

**Phân tích & Thiết kế Test Case:** Google Sheets, MS Excel.

**Quản lý lỗi (Bug Tracking):** Jira Software.

**Kiểm thử API:** Postman.

**Thiết kế sơ đồ:** UML / Draw.io.



## Chi tiết các tài liệu (Artifacts)

* [Đặc tả yêu cầu hệ thống (SRS)](link\_đến\_thư\_mục\_01)

* [Kịch bản kiểm thử (Test Cases)](link\_đến\_thư\_mục\_03): Bao gồm 50+ Test cases cho phân hệ Bán hàng (POS) và Phân quyền.

* [Báo cáo lỗi (Bug Reports)](link\_đến\_thư\_mục\_04): Danh sách các lỗi logic tìm thấy trong quá trình kiểm thử tĩnh (Static Testing).

* [Bộ kiểm thử API (Postman Collection)](link\_đến\_thư\_mục\_05): Chứa các Request giả lập luồng Thanh toán và Quản lý Kho.



## Bài học rút ra (Lessons Learned)

* Nắm vững kỹ thuật thiết kế Test Case: Phân vùng tương đương, Phân tích giá trị biên.

* Hiểu sâu về kiến trúc Multi-Tenant và cách kiểm thử bảo mật phân quyền.

