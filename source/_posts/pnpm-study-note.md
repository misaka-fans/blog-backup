---
title: 一些在实践中学到的pnpm使用技巧
date: 2023-12-08 20:57:21
tags: coding, study
cover: https://m365-dev.com/wp-content/uploads/2018/10/pnpm1.png
---
# 0、前言
本文章按照ubuntu编写，其他系统请自行更换brew等工具

# 安装pnpm管理器
```linux
npm i -g pnpm
```

全局安装pnpm。<b>首先要记得提前安装npm，nodejs>10</b>

# 使用npm安装、卸载包
安装：
```Linux
pnpm install <package-name>
```

卸载：
```linux
pnpm remove <package-name>
```

安装所有项目依赖:
```linux
pnpm install
```
在运行项目前推荐优先运行！

若要全局使用，加上-g参数。

# 运行脚本
```linux
pnpm <name>
```

# End
目前常用的命令就是这些，之后学到会加以补充。
