# toy-bundler
javaScript,babel.AST

## 依赖声明
* @babel/parser用于分析源代码，产出 AST；

* @babel/traverse用于遍历 AST，找到 import 声明；

* @babel/core用于编译，将源代码编译为 ES5；

* @babel/preset-env搭配@babel/core使用；

* resolve用于获取依赖的绝对路径。

### 相关命令：
`npm install --save @babel/parser @babel/traverse @babel/core  @babel/preset-env resolve`