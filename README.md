# Customer Management MVC

Ứng dụng quản lý khách hàng dùng Servlet, JSP, JSTL và kiến trúc MVC. Hỗ trợ hiển thị danh sách, thêm, sửa, xóa và xem chi tiết khách hàng. Dữ liệu được lưu trong Map tĩnh để mô phỏng cơ sở dữ liệu.

## Chạy

```powershell
mvn clean package
```

Deploy `target/customer-management.war` lên Tomcat 10.1+ và truy cập `/customer-management/customers`.
