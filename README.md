# back-end技术分享会系列01
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

**TIOBE 8月编程语言排行1-20**
![image](https://github.com/yuud/back-end/blob/master/1565506765653.jpg)

## PHP概念
PHP原始为Personal Home Page的缩写，已经正式更名为 "PHP: Hypertext Preprocessor"。

### PHP官方解释
PHP is a popular general-purpose scripting language that is especially suited to web development.
Fast, flexible and pragmatic, PHP powers everything from your blog to the most popular websites in the world.

### 发展历程
#### 问世
1994年，拉斯姆斯·勒多夫（Rasmus Lerdorf）创造了 PHP，事实上这个时候的 PHP 只是用 Perl 语言编写的一系列 CGI 脚本，用于跟踪他在线简历的访问情况，统计他自己网站的访问者。勒多夫把这些 CGI 脚本命名为“Personal Home Page Tools”。这里我们姑且称之为 PHP 1 吧！但这个早期的 PHP Tools 并不是一门语言，只是一些工具，提供基本的变量，并使用嵌入式HTML句法自动处理表单变量。

#### PHP 2
由于勒多夫写的这个小程序轻巧且简便，吸引了很多人的关注，在1995年，勒多夫发布了 PHP/FI 2.0。这个FI是一个可以做 SQL 查询的东西，2.0是其更新版本。这次发布了一个基本完善的工具包，它不仅可以访问数据库，还能嵌入 HTML 中动态处理数据。新的工具包，吸引了很多的程序开发者，其中包括 Zeev Suraski（泽埃夫·苏拉斯基）和 Andi Gutmans（安迪·古曼兹），他们后来加入到了PHP3的开发当中。

#### PHP 3
在1997年中，开始了第三版的开发计划，开发小组加入了 Zeev Suraski 及 Andi Gutmans。1998年末，PHP 3 第一个官方正式版发行，其特点是具有更好的执行效果和更清晰的结构。此外，该版本最强大的地方在于它的可扩展性，这点吸引的大量的开发人员加入并提交新的 PHP 扩展模块。


#### PHP 4
在 PHP 3 发布不久，Zeev Suraski 及 Andi Gutmans 就开始投入到 PHP 4 的开发当中，主要目标是增强程序运行性能和 PHP 自身的模块性。新的 PHP 核心被称为“Zend”引擎（两名开发者的缩写），由 C 语言编写，相同的 PHP 脚本在新版本中运行，性能提高了近十倍。在千禧年（2000年），PHP 4 正式发布。

主要增加了以下特征：

* 各种web服务器的支持
* 丰富的数组操作函数
* 完整的会话机制
* 对输出缓存的支持
* 增加了对类和对象的支持，是 PHP 面向对象的雏形

#### 新时代 PHP 5
尽管，PHP 发展势头之猛，但相比较其他语言如 Java 来说，还有很多问题。面向对象的支持不够完善，无法捕获异常（Exception）等，这导致多年以来 PHP 一直被认为是一门面向过程的语言（即使在 PHP 5 发布后）。2004年7月，PHP 5 正式发布，这标志着 PHP 一个新时代的到来。并且往后多年，PHP 一直在 5 这个版本上迭代，是 PHP 历时最长的一个大版本。
它的核心采用的是第二代 Zend 引擎，并引入了对 PECL 模块的支持。PHP 5 最大的特点是引入了面向对象的全部机制。

#### 飞跃 PHP 7
2015.12.3 PHP 7 问世了，这是 PHP 的一次飞跃。PHP7 修复了大量 BUG ，新增了功能和语法糖。这些改动涉及到了核心包、 GD 库、 PDO 、 ZIP 、 ZLIB 等熟悉和不熟悉的核心功能与扩展包。PHP 7 移除了已经被废弃的函数，如 mysql_ 系列函数在 PHP 5.5 被废弃，在 PHP 7 被删除。PHP 7 的性能高于 HHVM 。并且是 PHP 5.6 的两倍。

#### 发展现状
据相关信息得知全球前100万的站点中有70%左右的站点用PHP开发，它与Linux/Mysql/Apache/Nginx等组成黄金搭档，无论是成本的投入还是开发的周期，选择PHP都是一个不错的选择。

特别是在今天互联网迅速发展的今天，PHP凭着速度快、开发成本低、周期短、后期维护费用低、开源产品丰富等优势快速在市场上占领先机，这些优势也是其它语言无法比拟的。PHP技术和相关的人才，正是迎合目前的互联网的发展趋势，更多的PHP开发人员凭借着高工龄就可以领到高薪酬。

#### 负面消息
PHP 兼 Zend 联合创始人 Zeev Suraski 宣布从 Zend 离职。
![image](https://github.com/yuud/back-end/blob/master/666666.jpeg)

Zeev Suraski 在推特上的自我介绍是 PHP 联席架构师（Co-Architect of PHP）、Zend 联合创始人（Co-founder of Zend）。事实上，Zeev Suraski 是一名以色列程序员，他和另一名以色列程序员 Andi Gutmans 以及其他程序员一起发展了由 Rasmus Lerdorf 创建的 PHP 语言。

1997年，Andi Gutmans 和 Zeev Suraski 重写了 Rasmus Lerdorf 的 PHP-FI，这份作品被作为 PHP 3 发布。1998年，他们全部重新设计了 PHP 的语法解析器，并将它命名为 Zend 引擎。PHP 4 是第一个基于 Zend 引擎的产品，这一产品也获得了巨大的成功。1999年，两人共同创立了 Zend 公司，公司名字正是 Zeev 和 Andi 两人名字的结合。

由于在技术方面的权威性，Zend 公司及其创建者在 PHP 以及开源社区中持续处于领导的核心地位，对于 PHP 的迅猛发展起到了强力推动作用。Zend 公司也因此被认为是开源 PHP 语言的“官方团队”。

Zend 公司是一家 PHP 公司，一家企业和个人都可以在此寻求到专业技术解决方案的领先公司，它为推动 PHP 进入企业级应用提供了巨大的支持。

另外，Zend 公司也开发了多个知名的产品，包括 IDE、PHP 引擎和框架等。例如 Zend Studio（PHP IDE）、Zend Engine（PHP 解析引擎）、Zend framework（PHP 开发框架）、Zend Guard 和 Zend Optimizer 等。

Zeev Suraski 暂未透露离职的原因及后续的下一步计划。而对于 PHP 而言，虽然两位核心人物均已从 Zend 公司离职，但 PHP 作为一个有强大社区作为支撑的开源项目，相信并不会有太大的影响。

## PHP语言特点
* 1、开放源代码，所有的PHP源代码事实上都可以得到。


* 2、免费性，php和其它技术相比，PHP本身免费且是开源代码。


* 3、快捷性，程序开发快，运行快，技术本身学习快。嵌入于HTML：因为PHP可以被嵌入于HTML语言，它相对于其他语言。编辑简单，实用性强，更适合初学者。


* 4、跨平台性强，由于PHP是运行在服务器端的脚本，可以运行在UNIX、LINUX、WINDOWS、Mac OS下。


* 5、专业专注，PHP支持脚本语言为主，同为类C语言。


* 6、效率高PHP消耗相当少的系统资源。


* 7、面向对象，在php4, php5 中，面向对象方面都有了很大的改进，php完全可以用来开发大型商业程序。


* 8、图像处理，用PHP动态创建图像,PHP图像处理默认使用GD2。且也可以配置为使用image magick进行图像处理

## 轻松一刻
某程序员对书法十分感兴趣，退休后决定在这方面有所建树。于是花重金购买了上等的文房四宝。一日，饭后突生雅兴，一番磨墨拟纸，并点上了上好的檀香，颇有王羲之风范，又具颜真卿气势，定神片刻，泼墨挥毫，郑重地写下一行字：hello world.

## php语言特点
```
<?php
//变量:int/float/string/boolen/array/obj/null/resource(8种)，弱语言类型,$a = 12与 $a = '12'

//底层实现
/**
typedef union _zend_value{
	long aval;
	double val;
	struct {
		char *val;
		int len;
	} str;
	hashTable *ht;
	zend_object_value object;
}zend_value
*/

//字符串函数strlen|strrev|str|strpos
//数组函数array_pop|array_push|array_merage|array_map
//web应用核心技术 框架技术(php)+第三方库+队列(kafka|rabbitmq|activemq)+mysql+redis+elasticsearch+(大数据+Ai:TensorFlow)

echo "hello world!";
?>
```



## 软件开发主要分为以下几个阶段
* 1、问题定义
确定好要解决的问题是什么（what），通过对客户的访问调查，系统分析员扼要的写出关于问题性质、工程目标和工程规模的书面报告，经过讨论和必要的修改之后这份报告应该得到客户的确认。

* 2、可行性研究
确定该问题是否存在一个可以解决的方案。这个阶段的任务不是具体解决问题，而是研究问题的范围，套索这个问题是否值得去解决，是否有可行的解决办法。可行性研究的结果是客户做出是否继续进行这项工程的决定的重要依据，一般来说，只有投资可能取得较大的效益的那些工程项目才值得继续进行下去。

* 3、需求分析
深入具体的了解用户的需求，在所开发的系统要做什么这个问题上和用户想法完全一致。明确目标系统必须做什么，确定目标系统必须具备哪些功能。通常用数据流图、数据字典和简要的算法表示系统的逻辑模型。用《规格说明书》记录对目标系统的需求。

* 4、概要设计（总体设计）
概括的说，应该怎样实现目标系统，设计出实现目标系统的几种可能方案，设计程序的体系结构，也就是确定程序由哪些模块组成以及模块之间的关系。

* 5、详细设计
实现系统的具体工作，编写详细规格说明，程序员可以根据它们写出实际的程序代码。详细设计也称模块设计，在这个阶段将详细的设计每个模块，确定实现模块功能所需的算法和数据结构。

* 6、编码和单元测试（编码占全部开发工作量的10%-20%）

* 7、综合测试（测试占全部开发工作量的40%-50%）
分为集成测试和验收测试。

* 8、软件维护
通过各种必要的维护活动使系统持久的满足用户的需求。主要分为 改正性维护、适应性维护、完善性维护、预防性维护。

* 9、软件交付
软件产品包括：程序、文档、数据

## 我的后端之路
* 接触PHP编程的时间（2009，大三下半学期一个选修大作业，大部分用asp）
* 2010～2018技术路线
  * 基于开源系统的二次开发（ecshop）
  * 基于开源框架的二次开发（thinkphp/laravel/phalcon）
  * 基于公司原有技术平台的衍生产品开发（人人店小程序/erp api接口/soap应用）
  * 基于具体业务的开源技术开发（资管系统: node做抓取，solr/elasticsearch做搜索引擎，php写业务接口）
* 写程序的实质（数据结构+算法）
* 专业知识对开发工作的影响（软件工程:开发模型[瀑布模型,快速原型,增量模型,螺旋模型]/软件生命周期/程序流程图/UML统一建模语言，数据结构|操作系统|计算机网络|高等数学|计算机英语）
* 未来的技术规划与展望
  * 大数据|Ai|5G
    * Hadoop, Hibase, TensorFlow,  
  * 紧跟时代，将所学应用于公司实际工作

小结：进步最快的方式：师徒制做项目，从项目实践中学习，踩坑->挖坑->填坑熟能生巧

## 现阶段及未来社会对后端人才的综合素质要求
* 多面多种技术混合型人才（java+php+go+python+nodejs+linux+tensorflow+运维+测试+安全+算法）
* 快速学习及落地应用
* 全面考虑及风控预案
* 开发效率管理与合作
* 技术沉淀/归纳/文档能力

## 一枚码农的自我修养
* 码农的学习充电（极客，网易云课程，技术茶话会，技术分享会，同行切磋交流）
* 码农的转型之路（技术leader/项目主管/Cto）
* 码农的解压方法:蹦迪？跑步/爬山/钓鱼/看动漫...
