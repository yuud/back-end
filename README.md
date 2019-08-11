# back-end
## 后端技术栈


### 主流的后端技术
* Java
* Python
* Php
* C#
* C++
* C
* Javascript
* Golang
* Perl
* Visual Basic
* Object Pascal

TIOBE 8月编程语言排行1-20
![image](https://github.com/yuud/back-end/blob/master/1565506765653.jpg)

### PHP是啥？
PHP is a popular general-purpose scripting language that is especially suited to web development.
Fast, flexible and pragmatic, PHP powers everything from your blog to the most popular websites in the world.

## 发展历程
### 问世
1994年，拉斯姆斯·勒多夫（Rasmus Lerdorf）创造了 PHP，事实上这个时候的 PHP 只是用 Perl 语言编写的一系列 CGI 脚本，用于跟踪他在线简历的访问情况，统计他自己网站的访问者。勒多夫把这些 CGI 脚本命名为“Personal Home Page Tools”。这里我们姑且称之为 PHP 1 吧！但这个早期的 PHP Tools 并不是一门语言，只是一些工具，提供基本的变量，并使用嵌入式HTML句法自动处理表单变量。

### PHP 2
由于勒多夫写的这个小程序轻巧且简便，吸引了很多人的关注，在1995年，勒多夫发布了 PHP/FI 2.0。这个FI是一个可以做 SQL 查询的东西，2.0是其更新版本。这次发布了一个基本完善的工具包，它不仅可以访问数据库，还能嵌入 HTML 中动态处理数据。新的工具包，吸引了很多的程序开发者，其中包括 Zeev Suraski（泽埃夫·苏拉斯基）和 Andi Gutmans（安迪·古曼兹），他们后来加入到了PHP3的开发当中。

### PHP 3
在1997年中，开始了第三版的开发计划，开发小组加入了 Zeev Suraski 及 Andi Gutmans。1998年末，PHP 3 第一个官方正式版发行，其特点是具有更好的执行效果和更清晰的结构。此外，该版本最强大的地方在于它的可扩展性，这点吸引的大量的开发人员加入并提交新的 PHP 扩展模块。


### PHP 4
在 PHP 3 发布不久，Zeev Suraski 及 Andi Gutmans 就开始投入到 PHP 4 的开发当中，主要目标是增强程序运行性能和 PHP 自身的模块性。新的 PHP 核心被称为“Zend”引擎（两名开发者的缩写），由 C 语言编写，相同的 PHP 脚本在新版本中运行，性能提高了近十倍。在千禧年（2000年），PHP 4 正式发布。

主要增加了以下特征：

* 各种web服务器的支持
* 丰富的数组操作函数
* 完整的会话机制
* 对输出缓存的支持
* 增加了对类和对象的支持，是 PHP 面向对象的雏形

### 新时代 PHP 5
尽管，PHP 发展势头之猛，但相比较其他语言如 Java 来说，还有很多问题。面向对象的支持不够完善，无法捕获异常（Exception）等，这导致多年以来 PHP 一直被认为是一门面向过程的语言（即使在 PHP 5 发布后）。2004年7月，PHP 5 正式发布，这标志着 PHP 一个新时代的到来。并且往后多年，PHP 一直在 5 这个版本上迭代，是 PHP 历时最长的一个大版本。
它的核心采用的是第二代 Zend 引擎，并引入了对 PECL 模块的支持。PHP 5 最大的特点是引入了面向对象的全部机制。

### 飞跃 PHP 7
2015.12.3 PHP 7 问世了，这是 PHP 的一次飞跃。PHP7 修复了大量 BUG ，新增了功能和语法糖。这些改动涉及到了核心包、 GD 库、 PDO 、 ZIP 、 ZLIB 等熟悉和不熟悉的核心功能与扩展包。PHP 7 移除了已经被废弃的函数，如 mysql_ 系列函数在 PHP 5.5 被废弃，在 PHP 7 被删除。PHP 7 的性能高于 HHVM 。并且是 PHP 5.6 的两倍。




## Sort Algorithms


### Bubble
![alt text][bubble-image]

From [Wikipedia][bubble-wiki]: Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list to be sorted, compares each pair of adjacent items and swaps them if they are in the wrong order. The pass through the list is repeated until no swaps are needed, which indicates that the list is sorted.

__Properties__
* Worst case performance	O(n^2)
* Best case performance	O(n)
* Average case performance	O(n^2)
