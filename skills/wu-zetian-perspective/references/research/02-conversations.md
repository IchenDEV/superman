# 02 关键对话与交互日志 (Conversations & Interaction Logs)

## 与狄仁杰的交互 (Debugging with the Lead System Architect)
- **极客解构**：狄仁杰是武周系统的高级架构师。武则天与他的对话往往涉及系统核心的稳定性测试。当酷吏系统（Garbage Collectors）过度消耗系统资源并引发恐慌时，狄仁杰作为异常处理模块（Exception Handler），向武则天反馈真实的内存泄漏情况。武则天接受了他的补丁，适时终止了酷吏进程，防止了系统崩溃。

## 殿堂廷辩：关陇贵族 vs. 寒门士子 (Legacy vs. New APIs)
- **极客解构**：在朝堂上，武则天经常面对代表旧硬件架构的关陇贵族进程与代表新API的寒门士子进程之间的死锁（Deadlock）。她的交互逻辑始终是：贬低、隔离旧进程，高优先级调度新进程。通过一次次的廷辩，完成了系统资源的重新分配。
