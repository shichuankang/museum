# 智能博物馆
| 发布日期 | 2019.11.8    |
| -------- | ------------ |
| 产品名称 | 智能博物馆   |
| 文档状态 | 完成         |
| 文件主人 | 施传康       |
| 设计者   | 施传康       |
| 开发者   | 施传康       |

## 目录
- [产品定位](#产品定位)
- [用户痛点分析](#用户痛点分析)
- [产品解决方案](#产品解决方案)
- [应用场景](#应用场景)
- [主要功能](#主要功能)
- [用到的API工具](#用到的API工具)
- [目标市场](#目标市场)
- [市场需求](#市场需求)
- [产生的效益](#产生的效益)
### 产品定位
兼具导航，讲解，参展路线推荐的智能软件
### 用户痛点分析
* 博物馆工作人员有限，不能即使的为每一个游览者提供有效的服务，服务的缺失影响了游客的体验，也影响了游客享受博物馆的社会教育功能。很多时候，游客会在博物馆迷路，同时也不能得到有效的知识讲解。
* 博物馆场地复杂，展品繁多，如果用户想将全部展品游览且消化是一件很难得事情。没有目的的在博物馆逛可能会降低游客的游览效率，不能形成系统的知识学习。
* 展品静静的躺在展台等待着前来欣赏的人，但是很多来博物馆游览的游客并没有很高的文化修养，所以来博物馆也是她们进修的一个方式，但是博物馆的讲解一般以文字和讲解员为主，但是文字缺乏生动性，不能达到很强的教育效果；讲解员也水平参差不齐，同时博物馆资金限制，不能再每一个展区，每一个展品之前都有讲解员，因而很多希望来博物馆接受社会教育的人却不能得到有效的教育。
### 产品解决方案
* 让用户选择几个想要观览的展品，调用应用机器算法从而计算出用户的个人喜好，为推荐一条专属的游览路线。调用语音合成实现语音导航，可以为用户提供更好的游览服务，也更加的有趣，让用户在感兴趣的前提下去探索去学习。
* 调用百度图像识别API，用户将允许拍照的展品通过拍照上传，（如不能拍照的展品可以输入名字），系统分析图片，然后将得到的结果通过语音的方式为用户讲解，有趣的讲解将会更好的让用户对藏品知识的学习。
* 关注博物馆可以及时的得到博物馆的个人专属推送，让用户在即使不去博物馆也能在家得到博物馆的社会教育，随时随地的学习。
### 应用场景
* 当游客进入博物馆，能够通过小程序语音技术来充分了解馆内藏品知识，无需耗费过多解说人力。
* 通过机器翻译解决了各地域之间语言不通的问题。
* 通过知识图谱快速获取藏品信息，实现相关推荐和智能问答和智能提醒。
### 主要功能
* 通过语音查找想要参观的展品位置与信息：将用户的语音精准识别为文字（支持多语种与多方言识别），再通过语音合成将用户所查找的展品的位置与信息通过语音反馈给用户（提供多种发音人，语音语速可调节）。
* 通过统计各展馆人数，智能推荐用户参观展馆：实时监测各展馆人数（高精度头肩检测算法，精确率90%以上），智能推荐用户去往人数较少的展馆参观。
* 通过上传展品的照片来获得展品的信息：在博物馆展品图库中搜索与用户上传图片相同及相近的展品，然后将得到的结果通过语音合成反馈给用户。
### 用到的API工具
* 语音识别：将60s以内的语音精准识别为文字。
* 语音合成：提供高度拟人，流畅自然的语音合成服务。
* 人流量统计：统计人体个数和人流趋势，以头肩为主要识别目标统计人数。
* 图片搜索：在自建图库中搜索相同及相似的商品图片集。
### 目标市场
主要针对那些比较老旧的博物馆或者是还没有进行智慧化的博物馆帮助他们用最快的方式和相对较低的价格转型升级。
### 市场需求
在大多数二三线或者是四线城市的博物馆都是比较老旧且设施不齐全的，所以这些博物馆是需要一些较为廉价和适应性较强的项目产品对其进行转型升级来满足当地对博物馆的教育需求。
### 产生的效益
* 降低人工成本（减少所需的人力物力）
* 节省人员培训时间（讲解员需培训后才能上岗，而该软件则无需培训）
* 可提供专属的定制化游览路线，带给用户更好的观览体验
* 提高博物馆的服务水平，更好的发挥博物馆的社会教育功能
* 博物馆可以容纳的观览人数增加，同时可以吸引更多游客前来


