# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0308springboot基于Web手工艺品销售系统的开发与实现

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 绪论
## 1.1 选题背景
当人们发现随着生产规模的不断扩大，人为计算方面才是一个巨大的短板，所以发明了各种计算设备，从结绳记事，到算筹，以及算盘，到如今的计算机，都是在无法满足生产的前提下出现的。随着计算机的发展，又出现了互联网技术。到现在为止，互联网已经发展了几十年了，在几十年的时间里就已经风靡世界。各行各业都发现了计算机的好处，计算机刚开始是军用的，后来在民用行业开始使用，到互联网时代，各种行业信息如井喷一般充斥着互联网，信息产生和传播的速度不断的提高。针对互联网的优点，结合互联网，对传统行业信息处理技术进行升级是非常有必要的。本课题对于手工艺品销售信息的管理方面，开发一个手工艺品销售系统，在信息管理方面不至于混乱，也能降低数据的出错率，数据安全方面也有了保证，该系统还有其他的优点，比如优化信息处理流程，降低信息泄露风险，减少资金投入，产出更高，让管理人员的工作更有效率等。所以说，手工艺品销售系统是目前不可缺的，对使用者相当的重要。
## 1.2 选题意义
如今的年代，已经是步入信息社会了，不仅信息更新速度频繁，信息量也大，在信息时代必须有相应的处理信息的方法，如果还采用以前的结绳记事或者笔写纸记，不仅是信息录入效率上赶不上节奏，在信息检索的速度上更是让人无法承受。幸而当今社会上计算机技术发展的相当不错，可以通过计算机在信息处理上面实现自动化或者半自动化的作业，采用计算机技术，能有效的提高信息录入以及信息检索的效率，社会上相同行业之间本身就是效率高的淘汰效率低的，既然采用计算机来替代手工记录，必然是效率更高，稳定性更强，成本更低等诸多优点。针对于手工艺品销售信息管理，开发一个手工艺品销售系统不仅可以实现现代化的信息管理，也更符合现代化信息管理规范。

在实际的使用效果中，手工艺品销售系统的意义如下：

第一点：手工艺品销售系统的出现，就是为了提高工作人员的效率，能够在规定时间完成工作任务。

第二点：操作页面符合人体工程美学，符合日常人为操作习惯，使用友好。

第三点：区别于传统用纸张记录，提高了信息化水平。

第四点：在信息处理方面，极大的降低了人工处理成本。
## 1.3 研究内容
本文对系统的描述过程将按照绪论，系统开发技术，分析，设计，实现，测试等环节进行展开介绍。

绪论：本节内容主要展示研究该系统的背景和意义。

系统开发技术：本节内容主要展示该系统开发中需要使用的技术和搭建的开发环境。

系统分析：本节内容主要就是分析系统，包括性能，功能上的数据分析，也包括可行性分析等内容。

系统设计：本节内容主要就是根据系统分析的结果进行设计，主要包括功能和数据库的设计。

系统实现：本节内容主要就是通过程序编码对系统的功能进行实现，同时也对需要介绍的功能进行界面运行效果的展示。

