# MCCA

基于全新架构的 交错战线 小助手。图像技术 + 模拟控制，解放双手！  
由 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 强力驱动！

## 功能介绍

目前已有的功能：

1. 启动游戏
2. 每日免费礼包
3. 每日探索(只使用自然回复的燃料)
4. 模拟军演(只打第一个，次数耗尽为止)
5. 基建(换班+好友换抽)
6. 周本(只刷第一关，需提前配好至少一队，二队可刷好感)
7. 领取奖励(邮箱+每日+通行证)
8. 关闭游戏

## 使用说明

下载地址：<https://github.com/MaaXYZ/MCCA/releases>

### Windows

- 对于绝大部分用户，请下载 `MCCA-win-x86_64-vXXX.zip`
- 若确定自己的电脑是 arm 架构，请下载 `MCCA-win-aarch64-vXXX.zip`
- 解压后运行 `MaaPiCli.exe` 即可

### macOS

- 若使用 Intel 处理器，请下载 `MCCA-macos-x86_64-vXXX.zip`
- 若使用 M1, M2 等 arm 处理器，请下载 `MCCA-macos-aarch64-vXXX.zip`
- 使用方式：

  ```bash
  chmod a+x MaaPiCli
  ./MaaPiCli
  ```

### Linux

~~用 Linux 的大佬应该不需要我教~~

## 其他说明

- 添加 `-d` 参数可跳过交互直接运行任务，如 `./MaaPiCli.exe -d`
- 反馈问题请附上日志文件 `debug/maa.log`，谢谢！

## 图形化界面

先凑活用吧（

## How to build

**如果你要编译源码才看这节，否则直接 [下载](https://github.com/MaaXYZ/MCCA/releases) 即可**

0. 完整克隆本项目及子项目

    ```bash
    git clone --recursive https://github.com/MaaXYZ/MCCA.git
    ```

1. 下载 MaaFramework 的 [Release 包](https://github.com/MaaXYZ/MaaFramework/releases)，解压到 `deps` 文件夹中
2. 安装

    ```python
    python ./install.py
    ```

生成的二进制及相关资源文件在 `install` 目录下

## 开发相关

- [MaaFramework 快速开始](https://github.com/MaaXYZ/MaaFramework/blob/main/docs/zh_cn/1.1-%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B.md)

## Join us

- MCCA 开发交流 QQ 群：513065464
- MaaFramework 开发交流 QQ 群: 595990173

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

感谢以下开发者对本项目作出的贡献（下面链接改成你自己的项目地址）:

<a href="https://github.com/MaaXYZ/MCCA/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MaaXYZ/MCCA&max=1000" />
</a>

