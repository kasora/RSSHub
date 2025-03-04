---
pageClass: routes
---

# 其他

## acwifi 路由器交流

### 新闻

<Route author="cc798461" example="/acwifi" path="/acwifi"/>
## Apple

### 更换和维修扩展计划

<Route author="metowolf HenryQW kt286" example="/apple/exchange_repair/zh-cn" path="/apple/exchange_repair/:country?" :paramsDesc="['苹果官网 URL 中的国家代码, 默认美国 ，中国 `zh-cn`']"/>

### App Store/Mac App Store

见 [#app-store-mac-app-store](/program-update.html#app-store-mac-app-store)

## AutoTrader

### 搜索结果

<Route author="HenryQW" example="/autotrader/radius=50&postcode=sw1a1aa&onesearchad=Used&onesearchad=Nearly%20New&onesearchad=New&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on" path="/autotrader/:query" :paramsDesc="['查询语句']">

1.  在 AutoTrader 选择筛选条件进行搜索
2.  复制查询结果 URL 中`?`后的部分，例如 `https://www.autotrader.co.uk/car-search?radius=50&postcode=sw1a1aa&onesearchad=Used&onesearchad=Nearly%20New&onesearchad=New&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on` 则为 `radius=50&postcode=sw1a1aa&onesearchad=Used&onesearchad=Nearly%20New&onesearchad=New&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on`

</Route>

## BOOKSOURCE.STORE

### 书源仓库更新

<Route author="vhxubo" example="/booksource" path="/booksource"/>

## checkee.info

### 美国签证 check 动态

<Route author="lalxyy" example="/checkee/2019-03" path="/checkee/:month" :paramsDesc="['签证被 check 的年份-月份，如 2019-03']" />

## ClickMe

### 文章

<Route author="hoilc" example="/clickme/default/category/beauty" path="/clickme/:site/:grouping/:name" :paramsDesc="['站点, `default`为普通站, `r18`为成人站, 其它值默认为普通站','分组方式, `category`为分类, `tag`为标签, 其他值默认为分类','分类名或标签名, 分类名为英文, 可以在分类 URL 中找到']" />

## dcinside

### board

<Route author="zfanta" example="/dcinside/board/programming" path="/dcinside/board/:id" :paramsDesc="['board id']" />

## DHL

### DHL 国际快递包裹追踪

<Route author="ntzyz" example="/dhl/12345678" path="/dhl/:shipment_id" :paramsDesc="['运单号']"/>

## HackerOne

### HackerOne Hacker Activity

<Route author="imlonghao" example="/hackerone/hacktivity" path="/hackerone/hacktivity" radar="1"/>

## Instapaper

### 个人分享

<Route author="LogicJake" example="/instapaper/person/viridiano" path="/instapaper/person"/>

## iYouport

### 首页

<Route author="EsuRt" example="/iyouport/article" path="/iyouport"/>

## MobData

### 分析报告

<Route author="brilon" example="/mobdata/report" path="/mobdata/report"/>

## NOI 全国青少年信息学奥林匹克竞赛

### 新闻

<Route author="WenryXu" example="/noi" path="/noi"/>

### 获奖名单

<Route author="WenryXu" example="/noi/winners-list" path="/noi/winners-list"/>

### 各省新闻

<Route author="WenryXu" example="/noi/province-news" path="/noi/province-news"/>

### 报名新闻

<Route author="WenryXu" example="/noi/rg-news" path="/noi/rg-news"/>

## ONE・一个

### 图片文字问答

<Route author="fengkx" example="/one" path="/one"/>

## Parcel Tracking

### Hermes UK

<Route author="HenryQW" example="/parcel/hermesuk/[tracking number]" path="/parcel/hermesuk/:tracking" :paramsDesc="['Tracking number']"/>

## Pocket

### Trending

<Route author="hoilc" example="/pocket/trending" path="/pocket/trending"/>

## Product Hunt

> 官方 Feed 地址为: <https://www.producthunt.com/feed>

### Today Popular

<Route author="miaoyafeng" example="/producthunt/today" path="/producthunt/today">
</Route>

## SANS Institute

### 最新会议材料

<Route author="sbilly" example="/sans/summit_archive" path="/sans/summit_archive" />

## TransferWise

### 昨日汇率变动

<Route author="HenryQW" example="/transferwise/pair/GBP/USD" path="/transferwise/pair/:source/:target" :paramsDesc="['本币缩写','外币缩写']">

参见支持的[货币列表](https://transferwise.com/tools/exchange-rate-alerts/)。

</Route>

## TSSstatus（iOS 降级通道）

### Status

<Route author="xyqfer" example="/tssstatus/j42dap/14W585a" path="/tssstatus/:board/:build" :paramsDesc="['平台 id', '版本 id']">

board 和 build 可在[这里](http://api.ineal.me/tss/status)查看

</Route>

## WeGene

### 最近更新

<Route author="LogicJake" example="/wegene/newest" path="/wegene/newest" radar="1"/>
### 栏目

<Route author="LogicJake" example="/wegene/column/all/all" path="/wegene/column/:type/:category" :paramsDesc="['栏目类型，all（全部项目） 或 weapp（专业版）','栏目分类']" radar="1">

:::
type 为 all 时，category 参数不支持 cost 和 free
:::

| 全部 | 祖源分析 | 付费 | 遗传性疾病 | 药物指南 | 免费 | 运动基因 | 营养代谢   | 心理特质   | 健康风险 | 皮肤特性 | 遗传特征 |
| ---- | -------- | ---- | ---------- | -------- | ---- | -------- | ---------- | ---------- | -------- | -------- | -------- |
| all  | ancestry | cost | disease    | drug     | free | genefit  | metabolism | psychology | risk     | skin     | traits   |

</Route>

## wikiHow

### 首页

<Route author="sanmmm" example="/wikihow/index" path="/wikihow/index"/>

### 分类目录

<Route author="sanmmm" example="/wikihow/category/饮食与休闲/all" path="/wikihow/category/:category/:type?" :paramsDesc="['目录分类', '类型, 默认为`all`']">

顶级目录分类可在目录分类页[查看](https://zh.wikihow.com/Special:CategoryListing), 支持二级目录

类型

| 所有 | 推荐 |
| ---- | ---- |
| all  | rec  |

</Route>

## 爱发电

### 发现用户

<Route author="sanmmm" example="/afdian/explore/hot/所有" path="/afdian/explore/:type/:category?" :paramsDesc="['分类', '目录类型, 默认为 `所有`']">
分类

| 推荐 | 最热 |
| ---- | ---- |
| rec  | hot  |

目录类型

| 所有 | 绘画 | 视频 | 写作 | 游戏 | 音乐 | 播客 | 摄影 | 技术 | Vtuber | 舞蹈 | 体育 | 旅游 | 美食 | 时尚 | 数码 | 动画 | 其他 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 所有 | 绘画 | 视频 | 写作 | 游戏 | 音乐 | 播客 | 摄影 | 技术 | Vtuber | 舞蹈 | 体育 | 旅游 | 美食 | 时尚 | 数码 | 动画 | 其他 |

</Route>

### 用户动态

<Route author="sanmmm" example="/afdian/dynamic/@afdian" path="/afdian/dynamic/:uid?" :paramsDesc="['用户id, 用户动态页面url里可找到']"/>

## 艾瑞

### 产业研究报告

<Route author="brilon" example="/iresearch/report" path="/iresearch/report"/>

## 百度搜索风云榜

### 榜单

<Route author="xyqfer" example="/baidu/topwords/1" path="/baidu/topwords/:boardId?" :paramsDesc="['榜单 id, 默认为`1`']">

| 实时热点 | 今日热点 | 七日热点 | 民生热点 | 娱乐热点 | 体育热点 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 1        | 341      | 42       | 342      | 344      | 11       |

</Route>

## 毕马威

### 洞察

<Route author="LogicJake" example="/kpmg/insights" path="/kpmg/insights" />

## 东莞教研网

### 信息公开

<Route author="nczitzk" example="/dgjyw/news" path="/dgjyw/:type" :paramsDesc="['分类']">

| 动态 | 公示         | 通知   |
| ---- | ------------ | ------ |
| news | announcement | notice |

</Route>

## 福利资源 - met.red

### 福利资源 - met.red

<Route author="junfengP" example="/metred/fuli" path="/metred/fuli" />

## 古诗文网

### 首页推荐

<Route author="LogicJake" example="/gushiwen/recommend" path="/gushiwen/recommend"/>

## 国家留学网

### 通知

<Route author="Derekmini markmingjie" example="/csc/notice/lxtz" path="/csc/notice/:type?" :paramsDesc="['分类, 默认为 `lxtz`']" radar="1">

| 遴选通知 | 综合项目专栏 | 常见问题解答 | 录取公告 | 新闻资讯 | 新闻公告 |
| -------- | ------------ | ------------ | -------- | -------- | -------- |
| lxtz     | xmzl         | wtjd         | lqgg     | xwzx     | xwgg     |

</Route>

## 国家自然科学基金委员会

### 新闻通知

<Route author="Derekmini" example="/nsfc/news/jjyw" path="/nsfc/news/:type?" :paramsDesc="['分类, 默认为 `jjyw`']" radar="1">

| 基金要闻 | 通知公告 | 资助成果 | 科普快讯 |
| -------- | -------- | -------- | -------- |
| jjyw     | tzgg     | zzcg     | kpkx     |

</Route>

## 好队友

### 工作机会

<Route author="lotosbin" example="/network360/jobs" path="/network360/jobs"/>

## 惠誉评级

### 板块信息

<Route author="LogicJake" example="/fitchratings/site/economics" path="/fitchratings/site/:type" :paramsDesc="['板块名称，在网址 site 后面']"/>

## 静态模型爱好者

### 新品信息

<Route author="cc798461" example="/moxingfans" path="/moxingfans"/>

## 考研帮

### 考研帮调剂信息

<Route author="sushengmao" example="/kaoyan" path="/kaoyan" />

## 空气质量

### 实时 AQI

<Route author="xapool" example="/aqicn/beijing" path="/aqicn/:city" :paramsDesc="['城市拼音或地区 ID，详见[aqicn.org](http://aqicn.org/city/)']"/>

## 酷安

### 图文 - 编辑精选

<Route author="xizeyoupan" example="/coolapk/tuwen" path="/coolapk/tuwen" />

## 快递 100

### 快递订单追踪

<Route author="NeverBehave" example="/kuaidi100/track/shunfeng/SF1007896781640/0383" path="/kuaidi100/track/:number/:id/:phone?" :paramsDesc="['快递公司代号', '订单号', '手机号后四位（仅顺丰）']" radar="1">

快递公司代号如果不能确定，可通过下方快递列表获得。

::: warning 注意

1.  构造链接前请确认所有参数正确：错误`快递公司 - 订单号`组合将会缓存信息一小段时间防止产生无用查询
2.  正常查询的订单在未签收状态下不会被缓存：请控制查询频率
3.  订单完成后请尽快取消订阅，避免资源浪费

:::
</Route>

### 支持的快递公司列表

<Route author="NeverBehave" example="/kuaidi100/company" path="/kuaidi100/company" radar="1"/>

## 裏垢女子まとめ

### 主页

<Route author="SettingDust"  example="/uraaka-joshi" path="/uraaka-joshi"/>

### 用户

<Route author="SettingDust"  example="/uraaka-joshi/_rrwq" path="/uraaka-joshi/:id" :paramsDesc="['用户名']"/>

## 律师事务所文章

### 君合

<Route author="snipersteve" example="/law/jh" path="/law/jh" />

### 通商

<Route author="snipersteve" example="/law/ts" path="/law/ts" />

### 海问

<Route author="snipersteve" example="/law/hw" path="/law/hw" />

### 环球

<Route author="snipersteve" example="/law/hq" path="/law/hq" />

### 国枫

<Route author="snipersteve" example="/law/gf" path="/law/gf" />

### 中伦

<Route author="snipersteve" example="/law/zl" path="/law/zl" />

### 锦天城

<Route author="snipersteve" example="/law/jtc" path="/law/jtc" />

### 德恒

<Route author="snipersteve" example="/law/dh" path="/law/dh" />

### 金诚同达

<Route author="snipersteve" example="/law/jctd" path="/law/jctd" />

## 马良行

### 产品更新

<Route author="junfengP" example="/mlhang" path="/mlhang" />

## 每日生猪价格

### 每日生猪价格更新

<Route author="importcjj" example="/pork-price" path="/pork-price" />

## 米坛社区

### 表盘更新

<Route author="hoilc" example="/watchface/mi4/" path="/watchface/:watch_type?/:list_type?" :paramsDesc="['手环型号, 默认为`小米手环4`', '列表类型, 默认为`最新上传`']">

表盘型号

| 小米手环 4 | 华米 GTR 47mm | 华米智能手表青春版 |
| ---------- | ------------- | ------------------ |
| mi4        | gtr47         | gvlite             |

列表类型

| 最新上传 | 最多下载 | 编辑推荐   |
| -------- | -------- | ---------- |
| 0        | 1        | recommends |

</Route>

## 模型网

### 新闻

<Route author="cc798461" example="/moxingnet" path="/moxingnet"/>

## 且听风吟福利

### 分类

<Route author="qiwihui" example="/qtfyfl/guoji" path="/qtfyfl/:category" :paramsDesc="['分类，可在 URL 中找到']">

| 最新文章 | 福利社  | 求出处    | 套图集  | 门事件     | 内涵图   | 电影下载       | 影视资讯 |
| -------- | ------- | --------- | ------- | ---------- | -------- | -------------- | -------- |
| latest   | fulishe | qiuchuchu | taotuji | menshijian | neihantu | dianyingxiazai | yingshi  |

| 电视剧下载 | 动漫下载 | 电影彩蛋 | 影视剧情 | 涨姿势     | 娱乐 | 明星八卦 | 音乐歌曲 |
| ---------- | -------- | -------- | -------- | ---------- | ---- | -------- | -------- |
| dianshiju  | dongman  | caidan   | juqing   | zhangzishi | yule | mingxing | music    |

| 游戏  | 电脑软件 | 实时热点     | 心灵鸡汤 | 符号大全 | 国际新闻 | 科技苑 | 其他  |
| ----- | -------- | ------------ | -------- | -------- | -------- | ------ | ----- |
| games | software | shishiredian | xljt     | fhdq     | xljt     | tech   | other |

</Route>

## 親子王國

### 板块

<Route author="LogicJake"  example="/babykingdom/19/view" path="/babykingdom/:id/:order?" :paramsDesc="['板块id，可在 URL 中找到', '排序方式']">

| 发帖时间 | 回复 / 查看 | 查看 | 最后发表 | 热门 |
| -------- | ----------- | ---- | -------- | ---- |
| dateline | reply       | view | lastpost | heat |

</Route>

## 日本郵便

### 郵便追跡サービス

<Route author="tuzi3040" example="/japanpost/EJ123456789JP/ja" path="/japanpost/:reqCode/:locale?" :paramsDesc="['运单号', '语言，默认为`ja`']" radar="1">

| 日语 | 英语 |
| ---- | ---- |
| ja   | en   |

</Route>

## 上证债券信息网

### 可转换公司债券公告

<Route author="kt286" example="/sse/convert/beginDate=2018-08-18&endDate=2019-08-18&companyCode=603283&title=股份" path="/sse/convert/:query?" :paramsDesc="['筛选条件，见示例']"/>

### 科创板项目动态

<Route author="Jeason0228" example="/sse/renewal" path="/sse/renewal"/>

### 监管问询

<Route author="Jeason0228" example="/sse/inquire" path="/sse/inquire"/>

## 深圳证券交易所

### 上市公告 - 可转换债券

<Route author="Jeason0228" example="/szse/notice" path="/szse/notice"/>

### 问询函件 (全部 / 主板 / 中小企业板 / 创业板)

<Route author="Jeason0228" example="/szse/inquire/navall" path="/szse/inquire/:type"  :paramsDesc="['tab选项,navall为全部,nav1为主板,nav2,为中小企业板,nav3位创业板']"/>

## 四川省科学技术厅

### 四川省科学技术厅 - 公示公告

<Route author="Cubernet" example="/sckjt/news" path="/sckjt/news/:type?" :paramsDesc="['默认为`tz`']">

| 通知 | 公示公告 |
| ---- | -------- |
| tz   | gs       |

</Route>

## 搜狗

### 搜狗特色 LOGO

<Route author="xyqfer" example="/sogou/doodles" path="/sogou/doodles"/>

## 腾讯吐个槽

### 吐槽新帖

<Route author="Qixingchen" example="/tucaoqq/post/28564/CdRI0728" path="/tucaoqq/post/:project/:key" :paramsDesc="['产品 ID', '产品密钥']"/>

## 腾讯新闻较真查证平台

### 最新辟谣

<Route author="hoilc" example="/factcheck" path="/factcheck"/>

## 天津产权交易中心

### 产权转让

<Route author="kt286" example="/tprtc/cqzr" path="/tprtc/cqzr"/>

### 企业资产转让

<Route author="kt286" example="/tprtc/qyzc" path="/tprtc/qyzc"/>

### 新闻动态

<Route author="kt286" example="/tprtc/news" path="/tprtc/news"/>

## 新冠肺炎疫情新闻动态

### 国家卫健委 - 疫情通报

<Route author="Cielpy DIYgod" example="/coronavirus/nhc" path="/coronavirus/nhc"/>

### 财新网 - 新冠肺炎防疫全纪录

<Route author="DIYgod" example="/coronavirus/caixin" path="/coronavirus/caixin"/>

### 丁香园 - 新冠病毒疫情实时播报

<Route author="DIYgod" example="/coronavirus/dxy" path="/coronavirus/dxy"/>

### 丁香园 - 新冠病毒疫情数据统计

<Route author="DIYgod HenryQW" example="/coronavirus/dxy/data/湖北/武汉" path="/coronavirus/dxy/data/:province?/:city?" :paramsDesc="['省/直辖市名，缺省或错误则返回国内数据','城市名，缺省或错误则返回全省数据。直辖市请使用区/县名。']"/>

### 腾讯新闻 - 新型冠状病毒肺炎实时辟谣

<Route author="DIYgod" example="/coronavirus/qq/fact" path="/coronavirus/qq/fact"/>

### South China Morning Post - China coronavirus outbreak

<Route author="DIYgod" example="/coronavirus/scmp" path="/coronavirus/scmp"/>

### 澳門特別行政區政府 抗疫專頁：最新消息

官方網址：<https://www.ssm.gov.mo/apps1/PreventWuhanInfection/ch.aspx>

<Route author="KeiLongW" example="/coronavirus/mogov-2019ncov/ch" path="/coronavirus/mogov-2019ncov/:lang" :paramsDesc="['語言']"/>

| 中文 | 英文 | 葡文 |
| ---- | ---- | ---- |
| ch   | en   | pt   |

### Singapore Ministry of Health - Past Updates on 2019-nCov Local Situation in Singapore

<Route author="Gnnng" example="/coronavirus/sg-moh" path="/coronavirus/sg-moh"/>

## 新趣集

> 官方 Feed 地址为: <https://xinquji.com/rss>

### 今日最佳

<Route author="kiddyuchina" example="/xinquji/today" path="/xinquji/today">
</Route>

### 今日国内

<Route author="kiddyuchina" example="/xinquji/today/internal" path="/xinquji/today/internal">
</Route>

## 新田惠海官方网站

### 最近的更新

<Route author="luyuhuang" example="/emi-nitta/updates" path="/emi-nitta/updates"/>

### 新闻

<Route author="luyuhuang" example="/emi-nitta/news" path="/emi-nitta/news"/>

## 油价

### 今日油价

<Route author="xyqfer" example="/oilprice/shanghai" path="/oilprice/:area" :paramsDesc="['地区拼音，详见[成品油价格网](http://oil.usd-cny.com/)']"/>

## 邮箱

### 邮件列表

> 仅支持 IMAP 协议，邮件密码等设置见 [邮件设置](/install/#其他应用配置)

<Route author="kt286" example="/mail/imap/rss@rsshub.app" path="/mail/imap/:email" :paramsDesc="['邮箱账号']" />

## 源仓库

### 源仓库更新

<Route author="vhxubo" example="/ku" path="/ku/:name?" :paramsDesc="['默认为 `yuedu`']">
| 阅读 | 异次元 | 海阔 |
| ---- | ----- | ---- |
| yuedu | yiciyuan | haikuo |

</Route>

## 远程 work

### 远程 work 招聘信息

<Route author="luyuhuang" example="/remote-work/all" path="/remote-work/:caty?" :paramsDesc="['职位类型, 默认为全部职位']" radar="1">

| 所有职位 |     技术    |  设计  |    运营   |   产品  |  其他 |    市场   |  销售 |
| :------: | :---------: | :----: | :-------: | :-----: | :---: | :-------: | :---: |
|    all   | development | design | operation | product | other | marketing | sales |

</Route>

## 正版中国

### 分类列表

<Route author="sanmmm" example="/getitfree/category/8" path="/getitfree/category/:category?" :paramsDesc="['内容类型, 默认为`全部`']">

类型

| 全部文章 | 永久免费 | 限时折扣 | 限时免费 | PC | Mac | Android | UWP |
| -------- | -------- | -------- | -------- | -- | --- | ------- | --- |
| all      | 311      | 309      | 310      | 8  | 50  | 17      | 312 |

</Route>

### 搜索

<Route author="sanmmm" example="/getitfree/search/windows" path="/getitfree/search/:keyword" :paramsDesc="['搜索关键词']"/>

## 智联招聘

### 搜索

<Route author="SunShinenny" example="/zhilian/台州/JavaScript" path="/zhilian/:city/:keyword" :paramsDesc="['城市「如若无该城市数据，将会报错」','搜索关键词']"/>

## 中国银行

### 中国银行外汇牌价

<Route author="LogicJake HenryQW" example="/boc/whpj/zs?filter_title=%E8%8B%B1%E9%95%91" path="/boc/whpj/:format?" :paramsDesc="['输出的标题格式，默认为标题 + 所有价格。短格式仅包含货币名称。']">

| 短格式 | 中行折算价 | 现汇买卖 | 现钞买卖 | 现汇买入 | 现汇卖出 | 现钞买入 | 现钞卖出 |
| ------ | ---------- | -------- | -------- | -------- | -------- | -------- | -------- |
| short  | zs         | xh       | xc       | xhmr     | xhmc     | xcmr     | xcmc     |

</Route>

## 中国邮政速递物流

### 新闻

<Route author="luyuhuang" example="/ems/news" path="/ems/news" radar="1"/>

## 自如

### 房源

<Route author="DIYgod" example="/ziroom/room/sh/1/2/五角场" path="/ziroom/room/:city/:iswhole/:room/:keyword" :paramsDesc="['城市, 北京 bj; 上海 sh; 深圳 sz; 杭州 hz; 南京 nj; 广州 gz; 成都 cd; 武汉 wh; 天津 tj', '是否整租', '房间数', '关键词']"/>

## はてな

### はてな匿名ダイアリー - 人気記事アーカイブ

<Route author="masakichi" example="/hatena/anonymous_diary/archive" path="/hatena/anonymous_diary/archive"/>