系统测试：本节内容主要就是对系统的功能实现部分进行检测，发现系统的错误并及时纠正，让系统能够保证运行无误。
# 2 系统开发技术
对系统的开发需要做好准备工作，其中安装开发的工具以及学习开发中需要运用的技术都是需要提前进行的，本节内容就对开发中运用的工具还有技术进行阐述。
## 2.1 MySQL数据库
本设计用到的数据库就是MySQL数据库，之所以用到这个数据库的原因很多。首先，从满足功能需求上面来讲，MySQL是符合的；其次，从学习程度来讲，MySQL相比其他数据库不管是从安装还是使用上面来讲，都比较简单，最重要的是学习起来相当便捷，比较容易入手；再次，MySQL数据库对电脑要求不高，不管是什么样的电脑都可以安装MySQL数据库，并且并不会对电脑性能造成过多的影响。所以，就平常普普通通的电脑就可以作为开发用的电脑，不需要进行额外的电脑升级。虽然自从MySQL数据库被Oracle数据库收购后，有了一些闭源的风险，但是使用者还是很多，MySQL数据库目前的开发人员已经超过五百人了，对数据库开发者来讲已经是一个很大的开发团队了。MySQL在使用上面来讲，普通的增删改查操作已经可以满足大部分业务需求，像一些数据导出导入，以及一些函数，都可以满足一些不同的需求，最重要的是MySQL数据库可以创建索引，可以大大的提高数据的查询效率，当然，物极必反，如果因为索引好用而滥用，索引弄得比数据库表还要多，这样会造成MySQL数据库更新表数据时候的运行效率。总而言之，MySQL数据库在本次设计的使用上，是完全符合使用要求的。
## 2.2 IDEA简介
IDEA的诞生在Java集成开发工具行业正所谓平地起雷，瞬间震动了整个Java开发行业。真的是每个人用过的都说好。IDEA之所以相比于其他比如MyEclipse或者Eclipse之类的Java开发工具来讲比较好，原因首先在于设计方面。IDEA采用了所谓的人体工程学设计原理，让使用IDEA的人员用了就忘记不了。软件打开首先要设置主题，可以选择常规的白色或者暗色系列，长时间的白色或者长时间的暗色会让开发人员的眼睛疲劳加重，首先从这个细节就让程序开发人员备受青睐，让程序员看着舒服；然后再对一些常用性插件进行归类，让程序的开发注重于提升生产效率，而不是一味的让开发者找各种插件，有时候插件之间的版本还会存在不兼容，IDEA就把兼容的插件双手呈现，如此贴心的IDEA怎么能让人不喜爱。所以选择IDEA用来开发本项目就理所当然的了。
## 2.3 Spring Boot框架
Spring是一个很好的框架，但是发展到现在，在使用上面已经诟病不断，需要配置的越来越多，配置大于开发，让程序员用更多的精力去配置Spring，有点本末倒置了。Spring Boot框架是为了解决Spring框架的缺点而生，Spring框架好用是好用，但是配置起来相当的繁琐，Spring Boot则让简化了很多配置过程，让开发变得更有趣也更有效率，并且学过Spring框架的开发人员很容易理解Spring Boot框架，没有用过框架的人员学习Spring Boot框架的速度也很快的，Spring Boot得到了Java开发者的一致好评。
## 2.4 Vue框架
Vue框架的开发者是一个中国人，区别于其他框架的最核心的概念就是渐进式框架，Vue的出现，让网页前端的开发变成了一种纯前端职业，不需要在考虑后台数据类型以及业务逻辑，只需要进行数据绑定即可，大大的减少了前端开发工程师的学习难度。Vue是当前世界上最火的一种前段框架，学习成本比较低，只需要熟悉最基本的网页知识就可以理解相关知识，并且有很好的免费教程进行学习，有各个国家语言的教程，尤其是因为是中国人开发的框架，让中国的高级程序开发人员做了汉语教程。Vue框架发展之初就是高于IE8版本的，所以说只要是当前的主流浏览器都支持Vue框架，如果是很旧的那种电脑是不支持的，必须安装支持HTML5的浏览器才可以访问用Vue发布的站点。

# 3 系统分析
对于手工艺品销售系统开发设计到的流程有，分析系统的功能，设计系统的结构，设计数据库，编码以及测试，其中，在系统分析中，所做的工作包括功能的确定，性能的分析等。
## 3.1 可行性研究
手工艺品销售系统开发实现分析需要从不同的角度来进行分析可行性，比如从时间角度，经济角度，甚至操作角度。从不同的角度分析可行性会让手工艺品销售系统开发具体化，进而达到辩证开发的正确性。
### 3.1.1 经济可行性
从经济方面分析是第一要素，没有经济的支持，任何项目都如水中捞月，无法实现。实现手工艺品销售系统，开发过程不需要额外的经济条件，用本人现有的计算机就可以实现，这方面不需要额外的支出。
### 3.1.2 时间可行性
手工艺品销售系统设计主要作为毕业设计，在题目确定之后，答辩之前使用的项目，对不同的开发进度上面都有时间的要求，总不至于答辩完成后才能实现功能，这个肯定不行，所以从时间上来分析项目的工作量，发现是可行的，符合正常开发时间。
### 3.1.3 操作可行性
操作必须符合正常人的思维模式，市面上有很多符合要求的程序正在使用中，可以借鉴其他程序的操作流程，变成符合本设计的操作流程，在操作上面进行无缝衔接，让使用者操作过程中不会感到迷茫。

