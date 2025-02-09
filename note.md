1. Cách sử dụng
- 1 số khái niệm
+ clone : Clone là 1 bản sao của kho mã nguồn. Khi bạn muốn làm việc với 1 dự án, bạn có thể clone dự án đó về máy mình và làm việc với dự án dó
+ commit : Mỗi lần thay đổi mã nguồn, bạn cần commit để lưu lại phiên bản hiện tại của mã nguồn.
+ Push : Đẩy code từ máy lên git sau khi chúng ta commit 
+ Pull : lấy code commit từ trên git về máy tính. Khi bạn muốn lấy các commit mới nhận về máy

- Cách sử dụng câu lệnh 
B1 : Đăng nhập gitHub và tạo Repo (để chế độ public)
B2 : Lên google : Git Download : tải về theo phiên bản của máy
B3 : Kết nối giữa máy mình với tải khoản trên gitHub : gõ trên google : git config global
B4 : khởi tạo tên người dùng (trên Github) + mail đăng kí Github
- $git config--global user.name "trungdung"
- $git config--global user.email trungdung@gmail.com
B5 : kiểm tra xem config được hay chưa thì gõ như sau
- $git config -- list
B6 : Vào thư mục gốc chứa sản phẩm : Chuột phải chọn gitBash
B7 : Khởi tạo : git init ( file gốc sẽ hiển thị 1 file.git )
B8 : Kết nối , liên kết git trong máy mình với git trên internet
- $git romote add origin..
B9 : kiểm tra xem kết nối được chưa :
- $ git remove -v
B10 : Đưa toàn bộ code lên gitHub
- $git add
- Gói lại : $git commit -m ".."
- Đẩy từ máy lên gitHub ; git push origin master