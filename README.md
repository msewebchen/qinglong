## 青龙(WIP)

青龙，又名苍龙，在中国传统文化中是四象之一、[天之四灵](https://zh.wikipedia.org/wiki/%E5%A4%A9%E4%B9%8B%E5%9B%9B%E7%81%B5)之一，根据五行学说，它是代表东方的灵兽，为青色的龙，五行属木，代表的季节是春季，八卦主震。苍龙与应龙一样，都是身具羽翼。《张果星宗》称“又有辅翼，方为真龙”。

《后汉书·律历志下》记载：日周于天，一寒一暑，四时备成，万物毕改，摄提迁次，青龙移辰，谓之岁。

在中国[二十八宿](https://zh.wikipedia.org/wiki/%E4%BA%8C%E5%8D%81%E5%85%AB%E5%AE%BF)中，青龙是东方七宿（角、亢、氐、房、心、尾、箕）的总称。 在早期星宿信仰中，祂是最尊贵的天神[1]。 但被道教信仰吸纳入其神系后，神格大跌，道教将其称为“孟章”，在不同的道经中有“帝君”、“圣将”、“神将”和“捕鬼将”等称呼[2]，与白虎监兵神君一起，是道教的护卫天神。

## 多谢

本仓库部分shell脚本及其配置参考自[nevinee](https://github.com/nevinee)大佬, [https://github.com/nevinee/jd_shell](https://github.com/nevinee/jd_shell), 感谢👍👍👍

## 免责声明

1. 此仓储脚本仅用于学习研究，不保证其合法性、准确性、有效性，请根据情况自行判断，本人对此不承担任何保证责任。

2. 由于此仓储脚本仅用于学习研究，您必须在下载后 24 小时内将所有内容从您的计算机或手机或任何存储设备中完全删除，若违反规定引起任何事件本人对此均不负责。

3. 请勿将此仓储脚本用于任何商业或非法目的，若违反规定请自行对此负责。

4. 此仓储脚本涉及应用与本人无关，本人对因此引起的任何隐私泄漏或其他后果不承担任何责任。

5. 本人对任何脚本引发的问题概不负责，包括但不限于由脚本错误引起的任何损失和损害。

6. 如果任何单位或个人认为此仓储脚本可能涉嫌侵犯其权利，应及时通知并提供身份证明，所有权证明，我们将在收到认证文件确认后删除此仓储脚本。

7. 所有直接或间接使用、查看此仓储脚本的人均应该仔细阅读此声明。本人保留随时更改或补充此声明的权利。一旦您使用或复制了此仓储脚本，即视为您已接受此免责声明。
docker run -dit \
   -v /root/qinglong/scripts:/ql/scripts \
   -v /root/qinglong/config:/ql/config \
   -v /root/qinglong/log:/ql/log \
   -p 5700:5700 \
   -e ENABLE_HANGUP=true \
   -e ENABLE_WEB_PANEL=true \
   --network bridge \
   --name qinglong \
   --hostname qinglong \
   --restart always \
   whyour/qinglong:latest

### one more thing

![one-more-thing](https://image.whyour.cn/others/nice.png)
