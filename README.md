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

## XÂY DỰNG CÁC THỦ TỤC THEO CÁC CHỨC NĂNG MONG MUỐN
1. Quản lý việc bán hàng
- Thêm, sửa, xoá sản phẩm
- Tìm kiếm sản phẩm, lọc sản phẩm theo các tiêu chí của người quản lý hoặc của khách hàng
- Xem thông tin chỉ tiết mỗi sản phẩm
- Doanh thu của một ngày, một tháng,...
- Số lượng sản phẩm bán chạy nhất.
2. Quản lý kho 
- Thống kê số lượng hàng trong kho
- Báo cáo tình trạng hàng trong kho, số hàng tồn, số hàng đã hết chưa nhập về.

-------------------------
1. Quản lý việc bán hàng
- THÊM SẢN PHẨM:
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/4e620bb6-1d7f-47db-b18c-58df5190091c)

```
---TẠO THỦ TỤC THÊM SẢN PHẨM MỚI
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/3d836c40-b514-4c15-9746-8153337ef4e7)

CREATE PROCEDURE themsanpham
@TenSanPham nvarchar(50),
@ThuongHieu nvarchar(50),
@Mau nvarchar(50),
@ThongSo nvarchar(MAX),
@Gia decimal(10, 2),
@SoLuongConLai int,
@MaDanhMuc nvarchar(50),
@MaNhaCC nvarchar(50)

AS 
BEGIN 
SET NOCOUNT ON;
INSERT INTO SanPham (TenSanPham,ThuongHieu,Mau,ThongSo,Gia,SoLuongConLai,MaDanhMuc,MaNhaCC) 
VALUES (@TenSanPham,@ThuongHieu,@Mau,@ThongSo,@Gia,@SoLuongConLai,@MaDanhMuc,@MaNhaCC);
end
```

- Sử dụng thủ tục:
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/b8ed82c9-e3d0-4ed1-a1ee-8f7512252492)


```
EXEC themsanpham 
    @MaSanPham = 'M12',
    @TenSanPham = N'Laptop A',
    @ThuongHieu = N'BrandX',
    @Mau = N'Den',
    @ThongSo = N'Intel Core i7, 16GB RAM, 512GB SSD',
    @Gia = 1500.00,
    @SoLuongConLai = 10,
    @MaDanhMuc = 'D3',
    @MaNhaCC = 'NCC3';
```
Sản phẩm đã được thêm vào thành công 
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/ca3ba401-4767-4ffd-b23c-ecebb5217ea4)


- XOÁ SẢN PHẨM
  ![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/e1e5e0cf-0152-4115-a957-1c7a60bffb29)

```
CREATE PROCEDURE XoaSanPham
    @MaSanPham NVARCHAR(50)
AS 
BEGIN
    SET NOCOUNT ON;

    BEGIN TRY
        -- Kiểm tra xem sản phẩm có tồn tại hay không
        IF EXISTS (SELECT 1 FROM SanPham WHERE MaSanPham = @MaSanPham)
        BEGIN 
            -- Xóa sản phẩm khỏi bảng SanPham
            DELETE FROM SanPham WHERE MaSanPham = @MaSanPham;
        END 
        ELSE 
        BEGIN
            -- Nếu sản phẩm không tồn tại, đưa ra thông báo lỗi
            RAISERROR('Sản phẩm với MaSanPham = %s không tồn tại.', 16, 1, @MaSanPham);
        END
    END TRY
    BEGIN CATCH
        -- Xử lý lỗi
        DECLARE @ErrorMessage NVARCHAR(4000);
        DECLARE @ErrorSeverity INT;
        DECLARE @ErrorState INT;

        SELECT 
            @ErrorMessage = ERROR_MESSAGE(),
            @ErrorSeverity = ERROR_SEVERITY(),
            @ErrorState = ERROR_STATE();

        RAISERROR (@ErrorMessage, @ErrorSeverity, @ErrorState);
    END CATCH;
END;
```
Thử nghiệm thủ tục
```
EXEC XoaSanPham @MaSanPham = N'M12';
```
Đã Xoá thành công


