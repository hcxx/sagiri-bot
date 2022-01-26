# 内置模块

本篇为内置模块，若您不需要使用某一模块，可以删除模块或通过 `saya_manager` 进行管理

> ## 超分辨率

一个图片超分插件

模块位置：`sagiri_bot.handler.handlers.super_resolution`

使用方法：在群中发送 `/超分 图片` 即可

注意：若需要使用本插件，请运行 `pip install realesrgan basicsr`，若不安装则插件默认不启用

> ## 缩写预测

一个获取英文缩写意思的插件

模块位置：`sagiri_bot.handler.handlers.abbreviated_prediction`

使用方法：在群中发送 `缩 内容` 即可

> ## 普通话转抽象话

一个普通话转抽象话的插件

模块位置：`sagiri_bot.handler.handlers.abstract_message_transformer`

使用方法：在群中发送 `/抽象 文字` 即可

> ## 头像趣图

一个可以生成头像相关趣味图的插件

模块位置：`sagiri_bot.handler.handlers.avatar_fun_pic`

使用方法：在群中发送 `[摸|亲|贴|撕|丢|爬|精神支柱|吞] [@目标|目标qq|目标图片]` 即可

来源：部分来自于 [MeetWq](https://github.com/MeetWq/mybot/) & [SuperWaterGod](https://github.com/SuperWaterGod)

> ## 搜番

一个可以搜索番剧信息的插件

模块位置：`sagiri_bot.handler.handlers.bangumi_info_searcher`

使用方法：在群中发送 `番剧 {番剧名}` 即可

注意：可能需要设置代理

> ## 以图搜番

一个可以根据图片搜索番剧的插件

模块位置：`sagiri_bot.handler.handlers.bangumi_searcher`

使用方法：在群中发送 `搜番` 后，等待回应在30s内发送图片即可（多张图片只会搜索第一张）

注意：可能需要设置代理

> ## BiliBili 7日内新番

一个可以获取BiliBili7日内新番时间表的插件

模块位置：`sagiri_bot.handler.handlers.bilibili_bangumi_scheduler`

使用方法：在群内发送 `[1-7]日内新番` 即可

> ## 黑白生草图

一个生成黑白草图的插件

模块位置：`sagiri_bot.handler.handlers.black_white_grass`

使用方法：在群中发送 `黑白[草]图 内容 图片` 即可

> ## 智能回复

一个可以实现智能回复的插件

模块位置：`sagiri_bot.handler.handlers.chat_reply`

使用方法：

- 在群中发送 `@bot + 想说的话` 即可
- 使用 `setting -set speakMode(speak_mode)=value` 即可改变说话方式

其中 `value` 如下：

| 名称 | 描述 | 备注 |
| --- | --- | --- |
| normal | 不进行回复 |  |
| zuanLow | 嘴臭（低浓度） |  |
| zuanHigh | 嘴臭（高浓度） |  |
| rainbow | 彩虹屁模式 |  |
| chat | 腾讯云智能回复 | 自行注册腾讯云获取 `secret_id` & `secret_key` |

> ## CP文生成

一个生成CP文的插件

模块位置：`sagiri_bot.handler.handlers.cp_generator`

使用方法：在群中发送 `/cp {攻名字} {受名字}`

> ## 骰子

一个简单的投骰子插件

模块位置：`sagiri_bot.handler.handlers.dice`

使用方法：在群中发送 `{times}d{range}` 即可

> ## emoji融合

一个生成emoji融合图的插件

模块位置：`sagiri_bot.handler.handlers.emoji_mix`

使用方法：在群中发送 '{emoji1}+{emoji2}' 即可

来源：[nonebot-plugin-emojimix](https://github.com/MeetWq/nonebot-plugin-emojimix)

> ## 一个生成转发消息的插件

转发消息生成器

模块位置：`sagiri_bot.handler.handlers.fake_forward`

使用方法：在群中发送 `/fake {content} @target` 即可

> ## 闪照转换插件

闪照转换插件

模块位置：`sagiri_bot.handler.handlers.flash_image_catcher`

使用方法：自动触发，可通过 `setting -set antiFlashImage(anti_flash_image)=False` 关闭

> ## Github项目搜索

可以搜索Github项目信息的插件

模块位置：`sagiri_bot.handler.handlers.github_info`

使用方法：在群中发送 `github [-i] {项目名}` 即可，其中 `-i` 为可选项，代表图片化输出

注意：可能需要设置代理

> ## 群词云生成器

群词云生成器

模块位置：`sagiri_bot.handler.handlers.group_wordcloud_generator`

使用方法：

- 在群中发送 `我的月/年内总结` 即可查看个人月/年词云
- 在群中发送 `本群月/年内总结` 即可查看群组月/年词云（需要权限等级2）

> ## 热梗解释

一个可以查询热梗的插件

模块位置：`sagiri_bot.handler.handlers.hot_words_explainer`

使用方法：在群中发送 `{keyword}是什么梗` 即可

> ## 我有一个朋友

一个生成假聊天记录截图插件

模块位置：`sagiri_bot.handler.handlers.i_have_a_friend`

使用方法：在群中发送 `我(有一?个)?朋友(想问问|说|让我问问|想问|让我问|想知道|让我帮他问问|让我帮他问|让我帮忙问|让我帮忙问问|问) 内容 [@目标]` 即可

> ## 图片存储

一个能够在图库中添加图片的插件

模块位置：`sagiri_bot.handler.handlers.image_adder`

使用方法：在群中发送 `添加(图库名)图片([图片])+` 即可

> ## 以图搜图

一个可以以图搜图的插件

模块位置：`sagiri_bot.handler.handlers.image_searcher`

使用方法：在群中发送 `搜图` 后，等待回应在30s内发送图片即可（多张图片只会搜索第一张）

注意：可能需要设置代理

> ## 图库

一个可以自定义图库发送图片的插件

模块位置：`sagiri_bot.handler.handlers.image_sender`

使用方法：

- 在群中发送设置好的关键词即可
- 在群中发送 `(添加|删除|查看)图库关键词#{gallery_name}#{keyword}` 即可添加/删除/查看图库关键词
- 在群中发送 `查看已加载图库` 即可查看已加载图库

> ## 笑话生成

一个生成笑话的插件，内置了苏联&美国&法国笑话

模块位置：`sagiri_bot.handler.handlers.joke`

使用方法：在群中发送 `来点{keyword|法国|苏联|美国}笑话`

> ## 关键词回复

一个关键字回复插件，在群中发送已添加关键词可自动回复

模块位置：`sagiri_bot.handler.handlers.keyword_respondent`

使用方法：

- 在群中发送已添加关键词可自动回复
- 在群中发送 `添加回复关键词#{keyword}#{reply}` 可添加关键词
- 在群中发送 `删除回复关键词#{keyword}` 可删除关键词

> ## 钉宫语音

一个钉宫语音包插件

模块位置：`sagiri_bot.handler.handlers.kugimiya_voice`

使用方法：发送 `来点钉宫` 即可

> ## Leetcode信息

一个可以获取Leetcode信息的插件

模块位置：`sagiri_bot.handler.handlers.leetcode_info`

使用方法：

- 在群中发送 `leetcode userslug` 可查询个人资料（userslug为个人主页地址最后的唯一识别代码）
- 在群中发送 `leetcode每日一题` 可查询每日一题

> ## Lolicon图片

一个接入lolicon api的插件

模块位置：`sagiri_bot.handler.handlers.lolicon_keyword_searcher`

使用方法：在群中发送 `来点{keyword}[色涩瑟]图` 即可

> ## 鲁迅说过

一个生成鲁迅说过表情包的插件

模块位置：`sagiri_bot.handler.handlers.luxun_said`

使用方法：在群中发送 `鲁迅[曾经]说过 内容` 即可

来源： [真寻bot](https://github.com/HibiKier/zhenxun_bot)

> ## 营销号生成器

一个营销号内容生成器插件

模块位置：`sagiri_bot.handler.handlers.marketing_content_generator`

使用方法：在群中发送 `营销号#事件主体#事件内容#事件另一种说法` 即可

> ## 消息转图片

将收到的消息合并为图片，支持文字和图片

模块位置：`sagiri_bot.handler.handlers.message_merger`

使用方法：在群中发送 `/merge 文字/图片` 即可

> ## 网络编译器

一个网络编译器插件

模块位置：`sagiri_bot.handler.handlers.network_compiler`

使用方法：在群中发送 `super language\ncode`即可

> ## PDF搜索

一个可以搜索pdf的插件

模块位置：`sagiri_bot.handler.handlers.pdf_searcher`

使用方法：在群中发送 `pdf 书名` 即可

注意：可能需要设置代理

> ## 舔狗日记

一个获取舔狗日记的插件

模块位置：`sagiri_bot.handler.handlers.pero_dog`

使用方法：在群中发送 `舔` 即可

> ## 幻影坦克

一个幻影坦克生成器

模块位置：`sagiri_bot.handler.handlers.phantom_tank`

使用方法：

- 在群中发送 `幻影 [显示图] [隐藏图]` 可获得黑白幻影图
- 在群中发送 `彩色幻影 [显示图] [隐藏图]` 可获得彩色幻影图

> ## 毒鸡汤

一个获取毒鸡汤的插件

模块位置：`sagiri_bot.handler.handlers.poisonous_chicken_soup`

使用方法：在群中发送 `[鸡汤|毒鸡汤|来碗鸡汤]` 即可

> ## 文字转二维码

一个生成二维码的插件，仅支持文字

模块位置：`sagiri_bot.handler.handlers.qrcode_generator`

使用方法：在群中发送 `qrcode {content}` 即可（文字）

> ## 随机人设

一个随机生成人设插件

模块位置：`sagiri_bot.handler.handlers.random_character`

使用方法：在群中发送 `随机人设` 即可

来源：[A60](https://github.com/djkcyl/ABot-Graia)

> ## 随机老婆

一个生成随机老婆图片的插件

模块位置：`sagiri_bot.handler.handlers.random_wife`

使用方法：在群中发送 `[来个老婆|随机老婆]`

> ## 复读机

一个复读插件

模块位置：`sagiri_bot.handler.handlers.repeater`

使用方法：自动触发

> ## 语音合成

一个语音合成插件

模块位置：`sagiri_bot.handler.handlers.speak`

使用方法：在群中发送 `说 {content}` 即可

> ## steam游戏搜索

一个可以搜索steam游戏信息的插件

模块位置：`sagiri_bot.handler.handlers.steam_game_info_searcher`

使用方法：在群中发送 `steam {game_name}` 即可

注意：可能需要设置代理

> ## 风格logo图片生成

一个可以生成不同风格logo图片的插件

模块位置：`sagiri_bot.handler.handlers.style_picture_generator`

使用方法：在群中发送 `[5000兆|ph|yt] {文字1} {文字2}` 即可

其中 `ph` 为 `pronhub` 风格，`yt` 为 `youtube` 风格，`5000兆` 为 `5000兆元` 风格

> ## 塔罗牌

一个可以抽塔罗牌的插件

模块位置：`sagiri_bot.handler.handlers.tarot`

使用方法：在群中发送 `塔罗牌` 即可

来源：[MeetWq](https://github.com/MeetWq/mybot/)

> ## trending

一个获取热搜的插件

模块位置：`sagiri_bot.handler.handlers.trending`

使用方法：

- 在群中发送 `微博热搜` 即可查看微博热搜
- 在群中发送 `知乎热搜` 即可查看知乎热搜
- 在群中发送 `github热搜` 即可查看github热搜

注意：可能需要设置代理

> ## 科学计算

一个接入WolframAlpha的插件

模块位置：`sagiri_bot.handler.handlers.wolfram_alpha`

使用方法：在群中发送 `/solve {content}` 即可