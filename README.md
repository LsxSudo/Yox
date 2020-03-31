#需求规格说明书
##0. 目录
- 需求规格说明书
    - 0. 目录
    - 1. 引言
        - 1.1 目的
        - 1.2 预期读者
        - 1.3 背景
        - 1.4 定义
        - 1.5 参考文献
    - 2. 项目概述
        - 2.1 产品背景
        - 2.2 产品描述
        - 2.3 产品功能
        - 2.4 未来市场
        - 2.5 用户群体
        - 2.6 用户场景
        - 2.7 假设与约束
            - 2.7.1 假设
            - 2.7.2 约束
    - 3. 具体需求
        - 3.1 外部接口需求
            - 3.1.1 用户接口
            - 3.1.2 硬件接口
            - 3.1.3 软件接口
            - 3.1.4 通信接口
        - 3.2 功能需求
            - 3.2.1 界面设计
            - 3.2.2 UML类图
        - 3.3 性能需求
            - 3.3.1 精度需求
            - 3.3.2 静态数量化需求
            - 3.3.3 动态数量化需求
        - 3.4 属性
            - 3.4.1 可用性
            - 3.4.2 安全性
            - 3.4.3 可维护性
        - 4. 验证验收标准
            - 4.1 文档验收标准
            - 4.2 软件验收标准
            - 4.3 界面验收标准
            - 4.4 功能验收标准
##1. 引言

###1.1 目的

为准确描述软件定位，明确软件需求，减少开发工作以及便于软件升级和产品转移撰写本文档
本篇软件规格需求说眀书详细描述了“用心聚”这一软件的用户需求、软件规格等内容。方便用户深入
了解该软件，同时也是开发者进行开发、测试以及软件验收的主要依据

###1.2 预期读者

- 项目经理:项目经理可以根据本文档了解产品的实现预期以及产品的诸多细节，便于进行项目管理
- 设计员:根据软件的需求有针对性地设计出各种框架，其中包括数据库设计、UⅠ界面设计等
- 程序员:程序员可以根据本文档详细阐述的软件功能进行软件开发编码
- 测试员:测试员可以通过本文档阐述功能描述进行功能测试，测试接口以及各种细节。
- 用户:用户可以根据本篇文档了解产品的出发点以及软件的功能，有助于用户确定该软件是否
满足其需求以及是否解决痛点。协助用户与开发者更好地协商讨论。

本文档用于指导软件开发者于软件工程实践课程中开发软件项目的过程，通过规范软件项目承担
团队的开发过程达到提高软件质量，降低维护成本的目的。开发者应根据本文档进行软件开发和编制
软件开发文档。本指南是对软件项目承担单位的基本要求。在进行具体软件开发时，开发者可根据实
际情况采编写，但必须提供双方约定的文档，文档中约定的内容必须描述清楚。

###1.3 背景

软件名称：用心聚
项目开发者：福州大学2017级软件工程 “用心聚落步”小组
本项目经过大量问卷充分了解潜在用户需求，从用户的需求以及对于当前市场上产品不能解决的
用户痛点出发，经过组内讨论从而确定了软件定位和主要功能。本产品主要面向。。。。

###1.4 定义

| 序号|缩写| 定义  |
|:------:|:-----:|-----|
|1 | App | 应用程序，'Application'，一般指手机软件。 |
|2| Android|Android 是一种基于 Linux 的自由及开放源代码的操作系统，主要使用于移动设备，如智能手机和平板电脑，由 Google 公司和开放手机联盟领导及开发。|
|3|BUG|	狭义概念是指软件程序的漏洞或缺陷，广义概念除此之外还包括测试工程师或用户所发现和提出的软件可改进的细节、或与需求文档存在差异的功能实现等。|

###1.5 参考文献

【1】《GB9385-288计算机软件需求规格说明规范》
【2】《GB9386-28计算机软件测试文档编制规范》

##2. 项目概述

###2.1 产品背景

- 现如今就业是一大难题，就业形势日益严峻，许多人对就业深感忧心。
- 有些人有着创业的想法却苦于无从下手，该软件致力于为用户便捷，快速，高效的找到自己的团队。
- 根据国家统计局显示，2019年1-12月大城市的失业率逐年增加。许多失业者有意图有想法做自己的创业项目，而且国家对其也有政策支持。
- 但是最大的难题是无法找到与自己有相同兴趣爱好和专长并且相创业的小伙伴，这款软件还融合一系列的聊天系统,我们的目标是把最合适的人放在最合适的岗位上。
- 在校大学生也正在为毕业后因为没有好的履历而害怕找不到工作，所以我们的组队功能将实现2-8人组队的效果，这样他们可以通过参加比赛得奖，并且得到实战的机会，达到履历丰富的效果。

###2.2 产品描述

