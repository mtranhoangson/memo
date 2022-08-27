# git
## create a new repository on the command line

```
echo "# memo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mtranhoangson/terraform.git
(git remote rm origin)
git push -u origin main
```

## push an existing repository from the command line
```
git remote add origin https://github.com/mtranhoangson/memo.git
git branch -M main
git push -u origin main
```