从上面的角度来分析，后续工作可以继续进展。
## 3.2 系统性能分析
性能分析是软件开发过程中必不可少的一个环节，主要是为了降低软件在使用的过程中的容错率。通常来讲，分析软件系统的性能一般从以下几个方面进行分析。
### 3.2.1 系统的安全性
系统开发出来就是让正常使用的，那么在如今的互联网时代，首先考虑的就是安全性的问题。如果系统的安全性不够，那么使用价值就会降低。如果出现使用过程中丢失数据，那么用户就不再信赖，所以系统的安全性是第一要位，只有安全性存在了，才能考虑使用的问题，总不至于今天用户注册，明天用户账号泄露，这些都是不友好的。所以账号一般在数据库里存储会通过MD5进行加密，这样关键数据加密可以保证系统的安全性。
### 3.2.2 系统的易用性
安全性分析处理完毕，才考虑易用性。一个软件设计得符合操作规范，符合正常人类的理解逻辑，那么在使用上面就会很舒服，如果违背了这条原则，安全性再高的软件也是设计失败的，毕竟软件开发出来就是让人使用的，这一点尤为重要。
### 3.2.3 系统的健壮性
系统设计易用不代表没有规则，那么系统设计使用方面必须健壮，必须符合软件处理逻辑。比如设计一个价格类的输入框，用户需要输入价格，那么可以设定输入框最多两位小数的纯数字输入，如果用户不小心输入了其他字符，那么就会友好的提示让用户修改正确，只有输入符合规范的数据，才能进行提交，并且存储到数据库里。系统的健壮性就是这样，越是规范，越是健壮，有助于用户理解，还有助于程序使用。
## 3.3 系统流程分析
系统设计不是胡乱的设计，必须符合软件设计思想，具体的流程参考下图。系统设计的前期就是做各种分析，功能的设计，数据库的设计等，等一切都设计好了，逻辑上没有问题，符合设计流程和设计规范，才可以继续编码环节，编码只是实现设计的一个环节而已。

![](/md/blog.001.png)

图3.1系统开发流程图

用户是一切应用的基础，只要牵扯到用户，那么肯定需要用户进行注册，只有这样才能让注册的用户进行使用。如果用户没有注册，只能算是游客，那么只能访问一些大众用户可以浏览的信息，如果需要用户操作的部分是不允许访问的，这样能极大的保证用户的权利。用户注册流程用下面的图来表示，主要是先判断用户名，只有用户名能用了才可以进行后面的信息注册。

![](/md/blog.002.png)

图3.2 注册流程图

当需要用户登录的时候，肯定是要验证的，只有验证通过的用户才可以进行下一步操作，用户登录成功代表着用户模块的功能对登录用户进行了开放。流程就是如下面的图所示。

![](/md/blog.003.png)

图3.3 登录流程图
## 3.4 系统功能分析
在对设计的总体要求理解了之后，就要把要求给具体化，也就是功能化，要尽量的把每个功能模块和模块之前的关系理清楚，必须符合正常人的行为逻辑才可以，并且尽量研究同类型的项目，这样能避免走弯路，最终才能得到设计的具体功能。

手工艺品销售系统把操作该系统的用户群分为三类，即管理员，商家，用户。

管理员对于手工艺品销售系统操作的功能包括管理手工艺品信息，管理手工艺品求购信息，管理商家和用户，管理论坛帖子以及基础数据信息等。其用例图如图3.4所示：

![](/md/blog.004.png)

图3.4 管理员用例图

管理员功能包括个人中心，管理员管理，基础数据管理，论坛管理，手工艺品管理，公告信息管理，手工艺品求购管理，商家管理，用户管理，轮播图管理等功能模块。

个人中心：主要是让管理员更改个人信息，更改密码等；

管理员管理：主要是让管理员增删改查其他管理员的信息；

基础数据管理：主要包含手工艺品类型管理，订单类型管理，公告类型管理，商家信用类型管理，主要是对这些信息增删改查管理；

论坛管理：让管理员增删改查论坛帖子信息，以及查看论坛帖子回复；

手工艺品管理：主要包括手工艺品管理，手工艺品评价管理，手工艺品订单管理这三个子模块，主要用于管理手工艺品信息，回复手工艺品评价信息，管理手工艺品订单等；

公告信息管理：管理员增删改查公告；

手工艺品求购管理：用户发布并管理手工艺品求购信息，管理员也能增删改查手工艺品求购信息；

商家管理：管理员增删改查商家信息；

用户管理：管理员增删改查用户信息；

轮播图管理：管理员增删改查轮播图信息；

