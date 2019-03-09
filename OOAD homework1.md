#软件的本质与软件工程学#
##软件工程的定义：##
>software engineering is "(1) the application of  sa sysytenatic disciplined quantifiable approach to the development ,operation ,and maintenance of software ,that is .the applecation of  engineering to software ," and "(2)thue study of approaches as in (1)"   
软件工程是（1）将系统化的、规范的、可度量化方法应用与软件的开发、运行和维护，即将工程化方法应用于软件；（2）在（1）中所述方法的研究。--IEEE Standard 610.12
****
##软件危机的产生、现象以及处理方法##
**软件危机（software crisis）**是计算机在它的开发和维护中所遇到的一系列严重的问题，即落后的软件生产方式无法满足迅速增长的计算机软件需求，从而导致软件开发与维护过程出现严重问题
的现象。

**软件危机的根源：**

1.软件的大量需求与软件生产力效率之间的矛盾

2.软件系统的复杂性与软件开发方法之间的矛盾

**主要表现形式**
      
- 软件开发进度难以预测
 *实际进度比预定计划一再拖延*
- 软件开发成本难以控制 
    *开发成本超出预算*
- 用户对产品功能难以满足
 *用户需求不明确*
- 软件产品质量无法保证
  *存有Bug&Patch*
- 软件产品难以维护
 *数量不断膨胀的软件产品缺乏适当的文档资料*
- 软件开发生产效率跟不上硬件的发展和人们的需求的增长
**软件危机的消除**

- 解决途径：
在主观方面：

  ·1正确认知计算机软件的内涵

 ·2充分认识到软件开发不是某种个体劳动的神秘技巧，而是一种组织良好、管理严密、协同配合的工程活动

在客观方面:

    ·1采用工程项目的管理方法

   ·2采用合适的软件开发技术、方法与软件工具


****
##软件生命周期##
- 

