# Git

Git是目前世界上最先进的分布式版本控制系统。



## 安装与配置

https://baijiahao.baidu.com/s?id=1742123713265363048&wfr=spider&for=pc

```shell
# 更新存储库
sudo apt-get update

# 安装Git
sudo apt install git

# 检查git可用版本
apt-cache policy git

```





## Git工作流程图

![image-20231107195119887](/home/china/pictures/mdPirctures/image-20231107195119887.png)

- clone（克隆）: 从远程仓库中克隆代码到本地仓库 
- checkout （检出）:从本地仓库中检出一个仓库分支然后进行修订 
- add（添加）: 在提交前先将代码提交到暂存区 
- commit（提交）: 提交到本地仓库。本地仓库中保存修改的各个历史版本 
- fetch (抓取) ： 从远程库，抓取到本地仓库，不进行任何的合并动作，一般操作比较少
-  pull (拉取) ： 从远程库拉到本地库，自动进行合并(merge)，然后放到到工作区，相当于 fetch+merge 
- push（推送） : 修改完成后，需要和团队成员共享代码时，将代码推送到远程仓库



## Git配置







设置git-log别名

```shell
```

