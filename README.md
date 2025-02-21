# clash-rule

自用clash meta规则
请看到此项目的朋友关闭网页
规则源自：

[Loyalsoldier/clash-rules](https://github.com/Loyalsoldier/clash-rules)

[ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)

[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)

**等**多方规则，并依据个人情况进行调整更改
## 版本内容
* **clash-rule**版本使用白名单模式，对CN进行分流，漏网之鱼默认代理，含有~完整广告拦截及~自建落地，不含广告拦截（广告规则太大了）
* **clash-rule-general**版本没有自建落地和一些用于特定服务的分流，其他与clash-rule相同
* **clash-rule-mini**~版本为解决苹果网络扩展50M内存限制，对代理进行分流，漏网之鱼默认直连，含有Lite版广告拦截及自建落地~ 已经弃用

## 备忘小记

订阅转换网站
https://id9.cc/
https://suburl.v1.mk/
https://acl4ssr-sub.github.io/
生成订阅连接，复制出来，将config=xxxxxxxx进行替换例如：
https://sub.id9.cc/sub?target=clash&new_name=true&url=https%3A%2F%2FXXX.XXX%2F&insert=false&config=aaaaa&filename=TEST&emoji=true&list=false&tfo=false&scv=false&fdn=false&sort=false
替换为
https://sub.id9.cc/sub?target=clash&new_name=true&url=https%3A%2F%2FXXX.XXX%2F&insert=false&config=bbbbb&filename=TEST&emoji=true&list=false&tfo=false&scv=false&fdn=false&sort=false
&符号为不同参数的分割。

通用config为：

```http
https%3A%2F%2Fraw.githubusercontent.com%2Futopeadia%2Fmyclashrule%2Fmain%2Fclash-rule-general.ini
```

自建落地config为：

```http
https%3A%2F%2Fraw.githubusercontent.com%2Futopeadia%2Fmyclashrule%2Fmain%2Fclash-rule.ini
```
