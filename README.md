# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50253wxapp懂球短视频微信小程序SpringBoot

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


﻿懂球短视频微信小程序





**本 科 毕 业 设 计（论 文）**


`  `题目：懂球短视频微信小程序

understand the ball short video wechat applet

学生姓名                        

学    号                        

指导教师                        

学    院                        

专    业                        

交稿日期  

摘要
#########
在网络与微信小程序不断地发展，小程序技术不断发展的今天。对于一些球员和足球爱好者来说，需要时时刻刻了解，自己及自己所喜欢的足球赛事的相关信息，比赛赛事的相关事宜，比赛比分的相关信息，各个懂球短视频的小组赛。每场赛事球员发挥情况，比如查询自己所喜欢的足球视频、懂球视频、分享视频等这样才能更好的推动我国的体育事业发展,为此今后有必要对体育的发展做出更加深入的探索和研究。

对于懂球短视频微信小程序当然也不能排除在外，随着小程序的不断成熟，带动了懂球短视频微信小程序分享网站 ，它彻底改变了过去传统的管理方式，不仅使服务管理难度变低了，还提升了管理的灵活性。这种个性化的平台特别注重交互协调与管理的相互配合，激发了管理人员的创造性与主动性，对懂球懂球短视频小程序而言非常有利。

本系统采用的数据库是Mysql，小程序端采用微信开发者，结合后台eclipse使用jav语言开发，在设计过程中，充分保证了系统代码的良好可读性、实用性、易扩展性、通用性、便于后期维护、操作方便以及页面简洁等特点。

**关键词：**懂球短视频微信小程序；SSM框架；Mysql数据库；小程序
#########
**Abstract**

Today, with the continuous development of network and wechat applet and the continuous development of applet technology. For some players and football lovers, they need to know the relevant information about themselves and their favorite football events, the relevant matters of the game, the relevant information of the game score, and the group matches of each short video. The performance of players in each event, such as querying their favorite football videos, understanding videos and sharing videos, can better promote the development of China's sports. Therefore, it is necessary to make more in-depth exploration and Research on the development of sports in the future.

Of course, wechat applet for understanding ball short video can not be excluded. With the continuous maturity of applet, wechat applet sharing website for understanding ball short video has been driven. It has completely changed the traditional management mode in the past, which not only reduces the difficulty of service management, but also improves the flexibility of management. This personalized platform pays special attention to the mutual cooperation between interactive coordination and management, which stimulates the creativity and initiative of managers, and is very beneficial to the short video applet of understanding the ball.

The database used in this system is mysql, and the small program side is developed by wechat developers combined with background eclipse and Jav language. In the design process, it fully ensures the good readability, practicability, easy scalability, universality, easy later maintenance, convenient operation and concise page of the system code.


Key words: understand the ball short video wechat applet; SSM framework; Mysql database; Applet



目  录

