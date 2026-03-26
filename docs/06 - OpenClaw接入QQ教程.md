# OpenClaw 接入 QQ 教程

国内主流 OpenClaw 工具与平台基本都提供了接入 QQ 渠道的方式，如腾讯云、阿里云、火山引擎等公有云，以及WorkBuddy、QClaw、AutoClaw 等国产 OpenClaw 工具，都提供了配置 QQ 作为聊天的通道。

### 腾讯云 Lighthouse 接入 QQ

首先你需要到腾讯云官网选购一台 Lighthouse 服务器，腾讯云官网：https://cloud.tencent.com/act/pro/openclaw。

之后你会看到这样的服务器实例卡片。

![Screenshot](images/06/01.png)

点击这个实例卡片，进入到管理页面的「应用管理」选项卡页，在这一页的中间部分，有个「通道（Channels）」面板。

![Screenshot](images/06/02.png)

在通道面板里，下拉选择 QQ 通道。

![Screenshot](images/06/03.png)

然后前往 QQ 开放平台：https://q.qq.com/qqbot/openclaw/login.html

使用手机 QQ 扫码，并确认登录。

![Screenshot](images/06/04.png)

之后，进入机器人配置页，点击「创建机器人」按钮。

![Screenshot](images/06/05.png)

创建好机器人后，你会看到机器人的“AppID”和“AppSecret”，将其保存到备忘录，之后会用到。因为一旦关闭页面就看不到了，需要的话就得重置。

![Screenshot](images/06/06.png)

这时，我们在 QQ 消息列表中，就可以看到刚刚创建的这个机器人了。

但是此刻还不能和 OpenClaw 进行对话，需要接入。

![Screenshot](images/06/07.png)

回到腾讯云 Lighthouse 的道通面板处，将刚刚复制的 QQ 机器人的“AppID”和“AppSecret”粘贴到对应输入框中，然后点击「添加并应用」按钮。

![Screenshot](images/06/08.png)

添加之后，你会在下面「已接入道通」处，看到 QQ 通道了。

![Screenshot](images/06/09.png)

再回到 QQ 消息列表中的机器人对话窗口，就可以正常通过 QQ 与 OpenClaw 进行交流了。

![Screenshot](images/06/10.png)


### WorkBuddy 接入 QQ

WorkBuddy 是腾讯推出的一款桌面版 OpenClaw 小龙虾，按照官方的说法，WorkBuddy 是一个全场景职场 AI 智能体桌面工作台，适用于全角色，只需要一句话描述需求，就能像同事一样自主规划和执行复杂任务。

![Screenshot](images/06/11.png)

在 WorkBuddy 中接入 QQ，单击左侧「Claw」选项后的「设置」图标，会弹出 Claw 设置对话框。

![Screenshot](images/06/12.png)

在 Claw 设置对话框窗口，你会看到「QQ 机器人集成」选项，点击后面的「配置」按钮。

![Screenshot](images/06/13.png)

弹出输入“AppID”和“AppSecret”输入框页面。

![Screenshot](images/06/14.png)

此刻，我们像之前一样，前往 QQ 开放平台（ https://q.qq.com/qqbot/openclaw/login.html ）创建一个机器人，并将“AppID”和“AppSecret”复制下来保存好。

![Screenshot](images/06/15.png)

回到 WorkBuddy 的 Claw 配置 QQ 通道的对话框，将“AppID”和“AppSecret”输入到对应框里，选择「WebSocket 长连接」，然后点击「注册」按钮。

![Screenshot](images/06/16.png)

之后，「QQ 机器人集成」选项这里，显示「已连接」，表示配置成功。

![Screenshot](images/06/17.png)

回到 QQ 消息列表中，进入机器人对话窗口，可以正常对话了。

![Screenshot](images/06/18.png)

如果你想进一步管理 QQ 机器人更多权限，可以来到 QQ 开放平台机器人管理页：https://q.qq.com/#/apps

![Screenshot](images/06/19.png)

单击机器人，进入管理页，可以管理更多的配置。

![Screenshot](images/06/20.png)

如果你还没注册 QQ 管理平台账号，需要先注册一下，根据提示往下走即可。


### QClaw 接入 QQ

QClaw 也是腾讯推出了一款客户端版 OpenClaw 小龙虾，主打一个零部署，开箱即用。

官网链接：https://qclaw.qq.com/#

![Screenshot](images/06/21.png)

安装并登录之后，是这个样子：

![Screenshot](images/06/22.png)

点击左下角的「设置」图标，弹出对话框，选择「远控通道」选项，就能看到支持的通道了。

![Screenshot](images/06/23.png)

点击「QQ」选项之后的「配置」，弹出“AppID”和“AppSecret”对话框。

获取“AppID”和“AppSecret”的过程和上面如出一辙，不再赘述。