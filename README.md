# Titanworkk
Learn git --- Các câu lệnh
# Tìm hiểu chung
  - Gồm 3 loại lưu trữ  :
      + cục bộ
      + tập trung
      + ... ít xài
  - 2 cách lưu:
      + Truyền thống
      + Phân tán
# Kiểm tra phiên bản git
  - git --version

#Định hình cấu trúc git
  - git config --global user.name "daophanquochoai"
  - git config --global user.email "..."
# Khởi tại git
  - git init
# Cam kết lưu trữ local :
  - git add .
# Trạng thái git
  - git status
# Xác nhận 
  - git commit -m "lời cmt"
# Trợ giúp git
  - git help --all (ngoài ra còn nhiều cái)
# Tạo nhánh mới
  - git branch ten-nhanh
# Kiểm tra và di chuyển đến nhánh đó
  - git checkout ten-nhanh
# Hợp nhánh lại
  - git merge ten-nhanh
# Chỉ định kho lưu trữ 
  - git remote add origin URL
# Đẩy lên kho lưu trữ
  - git push -u origin main
# Copy về
  - git clone URL
# Thay đổi
  - git pull URL
# ! [rejected]        main -> main (fetch first) error: failed to push some refs to 'https://github.com/daophanquochoai/Titanworkk.git
  - git pull --rebase origin main
  - git push -u origin main