- CẬP NHẬT SẢN PHẨM
```
---TẠO THỦ TỤC CẬP NHẬT SẢN PHẨM 
CREATE PROCEDURE capnhatsanpham
@MaSanPham nvarchar(50),
@TenSanPham nvarchar(50),
@ThuongHieu nvarchar(50),
@Mau nvarchar(50),
@ThongSo nvarchar(MAX),
@Gia decimal(10, 2),
@SoLuongConLai int,
@MaDanhMuc nvarchar(50),
@MaNhaCC nvarchar(50)

AS
BEGIN
    SET NOCOUNT ON;

    BEGIN TRY
        -- Kiểm tra xem sản phẩm có tồn tại hay không
        IF EXISTS (SELECT 1 FROM SanPham WHERE MaSanPham = @MaSanPham)
        BEGIN 
            -- Cập nhật thông tin sản phẩm
            UPDATE SanPham
            SET 
                TenSanPham = COALESCE(@TenSanPham, TenSanPham),
                ThuongHieu = COALESCE(@ThuongHieu, ThuongHieu),
                Mau = COALESCE(@Mau, Mau),
                ThongSo = COALESCE(@ThongSo, ThongSo),
                Gia = COALESCE(@Gia, Gia),
                SoLuongConLai = COALESCE(@SoLuongConLai, SoLuongConLai),
                MaDanhMuc = COALESCE(@MaDanhMuc, MaDanhMuc),
                MaNhaCC = COALESCE(@MaNhaCC, MaNhaCC)
            WHERE MaSanPham = @MaSanPham;
        END 
        ELSE 
        BEGIN
            -- Nếu sản phẩm không tồn tại, đưa ra thông báo lỗi
            RAISERROR('Sản phẩm với MaSanPham = %s không tồn tại.', 16, 1, @MaSanPham);
        END
    END TRY
    BEGIN CATCH
        -- Xử lý lỗi
        DECLARE @ErrorMessage NVARCHAR(4000);
        DECLARE @ErrorSeverity INT;
        DECLARE @ErrorState INT;

        SELECT 
            @ErrorMessage = ERROR_MESSAGE(),
            @ErrorSeverity = ERROR_SEVERITY(),
            @ErrorState = ERROR_STATE();

        RAISERROR (@ErrorMessage, @ErrorSeverity, @ErrorState);
    END CATCH;
END;
```
Kết quả thực nghiệm thủ tục:
```
EXEC capnhatsanpham
    @MaSanPham = N'K10',
    @TenSanPham = N'LapTop Dell gameming G5',
    @Gia = 1600.00,
	@Mau = 'Gaming',
	@ThongSo = 'i5 1050H',
	@ThuongHieu = 'mau xanh',
    @SoLuongConLai = 8,
	@MaDanhMuc = 'D3',
	@MaNhaCC = 'NCC5';
```
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/9faeace7-6d85-4e0a-afe8-1bb0ba56cc19)

Sản phẩm được cập nhật thành công 

- Xây dựng thủ tục tìm kiếm sản phẩm theo yêu cầu của khách hàng hoặc của người quản lý dựa vào các thông số: Tên Sản Phẩm, Thương Hiệu, Mẫu,....
```
---TẠO THỦ TỤC TÌM KIẾM SẢN PHẨM DỰA VÀO CÁC YÊU CẦU-----
CREATE PROCEDURE timkiemsanpham
    @MaSanPham NVARCHAR(50) = NULL,
    @TenSanPham NVARCHAR(50) = NULL,
    @ThuongHieu NVARCHAR(50) = NULL,
    @Mau NVARCHAR(50) = NULL,
    @ThongSo NVARCHAR(MAX) = NULL,
    @MaDanhMuc NVARCHAR(50) = NULL,
    @MaNhaCC NVARCHAR(50) = NULL
AS
BEGIN
    SET NOCOUNT ON;

    SELECT *
    FROM SanPham
    WHERE 
        (MaSanPham = ISNULL(@MaSanPham, MaSanPham))
        AND (TenSanPham LIKE '%' + ISNULL(@TenSanPham, '') + '%')
        AND (ThuongHieu LIKE '%' + ISNULL(@ThuongHieu, '') + '%')
        AND (Mau LIKE '%' + ISNULL(@Mau, '') + '%')
        AND (ThongSo LIKE '%' + ISNULL(@ThongSo, '') + '%')
        AND (MaDanhMuc = ISNULL(@MaDanhMuc, MaDanhMuc))
        AND (MaNhaCC = ISNULL(@MaNhaCC, MaNhaCC));
END;
```

- Thực nghiệm thủ tục tìm kiếm sản phẩm
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/9be40117-5e99-4d4e-a4a8-209d220166ac)

