1. npm init
2. npm install gulp --save-dev
3. 在根目录gulpfile.js
4. gulpfile中抽象需要做的任务

- 初始化一个本地GIT仓储
``` shell
cd 项目目录
git init // 初始化一个本地仓库
```

- 查看本地仓库变更状态
git status

- 添加本地仓库资源
git add
git add .
git add --all
	类似node_modules 不应该被跟踪托管

.gitignore 忽略托管文件

git status -s

git commit 将本地变化提交的本地的仓库文佳佳归档
 -m ‘大版本提交说明’

git diff


恢复到某个版本
git reset --hard hash前6位