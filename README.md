# よく使う git のメモ

### ローカルにあるリモートのブランチを更新  
```
git remote update -p
```

### リポジトリだけのアカウント設定  
```
git config --local user.name "UserName"
git config --local user.email "address"
```

### gitignore の更新  
```
git rm -r --cached .
git add .
git commit -m ".gitignore is now working"
```
