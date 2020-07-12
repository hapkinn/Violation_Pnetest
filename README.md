# 渗透红线Checklist

多人协作的渗透项目中，往往每个人擅长点和经验都不同，那么团队有一个人误操作很有可能会带来很严重的后果，导致入口打点被发现，或者内网渗透被监测到。
这份Checklist需要遇到实战足够的坑才能形成这份文档，所以向渗透师发起邀请同共完成，"渗透操作红线列表"。
在**Issues**提交，经过审核有价值的，才会添加进来。

* WebShell不能使用普通一句话木马，连接端使用加密流量，不使用普通中国菜刀。
* 上传工具到服务器中，不能使用默认名称，例如，frp、nc、lcx等。
* 个人电脑浏览器不能保存任何个人信息。
* 不随意修改服务员密码、后台密码。
* 使用sqlmap要加--random-agent参数。
* nmap扫描要去除特征。
* 大文件需要打包分割下载。
* 不使用国内VPS（阿里云、腾讯云）做CobaltStrike做远控服务器。
* 不要相信工具的判断，工具测试一遍，手工测试一遍。
* 渗透项目结束后，不要继续进行测试。
