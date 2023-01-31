---
title: git Commands
date: 2018-07-11 05:28:34
tags: Linux
---
- 在特定目录下全文检索：
[grep -rnw '/path/to/somewhere/' -e 'pattern'](https://stackoverflow.com/questions/16956810/how-do-i-find-all-files-containing-specific-text-on-linux)
- 在当前目录查找文件名：
[find . -name "foo*"](https://stackoverflow.com/questions/5905054/how-can-i-recursively-find-all-files-in-current-and-subfolders-based-on-wildcard)
- [Remove directory from remote repository after adding them to .gitignore](https://stackoverflow.com/questions/7927230/remove-directory-from-remote-repository-after-adding-them-to-gitignore)
```
git rm -r --cached some-directory
git commit -m 'Remove the now ignored directory "some-directory"'
git push origin master
```
- Delete remote branch:
`git push origin -d branch-name`