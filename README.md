# Timeline Data

最新时间线互动图 [https://chinatimeline.github.io/](https://chinatimeline.github.io/)

**参与：** 欢迎提交PR (Pull Request)
1. 5分钟了解PR工作流程: [中文视频教程](https://boxueio.com/series/git-essential/episode/459), [文字教程：尝试Pull Request](https://www.jianshu.com/p/dd243fecf0f4), [English Video Tutorial](https://www.youtube.com/watch?v=rgbCcBNZcdQ), [About pull requests](https://help.github.com/en/articles/about-pull-requests)
2. 为避免被喝茶，请用与真实身份脱钩的github帐号
    * 墙内请用VPN+Tor访问: (1)如用本地目录请用[双虚拟机方案](https://program-think.blogspot.com/2013/11/tor-faq.html?m=1), (2)如仅网页编辑请用[Tor Browser](https://www.torproject.org/download/)
    * Github接受的匿名邮箱 [Protonmail](https://protonmail.com), [Tutanota](https://www.tutanota.com). 注册虚拟手机号 [TextNow](https://www.textnow.com)

## 1 目录结构与说明
```bash
├── README.md #本文件 数据仓库说明文档
├── ideology #中共意识形态保卫战
│   ├── CCP_Ideology_Timeline.json #从CPC Brainwashing Timeline导出的原始数据（停用）
│   ├── CCP_Ideology_Events.csv #事件数据文件
│   └── CCP_Presidential_term.csv #中共中央总书记任期（图中背景区块）
└── US_CN_TradeWar #美中贸易战
    ├── Persidential_Term.csv #美中领导人任期（图中背景区块）
    └── TradeWar_Events.csv #贸易战相关事件数据文件
```
### 1.1 数据格式说明

| date | name | group | description |
|---|---|---|---|
|2014-10-15|习近平主持召开文艺工作座谈会|网络空间实名制|新闻存档 https://archive.li/tDTZd |

文字编辑器中为
```text
date,name,group,description,
2014-10-15,习近平主持召开文艺工作座谈会,网络空间实名制,新闻存档 https://archive.li/tDTZd
```

注意：`,`必须是英文字符而非中文字符`，`如需在标题中使用英文字符`,`则须在内容加英文字符双引号`"xxx"`否则会出错，如：
```text
"2009-06-02","Twitter,Bing等微软服务被墙","网络空间实名制","http://www.chinagfw.org/2010/02/gfw_4590.html"
```
所以应尽量避免标题出现英文字符`,`

### 2 数据信息
#### 2.1 文件夹 ideology

中共为控制意识形态采取的各种措施及相关报道，分类如下（欢迎对分类提意见）：
1. 重大历史事件：具有标志性或里程碑意义、对历史产生重大影响的国内外政治或军事事件
1. 技术封锁：如GFW、金盾工程、黑客攻击等 （暂时并入“网络空间实名制”）
2. 网络空间实名制：各类促进网络实名制的行政措施、法律文件、拘留喝茶翻墙网友等
3. 建立宣传网站：各种宣传中共意识形态的极左网站、论坛、纪录片等
4. 进驻社交媒体：官方机构开设社交媒体帐号进驻各种互联网平台
5. 整治自由派社区：官方对自由派媒体、论坛、意见领袖的各种打压行动
6. 打击学术自由：针对学生、高校教师在高校环境内的迫害、洗脑、打压、处罚、审查、告密等
7. 干预互联网市场：以行政为主技术为辅的手段对互联网公司的运营进行插手、干扰、处罚等
9. (待添加)宗教迫害：为防止宗教思想传播而迫害宗教人士、群体、族群，审查和篡改宗教相关课文、书籍等

本数据初版来自“中共洗脑保党时间线” [https://time.graphics/line/226382](https://time.graphics/line/226382)

<!--![CPC Brainwashing Timeline](https://i.imgur.com/1xup0nr.png | width=50x)-->
<img src="https://i.imgur.com/1xup0nr.png" width="250">

#### 2.2 文件夹 US_CN_TradeWar

数据源: [The US China Trade War: A Timeline](https://www.china-briefing.com/news/the-us-china-trade-war-a-timeline/)

参考 [Bloomberg](https://www.bloomberg.com/news/articles/2019-01-30/u-s-china-trade-war-timeline-what-s-happened-and-what-s-next)

---
[MIT License](https://opensource.org/licenses/MIT) |
Update: 2019-06-18
