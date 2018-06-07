# ZhuoxinSocialWebsite
# 卓信社交平台的设计与实现

The designing and programming of the Zhuoxin social platform

作者：邱江坤

[TOC]

## 摘要

作者：邱江坤

随着网络的普遍应用和人民对网络的重视，越来越多的青少年已经意识到网络交友的重要性。现在，网络已经成为人们进行社交活动的重要渠道，成为很多人生活中的一部分。社交型网站除了构建用户的网络形象，更重视将用户到生活动态延伸到互联网，通过网络进一步拓宽交友渠道。拥有一个网站，我们的青少年就可以向将来的朋友提供24小时×365天无间断的自我展现。

在不可避免的互联网交友的大趋势下，如何结交良朋好友是一个大家共同关注的问题。各类社交平台成员良莠不齐，更有甚者充满商业气息。很多青少年苦于无法扩大自己的圈子，而父母担心自己的孩子结交不良青年。

在理念方面，本网站提倡自我展示这一环节，尤其是结交朋友之前的自我展示，而这正式目前在普通社交网站上难以达到的。每一个用户都能被公平对待，而不是依据经济投入而分为三六九等，或为他们搞特权。

本社交平台从青少年、家长的实际需求出发，以PHP为开发技术，Phpstorm为开发工具，MySQL为数据库开发平台，设计过程中,首先建立了系统的应用原型,然后在此基础上进行需求分析,详细设计时不断修正和完善,经过测试阶段反复调试和验证,最终形成达到设计要求的可行系统。最终发布至互联网，为青少年的网络交友提供一个良好的平台。本社交平台在网页方面，综合考虑了页面色彩、页面的构架，充分的利用了图片、文字、图层、表格等元素。网站内容明确，层次清楚，达到了预期的功能。

**关键字： 网站 动态 社交 PHP 数据库 展示**

## ABSTRACT

## 1. 绪论

### 1.1. 研究背景

在Internet飞速发展的今天，互联网成为人们快速获取、发布和传递信息的重要渠道，它在人们政治、经济、生活等各个方面发挥着重要的作用。Internet上发布信息主要是通过网站来实现的，获取信息也是要在Internet“海洋”中按照一定的检索方式将所需要的信息从网站上下载下来。当代的社交很大一部分是通过互联网进行的，已经成熟的产品有很多，比如腾讯公司的qq、微信，新浪、网易等公司的微博、博客，百度的贴吧，各大论坛，以及专门用来相亲的百合网等。

这些社交平台的已经非常庞大，但也存在一些问题，并不适合青少年的交友。

以百度贴吧为例，百度贴吧作为兴趣驱动的平台无疑是成功到，但是，百度贴吧到经济行为极为恶劣，经常可以看到百度将贴吧出售给莆田系医院，坑害患者钱财甚至生命健康的事件；百度贴吧并没有特别针对交友，编辑器功能极差，帖子发表后无法编辑，没有个人展示空间，这样很难满足交友的需要。

### 1.2. 可行性分析

#### 1.2.1. 对现有系统的分析

##### 同类产品

同类产品有腾讯公司的qq、微信，新浪、网易等公司的微博、博客，百度的贴吧，各大论坛，以及专门用来相亲的百合网等。这些产品都或多或少存在一定的问题，必然会损失一些用户，卓信社交平台可以很好地接纳这部份用户。

社交平台并不是互斥的，一个人可以同时利用多个社交平台，甚至越活跃，加入的社交平台数目越多。因此，存在一些同类产品不影响本社交平台的设计、开发、运维和推广。

##### 传统社交手段

传统的社交，一般是同学、同事之间的交往，总之几个人只见存在着一定的联系和关系。很明显传统社交的重要程度不如从前，也不会影响到本平台的推广。

综上所述，现有的系统不会影响本社交平台。

#### 1.2.2. 工作负荷

本社交平台的第一阶段为开发出最小产品，即能够满足、也只能最基本的社交需要。做到这一点的工作量不算很大，完全可以一个人完成。