- 1.用心聚一款完全针对用户的软件，用于收集用户信息，将求职者与企业配对的软件；
- 2.一款针对现在的失业人群而做的一款软件, 想进行自主创业但是没有门路和渠道找到小伙伴的软件，填写你的专业和资料，自动匹配的适合你的创业小组。
- 3.我们也很多需要组队参加比赛的比赛而服务,为有意愿参加比赛的在校大学生寻找一位知音人。（现阶段必须完成）

###2.3 产品功能

- 初期:
  - 网页实现浏览功能，推荐比赛项目，公告一些获奖团队信息，这样有利于推广而且也为相应的团队打响了名气。
  - app实现组队功能，自主创建小队（人数受限），发布招募队员页面，系统自分配功能，自由选择小队功能。注册页实现实名注册。聊天功能。
- 中期：
  - 
- 后期:
  - 1.app设置了搜索推荐功能，为您推荐了当下热门的职业方向，搜素相关职业的关键字，便于用户查找分析。
  - 2.app设置了定位系统，用户可以选择自己想就职的城市和地区。
  - 3.增加了就职方向选择功能，并推荐相关群聊，方便对该职业就业情况的了解。
  - 4.增加了分区选择功能，用户可以从大概方向选择到具体擅长技术
![](https://img2020.cnblogs.com/blog/1969029/202003/1969029-20200331120741806-1655098608.png)

###2.4 未来市场

本产品针对失业而且有意向创业的用户，但是找不到途径和志同道合的其他小伙伴，具体到（）领域。
根据系统自动分配创业小组或用户自己选择小组，方便用户快速获取创业小组资料以及选择最适合自己的创业小组。

###2.5 用户群体

- 1.失业者
- 2.有意向创业的用户
- 3.有意向参加各类比赛的在校大学生

###2.6 用户场景

- ![](https://img2020.cnblogs.com/blog/1969029/202003/1969029-20200331121121953-2038534843.png)


###2.7 假设与约束
####2.7.1 假设

- 人员调配:假设在开发过程中组长能够合理调度人员,分配任务合理,组员在都能在交稿日完成自己的任务。
- 团队协作:假设小组如家,每位组员都能够把自己当做小组内的一份子,每位组员心里都报有一颗为自己做事的心态。
- 

####2.7.2 约束

- 人员约束：团队成员皆为大三学生，共 8 人
- 管理约束: 本次开发实行以一人担任组长，分工合作的模式进行。力求每个人的分工涉及开发过程中的所有流程，并按照进度表进行，开发过程遇到的问题通过小组会议得到一致解决
- 技术约束：小组成员在相关技术水平方面存在一定的欠缺，缺乏相关的项目经验，需要在开发中不断学习新的技术.
- 时间约束：本项目开发周期短，时间相对紧张，需要开发者合理规划时间，做到多项任务并发
- 安全和保密考虑:对于用户个人信息的存储保护，对于数据库结构合理性、安全性需要严谨的考虑。
- 其他约束：开发期间，小组成员还有其他科目的学习任务，将对项目进度造成一定影响

##3. 具体需求
###3.1 外部接口需求
####3.1.1 用户接口
- 无特殊需求
####3.1.2 硬件接口
- 无特殊需求
####3.1.3 软件接口
- 无特殊需求
####3.1.4 通信接口
- 无特殊需求
###3.2 功能需求
####3.2.1 界面设计

####3.2.2 UML类图
![](https://img2020.cnblogs.com/blog/1969029/202003/1969029-20200331134827491-248395620.png)


###3.3 性能需求
####3.3.1 精度需求
-
####3.3.2 静态数量化需求
-
###3.4 属性
####3.4.1 可用性

- 并发性：支持多用户同时在线。
- 易操作：本产品操作简单，任意使用。
- 稳定性：在产品的升级中修复出现的bug，使系统越来越稳定。
- 界面友好：本软件产品界面对用户友好、直观。

####3.4.2 安全性

- 权限限制：本产品软件的数据库中对普通用户的访问控制设置权限，以防消息泄露。
- 最小权限原则：降低代码在被恶意用户利用时,造成的损失。
- 备份与恢复：本产品软件数据库采用记录生产日志文件、个人信誉度备份等方式保证信息安全。
- 审计：对于服务端每一次非自动的数据库操作进行审计记录，方便事后追究，控制数据泄露。

####3.4.3 可维护性

- 用户反馈：提供用户反馈途径，及时收集用户反馈的各种信息，方便软件维护。
- 更新：在每次更新过程中，修复系统出现的bug，实现软件的维护。
- 编码规范：本产品软件的开发编码按照事先约定好的编码规范进行，便于软件维护

###4. 验证验收标准
####4.1 文档验收标准
-
####4.2 软件验收标准
-
####4.3 界面验收标准
-
####4.4 功能验收标准
-
