gh tutorial

[link](https://www.youtube.com/watch?v=1yjbTgsnxLk)

git add .

git commit -m "Initial commit"

gh repo create gh --public --source=. --remote=origin --push

gh repo delete enjoywithouthey/gh

gh auth refresh -h github.com -s delete_repo

git commit -m "first push"

git push origin main