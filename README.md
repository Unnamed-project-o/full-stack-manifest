# 运行项目
```shell
mkdir full-stack-repo
cd full-stack-repo
repo init -u https://github.com/Unnamed-project-o/full-stack-manifest.git
# 如果你没有合适的梯子，可以使用如下命令
repo init -u https://github.com/Unnamed-project-o/full-stack-manifest.git --repo-url=https://mirrors.tuna.tsinghua.edu.cn/git/git-repo

# 拉取代码
repo sync -j16

# 执行
chmod +x run.sh
./run.sh
```

# FAQ
1. 前面操作显示缺失什么工具时，pip install 对应工具

