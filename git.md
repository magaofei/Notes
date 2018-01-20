# Git

```shell
# 删掉历史文件
git filter-branch --force --index-filter 'git rm --cached --ignore-unmatch file.type' --prune-empty --tag-name-filter cat -- --all
```



