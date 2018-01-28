---
layout: post
title: 解读Scrum燃尽图
date: 2018-1-14
categories: [project management]
tags: [scrum,project management]
excerpt: 敏捷开发流程中，从Scrum burndown chart能看出什么门道？
---

我的[Understand the burndown chart](http://www.methodsandtools.com/archive/scrumburndown.php)读书笔记。

#### 什么是燃尽图：

在敏捷开发中，燃尽图主要用于显示某一特定时间段内团队的剩余工作量，从而了解团队状态和项目进度。

#### 燃尽图其实很简单：
* X轴显示工作量天数
* Y轴显示剩余工作量
  不要使用Y轴来显示backlog数量,因为每个backlog的工作量都不一样。
* 以实际剩余工作量作图(实线)
* 以理想工作量作为对照(虚线)

#### 燃尽图能告诉我们什么？

1.  理想团队

    ![IdealTeam](/img/posts/burndownchart/IdealTeam.jpg)

    **解读**

-   工作计划准时完成

 -   完成团队能力评估:

      -   工作量估计准确

      -   自我管理能力很好

 -   回顾改进
     继续保持

2.  优秀团队

    ![GreatTeam](/img/posts/burndownchart/GreatTeam.jpg)

    **解读**

-   工作计划准时完成

-   团队能力评估

    团队经验丰富,有能力根据项目进度灵活调整backlog的范畴，甚至有能力在sprint后期承担额外的工作

-   回顾改进

    -   探讨sprint前期为什么进度滞后，找出解决方案

    -   探讨如何更准确地评估自我能力

        看起来团队应该可以承担更大的工作量

3.  不错的团队

    ![NiceTeam](/img/posts/burndownchart/NiceTeam.jpg)

**解读**

-   工作计划准时完成
-   团队能力评估
    -   团队经验丰富，有能力根据项目进度灵活调整backlog的范畴以保证准时完成计划
    -   团队具有自省能力，工作努力


-   回顾改进
    -   探讨是否应该调整计划因为从sprint一开始，项目进展就不如预期
    -   建议将一些低优先级的backlog挪到下一个sprint,或者挪回product backlog bucket

4.  进度滞后

    ![BehindSchedule](/img/posts/burndownchart/BehindSchedule.jpg)

**解读**

-   不能准时交付

     整个sprint进度一直滞后


-   团队能力评估

  -       不能在适当维度内及时调整Sprint范畴
  -       不能准确预估工作量和工作能力

-   回顾改进
  -   探讨如何改进对工作量的预估, Sprint backlogs是否应该进一步细分和明确

  -   探讨是否应该考虑更多的工作裕量(buffer time)

  -   考虑将一些低优先级的backlog挪到下一个sprint

  -   减少下个Sprint承诺的backlogs

      如果问题得不到改善，管理层需要介入和采取进一步的矫正措施。        

5.  进度超前

![AheadSchedule](/img/posts/burndownchart/AheadSchedule.jpg)

**解读**

-   可以准时交付

-   团队能力评估
  -   不能准确估计工作量，Sprint backlogs计划不合理(偏少)
  -   或者对团队(成员)的工作能力不够了解
  -   后续backlog准备不及时, 造成团队工作量不饱和。

-   回顾改进

    针对上述能力缺陷进行改进。

6.  任务不饱和

    ![LessAssignment](/img/posts/burndownchart/LessAssignment.jpg)

**解读**

-   工作计划准时完成
-   团队能力评估
  -   团队承诺的工作量相对于其工作能力而言明显偏少
  -   或product owner未能提供足够的sprint backlogs
-   回顾改进

    Scrum master应该尽早认识到该类问题，并和product owner沟通以及时增加工作内容

7.  进度停滞(亟需管理层介入)

    ![ManagementComing](/img/posts/burndownchart/ManagementComing.jpg)

**解读**

-   工作计划虽然最终完成,但是:

    -   团队成员都没有更新工作进度
      -   团队可能不清楚sprint的截止时间
      -   团队成员不能在任务结束前提供工作进度
      -   或者product owner不断加入新的backlogs到当前sprint,抵消了已完成的工作量

-   团队能力评估

    急需学习和遵守Scrum工作流程


-   回顾改进
  -   Scrum master首先需要明确自身职责,及时追踪和带领团队成员更新进度
  -   尽早发现并解决进度停滞的问题

8.  无人工作？

    ![DoYourDuties](/img/posts/burndownchart/DoYourDuties.jpg)

**解读**

-   工作计划完全未完成

-   团队能力评估

     团队存在多方面问题:

     -   Product owner不关心开发进度
     -   Scrum master未能及时追踪和带领团队更新项目进度

-   回顾改进

    整个团队需要从头接受scrum流程培训,明确各自职责，认真做好回顾反思。

9.  工作量为零

    ![ZeroEffort](/img/posts/burndownchart/ZeroEffort.jpg)

**解读**

-   未作任何工作量评估,或sprint尚未启动

-   团队能力评估

    未能正确执行scrum流程,第一步也未迈出


-   回顾改进
  -   学习并遵守Scrum工作流程
  -   立即召开planning meeting，评估用户案例，制订sprint backlogs并启动sprint.

10.  任务越做越多?

     ![UpToSky](/img/posts/burndownchart/UpToSky.jpg)

**解读**

-   工作计划不正确且被频繁调整, sprint失败

    这是第一个Sprint的典型症状。


-   团队能力评估
  -   不能正确理解和执行Scrum流程,不断向当前sprint(而非product bucket)追加backlogs;
  -   项目执行能力欠缺
    -   不能正确理解项目和制订项目计划,导致backlogs频繁改动
    -   不能正确评估工作量

-   回顾改进
  -   接受scrum流程培训
  -   引入外部资源，指导和帮助团队正确理解和开展项目

11.  任务量起伏不定

    ![BumpOnTheRoad](/img/posts/burndownchart/BumpOnTheRoad.jpg)

    **解读**

-   准时完成工作计划
-   团队能力评估
    -   未能正确执行Sprint流程
    -   或者对项目的理解不够导致不能在sprint开始前预估工作量
-   回顾改进
    -   不应该在sprint开始后再不停添加任务
    -   应该在sprint未开始前评估工作
    -   项目预研本身也应该作为当前sprint的一项backlog
    -   考虑缩短sprint时间,降低不确定性风险

#### 总结

**理想的燃尽图真的理想吗？**

 **不尽然！**尤其是连续几个sprints的燃尽图都很理想时，管理层可能得想一想团队成员们是否是为了确保"安全性"而正在故意保守地评估自身工作能力！

**不要尝试用燃尽图来管人！**

敏捷开发流程让我们得以更容易地聚焦于产品本身，通过快速迭代尽可能快地将产品推向市场。但是对于敏捷开发流程本身，我们也需要一种聚焦方式，燃尽图以其简单易用性正好可以担当此任，很好地帮助团队追踪和管理项目进度。但是切记燃尽图也只是一种项目管理辅助工具，千万不要试图将燃尽图作为团队成员的绩效考核标准，否则团队成员可能会故意引入越来越多让管理层难辨真假的backlog points来制造完美的燃尽图，导致项目管理失准，遑论管好人！
