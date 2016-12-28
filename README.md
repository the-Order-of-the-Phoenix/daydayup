# daydayup
This repository is to improve our skill of coding and also give some guidelines and anouncement.
## The Purpose
>关于为什么建立这个Organization以及qq群


<p>今天和肖神聊天，他突然提到说想建一个咱们班计算机方面的群，忽然发现学计算机/软件的这么多，不好好利用一下规模优势实在有一点儿可惜呀！于是想大胆地设想了一下，打算利用github和qq群来方便大家一起交流。至于为什么用github，<strong>抱歉，我也不知道，只是觉得它比较吊。</strong></p>
<p>至于<strong>具体要干什么</strong>，我有一个大概的想法，但是应该只能算alpha版，对于这个群的必要性和要干什么有想法的同学都可以来和我讨论一下。</p>
* 可以考虑一起准备acm/mcm之类，刷oj或者做题这样也许效率高一点？
* 可以一起做做工程什么的，技术问题可以共同进步嘛
* 代(zuo)码(ye)共享
* 有好的idea可以一起来实现一下
* 可以分组一起干...要不要加个作业什么的？
  <br/>


##The Order of the Phoenix
>没什么order啦，名字是因为前一段时间看哈利波特顺便注册了一下。。。

<p>
希望大家能够一起提高水平共同进步。说不定做个什么feihuobuke能<strong>搞个大新闻</strong>？
</p>
<br/>

## 关于git

*请预先下载好命令行工具进行操作。推荐使用cmder，可以使用git for windows覆盖其对应git子文件夹。注意其安装路径的各层文件名中都不要带有空格否则一些alas会失效。建议保持无空格的好习惯*

#### 使用ssh连接github

##### 先在cmder中运行以下两条命令：

```shell
git config --global user.name "xxxx"
git config --global user.email "xxxx@qq.com"
```

​	这两条命令用于设定全局的git用户信息（也就是config文件里的内容设定），这两个域可以用于进行ssh的生成。

##### 再运行以下命令

```shell
ssh-keygen
```

​	这时会需要提示输入密码，直接回车即可，不建议加入密码。ssh-keygen的加密参数中包含随机数，比密码要靠谱多了。

​	命令运行后会在user目录下创建.ssh文件夹，里面应当包含`id_rsa`，`id_rsa.pub`，`known_hosts`其中前两者分别为私钥和公钥。

##### 登录github添加ssh

将公钥字符串复制到Settings->SSH and GPG keys，以后就可以通过ssh方式进行连接。具体原理不做叙述，git中ssh的使用从此开始就是透明的了，所以不太需要了解。

#### 使用已建立的非空远程库进行初始化

```shell
git clone git@github.com:the-Order-of-the-Phoenix/daydayup.git
```

后面的为仓库地址。常用命令查看教程。

```shell
git add xx
git commit
git push
```

