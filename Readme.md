# Hotel Management System

## Giới thiệu

Đây là phần mềm quản lý khách sạn được phát triển bằng C++. Phần mềm này cho phép quản lý phòng, khách hàng và cung cấp các chức năng đăng nhập cho quản trị viên và khách hàng.

## Yêu cầu môi trường

Để chạy được phần mềm này, bạn cần phải có:

- **Trình biên dịch C++**: Mingw64 (GCC). Đây là trình biên dịch C++ phổ biến cho hệ điều hành Windows. Bạn có thể tải về và cài đặt từ [đây](http://mingw-w64.org/doku.php).

- **Visual Studio Code**: Đây là một môi trường phát triển tích hợp (IDE) miễn phí và mã nguồn mở. Bạn cần cài đặt phiên bản mới nhất để đảm bảo tương thích. Bạn có thể tải về và cài đặt từ [đây](https://code.visualstudio.com/download).

- **Hệ điều hành Windows**: Phần mềm này được phát triển và kiểm thử trên hệ điều hành Windows. Đảm bảo rằng bạn đang chạy một phiên bản Windows hỗ trợ (Windows 7 trở lên).



## Cách sử dụng

1. Clone repo này về máy của bạn.
2. Mở thư mục chứa mã nguồn bằng Visual Studio Code.
3. Mở Terminal trong Visual Studio Code (View -> Terminal).
4. Đảm bảo rằng bạn đã cài đặt trình biên dịch C++ Mingw64. Nếu chưa, bạn có thể tải về và cài đặt từ [đây](http://mingw-w64.org/doku.php).
5. Trong Terminal, điều hướng đến thư mục chứa mã nguồn - HotelManagementSystem (sử dụng lệnh `cd`). `cd .../HotelManagementSystem`
6. Biên dịch mã nguồn bằng cách sử dụng lệnh `g++ -o outputfile Hotel.cpp main.cpp` (thay `outputfile` bằng tên file output mà bạn muốn).
7. Chạy chương trình bằng cách sử dụng lệnh `./outputfile`.
8. Theo dõi hướng dẫn trên màn hình Terminal để tiếp tục sử dụng phần mềm.

## Phiên bản
Phiên bản hiện tại của phần mềm là 1.0.0.

## Tác giả

- Hồ Công Hiếu - 21200289
- Nguyễn Thừa Vũ Hiệp - 21200288
- Nguyễn Nhất Huy - 21200294

## Giấy phép

Phần mềm này được phát hành dưới giấy phép MIT. Điều này có nghĩa là bạn có quyền sử dụng, sao chép, sửa đổi, hợp nhất, xuất bản, phân phối, cấp phép lại và/hoặc bán bản sao của phần mềm này. Tuy nhiên, khi bạn sử dụng hoặc phân phối lại phần mềm, bạn phải luôn đi kèm với bản sao của giấy phép MIT này.