- XEM THÔNG TIN CHI TIẾT MỖI SẢN PHẨM
```SQL
---- XEM THONG TIN CHI TIET MOI SAN PHAM
CREATE PROCEDURE xemchitietsanpham
    @MaSanPham NVARCHAR(50) = NULL,
    @TenSanPham NVARCHAR(50) = NULL,
    @ThuongHieu NVARCHAR(50) = NULL,
    @Mau NVARCHAR(50) = NULL,
    @ThongSo NVARCHAR(MAX) = NULL,
    @MaDanhMuc NVARCHAR(50) = NULL,
    @MaNhaCC NVARCHAR(50) = NULL

AS
BEGIN 
SET NOCOUNT ON;
SELECT * FROM SanPham WHERE MaSanPham = @MaSanPham;
END
```
Kết quả thực nghiệm:

![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/524fc3b6-62e5-4c1c-895f-22c4165c462c)


- XÂY DỰNG THỦ TỤC TINMHS DOANH THU TRONG 1 NGÀY
```SQL
---- xay dung thu tuc tinh doanh thu 1 ngay
CREATE PROCEDURE xemdoanhthu1ngay
    @Ngay DATE
AS
BEGIN
    SET NOCOUNT ON
    DECLARE @DoanhThu DECIMAL(10, 2);

    SELECT @DoanhThu = SUM(TongTien)
    FROM DonHang
    WHERE NgayDat = @Ngay;

    SELECT @Ngay AS Ngay, ISNULL(@DoanhThu, 0) AS DoanhThu;
END;

```

Kết quả thực nghiệm chương trình
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/8e91cd94-ccd5-41e0-bcfd-bb5f1a118d02)

- XÂY DỰNG THỦ TỤC THỐNG KÊ 

```SQL
-- Tìm sản phẩm bán chạy nhất trong 1 tháng
CREATE PROCEDURE sanphambanchaynhattrongthang
    @Thang INT,
    @Nam INT
AS
BEGIN
    SET NOCOUNT ON; -- Tắt thông báo số bản ghi bị ảnh hưởng

    -- Khai báo biến để lưu ngày bắt đầu và ngày kết thúc của tháng cần thống kê
    DECLARE @StartDate DATE, @EndDate DATE;
    SET @StartDate = DATEFROMPARTS(@Nam, @Thang, 1); -- Ngày đầu tiên của tháng
    SET @EndDate = DATEADD(DAY, -1, DATEADD(MONTH, 1, @StartDate)); -- Ngày cuối cùng của tháng

    -- Sử dụng CTE để tính tổng số lượng sản phẩm bán ra và lấy sản phẩm bán chạy nhất
    WITH BanChayNhat AS (
        SELECT TOP 1
            CT.MaSanPham, -- Mã sản phẩm
            SUM(CT.SoLuong) AS TongSoLuongBan -- Tổng số lượng sản phẩm bán ra
        FROM ChiTietDonHang CT
        INNER JOIN DonHang DH ON CT.MaDonHang = DH.MaDonHang
        WHERE DH.NgayDat >= @StartDate AND DH.NgayDat <= @EndDate -- Điều kiện: Đơn hàng trong tháng
        GROUP BY CT.MaSanPham -- Nhóm theo mã sản phẩm
        ORDER BY SUM(CT.SoLuong) DESC -- Sắp xếp giảm dần theo tổng số lượng bán
    )
    -- Truy vấn để lấy thông tin chi tiết của sản phẩm bán chạy nhất
    SELECT 
        BC.MaSanPham, -- Mã sản phẩm
        SP.TenSanPham, -- Tên sản phẩm
        SP.ThuongHieu, -- Thương hiệu
        SP.Mau, -- Màu sắc
        SP.ThongSo, -- Thông số kỹ thuật
        SP.Gia, -- Giá sản phẩm
        SP.SoLuongConLai -- Số lượng còn lại trong kho
    FROM BanChayNhat BC
    INNER JOIN SanPham SP ON BC.MaSanPham = SP.MaSanPham; -- Liên kết với bảng SanPham để lấy thông tin chi tiết
END;

```
Kết quả thực nghiệm chương trình
![image](https://github.com/ngtuananh24/quanlykhovabanhangCUAHANGLAPTOP/assets/168797690/d8abb7f3-2a8a-4cdd-9743-df641d66e013)













