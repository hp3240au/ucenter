ucenter
=======

ucenter for wordpress_sae

=== Plugin Name ===

Contributors: 京金鹏

Donate link: http://www.youni.net.cn/

Tags: plugin, ucenter, integration ，sae

Requires at least: 2.9

Tested up to: 3.9.1

Stable tag: 0.3.5




WordPress的集成与UCenter的，这将使得WordPress的工作与UCenter的支持平台。




== Description ==




插件针对WordPress sae版本。使用它，您可以轻松地整合UCenter和WordPress。

提示：测试平台为wordpress sae 3.9.1

 

当用户登录WordPress：

1、如果用户在UCenter不存在，则自动注册用户名。

2、如果用户存在于UCenter的，如果启用了“覆盖选项”，用户将登录成功和密码在WordPress将在UCenter的被覆盖。否则，登录失败。

3、当删除用户在WordPress，用户在UCenter的将被删除。

4、当用户登录其他应用程序，用户也将自动登录WordPress的。

5、当用户注销的WordPress，用户也将自动注销其他应用程序的登陆。

6、当用户注销的其他应用程序，用户也将自动登出WordPress。







提示：本插件未在多站点上做测试。本插件是修订ucenter-integration插件而来的，感谢原作者ychen  




升级UCclient到1.6.0版本




== 安装 ==




1. 上传目录路径wp-content/plugins/ucenter-integration/

2. 激活插件

3. 设置参数

4、将安装包内的cache文件夹剪切粘贴到client\data\cache


== 常见问题==




=仪表盘访问被拒绝怎么办？=




除config.php文件然后登录仪表板复位的UCenter整合设置。




=如果问题仍然存在，我该怎么办？




进入插件目录，删除UCenter插件文件然后重新安装这个插件。

== 快照 ==




1、设置




== 更新日志 ==




= 0.1 =

>第一个版本

>sae用户可以集成到UCenter

>集成到UCenter会自动登录WordPress以及其他ucenter集成的应用程序

>当用户不存在UCenter，用户将被自动在UCenter注册

== 升级提示==




= 0.1 =

> 第一个版本，没有提示内容

  
