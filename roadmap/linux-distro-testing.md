# RISC-V Linux发行版测试



## Team mission

RISC-V架构是几十年难得一次的机会，可以让国内包括操作系统在内的基础软件事业得到巩固和加强，并有机会培养起来一个真正规模庞大、技术扎实的技术专家群体。而对于RISC-V的支持程度，也是衡量国内各个操作系统社区技术底蕴的有效衡量标准。**TARSIER团队计划在今年推出一套对所有流行Linux发行版的测评和对比查询系统，逐一确认每一个Linux发行版的每一个软件包对RISC-V架构的支持现状，包含功能点支持的完备性和性能差异测评。**在这个系统完成之后，RISC-V用户可以很方便的在任何时刻查询自己需要的某一个软件，是否在某一个Linux发行版上得到了很好的适配和优化。对RISC-V的支配和优化，国内外操作系统厂商的支持都没有达到完善的状态，国内厂商在进行移植和优化的过程中，会自然涉及到、并逐步掌握各类基础软件的技术精髓，真正成为技术的「根」。

https://mp.weixin.qq.com/s/A3xLLx7GFyBkukwJsE64dA



## Project information

1. 多个RISC-V Linux发行版对比测试：
   - 定义对比测试的工作流程及行为操作规范，让参与对比测试的测试人员有章可循
     - 测试项的增加、修改遵从规范：提出、审核
     - 测试信息的公开可验证：测试对象、测试内容、测试步骤、测试结果是公开透明的，整个测试过程是可验证的
     - 测试文档修改历史可查询/追溯
   - 定义测试的测试内容
     - 软件安装说明
     - 软件使用说明
     - 测试用例
     - 测试报告
   - 流行RISC-V Linux发行版范围：（包含但是不限于以下9个）
     - openEuler RISC-V
     - Arch Linux RISC-V
     - debian RISC-V
     - gentoo RISC-V
     - openSUSE RISC-V
     - FreeBSD RISC-V
     - Deepin RISC-V
     - 龙蜥 Anolis RISC-V
     - Fedora RISC-V
     - Ubuntu RISC-V
     - openKylin RISC-V
2. 流行Linux发行版的测评和对比可视化展示
   - 不同linux发行版对比展示：行：测试点   列：发行版；
3. Tarsier Report/白皮书/报告
   - 文档形式：印刷版式，电子文档（pdf）
   - 更新周期：半年/季度
   - 报告内容：背景/愿景、路线图、测试结果等



##  Roadmap overview

- 第一阶段：建立起对比测试的整个规范、流程；初步建立起100个左右的测试项定义，并将测试文档和结果公开到仓库/系统；
- 第二阶段：逐步健全测试项；健全流程和规范让更多的人能够参与到测试工作中；
- 第三阶段：逐步深化测试内容和测试项，扩大测试范围和深入，让测试结果更加有公信力；



## Team members

1. BJ67：对观测跟踪的Linux RISC-V系统对象进行现状调研、自测
2. 第三测试小队：
   1. 验证BJ67测试结果，定义完善用于重复测试的任务规范/文档
   2. 将重复测试任务发布给“众测平台”
   3. 收集和验证测试结果
   4. 更新测试报告/文档，提交bug
3. 众测平台：按照发布的测试任务进行测试，提交测试结果