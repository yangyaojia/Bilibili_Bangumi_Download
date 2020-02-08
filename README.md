# Bilibili_Bangumi_Download
### :star2:B站下载姬～召唤你喜爱的番剧吧！～:star2:

![](https://img.shields.io/badge/Python-3.7.4-green.svg) ![](https://img.shields.io/badge/requests-2.22.0-green.svg) ![](https://img.shields.io/badge/moviepy-1.0.1-green.svg)

### Bilibili官网 - https://www.bilibili.com/
|Author|YJSchaf|
|---|---
|Blog|yangyaojia.github.io
---
## :star2:声明
### 本软件仅供于二刺螈爱好者交流学习，请勿用于任何盈利活动！！！

## :star2:介绍
### B站下载姬用于下载[B站](https://www.bilibili.com/)的番剧！！(支持批量下载，也支持下载番剧以外的视频)
- 因为我的**朋友**想用B站上的番做MMD,于是就帮ta做了一个[B站](https://www.bilibili.com/)番剧下载姬了。
- 只需要告诉下载姬你想下载番剧的av号，她会很温柔地引导您下载哟！

## :star2:版本
- Alpha 2.7 版本
> * 本版本无任何错误抛出的处理，要是下载姬挂了就重来吧
> * 虽然本版本无可视化界面，但下载姬一定会变得更可爱的！
> * 本版本包括已经打包好的exe程序，可以随时随地使用哟！:sunglasses:

## :star2:运行环境

**Version : Python3**


## :star2:安装依赖库（~如果master想运行python版的话~）
```bash
pip install moviepy==1.0.1
pip install requests==2.22.0
```

## :star2:食用说明
> * 输入av号只要数字哟！

>
> * 【Y/N】请输入大写Y与大写N
>> * 关于如何看番剧的AV号
>> * 打开网页版B站 --> 进入你想下载的番剧 --> 在播放器面番剧封面的右边写有AV号！

> * 关于下载清晰度&大会员
>> * 应为下载姬继承了我的血统，可以在一定时间内下载需要大会员的番，也可以下载1080P+的番（不过我要持续更新啦！）如果那天下载不了了，请联系我更新！

> * 关于下载路径
>> * 请用/（正斜杠）来连接文件夹，并输入绝对路径，如果不想输入，视频将会下载到与下载姬相同的文件夹下

> * 关于视频合并 
>> * 因为B站的视频是分流的flv视频，所以较长的视频将会由几个flv文件组成，如果master觉得手动跳视频很很烦，下载姬提供合并服务哟！
>> * 合并所花的时间可能较长，取决于电脑处理器的速度，请根据实际情况选择是否合并
>> * 合并采用moviepy库进行合并，编码为H.264,输出文件格式为mp4，windows自带的播放器可能无法解码，但是手机肯定是可以播放的！

> * 关于选集
>> * 一般的番剧是一个av号对应一集番，对于这种master只需要输入av号就可以选择master想下载的集数了
>> * 但有些番剧（尤其是早些时候的番）是相当于一个视频（一个av号）分多p，这时下载姬会提醒master选择下载的集数，请选择master需要的集数。

> * 感性理解下载速度，耐心等待后，请开始master的食用吧！

## :heart:鸣谢
* 感谢[@Henryhaohao](https://github.com/Henryhaohao/)的同样的项目中关于B站上两个api的提供；这两个api并未在网页中出现，在网页中的vedio.js文件中很隐蔽地调用了，dalao真的牛！
* 感谢一些大佬的博客，他们交给我了很多知识！


## :star2:写在最后
**下载姬是我的第一个项目，如果你觉得这个项目很有趣或者是对你有点用，请点一下上面的星星吧！这也是对我学习上的鼓励！**
**那么,我是[YJSchaf](https://github.com/yangyaojia/)，我们下次更新再见！**


### :star2:写在写在最后的最后
如果您有上面有趣的想法和改进意见，请务必与我联系哟！
