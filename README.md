# 使用指南

本项目所使用的 box 为官方 hashicorp/bionic64 资源。

## 在线下载（建议海外用户使用）

可使用 `vagrant init hashicorp/bionic64` 命令，会自动在线下载 hashicorp/bionic64 资源。

## 离线下载（建议国内用户使用）

如果在线下载过慢，可直接[点击链接下载 box 到本地](https://app.vagrantup.com/hashicorp/boxes/bionic64/versions/1.0.282/providers/virtualbox.box)。

## 启动

下载完成之后，输入命令 `vagrant up` 启动容器。

## 配置

启动之后，使用 `vagrant init hashicorp/bionic64 {你自己的box所在路径}` 来初始化容器。

> Tips: hashicorp/bionic64后面跟空格，然后直接跟你的box所在路径，不要加大括号

## License

Copyright © 2013-2020 [九章算法](https://jiuzhang.com) 浙ICP备19045946号-1

商务合作：[fukesu@jiuzhang.com](mailto:fukesu@jiuzhang.com)

加入我们：[jiuzhang.com](https://jiuzhang.com/joinus)

了解更多：[微博/九章算法](https://weibo.com/ninechapter) [知乎/九章算法](https://www.zhihu.com/people/crackinterview)

友情链接：[领扣 LintCode](https://www.lintcode.com/)
