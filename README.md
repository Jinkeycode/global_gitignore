# 全局 gitignore 的方法
创建并指向一个全局配置
```
git config --global core.excludesfile ~/.gitignore_global
```
编辑配置
```
vim ~/.gitignore_global
```
输入本仓库.gitignore的内容
```
# for Mac OS X System Files
.DS_Store
Thumbs.db
 
# for emacs
*~
[#]*[#]
 
# for Eclipse
*.project
 
# for Logs and databases
*.log
 
# remove SVN
.svn
 
# for Xcode
.*.swp
.clang_complete
*.xcodeproj/project.xcworkspace/
*.xcodeproj/xcuserdata/
 
# for IDEA
*/build/*
.idea/*
*.iml
/out/*
```
