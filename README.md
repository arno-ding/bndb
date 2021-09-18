> 本数据库目前处于超早期的建设工作，许多设想中的工作尚未完成，欢迎感兴趣的朋友建言献策。
---
# 睡前消息数据库

> [睡前消息](https://space.bilibili.com/316568752)是由马前卒施工队制作的一档时政新闻评述类节目，本数据库是对其节目内容的简单索引，以及数据标注方便统计分析。

## 建立目的
- 本数据库的前身是石墨文档[睡前消息内容索引](https://shimo.im/sheets/H6pXDqDHjcYcv3YQ/MODOC)，由于石墨文档没有完善的版本控制，在维护的过程中遇到了很多困难，因此决定备份至Github，~~TODO:同时利用Github Pages建立一个简单的网站方便浏览~~。
- 原文档的数据是通过Excel组织的，无法很方便的做数据标注，因此在迁移过程中重新组织了数据格式，便利人工标注的同时也更容易利用程序做统计分析。
- 睡前消息的选题虽然具有较强的时效性，但许多往期优质内容依然值得新老观众回看，然而目前无法简单地通过视频标题找到自己想看的内容，本数据库可以一定程度填补这方面的空白。

## 文档说明

> 本数据库的建立非一人之功，欢迎更多感兴趣的朋友参与维护。

文档维护不需要任何复杂的技术背景，只需注册Github账号的同时了解Git的基本工作流程，无需任何命令行工具，只借助浏览器即可完成。

文档数据保存在data目录下的bndb.csv中，按照如下格式组织。
- 期数：当前内容所在的期数。
- 编号：当前内容所在期数内的编号。
- 关联：与当前内容相关的往期内容期数，通常在节目中指出，格式为“期数-编号”，例如：233-3。
- 类型：当前内容所属的类型，默认为新闻评述可不填，其他大致分为：简讯，花絮，彩蛋，影评，荐书，访谈，幕后等。
- 主讲：当前内容的主讲人或参演，默认为督工可不填。
- 内容：当前内容的索引概括，要求用语简明扼要，只描述客观事实的同时尽量突出重点，例如：分析三明市医改经验。
- 国家：当前内容的相关国家或事件发生的所在国家，国际事件或与地区弱相关的内容无需标注。
- 省级：当前内容所关联的一级行政区划，目前仅针对中国内容。
- 市级：当前内容所关联的二级行政区划，直辖市和特区暂按省级名称标注，台湾省暂不标注，目前仅针对中国内容。
- 标签：对当前内容的关键词索引，以客观描述为主，例如：企业经营 半导体 反垄断。
- 观点：对当前内容提出的主观观点，例如：社会化抚养。
> 以上每项之间用英文输入法逗号分隔；项内不要使用英文输入法的逗号或引号，可使用中文输入法符号代替；每一项均可为空，但不能省略逗号。

## 感谢

非常感谢[有多大仇](https://space.bilibili.com/134056531)朋友的帮助，他是原石墨文档的创建者与维护者，本数据库的建立离不开他和许多朋友无私的帮助。