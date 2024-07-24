# Database management systems 
Đồ án cuối kì: 
Thành viên nhóm:
1. Nguyễn Tiến Luyện (C) - 22IT3
2. Nguyễn Phương Thảo    - 22IT3
3. Phùng Thị Linh        - 22IT3
4. Hoàng Thị Duyên       - 22IT1
# Mô tả nghiệp vụ:
- Quản lí nhập xuất các thực đơn , bàn, khu vực, thống kê doanh thu, quản lí nhân viên.
- Một nhà hàng có nhiều khu vực được lưu trữ thông tin bởi: Mã khu vực, Tên khu vực, Trạng thái. Trong mỗi khu vực có các bàn ăn được lưu trữ thông tin bởi: Mã bàn, Tên Bàn, Trạng thái
- Mỗi nhân viên sở hữu một tài khoản quản lý để đăng nhập vào hệ thống. Các thông tin về tài khoản được lưu trữ bởi: Mã tài khoản, Loại tài khoản, Tên tài khoản , Mật khẩu. Các thông tin về nhân viên gồm: Mã nhân viên, Tên nhân viên, điện thoại, Ngày sinh, Địa chỉ, Vị trí.
- Nhà hàng có các thực đơn dạng Combo (không kinh doanh dạng mô hình từng món) thuộc danh mục thực đơn nhất định với danh mục lưu trữ bởi: Mã danh mục, Tên danh mục. Khách hàng sẽ được gọi các Combo theo ý muốn. Thông tin thực đơn sẽ được lưu trữ bởi: Mã, Tên, Số lượng tồn, Giá. 
- Nhân viên sẽ ghi lại những món khách hàng đã gọi và được ghi lại trong một phiếu gọi món định dạng bởi: Mã, số lượng. Trên mỗi phiếu gọi món có ghi số bàn, ngày và tên nhân viên order bàn đó. Nếu khách hàng gọi thêm món thì nhân viên ghi thêm 1 phiếu mới, vẫn ghi số bàn, ngày và tên mình.
- Nhân viên thu ngân tính tiền các thực đơn mà khách hàng đã gọi, in hóa đơn, trên hóa đơn thanh toán có ghi ngày giờ thanh toán và tên nhân viên order. 
- Nhân viên order đem hóa đơn đó cho khách, nếu khách không có gì thắc mắc thì khách trả tiền cho nhân viên, nhân viên đem tiền và hóa đơn vào cho quầy thu ngân, nhân viên thu ngân đóng dấu đã thanh toán vào hóa đơn.
# Xác định thực thể - thuộc tính:
![image](https://github.com/user-attachments/assets/c42b9a7f-00cf-4e22-bcbd-b574f3eaef81)
# Mô hình thực thể liên kết
![image](https://github.com/user-attachments/assets/f10a6484-d26d-4f81-9694-16f207dca56d)