#### 1.2.3. 费用开支

由于是个人利用空余时间开发，员工的费用为零，时间的费用大概为一个月。一般网站服务器的费用是每月30元，域名为每年50元，均在可接受范围内。此外网上存在免费提供的服务器和及其廉价甚至免费的域名，在用户量上涨之前，完全可以利用。

#### 1.2.4. 人员

网站的设计由本人完成

美工由本人兼任

研发由本人担任

指导由老师完成

测试由同学、朋友和网民完成

以上所有人员已经凑齐，所以在人员方面不存在问题

#### 1.2.5. 设备

网站需要的设备由网络服务器、网络基础设施，此两项已经备有。

网站的开发需要个人电脑、笔记本，已经备齐。

在设备方面上是完全可行的

#### 1.2.6. 局限性

由于缺乏人手，平台的开发速度不会特别快，平台的推广不会有很大的精力去做，平台的盈利不会非常理想。但由于本平台的定位是非营利性质的，以上几条局限性不能影响本平台的可行性。

#### 1.2.7. 社会因素方面的可能性

##### 法律方面的可行性

本平台由本人完成，本人拥有完全的知识产权。其中利用的软件、库均为自由/开源软件，依据其使用协议，可以在非营利情况下使用。本平台不侵犯他人的利益，不危害社会秩序，所以不存在法律方面的问题。

##### 使用方面的可行性

平台可以设计得易于使用，可以发布配套的使用教程，公布联系方式进行一对一解答。此外社交平台存在已久，人们对其使用方法可谓烂熟于心，所以不用担心不会使用的情况。

本平台符合家长的期待、青少年的需求，将会受到他们的欢迎。

#### 1.2.8. 结论

在不以盈利为目的的情况下，此平台的开发是完全可行的。

## 2. 设计架构

### 2.1. 设计理念

当前网站的设计理念有很多，以展现形式来看，有动态、静态网站之分；以编码技术来分，有纯html、html+js、php等技术手段；以编码框架来分，运用最广泛的是MCV架构，此外，还有数据驱动等新型开发框架。

这个网站的设计理念是：为每一个用户提供平等的展现自我、交友的机会。

### 2.2. 展现形式

本社交平台的展现形式为动态网站，这里的动态有多重含义。

#### 网站交互的动态

用户在网站上看到的页面是动态的，移动光标可以看到一些动态交互效果。这些效果样式美观，极大地增强了用户的体验。

本网站的交互动态实现，主要利用了jquery、semantic-ui等技术，这将在下文中详解。

#### 网站内容的动态

网站上的内容都是实时生成的，包括预订好的数据，用户填写、上传的数据等。网站内容的动态的背后，是动态的服务器语言和数据库技术。本网站采用的服务器语言主要是php。

#### 用户交友的动态

网站将会不断有新的成员加入，成员之间的交互是动态的， 这里体现出了网站的设计理念。

### 2.3. 开发架构

本社交平台采用修改过的mvc架构，同时运用OOP思想，依靠良好的设计，在保证执行效率的同时简化了开发的复杂度。

MVC全名是Model View Controller，是模型(model)－视图(view)－控制器(controller)的缩写。

mvc架构好处是将ui和数据解鞣化，使得程序的开发更加迅速，修改起来更加方便。通过mvc，还可以进一步设计成模块化程序，简化编程的复杂度，提高程序的复用性。

#### 模型

模型即数据，如果程序直接读写数据，将来在修改数据模型的时候会遇到很大的问题。在OOP思想中，数据的读取和写入应该由方法实现，并且应该隐藏不必要的细节。

#### 视图

视图即UI，不同类型的UI给人不同种类的视觉体验和操作体验。在mvc架构中，视图不应该直接与数据交互。MVC解鞣化的设计，使得更换视图变得非常容易。

#### 控制器

控制器接管程序的逻辑，程序的核心部分就在控制器中。控制器在更高层面上对程序逻辑进行抽象，提供高层次的方法，供不同的视图调用。

### 2.4. 模块设计

