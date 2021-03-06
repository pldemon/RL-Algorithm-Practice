<!--
 * @Description: A Help File
 * @version: V1.0
 * @Author: lesheng
 * @Date: 2021-04-14 19:00:53
 * @LastEditors: lesheng
 * @LastEditTime: 2021-04-16 14:57:16
-->

# RL-Algorithm-Practice

Algorithm course group work

## 传送门

[任务看板](./TaskBoard.md) <- 点击这里  
[课题七：强化学习](./Reference/课题七：强化学习.pdf) <- 点击这里  
[工程开源地址](https://github.com/EnTaroCLS/RL-Algorithm-Practice.git) <- 点击这里  
[一些可能会用到的强化学习核心论文](./Reference/RLPaperSummary.md) <- 点击这里  
[强化学习综述](./PublicWorkSpace/强化学习综述.md) <- 点击这里

## 研究步骤

1. 通过文献搜索强化学习相关算法
2. 编程实现
3. 数据可视化并和对比分析
4. 总结和书写文档

    __注意__
    1. 搜索某一算法资料时,应当查找阅读其在权威杂志上的论文,并了解它从诞生到现在的演变过程,理解其核心思想。根据其新颖性和可重现性,考虑本次实验是否可以编程实现
    2. 由于通常强化学习是智能体依靠从环境中不断地试错而产生智能,所以我们需要在试验算法之前搭建环境,考虑到从底层编写物理环境并非易事,所以我们可以借助于Unity游戏引擎。另外对于传统强化学习算法,在动作空间不大的情况下,可以使用任意语言编写,而对于深度强化学习算法我们需要借助于深度学习框架,所以应当用Python编写
    3. 实验数据应当保存,我们需要统计数据制作图表对其可视化,设置性能指标对算法进行对比分析,这些都是书写文档所必需的
    4. 书写文档,格式非常重要,图表等统计数据尽可能的避免长篇大论

## 团队协作

我们的工程通过GitHub在线协作，[开源地址](https://github.com/EnTaroCLS/RL-Algorithm-Practice.git) <- 点击这里  
上述只是简单概括的步骤,详细的任务我会每天在[任务看板](./TaskBoard.md)中更新

* 在每天睡觉前我会更新[任务看板](./TaskBoard.md),例如添加新任务、勾选已完成任务、移除任务
* 团队成员需要向@EnTaroCLS申请未派发的任务(先到先得),任务派出后我会在[任务看板](./TaskBoard.md)中该任务之后署名接受任务的同学及预期完成时间,若超时至少一天,则该任务重新开放,先前的同学可以将以获得的成果上传。如果一个任务长时间无人完成,而研究的继续必须依赖此任务,那么就来做

    __注意__  
  * 这个工程应当由全体成员共同完成
  * 我在工程根目录为每一个成员建立了以姓名命名的文件夹作为他的工作空间,当一位成员完成任务检查无误之后就可以上传至工作空间(代码除外)
  * 对于代码文件,每一个脚本都应该有文件注释,每一个公开的函数都应该有函数注释,注释模板的每一条信息都不应省略尤其是署名
  
    __注释模板__（根据编程语言变动）  
    * 文件注释

        ```C#
           /*
            * @Description: A Markdown File for helf
            * @version: V0.1
            * @Author: lesheng
            * @Date: 2021-04-14 19:00:53
            * @LastEditors: lesheng
            * @LastEditTime: 2021-04-14 21:02:24
            */
        ```

    * 文件注释

        ```C#
           /**
             * @Description: Contral the movement of agent
             * @Author: lesheng
             * @Param: {None}
             * @Return: {None}
             */
        ```

  * 某一位成员对团队的贡献由所有其署名的文件、函数以及其工作空间中的内容共同组成
