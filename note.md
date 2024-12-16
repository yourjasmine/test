# cấu hình git
- git config --global user.name "tên tài khoản github"
- git config --global user.email <tên email github>

# Câu lệnh
- git init : biến dự án thành một git - repository

- git add : lưu file trạng thái tạm thời(ngay tại thời điểm)
- git add <tên file>

- git status: xem trạng thái lưu file của repo

- git commit -m 'ghi chú': quan trọng nhất.

- git log --oneline: xem danh sách commit của repo/ xem id

# Tạo nhánh

- git checkout -b {tên nhánh} : tạo nhánh
- git branch -d {tên nhánh}: xóa nhánh

# up lên github
- git push <đường dẫn> <tên nhánh>

# lấy repo từ git về máy
- vào cmd của thư mục
- git clone <đường dẫn>
- cd <tên repo>
- code .

# tạo nhánh từ máy local và up lên github
- git checkout -b {tên nhánh}
- git push -u origin

# lấy nhánh từ github về máy local
- git fectch origin
- git checkout -b {tên nhánh} origin/{tên nhánh}

# Kết hợp các nhánh vào master trên git
- vào chức năng pul request trên github

# Lấy các chỉnh sửa, version mới trên github về máy
- git pull 

# Xung đột 
- Xóa / lấy hết

# gitignore
- Tạo một file tên .gitignore sau đó thêm file cần ẩn vào 

# fork 
- trên github - pull request