本社交平台的网页采用模块化设计，每一个php文件/库为一个模块。在编写模块的时候，特别注重OOP思想，充分发挥php的功用。

基本上，每一个用户可见页面都有一个php文件，每一个功能板块都有一个php文件，置于action文件夹中。偶尔调用别人的库，别人的库以文件夹为单位组织。在底层，也就是数据层，统一由自己编写的Database类管理数据库的读写。

![网站 mvc 前端](网站-mvc前端.png)

参考上图，上图并不完全，但涵盖了大部分功能。上图的一行为模型、视图、控制器中的一项，箭头为依赖关系。由于良好的设计，卓信社交平台各模块没有循环依赖关系，真正做到了高内聚、低糅合。

由于视图界面需要获取所需信息，少数显示信息的功能直接依赖于Database类。理论上讲，将这些功能独立出来也是完全可以的，只是没有立刻着手去做

### 2.5. 界面设计

本社交平台的界面采用semantic-ui这一UI库，这个UI库的样式美观，功能强大且易于开发。

在页面风格上，网站走的是清新简洁的路线。

### 2.6. 数据库设计

#### 2.6.1 为什么选用MySQL

本网站选用的数据库服务器为MySQL，理由如下：

- MySQL是最流行的、通用性最好的数据库，几乎所有主机提供商都会安装好MySQL，全球多数网站，尤其是论坛、政府网站等中小型网站都首选使用MySQL。MySQL的性能和设计并不是最优秀的，但由于其易于使用、历史较早的优点，吸引了大量的开发者用户。正因为其流行，它的社区及其活跃，很多问题都可以在这里得到解决。

- MySQL是一种关系数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。

- MySQL所使用的 SQL 语言是用于访问数据库的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择 MySQL 作为网站数据库。

- 由于其社区版的性能卓越，搭配 PHP 和 Apache 可组成良好的开发环境。在本人的开发电脑上，就安装了WAMP包，提供了Apache MySQL PHP 在windows系统的支持。

#### 2.6.2 数据库表的设计

本网站的数据库表单如下：

##### commit

commit 表保存了一个用户对另一个用户的评论信息。包含的字段有：

- id  -- 评论的编号
- user1id -- 收到评论的用户
- user2id -- 发送评论的用户
- text -- 评论的文本
- date -- 评论的时间

##### message

message 保存了一个用户对另一个用户的站内消息。包含的字段有：

- id  -- 站内信的编号
- user1id -- 收到站内信的用户
- user2id -- 发送站内信的用户
- text -- 站内信的文本
- date -- 站内信的时间

##### friendship

friendship 保存了一个用户对另一个用户的好友关系。包含的字段有：

- id  -- 好友关系的编号
- user1id -- 好友关系被申请人
- user2id -- 好友关系申请人
- state -- 好友关系是否被接受：0 - 未接受； 1 - 已经接受
- applicate_date -- 好友关系申请时间
- accept_date -- 好友关系通过的时间

##### topic

topic 保存了用户在某一个页面上的话题

- id 话题的编号
- poster 话题的发送者
- text 话题的内容
- postdate 话题的时间
- post_ip 记录了发送话题的人的ip地址
- reply_to 有可能对某人回复，在这里记下来
- show_at 在某一个页面上展示。主页为0

##### user

user 保存了用户的相关信息

- id -- 用户的编号，有时用uid代替
- email -- 用户注册时使用的邮箱
- password -- 用户的密码，通过加盐的md5保存
- realname -- 用户的真实姓名，可选设置但不会公开。在将来可能会用到
- nickname -- 用户的昵称，必填
- gender -- 性别 f 女性 m 男性 s 保密
- birthday -- 生日
- self_introduction -- 自我介绍文本
- intr_id -- 自我介绍页面的编号，目前没有用到
- province -- 省份
- city -- 城市
- relationship_status -- 感情状态，分为单身、已婚、恋爱等
- wanna_down -- 想要交往的朋友的年龄下限
- wanna_up -- 想要交往的朋友的年龄上限
- verified -- 是否验证过邮箱，可根据这一字段对没有验证过的用户做出一定限制，目前没有添加这项功能
- last_login -- 上次登录时间
- signup_date -- 注册时间
- img_path -- 头像的地址，只允许上传图片
- intr_view_times -- 自我介绍被查看的次数
- signup_ip -- 上次登录的ip
- is_admin -- 是否是管理员
- habits -- 兴趣爱好，以空格分割，以urlencode 编码
- reset_key -- 是否需要重置密码
- banned -- 是否被封禁
- bind_openid -- qq开放平台代码，用来和qq进行绑定，以支持第二次qq登录