[1 绪论	1](#_Toc32748)

[1.1 选题的背景	2](#_Toc21944)

[1.2 研究的主要内容	3](#_Toc10698)

[1.3 系统开发的意义	4](#_Toc26081)

[1.4 初步设计方法与实施方案	5](#_Toc26081)

[1.5 本文研究内容	6](#_Toc26081)

[2 开发环境和相关技术	7](#_Toc7845)

[2.1 系统的开发环境	8](#_Toc11116)

[2.2 技术路线	9](#_Toc9553)

[2.2.1 Java技术	9](#_Toc18090)

[2.2.2 SSM框架	9](#_Toc9848)

[2.2.3微信小程序简介	9](#_Toc10417)

[2.2.4 B/S架构	9](#_Toc13707)

[2.2.5 Eclipse环境配置	9](#_Toc10417)

[2.2.6 MySQL环境配置	9](#_Toc13707)

[3 系统的可行性研究及需求分析	1](#_Toc11036)0

[3.1 可行性研究	1](#_Toc12797)1

[3.1.1 经济可行性分析	1](#_Toc29386)1

[3.1.2 技术可行性分析	1](#_Toc19331)2

[3.2 需求分析	1](#_Toc18737)3

[3.2.1 用户需求分析	1](#_Toc29386)4

[3.2.2 功能需求分类	1](#_Toc19331)4

[3.2.3 网站性能需求分析	1](#_Toc29386)4

[3.3 系统流程分析	1](#_Toc18737)5

[3.4 网站现状分析	1](#_Toc18737)6

[4 系统的总体设计与实现	1](#_Toc22148)7

[4.1 总体设计	1](#_Toc13268)8

[4.2 数据库设计	1](#_Toc10943)9

[4.2.1 概念模型设计	2](#_Toc29063)0

[4.2.2 物理模型设计	21](#_Toc3674)

[5 系统的详细设计与实现	2](#_Toc21468)2

[5.1 管理员功能模块（服务端）	2](#_Toc14038)3

[5.2 用户功能模块（微信端）	](#_Toc2709)24

[6 系统测试	2](#_Toc4131)5

[结论	2](#_Toc16166)6

[致谢	2](#_Toc16166)7

[参考文献	2](#_Toc6115)8




V
![](/md/blog.001.png)

1 绪论

1.1选题的背景

随着微信小程序的普及和快速发展，线上管理系统被广泛的使用，有很多机构或、企业等都在实现小程序信息化管理，懂球短视频微信小程序也不例外，由比较传统的人工管理转向了电子化、信息化、系统化的管理。

传统的懂球懂球短视频，一开始都是管理者进行手工记录，然后将手工记录的信息进行分享；随着小程序的普及，懂球懂球短视频演变成了手机记录后，输入小程序进行分享。这两种管理方式，对管理员来说工作量大，不单要在球赛现场仔细观察、记录，后期足球视频还需要花费大量时间。而且这种存储的方式，容易出现遗失或因为失误输入错误的信息等等。在这些基础上，我把用小程序技术开发的懂球短视频微信小程序作为我的毕业设计，希望可以解决传统懂球懂球短视频分享中出现的问题，简化球赛管理员的工作，对各种信息进行系统化、电子化的管理。                             

1.2 研究的主要内容

研究的基本内容：本设计主要是实现一个懂球短视频微信小程序，实现懂球短视频微信小程序的自动化、信息化、管理简单。系统的主要的设计原则是：以实际应用为核心，重点突出“实用、易用、简洁、稳定”的优点。既能够注重到实效，满足现实用户的实际需要，也能够为系统以后的升级和扩展留有一定的余地。在技术设计的实现上，突出“实现合理、结构清晰、简单易懂”的特点。

本系统的主要目的在于加速懂球短视频微信小程序的信息化进程，充分利用计算机与手机技术和现代通讯的手段面向懂球视频、或分享视频的服务。建立一个方便管理的懂球短视频微信小程序的平台，方便信息资源的共享，提高管理的效率，为管理员、用户提供辅助的懂球短视频微信小程序服务。本系统将最大程度地提高懂球短视频整体的工作效率和工作质量，降低管理和工作的成本，改善工作的环境和条件，提高懂球短视频的管理和决策的自动化和科学化水平。帮助开发者节省费用，减少中间环节，优化业务流程，提高整体效率，促进管理的进步。

1.3 系统开发的意义

随着互联网技术的发展，人们的生活无处不在的受到互联网技术影响，而互联网技术给人们生活带来的便利是不言而喻的。对于现代化的懂球短视频微信小程序而言，它的目的并不是减少管理员的工作量，而是让管理者们从繁琐的信息填写过程中解脱出来，将更多的关注点放到关注体育的状态等，这样就可以提高体育关注，提高懂球短视频的爆光率，所以开发本系统是十分有意义的。
## 1.4初步设计方法与实施方案
软件体系结构方案：由于本系统需要在不同设备上都能运行，而且小程序配置要求也要越低越好，为了实现这一要求，经过考虑B/S结构成为最佳之选。使用B/S结构的系统可以几乎在任何小程序上运行，只要浏览器可以正常工作就可以正常运行该系统，而且后期维护及二次修改较为容易，符合要求。

操作后台系统方案：Windows10操作系统，该系统是目前微软公司推出的最新系统，目前大多数市面上的小程序都使用该系统，并且该系统功能完善，兼容性好。开发工具：选用微信开发者、 Eclipse、java语言。
## 1.5 本文研究内容
本文主要分为七个章节，第一部分为绪论，主要介绍了目前小程序技术发展状况、懂球短视频微信小程序行业发展阶段，分析传统懂球短视频微信小程序的弊端以及使用信息技术来管理。

第二部分为相关技术简介，主要介绍了各技术的发展历程，技术发展现状，技术优点以及选用该技术的原因等。

第三部分为系统分析，主要分析了软件设计所需要的功能。

第四部分为系统设计，主要进行了系统的架构设计、数据库设计等。

第五部分为系统详细设计。

第六部分为系统调试与测试，利用测试方法进行可行性测试、性能测试、系统测试等。

第七部分为总结与致谢，主要总结了程序设计的完成过程及完成情况，比对完成设计过程中施以援手的同学和老师表达中心的感谢和祝愿。




2 开发环境和相关技术

2.1系统的开发环境

懂球短视频微信小程序的开发环境主要有：

开发框架：SSM

语言：Java

服务器：tomcat7

数据库：mysql 5.7

开发软件：微信开发者、Eclipse

浏览器：谷歌浏览器

2.2技术路线
## 2.2.1 Java技术
Java是由Sun公司推出的一门跨平台的面向对象的程序设计语言。因为Java 技术具有卓越的通用性、高效性、健壮的安全性和平台移植性的特点，而且Java是开源的，拥有全世界最大的开发者专业社群，所以Java的发展迅速。

2.2.2 SSM框架

开发信息管理系统的主流框架是SSM（Spring + Spring MVC + MyBatis）[4]，SSM框架web层使用Spring MVC框架，使传输前后端数据变得简单；对于业务层使用Spring框架作为轻量级控制反转(IoC)和面向切面(AOP)[5]的容器框架；对于相关SQL操作，采用Mybatis作为持久层框架，对JDBC进行封装[6]，使得数据库的底层面向开发者操作处于一种透明状态。
## 2.2.3微信小程序简介
微信小程序的开发框架是微信所独有的一套框架，分为View视图层和App Service逻辑层两部分。框架提供了一种类似于Web中html语言的wxml语言，作为视图层的标签语言，用于构造页面的布局。另外提供了一种类似Web中css语言的WXSS语言，作为视图层的标签样式语言，用于表述页面的显示。而在逻辑层的框架，则同样使用了JS语言。微信小程序为了使开发者专注在代码的逻辑层面和数据处理上，还专门提供了两种解决方案，一种是事件，一种是数据的传输。这两种方案都位于小程序框架的视图层和逻辑层之间。会员在视图层进行交互之后，传递到逻辑层对数据进行处理，并返回数据到视图层向会员反馈。对于微信小程序视图层的开发设计，小程序官方提供了一系列的组件，这些基本组件可以极大的帮助开发者完成视图层的开发。同时，对于逻辑层的开发，小程序官方提供了一系列API来方便开发者请求一些额外功能。
## 2.2.4 B/S架构
B/S的系统是通过能上网的电脑就可以使用，它最大的优点是不需要安装专门的软件，首先浏览器向服务器发出请求，然后服务器处理请求把信息再返回给浏览器。不需要再次对数据进行存取与计算数据，只要负责显示数据来降低要求，如果说会员端像个“瘦子”，而服务器会越来越“胖”。B/S体系结构与C/S体系结构相比，最大的不同是：B/S体系的应用软件使用网络浏览器作为与会员交互的平台，而C/S则需要开发专用的应用程序。

![2009318052962238](/md/blog.002.png)

图2-1 B/S结构图
## **2.2.5 Eclipse环境配置**
安装完Eclipse后选择Eclipse“Window->Preferences”

（1）配置Eclipse的jre为sun的jdk，不要用Eclipse的默认jdk：

选择“java->Installed JREs”,勾中里面的“jdk1.7”.

（2）配置编译的级别为6.0：

选择“Compiler->Compiler compliance level”的值为“6.0”。

（3）配置Eclipse的默认的文件编码格式为“UTF-8”：

`   `选择“General->Workspace”，选中“Text file encod”下面的“Other”，设置里面的值为“UTF-8”。

（4）去掉Eclipse的java的验证：

选择“Eclipse->Validation”,将“Build”列的所有勾都给去掉,这样在编译时因为避免了java的验证，所以编译的速度会快很多.
## **2.2.6 MySQL环境配置**
（1）本系统的数据使用的是MySQL,所以要将MySQL安装到指定目录，如果下载的是非安装的MySQL压缩包，直接解压到指定目录就可以了。然后点击C:\Program Files\MySQL\bin\winMySQLadmin.exe这个文件其中C:\Program Files\MySQL是MySQL安装目录。输入winMySQLadmin的初始会员、密码（注：这不是MySQL里的会员、密码）随便填不必在意，确定之后右下角任务的启动栏会出现一个红绿灯的图标，红灯亮代表服务停止，绿灯亮代表服务正常，左击这个图标->winnt->install the service 安装此服务，再左击这个图标->winnt->start the service 启动MySQL服务。

（2）修改MySQL数据库的root密码。用cmd进入命令行模式输入如下命令:

cd C:\Program Files\MySQL\bin

MySQLadmin -u root -p password 123

回车出现Enter password: ，这是要输入原密码. 刚安装时密码为空,所以直接回车，此时MySQL 中账号 root 的密码被改为 123 安装完毕。









3系统的可行性研究及需求分析

3.1 可行性分析

可行性分析是系统开发过程中的的非常重要的一步，可行性研究是指在开发系统时，先对整体系统的所有的需求，所需要使用的技术和在开发时候需要用到的方法，以及开发所需要的的人员，资金等各方面的综合考虑之后，再对该系统是否符合实际开发的要求进行评估，满足实际要求之后再进行实际的开发工作。一般的可行性分析包括：技术可行性、经济可行性可行性等；

研究的目的就是使用最小的代价和最短的时间来确定问题是否能够完善解决。该系统的可行性分析主要包括以下几个方面的内容。

3.1.1 经济可行性分析

懂球短视频微信小程序，主要面向的是小程序用户，成本并不高，对于系统的维护和调试，只需要一个人就可以完成，所以在人力方面，投入的也很少。虽然说人力和资金的投入并不多，但是面临的收益是十分可观的，在21世纪，很多企业、公司等都会将管理的目标转移到线上管理，知识是无价的。在未来，很多企业投入的人力资源和资金不会太多，但却又能保证企业运转继续进行。这对整个企业的发展是非常有利的。

3.1.2 技术可行性分析

懂球短视频微信小程序的开发使用了比较成熟的企业级项目开发的模式。使用微信开发者、Eclipse作为开发工具，数据库使用MySQL。以java语言为基本，使用SSM框架搭建工程环境，结合自身的实际项目开发能力，完全可以开发出比较完善的懂球短视频微信小程序。 

3.2 需求分析

3.2.1用户需求分析

用户根据账号登陆进入懂球短视频微信小程序，系统根据用户的角色展示相应的功能权限。用户进入小程序系统前台后，可以修改个人信息，可以查询懂球视频、上传视频、分享视频、收藏视频等，并查看详情，。

3.2.2 功能需求分析

根据一般懂球短视频微信小程序的功能需求分析，本系统的功能模块如下：

（1）在个人中心，管理员可以修改自己的用户名和登录密码。

（2）在用户管理模块中，可以查看用户的信息，和进行修改、删除。

（3）在上传视频模块中，用户上传视频,管理员审核上传视频。

（4）在懂球视频模块中，在懂球视频页面，管理员可进行视频名称、用户账号、用户姓名、视频 封面、上传时间、作者增删改查操作。

（5）在收藏视频模块中，用户可通过自己喜欢的视频进行收藏。

3.2.3 网站性能需求分析

对网站性能进行分析，可对系统反应度、界面简洁清晰度、储存能性、易学性和稳定性进行分析；

系统反应度：同时上万人在线时反应时间应该在两三秒以内，。

界面简洁清晰：系统界面要求简单明了，操作简单，用户操作容易上手。

储存性能高：懂球短视频微信小程序中需要存储的信息有很多，所以对系统的存储量要求很高，因此数据库就应该很强大，才能保证信息能安全稳定的进行存储；

易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

稳定性：要求懂球短视频微信小程序运行要稳定，界面清楚、字体清晰等。
## 3.3系统流程的分析
由于不同的系统实际使用用户角色的不同，他们的业务分析也会变得有所不一样，为了论述方便接下来都将以管理员与用户功能权限下的系统业务流程来分析，如下图所展示:
### 3.3.1**添加模块**
对用户输入的输入的用户账号和密码进行检查，做出相应动作，提示其输入用户账号和密码，查询数据库判断其是否合法，当用户账号和密码合法时，对其具有的权限进行判断，做出相应动作使其进入下一模块，其对应的前台文件是userlogin.java。登录模块流程图如图3-1所示。

`              `![](/md/blog.003.png)

图3-1添加模块流程示意图

用户的删除也是管理的功能之一，只能管理员权限才能使用，在删除用户时会对管理员的权限进行删除。在删除用户时需要先查出要删除的用户账号。然后才能选择删除功能。在查询用户时，如果用户信息不存在或者查找失败，则输出提示信息。在进行这些操作的时候会对当前登录用户的权限进行再次验证以及信息的确认，防止错误操作，确保数据的完整性。如果身份合法则可以删除用户并且输出提示信息。如果身份不合法或者是删除用户部成功，则输出提示信息。用户删除流程图如图3-2所示。

`        `![](/md/blog.004.png)

图3-2用户删除流程示意图

系统流程的分析是通过调查系统所涉及问题的识别、可行性、可操作性、系统分析处理能力等具体环节来调节、整理系统的设计方案以确保系统能达到理想的状态。这些操作都要从注册、登录处着眼进行一系列的流程测试保证数据库的完整，从而把控系统所涉及信息管理的安全、保证信息输入、输出正常转换。然后，通过实际操作完成流程图的绘制工作。系统结构图，如图3-3所示。

![](/md/blog.005.png)

图3-3 系统结构图

## 3.4 网站现状分析
系统使用用户的数量直接决定了用户信息管理者的工作量，毫无疑问，网站管理者的工作量较大较繁琐。通过前期的调研总结出网站现有的对用户管理工作状况如下分析：

（1）缺少统筹规划，如果一个网站在信息化管理中缺少综合性、系统性、整体性，那不可避免的需要投入大量人力物力来规划整理信息。引入信息化管理方式无疑可以达到节省信息管理成本的目的不仅减少资源浪费还可以使懂球视频的管理变得井井有条，成为市场竞争中的一大优势。

（2）要循序渐进，心急吃不了热豆腐，任何事情都不可能一蹴而就，就算信息管理系统也一样，要让系统发挥最大效率还是应该多调研，多听取管理者的意见，并进行必要的统筹规划，有组织有目的地设计系统功能，团结各个部门发挥主观能动性。

(3)信息安全措施不到位

隐私权神圣不可侵犯，这是中华人民共和国宪法赋予我们的权利，人和人都不能侵犯我们的正当权益，而网络用户信息管理存在极大安全隐患，信息泄露的案列不在少数，加强信息安全措施是完善网络信息管理过程中不可避免的一环。

` `(4)资源不能充分共享

资源共享是网络的一大特点，没有共享就没有社交，网络也就失去了他应有的魅力，如果能够实现用户信息共享，无疑对于懂球短视频的发展存在不可或缺的帮助。

(5)现有系统可扩展性不高。

如今科学技术发展飞速，随着而来的就是技术更新，那势必会给软件更新带来挑战，因此，系统必须具备良好的开放性和可扩充性，为了不落后于时代，这是必备特色之一。

基于上述分析，懂球短视频微信小程序网站应该切合实际，做到确实有效，集体表现为：一是系统能够整理并集合归类用户信息，防止用户信息混乱，难以整理；二是系统要安全稳定，不能泄露用户信息，造成隐私泄露，不仅伤害用户利益更是对开发者名誉的损毁；三是系统要具有良好的开放性，不仅要方便定期的维护维修，更要方便及时增加新功能，保证先进的时代契合性。经过详细的讨论论证，确定系统的总体要求。

20
![](/md/blog.006.png)

4系统总体设计与实现

4.1 总体设计

懂球短视频微信小程序采用了结构化开发的方法。这种开发方法的优点是控制性比较强，开发过程中采用了结构化和模块化的设计思想，自顶向下，从总体到部分，合理划分系统的结构和模块。结构化开发时使用模块式开发，各模块之间互不影响，方便系统的开发与管理。 

本系统的设计是基于 B/S架构的三层体系结构，也就是浏览器和服务器结构。计算机技术发展的速度非常快，以前的设计结构都以C/S的模式为主，也就是用户端和服务端模式。但随着网页技术的发展，越来越多的用户习惯于使用浏览器。现在的网页技术可以在浏览器中实现非常漂亮的效果，以前的单一低调的用户端页面已经无法满足用户的需求。在B/S这种结构下，技术人员可以很轻松的设计出用户所需要的工作界面，页面代码通过浏览器进行解析展示，在浏览器中不做过多的事务逻辑的处理。主要的事务逻辑放在服务端进行处理。这样用户的小程序就不会承载过多的东西，只需要浏览器展示即可。对于开发人员也很方便进行系统的维护和升级。开发人员只需要在服务端进行系统的维护就可以了。使用java这样的跨平台性非常好的技术，这样的开发模式更加的方便，高效。本系统合理的进行了模块划分和组合，因此由于各个模块之间基本上是相互独立的，所以每个模块都可以独立的被解释、执行、调试和修改，让繁琐的系统设计工作简单化。
## 4.2 数据库设计
### 4.2.1 概念模型设计
数据可设计要遵循职责分离原则，即在设计时应该要考虑系统独立性，即每个系统之间互不干预不能混乱数据表和系统关系。

数据库命名也要遵循一定规范，否则容易混淆，数据库字段名要尽量做到与表名类似。

概念模型是对现实中的问题出现的事物的进行描述，ER图是由实体及其关系构成的图，通过E-R图可以清楚地描述系统涉及到的实体之间的相互关系。

` `4.用户信息实体

用户信息实体包括用户姓名、用户手机、邮箱、性别、出生年月日、民族、头像，用户信息实体图如图4-1所示：

![](/md/blog.007.png)

` `图4-1 用户信息实体结构图

上传视频实体，它反映了视频名称、视频封面、上传时间、用户账号、用户姓名。上传视频实体的E-R如图，如图4-2所示：

![](/md/blog.008.png)

图4-2上传视频功能实体属性图

分享视频功能属性主要有：视频名称、用户账号、用户姓名、视频 封面、上传时间、作者实体属性图如图4-3所示。

![](/md/blog.009.png)

图4-3分享视频功能实体属性图

### 4.2.2 数据库型设计
根据上诉的逻辑模型设计，下面给出数据库的设计，如下表:

allusers表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10|编号|
|2|username|varchar|150||255|登录名|
|3|pwd|varchar|150||255|密码|
|4|cx|varchar|150||255|权限|
|5|addtime|varchar|8||19|添加时间|

dongqiushipin表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10|编号|
|2|addtime|varchar|150||255|添加时间|
|3|shipinmingcheng`|varchar|150||255||
|4|shipin|varchar|8||255||
|5|fengmian|varchar|150||255||
|6|shangchuanshijian|varchar|8||255||
|7|zuozhe|varchar|150||255||

fenxiangshipin表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10|编号|
|2|addtime|varchar|150||255|添加时间|
|3|shipinmingcheng|varchar|150||255||
|4|yonghuzhanghao|varchar|8||255||
|5|yonghuxingming|varchar|150||255||
|6|shipin|varchar|8||255||
|7|fengmian|varchar|150||255||
|8|shangchuanshijian|varchar|8||255||
|9|zuozhe|varchar|150||255||

shangchuanshipin表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10|编号|
|2|addtime|varchar|150||255|添加时间|
|4|shipinmingcheng|varchar|8||255||
|5|shipin|varchar|150||255||
|6|fengmian|varchar|8||255||
|7|shangchuanshijian|varchar|150||255||
|8|yonghuzhanghao|varchar|8||255||
|9|yonghuxingming|varchar|150||255||
|10|sfsh|varchar|8||255||
|11|shhf|varchar|150||255||

shouzangshipin表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10|编号|
|2|addtime|varchar|150||255|添加时间|
|4|shipinmingcheng|varchar|8||255||
|5|yonghuzhanghao|varchar|150||255||
|6|yonghuxingming|varchar|8||255||
|7|shipin|varchar|150||255||
|8|fengmian|varchar|8||255||
|9|shangchuanshijian|varchar|150||255||
|10|zuozhe|varchar|8||255||

yonghu表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10|编号|
|2|addtime|varchar|150||255|添加时间|
|4|yonghuzhanghao|varchar|8||255||
|5|yonghuxingming|varchar|150||255||
|6|mima|varchar|8||255||
|7|yonghushouji|varchar|150||255||
|8|youxiang|varchar|8||255||
|9|xingbie|varchar|150||255||
|10|chushengnianyueri|varchar|8||255||
|11|minzu|varchar|150||255||
|12|touxiang|varchar|8||255||


5 系统功能的详细设计与实现

5.1 管理员功能模块（服务端）

管理员要登录懂球懂球短视频后台服务端，需要输入用户名和密码，选择登录角色进行登录，管理员有特权，只需要登录，管理员登录界面如图5-1所示：

![](/md/blog.010.png)

图5-1管理员登录界面

管理员功能：管理员登录系统后，查看首页、个人中心、用户管理、上传视频管理、懂球视频管理、分享视频管理、收藏视频管理、系统管理。管理员功能如下图5-2所示：

![](/md/blog.011.png)图5-2管理员功能界面

用户管理：在用户管理页面，查看用户账号、用户姓名、用户手机、邮箱、性别、出生年月日、民族、头像等信息可进行修改、删除等操作，如图5-3所示：

![](/md/blog.012.png)图5-3用户管理界面

上传视频管理：管理员在上传视频管理页面，查看视频名称、视频封面、上传时间、用户账号、用户姓名等内容，还能对用户上传视频进行审核并回复，以及修改、删除等操作等操作，如图5-4  5-5所示：

![](/md/blog.013.png)

图5-4上传视频管理界面

![](/md/blog.014.png)

图5-5审核界面

懂球视频管理：管理员在懂球视频管理页面，查看视频名称、视频、封面、上传时间、作者等内容，还能对用户评论进行回复，以及修改、删除等操作，如图5-6所示：

![](/md/blog.015.png)

图5-6懂球视频管理界面

分享视频管理：在分享视频管理页面，查看视频名称、用户账号、用户姓名、视频 封面、上传时间、作者等内容进行修改、删除等操作，以及对视频名称进行统计如图5-7 5-8所示：

![](/md/blog.016.png)

图5-7收藏视频界面

![](/md/blog.017.png)

图5-8统计报表界面


系统管理：管理员通过系统管理页面可新增小程序端轮播图上传修改、删除等操作，如图5-9所示：

![](/md/blog.018.png)

图5-9轮播图界面

## **5.2用户功能模块（微信端）** 
用户注册，在用户注册页面通过填写用户账号、用户姓名、密码、用户手机、邮箱、性别、出生年月日、民族等信息进行注册操作；如图5-10所示。

![](/md/blog.019.png)

图5-10用户注册界面图

用户登录，用户通过登录页面输入账号和密码，并点击登录进行系统登录操作，如图5-11所示。

![](/md/blog.020.png)

图5-11用户登录界面图

用户登陆进入小程序端后，查看底部首页、上传视频、我的等内容，如图5-12所示。

![](/md/blog.021.png)

图5-12首页界面图

懂球视频，在懂球视频页面查看视频名称、视频、封面、上传时间、作者等信息，可对视频分享、收藏、点赞、评论等操作，如图5-13  5-14所示。

![](/md/blog.022.png)

图5-13懂球视频界面图

![](/md/blog.023.png)

图5-14分享界面图

我的，用户进入我的页面查看用户信息、上传视频、懂球视频、分享视频、收藏视频等详细信息，如图5-15所示。

![](/md/blog.024.png)

图5-15我的界面图

个人中心，用户通过个人信息可修改个人用户账号、用户姓名、密码、用户手机、邮箱、性别、出生年月日、民族、头像等信息，选择保存与退出登录，如图5-16所示。

![](/md/blog.025.png)

图5-16用户信息界面图

分享视频管理，在分享视频管理页面用户编辑填写视频名称、用户账号、用户姓名、视频 封面、上传时间、作者进行提交，后台管理员审核用户上传视频，如图5-17所示。

![](/md/blog.026.png)

图5-17分享视频管理界面图
# **6 系统测试**
# 系统测试是软件开发过程中最后一步，但也是不可或缺的重要的一步，没有人可以保证一次性编写完成的系统不会出错，而系统测试就是将自己开发的系统成为成品前的最后一步。在测试过程中需要进行严谨细致的测试，要尽可能全面地在不同情况下运行该系统，排除一切出现错误的可能。该系统的系统测试主要包括功能测试，可用性测试，维护测试，性能测试等部分，测试结果如下：
## 6.1 功能测试
功能测试主要包括五项内容：适用性、准确性、可操作性、依从性、安全性。

本系统功能测试如表6.1所示：

**表6.1  系统功能测试**

|测试内容|测试结果|
| :-: | :-: |
|依从性|正常|
|安全性|正常|
|可操作性|正常|
|适用性|正常|
|准确性|正常|
## 6.2 可用性测试
可用性测试用于检测系统的可操作性、可理解性、可学习性等方面内容。具体测试方面如表6.2所示。

**表6.2 系统可用性测试**

|测试项|测试人员的评价|
| :-: | - |
|操作流程是否合理|是|
|所需数据项是否正确显示|是|
|模块布局是否协调、合理 |是|
|模块、提示内容等文字描述是否正确|是|
|对选中项能否发生对应切换|是|
|操作方式是否简单|是|
|窗口移动、缩放、关闭等操作是否正常|是|
|操作是否流畅|是|
## 6.3 维护测试
由于篇幅的原因，本节给出系统部分功能的维护测试用例。具体测试方面如表6-3所示。

表6.3  系统用例测试

|序号|用例名称|用例操作|预期结果|测试结果|
| :-: | :-: | :-: | :-: | :-: |
|1|用户登录|输入用户名、密码|输入正确用户名和密码进入系统主界面，输入错误用户名或密码无法进入并给出提示|符合预期|
|2|添加懂球视频|在页面内输入懂球视频，点击“添加”按钮|正确存储懂球视频|符合预期|
|3|查看上传视频|查看列表，按照查询条件，筛选符合需要的信息，进一步详细查看上传视频|审核上传视频，结果通过|符合预期|
|4|添加收藏视频|在懂球视频页面内，点击“收藏”按钮|正确存储收藏视频|符合预期|
|5|翻页功能|点击“上一页”“下一页”“首页”“尾页”|跳转到正确页|符合预期|
## 6.4 性能测试
性能测试主要通过模拟系统运行环境来测试该系统是否能达到用户期待。性能测试的重要技术指标就是：系统运行速度、网络响应时间和支持并发节点数。

1）系统运行速度：得益于B/S架构，该系统能在不同配置小程序上运行并无明显卡顿，滞后，完全符合用户要求。

2）网络响应时间：网络响应时间主要包括网络最小响应时间、平均响应时间、最大响应时间三个参数。经过测试，在正常网络运营状态下，局域网内响应时间三参数为：1/2/5s，外网响应时间三参数为3/7/12s，符合用户需求，属于用户心理可承受范围。

3）支持并发节点数：经过模拟环境测试，本系统在并发节点达45个时，网络运营速度会发生较大波动，延迟时间10秒左右，符合用户需求。
## 6.5 测试结果分析
经过对上述测试结果分析，本系统能够在不同小程序上使用运行，具备一定安全性，用户信息不易泄露，能够日后再增删功能，能够实现所有功能，产品运行性能良好，能达到毕业设计要求。

结论

到此为止，懂球短视频微信小程序已经基本完成，本系统主要使用了微信小程序与java语言、SSM框架技术，结合java工作流引擎以及功能强大的MySQL数据库管理工具。系统实现了用户、懂球视频、收藏视频、上传视频管理等功能的管理，完成了系统设计任务的所有要求。

在这次毕业设计的过程中，我理解了更多的关于懂球短视频微信小程序的内容，学会了如何将现实中需求转化成系统的功能，在摸索学习过程中不断的提高自己的代码能力，以前开发都只开发一些业务逻辑的功能，从未接触过一个整体系统的设计与实现，这次毕业设计，我一边学习一边思考设计，最终既学会了一般的系统功能设计也完成了毕业设计。当然，在这次毕业设计的过程中我遇到了很多的困难，很多的问题。在遇到困难的时候我没有逃避，自觉的查找相关资料加强学习，自己解决的不了的问题就咨询身边的同学和老师。身边的同学和老师都非常的热情，友好，对待我的问题都很热情帮我解决，所以在此，我非常的感谢他们。是他们的支持与帮助，才使我顺利的完成这次毕业设计。

致谢

时光这个沙漏，一转眼就流完了，转眼之间大学四年就接近尾声，曾经觉得大学的时光好久，然而现在离校日期即将来临，随着毕业论文的完成，我的大学生活已经开始了倒计时。回想这次毕业设计的开发过程，有许多我需要感谢的人。从一开始的选课开始，我的指导老师就给予了我非常大的帮助。一开始，我的选题选错了，是在老师的帮助下我才顺利的改了选题。对待系统功能设计上，我的指导老师兢兢业业的给我指导，帮助我修改任务中不合理的地方，给我提出了很多宝贵的意见。在此我想真诚的说一声：老师，谢谢你，没有你的帮助我不可能这么顺利的完成毕业设计。

当然，与此同时我想向我所有的授课老师表示衷心的感谢，当年刚刚步入大学校园的我并不懂得你们对我们的教导，整天无所事事，对学习的兴趣不大。现在我知道了，没有知识是很难在现实的社会中生存的，还有你们上课时讲给我们的道理，现在我都清晰的记得。非常的感谢你们。你们给我的不仅仅是专业的知识技能，更多的是在教授我做人的道理。在此，我还要感谢我身边的同学和朋友，大学四年以来，我们朝夕相处，一起学习，一起努力，相互支持，相互陪伴，正是因为有了你们，我的大学生活才会如此的美好。

最后感谢我的父母，我的父母没有很高的学历，他们不会给我知识上的指导，但他们教育了我很多做人的道理，在毕业设计的过程中，他们给予了我很多的支持和鼓励，他们把所有的爱都给了我。在此，我也想大声的说一声：爸妈，谢谢您们！


















参考文献

[1] 杨文志. Google 小程序程序设计指南[M]. 北京：电子工业出版社，2018：10-100.

[2] 韩超，梁泉著. 小程序系统原理及开发要点详解 [M]. 北京：电子工业出版社，2019：50-150. 

[3] 周元兴. Google入门与实例教程 [M]. 北京：电子工业出版社，2017：30-80.

[4]熊伟,叶淋玮. 我国虚拟旅游网站的功能评价研究[J]. 人文地理,2018,02:154-160.

[5]赵宣容. 计算机软件数据库设计的重要性以及原则探讨[J]. 电子技术与软件工程,2019,17:209.

[6]李凯,鹿艳晶.网站的设计与开发[J]. 软件导刊,2019,03:79-81.

[7]白凯,吕洋洋,李薇薇.网站信息类型、品牌与服务保证对网站信任的影响[J]. 旅游学刊,2019,03:91-99.

[8]郝进义. 数据库设计规范及设计技巧研究[J]. 计算机光盘软件与应用,2017,12:176-177.

[9]赵春燕. 网站优化深度研究[J]. 信息安全与技术,2019,01:61-63.

[10] 靳岩. 小程序 开发入门与实战 [M]. 北京：人民邮电出版社，2019：10-50.

[11] 余志龙 陈昱勋. Google 小程序 SDK开发范例大全 [M]. 北京：人民邮电出版社，2019：30-70.

[12] 杨丰盛. 小程序应用开发揭秘 L004 [M]. 北京：机械工业出版社，2018：43-65.

[13] 张志锋, 朱颢东. java Web技术整合应用与项目实战[M]. 清华大学出版社, 2017.

[14] 王剑南. 软件B/S前台开发[M]. 清华大学出版社, 2018.

[15] 西尔伯沙茨. 数据库系统概念[M]. 机械工业出版社, 2018.

[16] 常建功. java Web典型模块与项目实战大全[M]. 人民邮电出版社, 2019.

[17] 杨晓军, 秦方. MVC Web开发学习实录[M]. 机械工业出版社, 2017.

[18] 伊雯雯. 基于MVC的SSM Web开发项目式教程[M]. 人民邮电出版社, 2018.

[19] 高洪岩. java EE核心框架实战[M]. 机械工业出版社[M]. 清华大学出版社, 2019.

[20] 陈丹丹, 卢瀚. 学通SSM Web的24堂课[M]. 机械工业出版社, 2019.

[21] 丁旭. 基于B/S架构的软件项目实训: java [M]. 清华大学出版社, 2017.













44
![](/md/blog.027.png)










