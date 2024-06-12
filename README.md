# CHƯƠNG TRÌNH QUẢN LÝ KHO VÀ BÁN CỦA CỬA HÀNG LAPTOP88
Mô tả bài toán quản lý: Cửa hàng laptop88 là một trong những chuỗi cửa hàng bán laptop lớn và uy tín. Có rất nhiều chi nhánh trên cả nước. Để quản lý chuỗi cửa hàng nhiều như vậy cần sự quản lý thật tốt để đảm bảo lợi nhuận và doanh thu. Giúp tối ưu hoá công việc, giúp báo cáo chính xác về tình hình kinh doanh. Bài tập này sẽ sử dụng ngôn ngữ SQL để quản lý kho nhập - xuất sản phẩm và việc bán hàng của của hàng.

## Những chức năng xây dựng để quản lý kho và bán hàng:
1. Quản lý sản phẩm
- Thêm, sửa đổi, xoá sản phẩm
- Tìm kiến, lọc sản phẩm theo các tiêu chí của người dùng
- Xem thông tin chi tiết từng sản phẩm
- Xem số lượng tồn kho của mỗi sản phẩm
  
2. Quản lý kho
- Khi bán sản phẩm hoặc nhập thêm sản phẩm cập nhật số lượng hàng còn lại trong kho.
- Xem số lượng và thống kê sản phâm hàng tồn kho
## Nhập xuất và báo cáo các thông tin liên quan đến kho và việc bán hàng
1. Nhập hàng:
- Quản lý việc nhập hàng từ nhà cung cấp vào kho hàng.
- Ghi nhận thông tin về sản phẩm, số lượng, giá cả và nhà cung cấp.
- Cập nhật lại số hàng toofn kho sau mỗi lần bán hoặc nhập hàng về.
- Theo dõi đơn hàng từ nhà cung cấp và xác nhận quản lý khi hàng đã vào kho.
2. Xuất hàng:
- Quản lý việc xuất các mặt hàng từ kho hàng để bán cho khách hàng.
- Ghi nhận thông tin về sản phẩm, số lượng, giá cả và thông tin khách hàng.
- Cập nhật tồn kho sau mỗi lần xuất hàng.
- Theo dõi đơn hàng và xác nhận khi đã được giao.
3. Báo cáo
- Báo cáo về doanh thu theo ngày, doanh thu theo tháng,... giúp quản lý được lợi nhuận.
- Tạo và xem báo cáo hoạt động kinh doanh của cửa hàng, số lượng hàng tồn kho nhiều nhất, số lượng hàng bán chạy nhất,....
  
1. Sản phẩm sẽ quản lý những thông tin như: 🔑Mã sản phẩm, tên sản phẩm, thương hiệu, mẫu, thông số, giá, số lượng còn lại.
2. Khách hàng: 🔑Mã khách hàng, tên khách hàng, số điện thoại,địa chỉ.
3. Đơn hàng: 🔑Mã đơn hàng, mã khách hàng, ngày đặt hàng, tổng tiền.
4. Chi tiết đơn hàng: 🔑Mã chi tiết đơn hàng, mã đơn hàng, mã sản phẩm, số lượng, giá.
5. Nhà cung cấp: 🔑Mã nhà cung cấp, tên nhà cung cấp, tên người liên hệ, số điện thoại người liên hệ, địa chỉ.
6. Danh mục: 🔑Mã danh mục, tên danh mục.
7. Giao Dịch kho: 🔑Mã giao dịch, mã sản phẩm, số lượng, ngày giao dịch, loại giao dịch.
   
Như vậy, dựa theo những thông tin mà ta đã thu thập được chúng ta sẽ xây dựng các bảng đáp ứng yêu cầu quản lý của của hàng laptop88.

Tạo các bảng như mô tả trong SQL Sever:
1. Bảng Sản Phẩm
   
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/7859b2ac-35ef-45b4-8565-b449629f3f91)

2. Bảng Khách Hàng

![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/40b42ca9-9d15-4cba-a28e-ae91afa9ed53)

3. Bảng Đơn Hàng 

![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/79c004e4-4187-4dc2-9fe4-95c32e51db23)

4. Bảng Chi tiết đơn hàng

![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/1354b432-1e09-48e9-957c-537298cc097b)

5. Bảng Nhà Cung Cấp

![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/1f87356d-7d0d-49bc-9c33-a3ae00e338ad)

6. Bảng danh mục

![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/d10efd30-6977-44d5-b259-87e511193b6e)

7. Giao dịch kho

![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/ae843c0b-c46d-4650-b062-1435ef5729a6)

Tạo sơ đồ thực thể liên kết giữa các bảng
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/0cb4ae05-4722-4a9f-a839-68f60e8109d7)