## 2.7. 后台管理设计

### 2.7.1 后台管理的概念

后台管理是一个网站重要的模块，能否提供一个方便强大的后台，决定了管理的效率。一个后台需要良好的设计，比如提供权限系统、用户管理、消息通知等强大的功能，还要提供一些易用的接口。

#### 2.7.2 后台管理的构成

如前文所述，本社交平台立志于提供一套易于使用的后台。由于社交平台的特殊性，现有的开源后台在功能和构成上无法满足本平台的使用，所以本次的后台需要完全重写。其中，后台的ui参考了X-admin的实现。

本后台由用户管理、消息、高级管理和统计四大部分组成，辅助模块有权限系统，详情请看下图：
![后台架构](网站-后端.png)

##### 用户管理

提供了管理用户的方法，管理员有权限查看、封禁和删除不符合相关法律法规的用户及其发表文章，但不可以修改用户的信息。管理员使用本模块的功能需要相应的权限。

##### 消息

拥有权限的管理员可以利用本模块推送消息。推送的消息分为两种，一种是站内信，另一种是邮件，可以选择一到两项发送。管理员只要有相应权限，还可以查看用户发送过的站内信和评论。

##### 高级管理

可以在这里登记新的管理员和配置相应权限。管理员的等级有不同之处。本系统目前不需要过于复杂的管理员权限，所以实现得仅仅够用。

以下为可以控制的权限

- user_level
- see_user
- ban_user
- see_admin
- cancel_admin
- send_message
- delete_message
- send_email
- delete_user
- see_message
- see_commits
- see_topics
- delete_commit
- see_intro

高级管理模块为user_level 大于1000的超级管理员开放mysql接口，方便其进行没有提供的管理方式。

##### 统计

统计模块提供了百度统计的接口，以及网站自动测速的接口，可以方便站长查看网站的运行情况。

## 3. 开发技术及实现细节

### 3.1. PHP

PHP（外文名:PHP: Hypertext Preprocessor，中文名：“超文本预处理器”）是一种通用开源脚本语言。语法吸收了C语言、Java和Perl的特点，利于学习，使用广泛，主要适用于Web开发领域。PHP 独特的语法混合了C、Java、Perl以及PHP自创的语法。它可以比CGI或者Perl更快速地执行动态网页。用PHP做出的动态页面与其他的编程语言相比，PHP是将程序嵌入到HTML（标准通用标记语言下的一个应用）文档中去执行，执行效率比完全生成HTML标记的CGI要高许多；PHP还可以执行编译后代码，编译可以达到加密和优化代码运行，使代码运行更快。

php相对于其它语言具有以下有点：

#### 开放源代码

所有的PHP源代码事实上都可以得到。

#### 免费性

和其它技术相比，PHP本身免费且是开源代码。

#### 快捷性

程序开发快，运行快，技术本身学习快。嵌入于HTML：因为PHP可以被嵌入于HTML语言，它相对于其他语言。编辑简单，实用性强，更适合初学者。

#### 跨平台性强

由于PHP是运行在服务器端的脚本，可以运行在UNIX、LINUX、WINDOWS、Mac OS、Android等平台

#### 效率高

PHP消耗相当少的系统资源。

#### 图像处理

用PHP动态创建图像,PHP图像处理默认使用GD2。且也可以配置为使用image magick进行图像处理。

#### 面向对象

