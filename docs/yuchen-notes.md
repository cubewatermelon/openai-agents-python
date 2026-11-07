# Git 协作流程笔记

我在 fork 的仓库里实践分支与 Pull Request 的完整流程。

## 三个远程角色

- upstream：原始仓库，只读，拉更新用
- origin：我的 fork，推代码用
- local：本机工作目录

## 一次循环

1. 切回 main 并同步
2. 开自己的工作分支
3. 改文件
4. add 与 commit
5. push 到远程分支
6. 开 PR 请求合并

## 记住

main 是结果，不是工作台。