管理员登录：管理员登录手工艺品销售系统才可以使用其功能；

商家对于手工艺品销售系统操作的功能包括管理手工艺品信息，回复用户对手工艺品的评价，管理手工艺品的订单，查看手工艺品求购信息等。其用例图如图3.5所示：

![](/md/blog.005.png)

图3.5 商家用例图

商家包括个人中心，手工艺品管理，公告信息查看，手工艺品求购查看等功能模块。

个人中心：主要是让商家更改个人信息，更改密码等；

手工艺品管理：主要包括手工艺品管理，手工艺品评价管理，手工艺品订单管理这三个子模块，主要用于商家管理手工艺品信息，回复手工艺品评价信息，管理手工艺品订单等；

公告信息查看：商家查看公告，查询公告；

手工艺品求购管理：用户发布并管理手工艺品求购信息，商家查看手工艺品求购信息，查询手工艺品求购信息；

商家注册登录：商家注册手工艺品销售系统，然后登录系统；

用户对于手工艺品销售系统操作的功能包括发布和管理手工艺品求购，在前台购买手工艺品，管理收货地址，管理购买的手工艺品信息，查看商家，在在线论坛模块发帖以及评论帖子等。其用例图如图3.6所示：

![](/md/blog.006.png)

图3.6 用户用例图

用户功能包括个人中心，在线论坛，手工艺品信息，公告信息，商家信息，购物车，手工艺品求购信息，手工艺品求购管理，注册登录等功能模块。

个人中心：用户在该模块更改个人信息，管理收货地址，管理手工艺品订单等；

在线论坛：用户发布帖子，评论查看的帖子等；

手工艺品信息：用户查询手工艺品，对手工艺品的介绍进行查看，以及购买手工艺品；

公告信息：用户查询并查看公告；

商家信息：用户查询并查看商家；

购物车：用户通过购物车下单结算需要购买的手工艺品；

手工艺品求购信息：查看非本人发布的手工艺品求购信息；

手工艺品求购管理：用户增删改查手工艺品求购信息；

注册登录：用户注册手工艺品销售系统，然后登录；



# 4 系统设计
系统在设计的过程中，必然要遵循一定的原则才可以，胡乱设计是不可取的。首先用户在使用过程中，能够直观感受到功能操作的便利性，符合正常思维逻辑的操作，这才是系统好用的一个开端，给使用者第一印象就是这个系统设计的相当不错。
## 4.1 系统设计原则
系统遵循设计原则进行开发，会有很多可以预料到的好处，只要遵循了设计原则，那么开发出来的系统必然是有质量保证的。

首先第一条原则就是安全性原则：程序必须设定角色管理，不同的角色有不同的功能模块，不同的角色登录都需要输入相对应的账号和密码，否则不允许进行操作相对应的权限。每个用户登录只能修改自己的密码，不需要对别的账号进行密码或者其他资料的修改，否则就违背了安全性原则的设定。

其次第二条原则就是易用性原则：符合安全性只是功能的符合，不代表操作就符合，所以要设定易用性原则。易用性原则就是规定程序符合操作流程，正常人的思维定向为基础，在不违背程序运行逻辑定义的情况下，必须使用简单，操作规范，让每个用户使用起来都能看到页面，就能感知功能模块的作用，短时间的就能使用程序，达到易用效果。

再次第三条原则就是实用性原则：实用性代表着花里胡哨的功能必须抛弃，尽量符合数据处理的简洁性，不仅需要这样进行设定，还需要有预知性，系统后期可能会出现的功能模块尽量要解耦，与程序设定要模块化体现，这样才能达到扩展性。

第四条原则就是准确性原则：准确性原则的唯一定义就是准确，包含数据输入格式的准确，数据处理的准确，以及数据存储的准确。程序里面关于数据准确才有存在的意义，如果一堆不相干的数据存在是没有任何用处的，甚至会产生各种问题，所以必须要保证数据的准确性。

第五条原则是易维护原则：易维护代表着程序运行必须是可控的状态，如果不可控出现各种问题，那么所有的工作都是空谈。程序开发中对于各种程序判定异常，必须有统一的处理模式，异常是程序开发中不可避免的，但是可以对出现的异常进行抛出，有助于程序异常处理的复盘，只要每个异常都能定位准确，那么代表程序设计是趋于完美的，维护起来会更加的方便，只要有助于程序维护的都必须给予支持。
## 4.2 功能模块设计
对管理员具体功能的设计结果将以图4.1所示的管理员功能结构图来进行体现。管理员对于手工艺品销售系统操作的功能包括管理手工艺品信息，管理手工艺品求购信息，管理商家和用户，管理论坛帖子以及基础数据信息等。

