# paper
由于我现在主要在学习IoT、协议、fuzz方向，所以会把自己看过的觉得有意思的资料放上来。

并会写一些自己对这篇文章的思考，方便大家参考，并且监督自己阅读paper。

希望一周能读完一篇。（或许会有阅读笔记在我的[博客](https://kazamayc.github.io/)上，但是会取决于我想不想放，所以大家可以直接找我聊idea，互相学习一下）

## 对于读论文的参考

> 初次学习的时候看了很多文章，摘抄了一些他人的观点

**论文复现：**

读几篇你所选的领域里最近的权威综述，设计一个新实验，用过去没有的新技术或者方法。再次检验这个假说，不能完全依照旧方法去重复旧实验，因为重复别人的实验是不被重视的。
你的实验可能有两种结果。第一，你可能证实了旧的实验结果是正确的，因为你使用了新的实验技术或方法， 为一个公认的重要假说提供了新证据，对这个领域是有相当的贡献，可以发表在高水平的杂志。另一个可能是你的实验结果与旧的实验结果不符或甚至相反，那你就「中奖」了。 你的证据可以对目前公认的假说提出质疑，流行的概念与假设需要重新考虑，你可以发表一篇 「热」文章，一连串的新研究课题也将从此诞生。科学的进展就是不断对目前流行的假说进行修正。



**如何开启一段科研：**

选题目->读文献->想idea->实现idea->写论文

1. 寻找找出最相关论文，并对文献进行分类
2. 略读论文标定次序，标注假设和优点(创意)
3. 整理缺点、特点、局限性
4. 根据前面读的论文，归纳该领域目前存在的问题，以更好的关键词寻找文献
5. 提出自己想法，试着实现

先想后做：要想自己的结果能不能发表，发表在哪里。

## IoT

* IoT模拟仿真模拟环境

| Year      | PDF                                                          | Content                                |
| --------- | ------------------------------------------------------------ | -------------------------------------- |
| ACSAC2020 | [FirmAE: Towards Large-Scale Emulation of IoT Firmware for Dynamic Analysis](https://github.com/Kazamayc/paper/blob/main/iot/FirmAE-ACSAC2020.pdf) | 目前最好用的仿真软件FirmAE做了哪些工作 |



## Fuzz

| Year    | PDF                                                          | Content                    |
| ------- | ------------------------------------------------------------ | -------------------------- |
| CCS2021 | [Snipuzz: Black-box Fuzzing of IoT Firmware via Message Snippet Inference](https://github.com/Kazamayc/paper/blob/main/fuzz/Snipuzz-CCS2021.pdf) | 物联网固件自动黑盒模糊测试 |



## Honeypots

| Year         | PDF                                                          | Content                             |
| ------------ | ------------------------------------------------------------ | ----------------------------------- |
| ACSAC2022    | [Interaction matters: a comprehensive analysis and a dataset of hybrid IoT/OT honeypots](https://github.com/Kazamayc/paper/blob/main/honeypots/RIoTPot-ACSAC2022.pdf) |                                     |
| blackhat2017 | [IoTCandyJar: Towards an Intelligent-Interaction Honeypot for IoT Devices](https://github.com/Kazamayc/paper/blob/main/honeypots/IoTcandyjar-blackhat2017.pdf) | 机器学习技术自动学习IoT知识构建蜜罐 |
| 信息安全学报 | [物联网蜜罐综述](https://github.com/Kazamayc/paper/blob/main/honeypots/%E7%89%A9%E8%81%94%E7%BD%91%E8%9C%9C%E7%BD%90%E7%BB%BC%E8%BF%B0-%E4%BF%A1%E6%81%AF%E5%AE%89%E5%85%A8%E5%AD%A6%E6%8A%A5.pdf) | 介绍展望IoT蜜罐知识                 |

IoTCandyJar：攻击者对设备一般会进行检查，如果检查失败就不会继续攻击，我们的目的就是通过机器学习（提前传入类似的数据seed）返回给攻击者一个想要的数据。

[IoT、IIoT和CPS领域的蜜罐和蜜网相关研究](https://zhuanlan.zhihu.com/p/516470935)：整理历年来IoT领域的蜜罐技术



由于最近比赛+工作事情略多，一直未更新，实在惭愧。下周开始恢复此项目的更新，立字为证！(23.11.20)





