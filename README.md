速录宝是一款使用PC键盘进行并击录入的开源绿且色便携式的并击输入法平台，目前支持在windows平台使用。可以自定义并击方案，词库，也可以配合第3方输入法使用。自带空明码，也支持五笔、两笔、郑码、小鹤等等。

IDE VS2022 开发前先将本目录下的bin.zip解压到项目：Core\bin 中

交流群：374971723 http://srkmm.ys168.com/

此项目的目标是能运行在Win，Linux，苹果，安卓，IOS等平台下的一个中文并击录入平台

主要实现功能 Win：

1.支持自定义码表

2.支持自定义并击映射

3.支持中英文并击录入，不需要使用shift配合，演示：https://www.bilibili.com/video/BV1uT411F7Q2/

4.支持自定义

5.一码、三码、四码自动上屏

6.支持大于4位 小于50位 码长

7.速录助手模式，配合第3方输入法实现键盘并击录入

8.支持整句输出文字和输出图片 演示：https://www.bilibili.com/video/BV1Ck4y147na/ https://www.bilibili.com/video/BV1gv4y1g7fG/


为验证大码元方案的高效性，在超强两笔的基础上设计了空明码： 空明码可以使用60个码元进行编码，可扩展码元70个，26个小写字母，26个大写字母，0-9数字,还有标点都可做为编码。于2015年设计的并击速录方案，历经六年时间校对、使用验证才得以完善；何故取名空明码？其来源于空明拳，是中国武侠小说中的人物周伯通使用的一种左右互搏的绝世武功。由于左右手同时使用与左右同时并击相似而得名。它有重码极低、词汇量大、简单易学、科学规范的特点。重码低表现为：音码单字无重码；支持GBK在内2万多汉字输出，解决了不认识的汉字编码统一问题。词汇量大表现为：词库超过300万，让你打词随心所欲，且选重率低。简单易学表现在：只有10个字根和5种笔划（横竖撇点折），而且键位分布规律性强，不用死记硬背，取码简单规则统一，最快仅需十分钟就可学会。科学规范表现于：继承了超强两笔优点，编码严格遵循汉字笔划顺序，首码包含声韵，因此对汉字的读音和笔顺都起到积极的读写规范的作用。除上述特点，并击录入效率也提高了很高，普通文章理想平均码长0.8，只需每秒2.7次击键便可达到200以上的速度。所以它是一种打单不选重，打词“不选重”的简单高效且易学地并击速录输入法。

它的特点： 1、 音码单字无重码 2、超300万大词库，高频词低重码 3、一击字支持3000+ 4、一击高频词6500+ 5、分左右一简，一简字80+ 6、右手单击顶功 7、取码规律强，不用死记硬背

空明码 300速度演示地址：https://www.bilibili.com/video/BV1M3411Y7aB/

搜狗双拼 配合 并击助手 300速度录屏：https://www.bilibili.com/video/BV1VB4y1X7mz/

更新日志:

1.1版本 修复bug

1.2版本 加Alt和空格并击支持；支持Alt选2位置字词，支持Alt+空格选第3位置字词

1.5版本 支持win/alt加空格选重；支持`~@*_ 五个字符编码，支持7890四个数字编码

2.0版本 支持多并击方案，支持词库自动更新

2.0.8版本 支持分裂空格键盘(两个以上空格)定义并击选重和补码,去掉无用代码模块

2.1版本 支持拼音提示

2.2版本 支持按'键使用全拼模式

2.3版本 支持单击模式，并击辅助

2.6版本 修复已知问题，支持鼠标跟随

3.0 支持指法方案选择，支持皮肤换服

3.1.2 支持标点并出，支持指法正则配置，支持速录方案

3.1.6 支持标点并出