![](/md/blog.007.png)

图4.1 管理员功能结构图

对商家具体功能的设计结果将以图4.2所示的商家功能结构图来进行体现。商家对于手工艺品销售系统操作的功能包括管理手工艺品信息，回复用户对手工艺品的评价，管理手工艺品的订单，查看手工艺品求购信息等。

![](/md/blog.008.png)

图4.2 商家功能结构图

对用户具体功能的设计结果将以图4.3所示的用户功能结构图来进行体现。用户对于手工艺品销售系统操作的功能包括发布和管理手工艺品求购，在前台购买手工艺品，管理收货地址，管理购买的手工艺品信息，查看商家，在在线论坛模块发帖以及评论帖子等。

![](/md/blog.009.png)

图4.3 用户功能结构图
## 4.3 数据库设计
用户通过系统的功能操作来进行数据交互，包括数据的添加，数据的更新，数据的删除，数据的查询等基本功能操作，表面上虽然是操作系统界面提供的功能，但是实际上系统的这些数据是在数据库当中进行访问与操作的。目前市场上可供选择的存储数据的数据库有很多，除了简单版的Access之外，还有SQL Server，DB2，Informix，MySQL等关系型数据库可供选择，由于关系型数据库具有固定的表结构，以及对数据一致性要求比较强，所以相比没有固定表结构以及具有灵活的数据格式的非关系型数据库而言，在程序配套数据库的选择中，关系型数据库的使用率更高。本系统选择MySQL来存放数据，其相关理论以及技术在经过了很长时间的发展之后，变得非常成熟，各大网络平台都公开分享其开发源码，而且其对计算机的配置要求很低，不需要过多内存进行安装，很符合本系统对于数据库的选择要求。
### 4.3.1 数据库E-R图
本节需要对系统中存放在数据库中的数据进行充分分析，对数据的实体，实体特征，联系等进行确定，然后通过概念模型的表示方法即E-R图进行表达，在E-R图绘制工具中，选择椭圆，菱形框，矩形等形状表达实体属性，实体间联系，实体这些信息，使用实线段将这些形状进行连接即可。初步完成E-R图之后，需要进行检查，及时进行有误数据的更改，删除实体间存在的冗余联系，删除E-R图中冗余的数据，最终要展示一个内容准确的E-R图。

（1）手工艺品包括的属性有手工艺品照片，手工艺品库存，手工艺品原价等。其属性图如下。

![](/md/blog.010.png)

图4.4 手工艺品实体属性图

（2）手工艺品订单包括的属性有购买数量，订单类型，支付类型等。其属性图如下。

![](/md/blog.011.png)

图4.5 手工艺品订单实体属性图

（3）商家包括的属性有商家名称，联系方式，邮箱等。其属性图如下。

![](/md/blog.012.png)

图4.6 商家实体属性图

（4）用户包括的属性有用户头像，性别，电子邮箱等。其属性图如下。

![](/md/blog.013.png)

图4.7 用户实体属性图

（5）设计的各实体间关系E-R图如下。

![](/md/blog.014.png)

图4.8 实体间关系E-R图
### 4.3.2 数据库表结构
在指定的数据库里面对数据表进行创建命名，然后设计各个数据表的存储结构，需要对该数据库的操作非常熟悉，并且还需要学习并掌握一定的数据表设计方面的知识，比如数据命名，作为系统的开发人员，为了避免程序运行产生乱码现象以及为了确保系统的正常运行，在对数据表进行命名时，一般都是采用英文名称，同时在对数据表的字段进行编辑时，也是采用英文的方式进行，为了方便今后对数据表的设计内容进行更改或查看，对一些比较重要的字段都会进行中文备注，或者是使用中文进行字段描述。设计期间，也需要对各个字段选择合适的数据类型以及设置匹配的取值范围，当一张数据表设计完成之后，还要对该表的主键进行标注，就是为了确保该数据表的唯一性与独立性。

