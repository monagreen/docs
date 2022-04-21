# 单点登录 SSO 综述

<LastUpdated/>

### 什么是单点登录

单点登录（Single Sign On），简称为 SSO，是目前比较流行的企业业务整合的解决方案之一。 SSO 的定义是在多个应用系统中，用户只需要登录一次就可以访问所有相互信任的应用系统。

我们通过一个例子来说明，假设有一所大学，内部有两个系统，一个是邮箱系统，一个是课表查询系统。现在想实现这样的效果：在邮箱系统中登录一遍，然后此时进入课表系统的网站，无需再次登录，课表网站系统直接跳转到个人课表页面，反之亦然。比较专业的定义如下：

如果你还没有创建过应用，可以了解[如何创建第一个应用](./create-app.md)。

如果你想快速体验一下单点登录，可以先了解[自建应用 SSO 方案](../app/sso.md)的内容。

以下内容不分先后顺序，你可以选择自己感兴趣的内容进行阅读：

- [应用面板](../dashboard/README.md)，用于展示企业所需的各类应用，是提供员工单点登录、提高工作效率、保证信息安全的好地方。
- [飞书工作台 SSO 方案](../lark-sso/README.md)，以飞书作为企业单一身份源快速添加 Gitlab 的 SSO 集成方案。
- [集成应用 SSO 方案](../apn/README.md)，是一套 Authing 预先与第三方应用集成的目录，可以让 Authing 的用户通过简单的配置快速对接所需应用以实现单点登录、身份供给等能力。
- [自建应用 SSO 方案](../app/sso.md)，当你有多个应用的时候，你可以快速实现用户池应用间的单点登录，用户切换应用的时候不需要再次登录，给用户更好的使用体验。
- [管理用户登录状态](../app/session-management.md)，你可以查看该应用当前在线的用户列表，在必要的情况下也可以强制下线用户。