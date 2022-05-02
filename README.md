[![Build Status](http://peeeq.de/hudson/job/StdLib2/badge/icon)](http://peeeq.de/hudson/job/StdLib2/) [![Build Status](https://travis-ci.org/wurstscript/WurstStdlib2.svg?branch=master)](https://travis-ci.org/wurstscript/WurstStdlib2)

# StdLib127

[中文](https://github.com/fbicirno/WurstStdlib2/blob/master/README.md)  [English](https://github.com/fbicirno/WurstStdlib2/blob/master/README_EN.md)

【版本限制】仅适用于带有dzapi和japi 的war3 1.27版本

【不做改动】我们对wurst官方依赖库不做函数修改，只翻译

【可能更新】对官方依赖库的更新内容，有选择性的更新(没有1.32函数的)

# 版本

【2021/12/2更新】

wurst官方版本：unknown

鹿力半仙依赖库：鹿头版 v0.1-build1315

DZAPI编辑器版本:1.29c

# 更新日志

v1.86-2022/5/3

增加变大漂浮文字功能

v1.85-2022/4/28

在stringex中加入中文实数转换，转文本后显示万亿，并约去小数点

v1.84-2022/4/19

默认关闭报错调试信息，需要打开StdLibConfig中的debug模式才显示，防止影响玩家。

v1.83-2022/4/11

为了防撞hash，玩家customv系统对idset，setcvr进行了偏移。

v1.82-2022/4/7

增加superarray泛型，发现泛型real只能存214万以下的数字

所以将自定义值系统加入特殊的保存R实数函数。

v1.81-2022/3/22

intarray支持取随机数

v1.8-2022/3/21

新增present百分数，在mathex中增加了一些函数支持。

新增texttag的转整数支持。

新增intarray，整数数组的遍历，比hashlist效率快。

v1.7-2022/2/26

修复framehandle，可用于1.27

优化部分handle脚本的函数

新增部分加强脚本，customvalue增强版。

v1.6—2022/2/9

翻译knockback，删改了std_fix中的config文件

v1.5—2021/12/17

支持了部分默认导入的包，增加了4个基础的yd japi技能函数

v1.4—2021/12/6

增加了API_help 就是API操作手册，预览wurst提供的函数使用案例！

对于浪费字节码的字符串处理函数加了@deprecated过时提示

v1.3—2021/12/3

更新了lua版print函数，以及堆栈报错

多种config覆写，支持字符串+数字，单位函数plus，编译哈希，触发添加条件code等

v1.2—2021/12/3

更新了配置开关，默认关闭伤害系统。

对1.32部分函数无效处理，返回error

同步bj cj dzj等build中的jass脚本

V1.1—2021/12/2

更新了新版readme



V1.0—2021/10/23

采用了[鹿力半仙](https://github.com/yefq) 的依赖库为模板。
