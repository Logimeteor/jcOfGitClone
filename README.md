# jc-git clone  等相关问题

 ***在执行 git clone 时网速往往成为一大痛点，不论是否翻墙，撑死只有 200 kb 每秒，而关于提速的方法，网上众说纷纭，但大都没什么大用，使用下面我的方法，可以让你的 git clone 速度直接达到 2MB 每秒，无论是克隆什么仓库，都不再头大***

******

## **本次教程仓库地址**

> gitee：https://gitee.com/logimeteor/jcForGitClone.git
>
> github：https://github.com/Logimeteor/jcOfGitClone.git

****

## 前提，使用我的翻墙教程实现翻墙操作

教程网址如下：

> github：https://github.com/Logimeteor/packageOfClash.git
>
> gitee：https://gitee.com/logimeteor/package-of-clash.git

****

## 配置  git 代理

```sh
# 必须操作（127.0.0.1 为本地回环地址，简单来说，这个 ip 指代本机，后面的 7897 为端口号，这里参考 clash 中的配置）
git config --global http.proxy 127.0.0.1:7897
git config --global https.proxy 127.0.0.1:7897
# 不是必须操作
git config --global http.timeout 300          # 设置 HTTP 超时为 300 秒（5 分钟）

```

![image-20250728101620639](F:\aziliao\note\jc\gitClone\image-20250728101620639.png)





