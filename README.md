[I. Các bước chạy](#Modau)


[I. hai](#Modau1)
<a name="Modau1"></a>
1.Các bước để chạy CT Quản lý Giaó Viên


1.1tải tập tin QLGV.sql về và sử dụng  SQL SERVER,(KHUYẾN KHÍCH SỬ DỤNG SQL 2012 TRỞ LÊN )

Mở tập tin vừa tải lên 

copy dòng lệnh đầu tiên ấn excute để tạo database , và bôi đen dòng còn lại và excute tiếp

![image](https://github.com/taochangbang123/bt1/blob/master/CHAY%20SQL.png?raw=true)

 1.2Qua phần mềm visual studio  ( khuyến khích sử dụng VS từ 2017 )

 mở file visual tải lên , mở file visual studio  và chạy chương trình , Người dùng ấn start để chạy CT
 
![image](https://github.com/taochangbang123/bt1/blob/master/BAT%20DAU%20CT.png?raw=true)

CT sẽ được chạy .





2.Sử dụng CT

2.1 Sau khi start CT hiển thị như sau : 

![image](https://github.com/taochangbang123/bt1/blob/master/KET%20NOI%20DU%20LIEU.png?raw=true)

(1)Nhập tên máy là sever máy ở SQL của bạn

(2) Nhập  Tên CSDL vừa chạy

(3)  Nhập tài khoản đăng nhập của máy SQL , lưu  ý tài khoản này cần set quyền đọc , sửa ,  dữ liệu sql của mình


(4)  Nhập pass máy sql của bạn

Nếu muốn thoát CT bạn có thể ấn vào thoát và chọn yes để thoát , no để ở lại CT

2.2 Ấn kết nối sau khi đã kết nối dữ liệu thành công , ( nếu lỗi CT sẽ báo lỗi bạn mắc phải để sửa)

![image](https://github.com/taochangbang123/bt1/blob/master/DANH%20S%C3%81CH.png?raw=true)

Cửa sổ hiển thị cơ sở giáo viên và danh sách đào tạo

(1)  Nhấp vào để chọn cơ sở

(2) Nhấp chọn đơn vị đào tạo

(3) Sau khi chọn thì danh sách sẽ hiển thị danh sách giáo viên

(4) Để hiển thị thông tin giáo viên Nhấp chuột trái  ở Gv đó và chọn hiển thị

(5) Nhấp chuột trái  ở Gv và chọn xóa để xóa Gv khỏi danh sách

(6) Thoát CT 

![image](https://github.com/taochangbang123/bt1/blob/master/101831265_263438288225349_4441083698317623296_n.png?raw=true)

 Từ băng này ta có các thao tác xóa , hiển thị thông tin giáo viên ở dưới như sau :

<a name="Modau1"></a>
2.2.1 Ở hiện thị danh sách giáo viên  


![image](https://github.com/taochangbang123/bt1/blob/master/%E1%BA%A8N%20MENU.png?raw=true) 
 
 Lúc không có giáo viên thanh menu hiển thị thông tin và Xóa Gv sẽ bị mờ đi
 
 
 2.2.2 Xóa giáo viên trong bảng danh sách
 
 ![image](https://github.com/taochangbang123/bt1/blob/master/X%C3%93A%20GV.png?raw=true)
 
 Ở bảng danh sách giáo viên có nút xóa giáo viên nhấn vào đó
 
 Lúc chọn bạn chọn xóa , sẽ hỏi bạn thêm  1 lần nữa , nếu chắc chắn muốn xóa ấn yes , nếu không ấn no để quay về danh sách
 
 
 2.2.3 hiển thị thông tin giáo viên
 
![image](https://github.com/taochangbang123/bt1/blob/master/hi%E1%BB%83n%20th%E1%BB%8B%20th%C3%B4ng%20tin%20Gv.png?raw=true)

Khi nhấp vào hiển thị thông tin của 1  giáo viên bất kỳ sẽ hiển bảng như trên 

Thông tin ở bảng này bao gồm :  

+Họ và tên giáo viên

+Sdt 

+Đơn vị đào tào

+Ghi chú

+Cơ sở của Giáo viên 

Ấn quay về để quay về danh sách giáo viên .

Kết thúc CT bằng nút thoát và chọn yes ở menu.


CHƯƠNG TRÌNH QUẢN LÝ GIÁO VIÊN ĐƠN GIẢN .ĐỂ QUẢN LÝ GIÁO VIÊN Ở CƠ SỞ ĐÀO TẠO ,  ĐƠN VỊ ĐÀO TẠO

1 số code đc tham khảo trong bài https://alexyangit.wordpress.com/2017/10/02/ket-noi-database-sql-server-su-dung-c/

https://csharpcanban.com/wpf-huong-dan-hien-thong-bao-truoc-khi-thoat-ung-dung.html
...


