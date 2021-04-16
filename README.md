# Create & Update package

## Create package

```mkdir fixme01
cd fixme01/
git init
vim README.md
git add .
git commit -m "First commit"
git remote add origin  https://username:passwd@github.com/yuroapps/fixme01.git
git push -u origin master
```

## Update package

```git add .
git commit -m "Second commit"
if `git push` throws an error, do `git push origin master --force` ```
