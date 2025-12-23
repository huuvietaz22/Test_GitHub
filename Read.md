#terms -- danh từ

- branch: cành (master)
- repository
- conflict: xung đột
- local: những thứ nằm trên máy tính
- remove: những thứ không nằm trên máy của chúng ta

#commad

- git init (thêm dự án)
- git status (ktra trạng thái)
- git add (chuẩn bị lưu lại thời điểm)
- git reset
- git commit (dùng để lưu )
- git commit -m 'ghi chú'
- git log (để xem những lần commit)
- git log --oneline (ngắn gọn hơn)
- git checkout + id -- ex: git checkout 968a759 (xem lại tại thời điểm id)
- git checkout master (trở lại ban đầu)
- git checkout {branch name} (dùng để chuyển branch)
- git branch
- git checkout -b {branch name} (thêm branch mới)
- git merge {branch name} (tổng hợp nhánh đc gọi tên)
- git branch -d {branch name} (xóa 1 branch)
  lưu ý: khi xóa nhớ lưu bằng lệnh commit và xem lại bằng lệnh git log xem đã lưu chưa.
- git push (dùng khi lấy repo từ trên github về local)
- git push {link github} {branch name} (dùng để đẩy lên repo trên github)
- git remote add origin {link} (đặt tên cho link) 
- git clone {repo url}
- git fetch origin
- git push -u origin {branch name} (đẩy branch lên trên git) 
- git checkout -b {branch name} origin/{branch name}
- git pull (đẩy merge từ trên remote xuống dưới local)