在php4,php5 中，面向对象方面都有了很大的改进，php完全可以用来开发大型商业程序。

#### 专业专注

PHP支持脚本语言为主，同为类C语言。

#### 应用广泛

由于PHP的时间非常早，技术成熟，所以PHP的应用非常广泛。PHP有着庞大的用户群体，他们构成的技术社区是无法比拟的。
![网页服务器语言](php_rank.png)

### 3.2. MySQL

选用MySQL的理由：

- 体积小、速度快、总体拥有成本低，开源；
- 支持多种操作系统；
- 是开源数据库，提供的接口支持多种语言连接操作
- mysql的核心程序采用完全的多线程编程。线程是轻量级的进程，它可以灵活地为用户提供服务，而不过多的系统资源。用多线程和C语言实现的MySql能很容易充分利用CPU；
- MySql有一个非常灵活而且安全的权限和口令系统。当客户与MySql服务器连接时，他们之间所有的口令传送被加密，而且MySql支持主机认证；
- 支持ODBC for Windows， 支持所有的ODBC 2.5函数和其他许多函数， 可以用Access连接MySql服务器， 使得应用被扩展；
- 支持大型的数据库， 可以方便地支持上千万条记录的数据库。作为一个开放源代码的数据库，可以针对不同的应用进行相应的修改。
- 拥有一个非常快速而且稳定的基于线程的内存分配系统，可以持续使用面不必担心其稳定性；
- MySQL同时提供高度多样性，能够提供很多不同的使用者介面，包括命令行客户端操作，网页浏览器，以及各式各样的程序语言介面，例如C+，Perl，Java，PHP，以及Python。你可以使用事先包装好的客户端，或者干脆自己写一个合适的应用程序。MySQL可用于Unix，Windows，以及OS/2等平台，因此它可以用在个人电脑或者是服务器上；

### 3.3. html & javascript

#### 3.3.1. html

说在前面：网页开发，实质上都是生成html文档。
万维网上的一个超媒体文档称之为一个页面（外语：page）。作为一个组织或者个人在万维网上放置开始点的页面称为主页（外语：Homepage）或首页，主页中通常包括有指向其他相关页面或其他节点的指针（超级链接），所谓超级链接，就是一种统一资源定位器（Uniform Resource Locator，外语缩写：URL）指针，通过激活（点击）它，可使浏览器方便地获取新的网页。这也是HTML获得广泛应用的最重要的原因之一。在逻辑上将视为一个整体的一系列页面的有机集合称为网站（Website或Site）。超级文本标记语言（英文缩写：HTML）是为“网页创建和其它可在网页浏览器中看到的信息”设计的一种标记语言。

网页的本质就是超级文本标记语言，通过结合使用其他的Web技术（如：脚本语言、公共网关接口、组件等），可以创造出功能强大的网页。因而，超级文本标记语言是万维网（Web）编程的基础，也就是说万维网是建立在超文本基础之上的。超级文本标记语言之所以称为超文本标记语言，是因为文本中包含了所谓“超级链接”点。

它通过标记符号来标记要显示的网页中的各个部分。网页文件本身是一种文本文件，通过在文本文件中添加标记符，可以告诉浏览器如何显示其中的内容（如：文字如何处理，画面如何安排，图片如何显示等）。浏览器按顺序阅读网页文件，然后根据标记符解释和显示其标记的内容，对书写出错的标记将不指出其错误，且不停止其解释执行过程，编制者只能通过显示效果来分析出错原因和出错部位。但需要注意的是，对于不同的浏览器，对同一标记符可能会有不完全相同的解释，因而可能会有不同的显示效果。  _-- 百度百科_

#### 3.3.2. javascript

JavaScript一种直译式脚本语言，是一种动态类型、弱类型、基于原型的语言，内置支持类型。它的解释器被称为JavaScript引擎，为浏览器的一部分，广泛用于客户端的脚本语言，最早是在HTML（标准通用标记语言下的一个应用）网页上使用，用来给HTML网页增加动态功能。