![打开新的 phpMyAdmin 窗口](/md/blog.015.png "打开新的 phpMyAdmin 窗口")表4.1 收货地址表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(20)|否|
|yonghu\_id|创建用户|int(20)|否|
|address\_name|收货人|varchar(200)|否|
|address\_phone|电话|varchar(200)|否|
|address\_dizhi|地址|varchar(200)|否|
|isdefault\_types|是否默认地址|int(11)|否|
|insert\_time|添加时间|timestamp|否|
|update\_time|修改时间|timestamp|否|
|create\_time|创建时间 |timestamp|否|
表4.2 购物车

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|yonghu\_id|所属用户|int(11)|是|
|goods\_id|手工艺品|int(11)|是|
|buy\_number|购买数量|int(11)|是|
|create\_time|添加时间|timestamp|是|
|update\_time|更新时间|timestamp|是|
|insert\_time|创建时间|timestamp|是|
表4.3 论坛表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|forum\_name|帖子标题|varchar(200)|是|
|yonghu\_id|用户|int(11)|是|
|users\_id|管理员|int(11)|是|
|forum\_content|发布内容|text|是|
|super\_ids|父id|int(11)|是|
|forum\_state\_types|帖子状态|int(11)|是|
|insert\_time|发帖时间|timestamp|是|
|update\_time|修改时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|
表4.4 手工艺品表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|shangjia\_id|商家|int(11)|是|
|goods\_name|手工艺品名称|varchar(200)|是|
|goods\_photo|手工艺品照片|varchar(200)|是|
|goods\_types|手工艺品类型|int(11)|是|
|goods\_kucun\_number|手工艺品库存|int(11)|是|
|goods\_old\_money|手工艺品原价|decimal(10,2)|是|
|goods\_new\_money|现价|decimal(10,2)|是|
|goods\_clicknum|点击次数|int(11)|是|
|shangxia\_types|是否上架|int(11)|是|
|goods\_delete|逻辑删除|int(11)|是|
|goods\_content|手工艺品简介|text|是|
|insert\_time|上架时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|
表4.5 手工艺品评价表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|goods\_id|手工艺品|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|goods\_commentback\_text|评价内容|text|是|
|insert\_time|评价时间|timestamp|是|
|reply\_text|回复内容|text|是|
|update\_time|回复时间|timestamp|是|
|create\_time|创建时间|timestamp|是|
表4.6 手工艺品订单表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|goods\_order\_uuid\_number|订单号|varchar(200)|是|
|address\_id|收货地址|int(11)|是|
|goods\_id|手工艺品|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|buy\_number|购买数量|int(11)|是|
|goods\_order\_true\_price|实付价格|decimal(10,2)|是|
|goods\_order\_types|订单类型|int(11)|是|
|goods\_order\_courier\_name|快递公司|varchar(200)|是|
|goods\_order\_courier\_number|快递单号|varchar(200)|是|
|goods\_order\_payment\_types|支付类型|int(11)|是|
|insert\_time|订单创建时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|
表4.7 公告信息表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|news\_name|公告标题|varchar(200)|是|
|news\_types|公告类型|int(11)|是|
|news\_photo|公告图片|varchar(200)|是|
|insert\_time|添加时间|timestamp|是|
|news\_content|公告详情|text|是|
|create\_time|创建时间|timestamp|是|
表4.8 手工艺品求购表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|qiugou\_name|手工艺品名称|varchar(200)|是|
|goods\_types|手工艺品类型|int(11)|是|
|qiugou\_new\_money|求购价格|decimal(10,2)|是|
|yonghu\_id|用户|int(11)|是|
|insert\_time|添加时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|
表4.9 商家表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|username|账户|varchar(200)|是|
|password|密码|varchar(200)|是|
|shangjia\_name|商家名称|varchar(200)|是|
|shangjia\_phone|联系方式|varchar(200)|是|
|shangjia\_email|邮箱|varchar(200)|是|
|shangjia\_photo|营业执照展示|varchar(200)|是|
|shangjia\_xingji\_types|商家信用类型|int(11)|是|
|new\_money|现有余额|decimal(10,2)|是|
|shangjia\_content|商家简介|text|是|
|shangjia\_delete|逻辑删除|int(11)|是|
|create\_time|创建时间 |timestamp|是|
表4.10 管理员表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|bigint(20)|否|
|username|用户名|varchar(100)|否|
|password|密码|varchar(100)|否|
|role|角色|varchar(100)|是|
|addtime|新增时间|timestamp|否|
表4.11 用户表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|username|账户|varchar(200)|是|
|password|密码|varchar(200)|是|
|yonghu\_name|用户姓名|varchar(200)|是|
|yonghu\_phone|用户手机号|varchar(200)|是|
|yonghu\_id\_number|用户身份证号|varchar(200)|是|
|yonghu\_photo|用户头像|varchar(200)|是|
|sex\_types|性别|int(11)|是|
|yonghu\_email|电子邮箱|varchar(200)|是|
|new\_money|余额|decimal(10,2)|是|
|create\_time|创建时间|timestamp|是|
![打开新的 phpMyAdmin 窗口](/md/blog.015.png "打开新的 phpMyAdmin 窗口")



