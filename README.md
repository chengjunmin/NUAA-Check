<h2 id="canshu">参数配置</h2>
student_id 学号  

password 密码  

sckey 在 [Server酱-发送消息](http://sc.ftqq.com/?c=code) 绑定微信找到SCKEY填入  

address XX省XX市（区）(XX县)XXX  

## 注意：
1. config.ini中所有的参数都是提交时提交上去的，默认全否，也就是不影响进校的最正常状态。
2. 如果您要修改打卡时间，请修改nuaa.yaml中的` - cron: '01 16 * * *'`,01代表分钟，16代表小时。请注时间是GMT时间，也就是比北京时间慢8个小时。
3. 程序设定每天00:01打卡，但是经过实际测试有很长延迟，可能为一小时左右

### 免责声明
本程序仅供学习参考，请在下载或fork后24小时内删除，否则后果自负！