在1995年时，由Netscape公司的Brendan Eich，在网景导航者浏览器上首次设计实现而成。因为Netscape与Sun合作，Netscape管理层希望它外观看起来像Java，因此取名为JavaScript。但实际上它的语法风格与Self及Scheme较为接近。 _-- 百度百科_

### 3.4. jquery

jQuery是一个快速、简洁的JavaScript框架，是继Prototype之后又一个优秀的JavaScript代码库（或JavaScript框架）。jQuery设计的宗旨是“write Less，Do More”，即倡导写更少的代码，做更多的事情。它封装JavaScript常用的功能代码，提供一种简便的JavaScript设计模式，优化HTML文档操作、事件处理、动画设计和Ajax交互。

jQuery的核心特性可以总结为：具有独特的链式语法和短小清晰的多功能接口；具有高效灵活的css选择器，并且可对CSS选择器进行扩展；拥有便捷的插件扩展机制和丰富的插件。jQuery兼容各种主流浏览器，如IE 6.0+、FF 1.5+、Safari 2.0+、Opera 9.0+等。 _-- 百度百科_

### 3.5. semantic-ui

semantic-ui是一套美观的网页ui的实现，其目的是为了更快地设计赏心悦目的网站Semantic作为一款开发框架，帮助开发者使用对人类友好的HTML语言构建优雅的响应式布局。

semantic-ui拥有简洁的 HTML语法,其中词语和类(css clases)是可以相互替换的概念。它直观的使用自然语言中的语法，词汇和语序等来定义一个类(css class)。

可以使用直观明了的 Javascript，Semantic 使用被叫做 behaviors 的简单短语来触发功能。

### 3.6. 具体页面实现

#### 3.6.1. 主页

![主页图](网站-index.png)

主页被设计成为一个非常美观大方的页面，同时起到了展示用户的功能，站点的部分功能在主页得到体现。主页上方为菜单栏，用户可以通过菜单栏进入所需的功能页面。当管理员登录后，菜单会附加“进入后台”一项，点击后即可进入网站的后台。

主页在移动平台的表现和电脑端有一定的区别：移动端的顶部导航栏会消失，但会出现一个按钮，触及按钮，会出现侧边栏。
![移动端侧边栏效果展示](mobile.png)

主页下方有额外的功能区，比如热度排名、最近登录。
![热度排名](hot_rank.png)

#### 3.6.2. 登录

![登录页面](login.png)
登录界面要求输入邮箱和密码，在忘记密码时可以点击忘记密码进行重置。

本社交平台已经开通了qq登录，qq登录后可以新建帐号，或与已有帐号绑定，此后不需要记忆本站的账号和密码。

#### 3.6.3. 个人主页

![个人主页](front_profile.png)
个人主页被设计为一个单页面的网页，主要功能是展示用户的基本信息和自我介绍。个人主页分为几大功能区，如图，有个人资料区，自我介绍区，好友展示区和评论区。可以添加对方为好友，可以给对方发送消息。
个人主页配合其他页面，共同构成了本社交平台的核心功能。

#### 3.6.4. 编辑资料

个人主页上的资料都是可以编辑的，我们提供了强大而易于使用的markdown编辑器，用户可以编写带有格式的自我介绍。
![编辑基本资料](edit_settings.png)
![编辑资料](edit_profile.png)



#### 3.6.5. 我的好友

所有添加过的好友、被添加的好友都会在这里显示。可以接触好友关系，审核通过好友请求。点击好友的昵称可以进入ta的个人主页。从而进行更多操作。
![我的好友](friends.png)

#### 3.6.6. 我的消息

![我的消息](my_messages.png)
每一条消息都会在这里显示出来，单击某条消息，会进入与对方的对话模式，所有给对方发送的消息和从对方收到的消息都会显示出来。

#### 3.6.7. 搜索好友

![搜索好友](search.png)
这是搜索界面，可以根据提示选择搜索的条件，将会显示出同时复合条件的用户。

#### 3.6.8. 联系我们