**[软件生命周期](https://wiki.mbalib.com/wiki/%E8%BD%AF%E4%BB%B6%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F)
（SLC，Software Life Cycle）**是指软件的产生直到报废或者停止使用的生命周期，又称软件生存周期或者系统开发生命周期。
周期内有问题定义、可行性分析、总体描述、系统设计、编码、调试和测试、验收与运行、维护升级到废弃等阶段，这种按时间分程的思想方法是软件工程中的一种思想原则，即按部就班、逐步推进，每个阶段都要有定义、工作、审查、形成文档以供交流或备查，以提高软件的质量。但随着新的面向对象的设计方法和技术的成熟，软件生命周期设计方法的指导意义正在逐步减少。

##软件工程知识体系(Software  Engineering Body of Knowledge, SWEBok)##

[SWEBOK](https://www.sebokwiki.org/wiki/An_Overview_of_the_SWEBOK_Guide)
V3  一共包括15个知识域,其中十一个是软件工程实践知识域，分别是软件需求、软件设计、软件构造、软件测试、软件维护、软件配置管理、软件工程管理、软件工程过程、软件工程模型和方法，软件质量、软件工程职业实践；以及四个软件工程教育基础知识域：软件工程经济学、计算基础、数学基础和工程基础。

####软件工程实践中的知识域####

- 软件需求（software requirements）

软件需求 KA 要求设计软件需求的启发、协商、分析、规范和验证。

- 软件设计（software design）

设计被定义为系统或组件的体系结构、组件、接口和其他特征的定义，以及此过程的结果。软件设计 KA 涵盖了设计过程和由此产生的产品。

- 软件构造（software construction）

软件构造 KA 包括与软件程序设计开发相关的主题，还涵盖了软件构造基础知识、管理软件建设、施工技术、实际考虑和软件构建工具。

- 软件测试（software testing）

软件测试 KA包括软件测试的基础知识，测试技术，人机界面测试与评估
；与测试有关的
措施和实际考虑

- 软件维护（software maintenance）

软件维护 KA包含软件维护的基本知识（维护的性质和需要、维护的类别、维护费用）；软件维护中的关键问题（技术问题、管理问题、维护成本估算、软件维护测量）；维护过程；软件维护技术（程序理解、重新设计、逆向工程、重构、软件停用；灾难恢复技术和软件维护工具）

- 软件配置管理（software configuration management）

软件配置管理KA包括供应链管理过程，软件配置识别、控制、状态核算、审核，软件发布管理和交互，和软件配置管理工具。

- 软件工程管理（software engineering management）


软件工程管理 ka 涵盖启动和范围定义 (确定和谈判要求、可行性分析以及审查和修订要求);软件项目规划 (流程规划、工作量估算、成本和进度、资源分配、风险分析、质量规划);软件项目的制定 (测量、报告和控制; 采购和供应商合同管理);产品验收;审查和分析项目执行情况;项目关闭;和软件管理工具。

- 软件工程过程（Software Engineering Process）

软件工程 ka 负责软件生命周期过程的定义、实施、评估、测量、管理和改进。所涉及的主题包括流程实施和变更 (流程基础结构、流程实施和变更模型以及软件流程管理);过程定义 (软件生命周期模型和流程、过程定义符号、流程适应和过程自动化);过程评估模型和方法;测量 (过程测量、产品测量、测量技术和测量结果质量);和软件处理工具。

- 软件工程模型与方法（Software Engineering Models and Methods）

软件工程模型和方法 ka 解决了包含多个生命周期阶段的方法

- 软件质量（Software Quality）

软件质量 ka 还包括软件质量的基础知识 (软件工程文化、软件质量特征、软件质量的价值和成本以及软件质量的提高);软件质量管理流程 (软件质量保证、验证和验证、审查和审核);和实际注意事项 (缺陷表征、软件质量测量和软件质量工具)。

- 软件工程专业实践（Software Engineering Professional Practice）

软件工程专业实践 ka 涵盖专业 (专业操守、专业社团、软件工程标准、雇用合同和法律问题);道德守则;群体动态 (团队合作, 认知问题复杂性, 与利益相关者互动, 处理不确定性和歧义, 处理多元文化环境);和沟通技巧。

####软件工程教育要求的知识域####

- 软件工程经济学（Software Engineering Economics）

软件工程经济学 ka 负责在业务环境中做出决策, 使技术决策与组织的业务目标保持一致。所涉及的主题包括软件工程经济学的基础知识 (建议、现金流、资金的时间价值、规划范围、通货膨胀、折旧、更换和退休决定);非营利决策 (成本效益分析、优化分析);估计、经济风险和不确定性 (估计技术、风险和不确定性下的决定);和多重属性决策 (价值和测量尺度、补偿和非补偿技术)。

- 计算基础（computing foundations）

计算基础 ka 涵盖了提供软件工程实践所需的计算背景的基本主题。所涉及的主题包括问题解决技术、抽象、算法和复杂性、编程基础知识、并行和分布式计算的基础知识、计算机组织、操作系统和网络通信。

- 数学基础（mathematical founfdations）

数学基础 ka 涵盖的基本主题, 提供必要的数学背景, 为软件工程的实践。所涵盖的主题包括集合、关系和功能;基本命题和谓词逻辑;证明技术;图形和树木;离散概率;语法和有限状态机;和数论。

- 工程基础（Engineering Foundations）

工程基础 ka 涵盖了为软件工程实践提供必要的工程背景的基本主题。所涉及的主题包括经验方法和实验技术;统计分析;测量和指标;工程设计;模拟和建模;和根本原因分析。

##软件能力成熟度模型（Capability Maturity Model for Software / CMM）或 CMMI##

- 台阶一：CMMI一级，完成级。在完成级水平上，企业对项目的目标与要做的努力很清晰，项目的目标得以实现。但是由于任务的完成带有很大的偶然性，企业无法保证在实施同类项目的时候仍然能够完成任务。企业在一级上的项目实施对实施人员有很大的依赖性。

- 台阶二：CMMI二级，管理级。在管理级水平上，企业在项目实施上能够遵守既定的计划与流程，有资源准备，权责到人，对相关的项目实施人员有相应的培训，对整个流程有监测与控制，并与上级单位对项目与流程进行审查。企业在二级水平上体现了对项目的一系列的管理程序。这一系列的管理手段排除了企业在一级时完成任务的随机性，保证了企业的所有项目实施都会得到成功。

- 台阶三：CMMI三级，定义级。在定义级水平上，企业不仅能够对项目的实施有一整套的管理措施，并保障项目的完成；而且，企业能够根据自身的特殊情况以及自己的标准流程，将这套管理体系与流程予以制度化这样，企业不仅能够在同类的项目上生到成功的实施，在不同类的项目上一样能够得到成功的实施。科学的管理成为企业的一种文化，企业的组织财富。

- 台阶四：CMMI四级，量化管理级。在量化管理级水平上，企业的项目管理不仅形成了一种制度，而且要实现数字化的管理。对管理流程要做到量化与数字化。通过量化技术来实现流程的稳定性，实现管理的精度，降低项目实施在质量上的波动。

- 台阶五：CMMI五级，优化级。在优化级水平上，企业的项目管理达到了最高的境界。企业不仅能够通过信息手段与数字化手段来实现对项目的管理，而且能够充分利用信息资料，对企业在项目实施的过程中可能出现的次品予以预防。能够主动地改善流程，运用新技术，实现流程的优化。

##对CMMI的个人见解##

实施CMMI的意义不不仅在于能使项目工程走向世界，获得更多商机，还能够提高企业的管理水平，降低工程成本，得到更高的回报，。对于采购部门来说，掌握了CMMI技术可以有目的的考察项目实施人员或公司的实施能力，从而保证所采购项目能否顺利完成。对于项目经理来说，掌握CMMI技术能提高自己的管理能力，从而能够是项目质量提高，成本降低，按期限完成。对于企业来讲CMMI还能够引入科学的管理理念，提审企业整体管理水平。