# 5 系统实现
下面主要是通过功能实现界面截图的形式，并且运用文字来描述功能实现界面的内容。
## 5.1 管理员功能实现
### 5.1.1 商家管理
该功能主要用于实现对商家基本信息的管理，商家管理界面的运行效果见图5.1。在此界面，管理员根据商家名称查询商家，可以修改，删除商家资料。商家资料包括商家名称，联系方式，商家信用类型，营业执照等信息。

![](/md/blog.016.png)

图5.1 商家管理界面
### 5.1.2 论坛管理
该功能主要用于实现对论坛帖子基本信息的管理，论坛管理界面的运行效果见图5.2。在此界面，管理员修改帖子内容，删除需要删除的帖子信息，可以对论坛帖子的回复信息进行查看等。

![](/md/blog.017.png)

图5.2 论坛管理界面
### 5.1.3 手工艺品求购管理
该功能主要用于实现对手工艺品求购基本信息的管理，手工艺品求购管理界面的运行效果见图5.3。在此界面，管理员新增手工艺品求购信息，对手工艺品求购信息包括手工艺品名称，求购价格，手工艺品类型等信息进行查询，修改等。

![](/md/blog.018.png)

图5.3 手工艺品求购管理界面
## 5.2 商家功能实现
### 5.2.1 手工艺品管理
该功能主要用于实现对手工艺品基本信息的管理，手工艺品管理界面的运行效果见图5.4。在此界面，商家对手工艺品信息进行修改，手工艺品信息包括手工艺品原价，现价，手工艺品照片，手工艺品名称等信息，商家可以在手工艺品管理界面增加手工艺品库存，减少手工艺品库存以及下架手工艺品，上架手工艺品等。

![](/md/blog.019.png)

图5.4 手工艺品管理界面
### 5.2.2 手工艺品评价管理
该功能主要用于实现对手工艺品评价基本信息的管理，手工艺品评价管理界面的运行效果见图5.5。在此界面，商家回复评价手工艺品的用户，查看用户评价手工艺品的内容。

![](/md/blog.020.png)

图5.5 手工艺品评价管理界面
### 5.2.3 手工艺品订单管理
该功能主要用于实现对手工艺品订单基本信息的管理，手工艺品订单管理界面的运行效果见图5.6。在此界面，商家可以根据手工艺品名称，手工艺品类型以及用户姓名等条件来实现对手工艺品订单的查询操作，同时可以查看手工艺品订单详情。

![](/md/blog.021.png)

图5.6 手工艺品订单管理界面
## 5.3 用户功能实现
### 5.3.1 手工艺品信息
手工艺品信息界面的运行效果见图5.7。在此界面，用户可以查看手工艺品信息界面右侧区域的系统推荐信息，可以通过立即购买功能实现对手工艺品的快速下单。

![](/md/blog.022.png)

图5.7 手工艺品信息界面
### 5.3.2 确认下单
确认下单界面的运行效果见图5.8。在此界面，用户检查收货地址信息是否正确，检查购买的手工艺品的信息是否正确，查看总价以及实际支付价格，最后支付。

![](/md/blog.023.png)

图5.8 确认下单界面
### 5.3.3 手工艺品订单
手工艺品订单界面的运行效果见图5.9。在此界面，用户查看所有的手工艺品订单信息，包括已评价，已发货等手工艺品订单信息，用户根据个人需要对手工艺品订单进行相应操作。

![](/md/blog.024.png)

图5.9 手工艺品订单界面
### 5.3.4 购物车
购物车界面的运行效果见图5.10。在此界面，用户可以把需要购买的手工艺品都放入购物车保存，然后统一下单支付购买的手工艺品，这样既方便又节省时间。

![](/md/blog.025.png)

图5.10 购物车界面

# 系统










