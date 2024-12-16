# Câu lệnh
- git init : biến dự án thành một git - repository

- git add .  : lưu file trạng thái tạm thời(ngay tại thời điểm)
- git add <tên file>

-git status: xem trạng thái lưu file của repo

-git commit -m 'ghi chú': quan trọng nhất.

- git log --oneline: xem danh sách commit của repo

# Tạo nhánh

- git checkout -b {tên nhánh} : tạo nhánh
- git branch -d {tên nhánh}: xóa nhánh

# up lên github
- git push <đường dẫn> <tên nhánh>

# lấy repo từ git về máy
- git clone <đường dẫn>

# tạo nhánh từ máy local và up lên github

# lấy nhánh từ github về máy local
- git fectch origin
- git checkout -b {tên nhánh} origin/{tên nhánh}

# 