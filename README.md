# ac-predictor-zh <sub>v2.0.12.5<sub>——青，取之于蓝，而青于蓝</sub></sub>

## 简介

ac-predictor最新汉化版，用以在AtCoder比赛进行中进行rating变化预测。

添加`在比赛开始前显示rating`等实用的功能，并对 rating 变化箭头进行了美化，比赛排行榜可以使用两种不同的风格来显示rating变化，对大部分内容进行了汉化。

ac-predictor-zh 2.0.12.4 优化了错误处理，2.0.12.5 基本完成，灵感来自 ac-predictor-cn-ez，感谢[@Gary-0925](https://github.com/gary-0925)！

2.0.12.6 进一步优化了错误处理机制，目前以[测试版](https://github.com/zyx201207/ac-predictor-zh/tree/%E6%B5%8B%E8%AF%95%E7%89%88)的形式发布。

如果不错就[GitHub上](https://github.com/zyx201207/ac-predictor-zh)给个star并给个好评谢谢喵。

感谢[@key-moon](https://github.com/key-moon)提供[原版脚本](https://github.com/key-moon/ac-predictor)。

另外，[ac-predictor-cn-ez](https://github.com/Gary-0925/ac-predictor-cn-ez/)也是一个不错的选择，不过这个好像停止更新了。

保证一旦有新功能研发完成，哪怕只是一个功能，我也会第一时间以测试版的形式发布。

## 安装流程

### 1. 安装篡改猴

<blockquote>
  如果已经安装了篡改猴可以跳过这一步。
</blockquote>

点击[此链接](https://tampermonkey.net)安装篡改猴。

### 2. 安装脚本

<blockquote>
  如果已经安装了ac-predictor、ac-predictor-cn等脚本请先删除或禁用，否则会发生脚本冲突导致页面无法正常加载。
</blockquote>

安装完篡改猴后，从[这里](https://greasyfork.org/zh-CN/scripts/567082-ac-predictor-zh)获取该脚本即可。

如果 GreasyFork 访问困难，可以从[这里](https://greasyfork.icu/zh-CN/scripts/567082-ac-predictor-zh)获取。

### 3. 测试是否安装成功

打开 [AtCoder](https://atcoder.jp)，如果导航栏用户名下拉栏里出现了`ac-predictor 设置`，则你的ac-predictor-zh已安装成功。

## 主要功能

在AtCoder比赛中预测rating变化。

对大部分内容进行了人工翻译，不过可能尚有未尽内容未完成翻译，如果你发现了未翻译部分，bug的存在，或者想要提出功能改进建议，**欢迎大家[前来反馈](https://github.com/zyx201207/ac-predictor-zh/issues)！**

注：如果在使用除篡改猴以外的脚本管理器时发现bug，请验证使用篡改猴时会不会出现相同的bug，如果会再提交bug反馈，否则，可能由于无法复现该bug导致反馈不被受理。

## 扩展功能

排行榜页面经过箭头美化等处理，可以在`ac-predictor-zh 设置`一栏中选择你心仪的风格。

支持在比赛开始前显示每个人当前的rating，便于比较自己与他人的rating差。

如果你觉得侧栏碍眼，可以选择将其隐藏。

这些功能你可以在`ac-predictor-zh 设置`一栏中随意调节。