![联系我们](contact_us.png)
在输入框内填写自己的信息，会以邮件方式通知管理员。

如果已经登录，邮箱和昵称会自动填好。

#### 3.6.9. 客户端下载

![客户端下载](android_ios.png)
社交平台配套开发了安卓客户端和苹果客户端，点击下载链接即可下载安装，其中苹果客户端没有在appstore上发布，所以需要越狱。

#### 3.6.10. 注册

![注册](sign_up.png)

这时注册页面，需要填写的内容有邮箱地址、昵称、生日、密码和性别。为避免恶意注册，本网站开启了验证码和邮箱验证功能，需要通过这两项验证才能完成注册。

#### 3.6.11. 服务协议

注册时必须接受服务协议。
![服务协议](privacy.png)

#### 3.6.12. 后台页面--主页

![后台主页](back_index.png)

后台页面的样式是统一的，左侧为侧边栏，上方为标题栏，次上方为标签栏，中间为操作区。
后台主页主要显示了服务器的基本信息。

#### 3.6.13. 后台页面-管理用户

![管理用户](back_usermanage.png)

管理用户页面可以对用户进行搜索、删除和封禁，但不能对用户进行修改。

#### 3.6.14. 后台页面-发布通知

![发布通知](back_messageposter.png)
发布通知支持发送站内信和电子邮件，支持选择用户发送通知。

#### 3.6.15. 后台界面-管理管理员

![管理管理员](back_manage_admin.png)
可以在这里管理管理员的资料。授予管理员权限或取消管理员身份。

#### 3.6.16. 百度统计

![百度统计](baidu_statistatic.png)
这里百度统计嵌入到了网站后台中，方便网站的管理员查看网站的流量情况，优化网站。百度统计在国内是起步最早、功能最强的互联网网站统计平台，在此选用了百度统计。

### 3.7. 网站安全

网站出现安全问题，全部源于编写的程序的bug。这类bug上至操作系统，下到编程语言，再到自己的网站。通常bug出现在自己编写的网站上。

关于网站的安全，我已经用相应的网络软件扫描过了，我可以确信，我对所有的字段都进行了过滤，防御了常见的攻击方法，如MySQL注入攻击，跨站脚本攻击。

>[12:34:36] [CRITICAL] all tested parameters do not appear to be injectable. Try to increase values for '--level'/'--risk' options if you wish to perform more tests. If you suspect that there is some kind of protection mechanism involved (e.g. WAF) maybe you could try to use option '--tamper' (e.g. '--tamper=space2comment')

上述文档为sqlmap对登录界面的测试结果。sqlmap为专业的自动化检测和攻击的sql注入工具。结果表明，sqlmap的漏洞不存在。

本人没有做跨站请求伪造的防御，因为本社交平台无特别重要的信息，亦无危险操作。下面的page参数代表了搜索好友的页码，被跨站请求显然无危险。

>[12:39:28] [INFO] heuristic (XSS) test shows that POST parameter 'page' might be vulnerable to cross-site scripting (XSS) attacks

一些攻击类型无法防御，比如拒绝服务类攻击，这次攻击以大流量干扰正常服务为主要特征，除了加大网站的宽带（即使这样也是效果慎微），至今无法有效防御。

## 4. 后续工作

### 3.6. 网站空间

本网站对网站空间的要求是php+mysql。最高性能的配置是自己购买服务器和宽带，这样的价格最高。通常的选择是在线租用服务器，价格稍微低廉一些，同时网上也有免费提供的服务器。

### 3.7. 域名

域名（英语：Domain Name），简称域名、网域，是由一串用点分隔的名字组成的Internet上某一台计算机或计算机组的名称，用于在数据传输时标识计算机的电子方位（有时也指地理位置）。

网域名称系统（DNS，Domain Name System，有时也简称为域名）是因特网的一项核心服务，它作为可以将域名和IP地址相互映射的一个分布式数据库，能够使人更方便的访问互联网，而不用去记住能够被机器直接读取的IP地址数串。

