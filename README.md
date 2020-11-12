# 此项目本是个付费主题，可是他们放弃了，我不想 Malio 就此消失就放到了这里
# 不能删改页面底部的 Powered by SSPANEL，不能删改staff页面的任何信息。
## 删除Powered by SSPANEL可能会导致你的网站被D，现在 Theme by editXY 可以随意去掉

本主题包含了SSPANEL的完整代码，需要删除原来的面板，然后全新安装（数据库通用），操作前请备份面板

## 贡献

[提出新想法 & 提交 Bug](https://github.com/Cadwalader307/Malio-Theme-for-SSPANEL/issues/new) | [改善文档 & 投稿](https://github.com/Cadwalader307/Malio-Theme-for-SSPANEL/Wiki) | [Fork & Pull Request](https://github.com/Cadwalader307/Malio-Theme-for-SSPANEL/pulls)

由于原开发团队已经放弃Malio主题，因此此项目欢迎各种贡献，包括但不限于改进，新功能，文档和代码改进，问题和错误报告。

## Wiki
[详细安装教程](https://gitlab.com/maxitio/malio-theme-for-sspanel/wikis/详细安装教程)

[授权说明](https://gitlab.com/maxitio/malio-theme-for-sspanel/wikis/授权说明)

## 注意事项
.malio_config.php 文件里的商品id必须设置好，不然在商店plans模式下没办法购买。

在.config.php里设置新用户注册等级为-1，如果不设置为-1的话，就没有新手引导教程，同时需要在.config.php里设置用户等级过期时间，建议设置为超过一个月的时间(720小时)。

安装完成后如果旧用户无法登录的话，检查下 .config.php 里面的 salt 和 pwdMethod 的值是否跟原来的 .config.php 一致。

端口偏移的说明查看 [端口偏移的食用方法](https://678765.xyz/2019/2.html)，根据群友说支持普通端口和单端口，格式跟uim原版的偏移不一样

如果需要配置Stripe支付接口的话，请看本仓库的wiki

需要去.config.php打开订阅记录的开关才会记录订阅


## AFF
推荐的支付平台👉 [BitPayX](https://merchants.mugglepay.com/user/register?ref=MP8DF1B016220D) ，支持数字货币、支付宝、微信，提款数字货币

## CREDIT
基于 [rico](https://github.com/rico93) 和 [GeekQu](https://github.com/GeekQu) 维护的 [ss-panel-v3-mod_Uim](https://github.com/rico93/ss-panel-v3-mod_Uim) 修改

