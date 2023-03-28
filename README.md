# projX-control-center-startup-management-plugin

### DDE 控制中心自启动管理插件

为 DDE 桌面环境的控制中心编写自启动管理插件

### 项目描述

DDE 深度桌面环境的控制中心提供了插件功能，以便第三方开发者可以扩展其功能，将额外的功能组件添加到控制中心之中。请为 DDE 桌面环境的控制中心编写一个自启动管理插件。

### 所属赛道

2023全国大学生操作系统比赛的“OS功能挑战”赛道

### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生（2023年春季学期或之后毕业的大一~大四的本科生或研究生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2023全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

......

* github https://github.com/BLumia

* email wangzichong@deepin.org


### 难度

易

### 特征

- 熟悉 C++ 语言。
- 了解 Qt 应用程序框架，了解 QML 的使用方式。
- 能够根据阅读代码与文档，了解相关组件的工作方式与架构。


### 文档

- Desktop Application Autostart Specification：https://specifications.freedesktop.org/autostart-spec/autostart-spec-latest.html
- 控制中心插件示例： https://github.com/linuxdeepin/dde-control-center/tree/master/tests

### License

GPL-2.0-or-later

## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

1. （必须）完成一个控制中心插件，能够展示当前所有开机启动项的列表
2. （必须）插件以单独的仓库提供，并能够单独构建，不需要合并入 dde-control-center 项目
3. （必须）能够在插件中，通过用户界面的交互来管理（添加、删除、启用、禁用）开机启动项
4. （必须）编写博客，记录开发过程的心得与体会，并将博客投递至 planet.deepin.org
5. （可选）同时将此插件移植到 deepin-tweaks 项目之中（若完成移植，可合入 deepin-tweaks 仓库）
6. （可选）与 dde-control-center 共同完善相关接口的开发文档，使其他插件开发者可以更方便的参与插件的开发

## 备注

关于研发相关的讨论，可以在 [Matrix](https://wiki.deepin.org/Matrix) 平台的 deepin 开发者讨论群中公开的展开。
