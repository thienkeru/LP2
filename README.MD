# Hệ thống quản lí Cafe
- Đề bài: Hệ thống quản lí Cafe
- Hồ sơ phân tích hệ thống:
    
    ## Khách hàng: 
    - Trực tiếp đến quán cafe
    - Gọi đặt bàn, cọc tiền
    - Gọi hủy đặt bàn
	## Phục Vụ:
    - Tìm bàn trống đưa khách vào
    - Đăng nhập hệ thống tiếp nhận order từ khách và lập hóa đơn 
    - Nếu khách đặt bàn sẽ tìm bàn trống và thông báo cho khách, ghi lại thời gian cụ thể mà khách muốn đặt.
    -  Tính tiền in hóa đơn

    ## Người thủ kho: 
    - Chịu trách nhiệm tạo phiếu nhập hàng khi hàng được nhập về, tạo phiếu xuất hàng khi hàng được bán cho khách, kiểm kê hàng trong kho, tạo phiếu trả hàng nếu hàng không đạt yêu cầu
    ## Người Quản Lý:
    - là người nắm tình hình mua bán, doanh thu của nhà hàng, quản lí nhân viên. Việc thống kê được thực hiện hàng tháng, hàng năm, và có thể thống kê đột xuất.
## Hệ thống User Case:
- Phục vụ Cafe: 
    + Đăng nhập, order
    + Tìm bàn trống để đặt bàn, nhận tiền cọc ( nếu có )
    + lập hóa đơn thanh toán
-  Người thủ kho:

    + tạo phiếu xuất kho
    + kiểm kê hàng trong kho
    + tạo phiếu trả hàng
- Người quản lý:
    + tạo các báo cáo về doanh thu, tình hình mua bán của nhà hàng từng tháng, năm và có thể đột xuất
    + Quản lí nhân viên ( chấm công, thưởng, phạt .vv…)

## Các Chức Năng Chính
    1.  Chức năng quản lý danh mục
    2.  Chức năng quản lý hàng hóa
    3.  Chức năng quản lý danh mục bàn , khu vực
    4.  Chức năng quản lý kho hàng
    5.  Chức năng quản lý bàn
    6.  Chức năng quản lý nhập xuất
    7.  Chức năng quản lý chi tiết công nợ
    8.  Chức năng quản lý quỹ tiền mặt
    9.Chức năng quản lý người dùng
    10. Hỗ trợ thiết bị và công nghệ
    11. Hệ thống báo cáo
    12. Chức năng kiểm kê hàng hóa
    13. Chức năng sao lưu dữ liệu

## CHI TIẾT CÁC CHỨC NĂNG PHẦN MỀM  QUẢN   LÝ NHÀ HÀNG
1. Quản lý danh mục
    - Cho phép người dùng tự thiết lập hệ thống danh mục theo đặc thù đơn vị
    - Danh mục bàn
    - Danh mục nhóm món ăn, nhóm đồ uống
    - Danh mục khách hàng thân thiết
    - Danh mục đối tượng công nợ
    - Danh mục nhân viên

2. QUẢN LÝ HÀNG HÓA
    - Cho phép phân nhóm hàng hóa dễ dàng quản lý
    - Quản lý thông tin xuất xứ của hàng hóa
    - Quản lý giá nhập xuất hàng hóa linh hoạt và chính xác
    - Quản lý hàng tồn kho
    - Quản lý định mức nguyên vật liệu
    - Truy vấn tìm kiếm hàng tồn kho
    - Truy vấn tìm kiếm thông tin nhà cung cấp hàng hóa

3. QUẢN LÝ DANH MỤC BÀN, KHU VỰC
    - Cho phép phân nhóm loại bàn
    - Quản lý giá bán cụ thể theo loại bàn, mặc định giá bán theo khu vực
    - Không giới hạn số lượng bàn , khu vực
    - Cho phép thay đổi giá linh hoạt

4. QUẢN LÝ KHO HÀNG
    - Quản lý hàng nhập hàng ngày
    - Tự động cộng kho khi có phát sinh nhập hàng
    - Tự động hiển thị hàng tồn khi có phát sinh
    - Truy vấn tìm kiếm hàng tồn dễ dàng nhanh chóng
    - Hỗ trợ kiểm hàng nhanh chóng chính xác
    - Cảnh báo số lượng hàng khi dưới mức tồn tối thiểu
