## Git basic
### Branch
* Tạo mới branch
>git branch {name branch}
* Chuyển sang nhánh
> git checkout {name branch}
* Tạo mới và chuyển sang nhánh mới
> git chechout -b {name branch} && 
* Tạo empty commit
> git commit --allow-empty "[start] [skip ci] {title task} {URL task}"
* Delete branch
> git branch -d {name branch}
* List all branch
> git branch
### Tạo Pull request mới
* From github > pull request > title task + URl link tasktask > chọn label > assign

### Lưu lại thay đổi trong stash trước khi checkout master or rebase
* Lưu lại sửa đổi
> git stash
* List các lần thay đổi
> git stash list
* Lấy ra các thay đổi gần nhất
> git stash apply
* Chỉ định lấy ra thay đổi
> git stash apply stash@{1}
* Xoá stash
> git stash drop stash@{1}
* Tạo branch trên stash
> git stash branch

### Tích hợp dữ liệuliệu
* Trở về master
> git checkout master
* Tích hợp dữ liệu
> git merge {name branch}
