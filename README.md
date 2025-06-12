# demo-gitflow
# GIT là gì ?
- Git là hệ thống quản lý phiên bản phân tán
Theo doi lịch sử thay đoi của dự an ( ma code, ... )
- Quản lý nhiều nhánh phát triển song song
- Cho phép nhiều ngưoi cung làm việc tren một du an ma không bị xung đột (conflict)
You, now . Uncommitted changes
# Các khái niệm cơ bản trong GIT
## Repository
- Kho chứa mã nguồn, có thể là local hoặc remote (sever)
## Commit
- Ghi lại trạng thái của một mã nguồn ( sự kiện ) tại một thời điểm nhất
## Branch
- Nhánh phát triển riêng biệt
## Merge
- Gộp nội dung của một branch vào nhánh khác
## Clone
- Tải repo từ server ve máy
## Pull
- Lay code moi nhat tu nhanh tren server ve local
## Push
- Đay code commit từ local len server
# Một số cầu lệnh GIT cơ bản
- git init: Khai báo một sự án bắt đầu sử dụng git
- git status : Kiem tra trạng thái thay đổi của các file trong dự án
- git add file_name: Xác nhận (thêm ) file thay đổi vào repo của local ( sn sàng cho commit)
- git add . : Xác nhan(thêm) tat cả cac file thay đoi vao repo local ( san sang cho commit)
- git commit -m "Your comment" : Đẩy các file thay đổi vào store local sẳn sàng cho push code lên server và đồng thời thêm comment
You, 8 minutes ago . Uncommitted changes

- git push origin your_branch: Day code tu local vao nhanh your_branch tren server
- git checkout -b branch_name : Tạo một nhánh mới có tên la branch_name đồng thoi di chuyển sang nhanh đó

Khởi tạo repository => clone code về máy local => Thêm file mới va thay đổi file cũ => commit code => push code lên nhánh mới