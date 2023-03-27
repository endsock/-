## 一、初次拉取项目
找个目录，用于存放目录，如`/Users/xxxx/Documents/projects`

打开`iterm.app`，按如下命令操作
```bash
cd /Users/xxxx/Documents/projects
git clone git@github.com:endsock/lengyan.git
```

## 二、更新项目
打开`iterm.app`，按如下命令操作
```bash
cd /Users/xxxx/Documents/projects/lengyan
git pull # 先更新
```

## 三、提交项目
> 每次操作之前先 **【更新项目】** ，最后操作完再提交

打开`iterm.app`，按如下命令操作
```bash
git add .         # 添加文件到缓存区
git commit -m 'xxx'  # xxx为本次提交的意见/或其他标题，或简单的写一个'更新', eg: git commit -m '更新'
git push -u origin main
```

## 总结
非冲突状态下，每次操作的流程就是 `更新项目` -> `提交项目`