5. QUẢN LÝ BÁN
    - Thao tác đơn giản, cho phép sử dụng phím tắt 
    - Quản lý tình trạng bàn trống, bàn đang có khách
    - Quản lý thực đơn theo từng bàn
    - Hiển thị giờ vào giờ ra của khách hàng
    - Cho phép ghép bàn, chuyển bàn dễ dàng nhanh chóng
    - Tự động thống kê tiền bàn, tiền giờ theo ca làm việc của nhân viên
- Hỗ trợ thu ngân tính tiền, thối tiền, tổng tiền.
6. QUẢN LÝ NHẬP XUẤT
    - Quản lý chi tiết hàng hóa nhập mua
    - Quản lý chi tiết hàng hóa của từng nhà cung cấp
    - Quản lý thông tin xuất xứ của hàng hóa
    - Tự động cập nhật công nợ nhà cung cấp
    - Tự động hiển thị công nợ nhà cung cấp
    - Cho phép thanh toán tiền hàng theo từng hóa đơn mua hàng 
7. QUẢN LÝ CÔNG NỢ
    - Tự động hiển thị công nợ cũ của cùng đối tượng công nợ
    - Cho phép thanh toán công nợ linh hoạt
    - Báo cáo chi tiết công nợ của từng nhà cung cấp
    - Báo cáo tổng hợp công nợ phải trả 
8. QUẢN LÝ QUỸ TIỀN MẶT
    - Tự động tạo phiếu thu tiền mặt khi khách hàng thanh toán tiền
    - Tự động tạo phiếu chi tiền mặt khi thanh toán tiền mua hàng
    - Tự động bù trừ công nợ khi thanh toán tiền cho nhà cung cấp
    - Quản lý chi tiết các khoản thu chi hàng ngày của đơn vị
    - Hỗ trợ nhân viên thu ngân bàn giao sau mỗi ca làm việc 
9. QUẢN LÝ NGƯỜI DÙNG
    - Cho phép người dùng làm việc theo vị trí quyền hạn
    - Mỗi tương tác của người dùng đều được ghi nhận vào lịch sử
    -   Mỗi người dùng có tài khoản làm việc riêng
    - Cho phép người dùng tự quản lý tài khoản của mình
    - Cấp quyền xem báo cáo thống kê, quyền xem xóa sửa dữ liệu cho từng nhân viên
-  Dễ dàng theo dõi đánh giá và kiểm soát công việc của nhân viên
10. HỔ TRỌ THIẾT BỊ CÔNG NGHỆ
    - Phần mềm hỗ trợ đầu đọc mã vạch và máy in mã vạch thông dụng trên thị trường
    - Phần mềm hỗ trợ tất cả các loại máy in thông dụng (in thường, in kim, in bill…) 
11. HỆ THỐNG BÁO CÁO: 
    - Hệ thống báo cáo được thiết kế dựa trên sự ảnh hưởng của hoạt động hàng ngày và yêu cầu của nhà quản lý.
    - Báo cáo hàng xuất - nhập - tồn kho
    - Báo cáo công nợ
    - Báo cáo doanh thu
    - Nhiều báo cáo, thống kê và biểu đồ phân tích 
    - Tất cả báo cáo được xuất ra các tập tin định dạng thông dụng: Word, Excel, PDF...
12. KIỂM KÊ HÀNG HÓA:
    - Hỗ trợ kiểm kê kho nhanh chóng chính xác
    -  Kiểm kê kho hàng hoặc kiểm kê theo nhóm hàng trong kho
    -  Cho phép đối chiếu số liệu phần mềm - sổ sách dễ dàng
    -  Cho phép sửa số liệu kiểm kê trong phần mềm tương ứng với sổ sách
    - Cho phép xuất file excel báo cáo lưu trữ
13. SAO LƯU DỮ LIỆU: 
    - Chức năng sao lưu dữ liệu hỗ trợ việc bảo mật và an toàn dữ liệu
    - Cho phép người dùng tự thiết lập chế độ sao lưu dữ liệu
    - Dữ liệu sao lưu được lưu trữ ở nơi chứa chương trình nguồn
    - Dữ liệu sao lưu tự động theo ngày giờ thực trên hệ thống
    - Dữ liệu được sao lưu vào đầu hoặc cuối mỗi phiên làm việc







