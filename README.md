# JS-performance-test
这个项目收集了一些JS 语言本身的性能开销测试用例，比如 for 循环 for...of  forEach 的性能优劣，以及循环体内特定方法对遍历性能的影响；Object.assign() 和 扩展对象操作符（...）性能开销对比，以及一些比较冷门有意思的特性，比如Array.prototype.length;


### 文件及目录说明
 - 文件名一般表明本文件测试的主要内容
 - `result/` 目录下 存放对应页面的性能开销结果截图 比如：`iterator.html` 的测试结果存放在 `result/iterator/` 目录