Thêm dữ liệu vào các bảng
1. Dữ liệu thêm vào bảng SanPham
```
INSERT INTO SanPham (MaSanPham, TenSanPham, ThuongHieu, Mau, ThongSo, Gia, SoLuongConLai, MaDanhMuc, MaNhaCC) VALUES
('K1', 'Laptop A1', 'BrandA', 'Đen', 'CPU: i5, RAM: 8GB, SSD: 256GB, Màn hình: 14 inch', 15000000, 30, 'D1', 'NCC1'),
('K2', 'Laptop A2', 'BrandA', 'Xám', 'CPU: i7, RAM: 16GB, SSD: 512GB, Màn hình: 15.6 inch', 25000000, 20, 'D1', 'NCC1'),
('K3', 'Laptop B1', 'BrandB', 'Trắng', 'CPU: Ryzen 5, RAM: 8GB, SSD: 512GB, Màn hình: 14 inch', 14000000, 50, 'D2', 'NCC2'),
('K4', 'Laptop B2', 'BrandB', 'Đen', 'CPU: Ryzen 7, RAM: 16GB, SSD: 1TB, Màn hình: 15.6 inch', 27000000, 15, 'D2', 'NCC2'),
('K5', 'Laptop C1', 'BrandC', 'Xanh', 'CPU: i3, RAM: 4GB, HDD: 1TB, Màn hình: 14 inch', 10000000, 40, 'D1', 'NCC3'),
('K6', 'Laptop C2', 'BrandC', 'Đỏ', 'CPU: i5, RAM: 8GB, SSD: 256GB, Màn hình: 14 inch', 18000000, 25, 'D1', 'NCC3'),
('K7', 'Laptop D1', 'BrandD', 'Đen', 'CPU: Ryzen 5, RAM: 8GB, SSD: 512GB, Màn hình: 14 inch', 16000000, 35, 'D3', 'NCC4'),
('K8', 'Laptop D2', 'BrandD', 'Xám', 'CPU: i7, RAM: 16GB, SSD: 1TB, Màn hình: 15.6 inch', 29000000, 10, 'D3', 'NCC4'),
('K9', 'Laptop E1', 'BrandE', 'Trắng', 'CPU: i5, RAM: 8GB, SSD: 256GB, Màn hình: 14 inch', 17000000, 20, 'D2', 'NCC5'),
('K10', 'Laptop E2', 'BrandE', 'Đen', 'CPU: Ryzen 7, RAM: 16GB, SSD: 1TB, Màn hình: 15.6 inch', 30000000, 15, 'D2', 'NCC5'); 
```

2. Dữ liệu thêm vào bảng Khach Hang
```
INSERT INTO KhachHang (MaKhachHang, TenKhachHang, DiaChi, SoDienThoai) VALUES ('KH1', 'Nguyễn Văn Anh', 'Số 123, Đường ABC, Quận XYZ, Thành phố HCM', '0123456789'),
('KH2', 'Trần Thị Bình', 'Số 456, Đường DEF, Quận UVW, Thành phố Hanoi', '0987654321'),
('KH3', 'Lê Văn Cung', 'Số 789, Đường GHI, Quận RST, Thành phố Đà Nẵng', '0365478921'),
('KH4', 'Phạm Thị Dung', 'Số 012, Đường JKL, Quận MNO, Thành phố Hải Phòng', '0932145678');
```
3. Dữ liệu thêm vào bảng đơn hàng

```
INSERT INTO DonHang (MaDonHang, MaKhachHang, NgayDat,TongTien)
VALUES
('DH1', 'KH1', '2024-06-12','100000'),
('DH2', 'KH2', '2024-06-13','123456'),
('DH3', 'KH3', '2024-06-14','245654'),
('DH4', 'KH4', '2024-06-15','135768');
```
4. Thêm dữ liệu vào bảng ChiTietDonHang
```
INSERT INTO ChiTietDonHang(MaChiTietDonHang,MaDonHang,MaSanPham,SoLuong,Gia)
VALUES 
('M10', 'DH1', 'K1', 2, 15000000),
('M11', 'DH1', 'K2', 1, 25000000),
('M12', 'DH2', 'K3', 3, 14000000),
('M13', 'DH3', 'K4', 1, 27000000),
('M14', 'DH3', 'K5', 2, 10000000),
('M15', 'DH4', 'K6', 1, 18000000);
```
5. Thêm dữ liệu vào bảng NhaCungCap
```
INSERT INTO NhaCungCap (MaNhaCC, TenNCC, TenNguoiLienHe, DiaChi) VALUES
('NCC1', N'Công ty A', N'Nguyễn Văn A', N'123 Đường ABC, Quận XYZ, Thành phố HCM'),
('NCC2', N'Công ty B', N'Trần Thị B', N'456 Đường DEF, Quận UVW, Thành phố Hanoi'),
('NCC3', N'Công ty C', N'Lê Văn C', N'789 Đường GHI, Quận RST, Thành phố Đà Nẵng');
```
6. Thêm dữ liệu vào bảng Danh Mục
```
INSERT INTO DanhMuc(MaDanhMuc,TenDanhMuc) VALUES
('D1','Danh muc 1'),
('D2','Danh muc 2'),
('D3','Danh muc 3');
```

8. Thêm dữ liệu vào bảng GiaoDichKho
```
INSERT INTO GiaoDichKho(MaGiaoDichKho,MaSanPham,SoLuong,NgayGiaoDich,LoaiGiaoDich,MaNCC) VALUES
('GD1', 'K1', 10, '2024-06-12', N'Nhập hàng', 'NCC1'),
('GD2', 'K2', 5, '2024-06-13', N'Nhập hàng', 'NCC2'),
('GD3', 'K3', 8, '2024-06-14', N'Nhập hàng', 'NCC3'),
('GD4', 'K4', 15, '2024-06-15', N'Nhập hàng', 'NCC1'),
('GD5', 'K5', 20, '2024-06-16', 'Nhập hàng', 'NCC2'),
('GD6', 'K6', 12, '2024-06-17', 'Nhập hàng', 'NCC3'),
('GD7', 'K7', 25, '2024-06-18', 'Nhập hàng', 'NCC1'),
('GD8', 'K8', 18, '2024-06-19', 'Nhập hàng', 'NCC2');
```








