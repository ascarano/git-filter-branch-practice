# Git filter-branch practice

See http://git-scm.com/docs/git-filter-branch for details

Especially look at:

```
git filter-branch --index-filter 'git rm --cached --ignore-unmatch filename' HEAD
```
