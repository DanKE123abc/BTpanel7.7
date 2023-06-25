# 宝塔面板7.7安装脚本&优化补丁

### 宝塔面板7.7优化版安装脚本

1. 优化：去除无用接口、减少无用代码执行、减少对于宝塔云端请求、去除面板广告等，保持面板干净清爽。

2. 修复：兼容新版本面板运行环境、修复面板XSS高危漏洞。


* Github链接（若无法访问请重试或使用加速器）
```bash
wget -O install.sh https://raw.githubusercontent.com/DanKE123abc/BTpanel7.7/main/install_6.0_mod.sh && bash install.sh
```
* 彩虹云链接
```bash
wget -O install.sh http://f.cccyun.cc/bt/install_6.0.sh && bash install.sh
```

### 宝塔面板7.7优化补丁

1. 去除宝塔面板强制绑定账号
2. 去除各种删除操作时的计算题与延时等待
3. 去除创建网站自动创建的垃圾文件（index.html、404.html、.htaccess）
4. 关闭未绑定域名提示页面，防止有人访问未绑定域名直接看出来是用的宝塔面板
5. 关闭活动推荐与在线客服，去除首页企业版广告
6. 去除自动校验文件与上报信息定时任务
7. 去除面板日志与网站绑定域名上报

* Github链接（若无法访问请重试或使用加速器）
```bash
wget -O optimize.sh https://raw.githubusercontent.com/DanKE123abc/BTpanel7.7/main/optimize_mod.sh && bash optimize.sh
```
* 如果Ngnix创建的网站出现403 forbidden(保留网站创建的文件，若无法访问请重试或使用加速器）
```bash
wget -O optimize.sh https://raw.githubusercontent.com/DanKE123abc/BTpanel7.7/main/optimize_mod_fixngnix.sh && bash optimize.sh
```
* 彩虹云链接
```bash
wget -O optimize.sh http://f.cccyun.cc/bt/optimize.sh && bash optimize.sh
```

### 卸载宝塔面板

- Github链接（若无法访问请重试或使用加速器）

```shell
wget -O bt-uninstall.sh https://raw.githubusercontent.com/DanKE123abc/BTpanel7.7/main/bt-uninstall.sh && bash bt-uninstall.sh
```