本社交平台在阿里云上购买了<http://zhuoxinsocial.top/> 作为域名。域名在购买后需要在购买处填写解析记录，在网站空间绑定域名，这样才可以通过域名访问网站。

### 3.8. 统计

一般网站的统计功能借助于第三方统计平台实现，比较常见的有百度统计、谷歌统计、腾讯分析、阿里云统计等。统计功能可以查看站点的被访问情况，分析来访者的分布和兴趣所在，进一步优化站点从，而提高站点的访问量。

由于本人曾经用过百度统计，卓信社交平台继续沿用了百度统计。百度统计是百度推出的一款免费的专业网站流量分析工具，能够告诉用户访客是如何找到并浏览用户的网站，在网站上做了些什么，有了这些信息，可以帮助用户改善访客在用户的网站上的使用体验。

## 5. 设计理念的体现

### 5.1. 人人平等

本社交平台的设计理念之一为人人平等，体现在每个人都有展现自我的机会。每个用户登录后，都会出现在“最近登录”的最前端，直到有下一位用户登录。
_不像QQ，QQ添加好友的时候资料不多，且没有一个公开的交友平台。_

另一方面，人人平等意味着没有特权，不搞收费，让青少年更容易地交到良朋好友。

### 5.2. 公开交友

本社交平台为交友提供了一个公开的交友平台，每个用户的自我介绍都有机会被其他用户查看、搜索。

### 5.3. 基于自我展示

这是本社交平台的核心部分，每位用户有且仅有一个用户界面，用以填写个人自我介绍，展示自己的兴趣和志向。这时最适合交友的方式。为避免虚假信息，我们会对他人的自我介绍进行验证，来净化本社交平台。

## 6. 效果验证

### 6.1. 用户评价

据同学们的使用评价，本社交平台页面美观，功能强大，符合一个社交平台的功能和定位。他们对社交平台的理念也是非常赞叹。

### 6.2. 自我感想

从萌生想法到最终开发完成，成功在网站上启用时，那种喜悦是无法言语的。刚开始编写网页时，我只会最基本的html，我基本上边学边写，完成了第一版网页。后来学习编写了一套wap页面。在学习和编码的过程中，发现这一版的设计拙劣，已经无法继续优雅地写下去了，于是推倒重来，顺便取代了第二版的wap。由于有第一、二次编写的经验，第三次编写非常快速，UI也有了大的进步。

## 7. 未来展望

### 7.1. 对未来的展望

本社交平台设计良好，页面美观，内容新颖，想法独到，有进一步发展的前景。

我会根据用户的反馈，进一步改善网站状况。

网站已经找到了合伙人，在网站的前期，我提高技术，对方进行市场宣传，为求扩大用户数量。有了一定基数的用户之后，应该适当地更换更好的服务器，或利用更高级的语言重写网站，进一步丰富网站的内容和功能。这时还可以开放捐赠方式，希望能减轻服务器的租赁费用。如果网站发展迅速，我会考虑扩大管理团队的人数，但会坚持非商业的营业模式，坚持回馈青少年用户。

推广方面，主要为在已有的平台推广，也凭用户的口口相传。将来可能会加入实名认证功能，新用户有一定的操作权限，认证过的用户拥有特殊的标识，此举有利于营造良好的平台环境。

### 7.2. 不足之处

如前文所述，本社交平台基本上实现了自己的任务，可以应对一定数目有社交需求的青少年用户。不过，本社交平台还是有一定的不足之处的。

首先，由于是个人开发，无法将大量时间和精力投入到网站建设和推广中去，网站性能有待进一步优化，市场应该进一步拓宽。不难得知，制作一个网站需要大量的知识和技术储备，技术栈多而杂，还需要美术方面的知识，这很难被同一个人精通。本人的技术仅是够用，能独立完成是特例，期间边开发边学习，占据了多数时间。在界面的布局和美观程度上需要进一步优化，这最好是找相关专业人士完成。

本社交平台的后台和服务器配置薄弱，这有待进一步提高。

## 参考文献

<https://www.w3cschool.cn/>

