# py2go
转换python代码结构到golang的小工具。只是简单的结构代码转换，方便再手动调整。

### 完成的内容
- 基本语法树的分析，重建。
- 转换成golang,稍微改下可以支持转换到其他语言
- class,func,if,else,for的基本转换
- 一些关键字的批量替换

### 未完成的内容
- 变量的初始化
- 类型识别
- 特殊语法的转换(例如：if a in [])

### 使用方法
- 转换单个python文件（示例：py2go.exe res/test.py）
- 转换所有当前目录和res目录的python文件（直接执行exe）  

