# 2022-10-11-git_basics

- `git init`: initialize git repository in current directory
    - make sure that you don't nest git repositories
- `git status`: tells you things about your current git repo

- `git add <FILE>`: puts <FILE> into your staging area
- `git commit`: open up editor for you to write a meesage and create commit
    - `git commit -m "MESSAGE"`: writes commit message without editor

- `git log`: shows us the log / commit history
    - `git log --oneline`: shows us the 1 line per commit version

- `git diff`: shows you new chagnes to a file that has not been committed
    - `git diff --stanged`: shows you changes in the staging area
    - `git diff <HASH> <FILE>`: shows you difference between current and commit
        - `HEAD~1`: to use relative to head
        - `<HASH>`: to use the actual hash location

