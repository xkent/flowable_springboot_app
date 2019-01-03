# flowable_springboot_app
Springboot框架下的flowable 流程管理应用中心。

使用springboot框架来演示flowable的使用。自启动时自动部署bpmn流程配置文件。然后提供相应的http入口来进行操作演示。

功能：
1. 使用springboot的jwt接口校验机制，提供相应的接口监控、处理机制；
2. 同步账号用户ID，使用flowable的监听，实现flowable的账号同步实现；
