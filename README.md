"# tinh-dien-tich-html" 
git init                     # Tạo repository Git trong thư mục hiện tại
git remote add origin <url> # Thêm remote (GitHub)

git add .                                   # Thêm tất cả thay đổi vào staging
git commit -m "Thông điệp commit"           # Tạo commit mới
git log                                     # Xem lịch sử commit
git log --oneline                           # Xem lịch sử ngắn gọn

git push origin main                        # Đẩy commit lên GitHub nhánh main
git push origin main --force                # Ghi đè lên GitHub (cẩn thận!)

git reset --hard <commit-hash>             # Quay về commit cũ

git branch -r                               # Xem nhánh từ GitHub
git push origin --delete <branch-name>      # Xóa nhánh từ GitHub

git branch -r                               # Xem nhánh từ GitHub
git push origin --delete <branch-name>      # Xóa nhánh từ GitHub

git remote -v                               # Kiểm tra remote hiện tại
git remote remove origin                    # Xóa remote tên origin
git remote set-url origin <url>             # Thay đổi URL của origin
