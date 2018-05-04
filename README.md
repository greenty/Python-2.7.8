Python源码阅读注释
=========================



版本2.7.8

干净版本, 注释逐步加入中...

**Include** ：该目录下包含了 Python 提供的所有头文件，如果用户需要自己用 C 或 C++来编写自定义模块扩展 Python，那么就需要用到这里提供的头文件。

**Lib** ：该目录包含了 Python 自带的所有标准库，Lib 中的库都是用 Python 语言编写的。 

**Modules** ：该文件夹中包含了所有用 C 语言编写的模块，比如 ramdom，cStringIO 等，Modules 中的模块是那 些对速度要求非常严格的模块。而有一些对速度没有太严 格要求的模块，比如 os，就是用 Python 编写，并且放在 Lib 目录下。 

**Parser** ：Parser 目录中包含了 Python 解释器中的Scanner 和 Parser 部分，即对 Python 源代码进行词法分 析和语法分析的部分。除了这些，Parser 目录下还包含 了一些有用的工具，这些工具能够根据 Python 语言的语 法自动生成 Python 语言的词法和语法分析器，与 YACC 非 常类似。 

**Objects** ：该目录中包含了所有 Python 的内建对象， 包括整数，list，dict 等；同时，该目录还包括了 Python 在运行时需要的所有的内部使用对象的实现 

**Python** ：该目录下包含了 Python 解释器中的Compiler 和执行引擎部分，是 Python 运行的核心所在。 

**PCBuild** ：包含了 Visual Studio 2003 工程文件，研究 Python 源代码就从这里开始。
