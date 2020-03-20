# duitasiwei
一款完全免费的效率工具，提供网页信息标注、pdf信息标注、思维导图整理、卡片记忆等功能，能够高效利用日常阅读笔记数据，有序的构建知识和想法，完善个人的知识体系。
经过2个多月的抗疫居家生活，过了一个长、长、长的假期，两个老程序员除了烹饪能力有所增长之外，也没有闲着，一直在收集1.0的版本的需求问题，准备产品的更新工作，和我们的产品名称一样，我们也在一点一点的进步。在一点一点的去满足用户的需求，即使我们慢的像蜗牛，也要拖着自己产品义无反顾的前进。废话就不多说了，产品更新具体内容如下：
1、给产品穿了一件外衣，我们叫它主页，使产品不再光溜溜的，面对用户的时候不那么害羞了，之前裸露的有点过分。现在的主界面是长这样的。

2、实验性的引入了分词工具，在首页做了一个词云，还不是很准确，也没有丰富词库，具体效果，有啥作用，只能运行一段时间，由用户说了算，以后还会改进。
        具体说明几点：
 词云主要是抽取笔记内容的关键字，每条笔记抽取5个权重比较高的关键词，并没有对词性做处理，一并加入到统计库中；
默认在关键词不足100个的情况下，主界面词云加载默认词云；
词云数据是延迟加载的，也就是你启动应用后，程序抽取你的笔记数据，放到词云表中，抽取完成后，在你下次打开界面后，就会加载最新数据的词云了。也就是说需要2次启动，而且需要给程序时间处理数据；
在关键词云的基础上，也加入了各笔记库标签词云的功能，如果没有标签，也会显示默认的三句话，其中一句（零散的知识终于可以归队了）感谢用户delacula提供。
再补充一点，词云分词使用的是jieba分词，词库可以自己维护，有感兴趣需要自己维护词库的用户，可以加我们的qq群，我们告诉你怎么手动修改词库，当然，也可以到github上找结巴分词的库，看看教程，很简单，后续我们会推出专门的分词工具，让那么好的分词技术更贴近用户。
3、 修改了一下默认的界面颜色，还是不满意，苦于没有设计师mm与gg的支持，凭我们这40岁的老程序员，只能先这样了，后续会考虑把界面主题抽取出来，能够用户自配置。（之前有好心的用户诟病我们的界面黑不溜秋的，不好看，说实话，如果换个颜色，我们能驾驭的就只有屎黄色了。）
4、 添加了笔记的概要情况统计功能，力求让每个用户都清楚的知道自己的笔记积累情况。后续也许会推出专题的笔记积累情况分析，时间更长，内容更丰富，我们中一个老程序员就是执着的喜欢所见即所得，钱摆在哪数才叫过瘾。
5、清理了一下脑图的无用代码，也许效率会高一点，谁知道那，每个版本升级都会做这个工作，同时添加了一些脑图的使用提示。这里做一下说明：
实际上这个软件里的思维导图，并不完全算是思维导图工具，不能快速的支持思维的爆炸式输出，只能算作树形笔记，它其实刻意的把每个环节放得慢一些，力求增加用户在整理主题知识时的思考投入，我们做的就是把与思考无关的素材收集帮你做好。
思维导图是一个老程序从业20年一直用的一个工具，它是一个人思维可视化的支撑工具，无所谓结果如何，其目的是梳理自己的无序思维，让自己的思路更清晰、更全面。是你面对问题，毫无头绪时最佳工具，你说拿来用它背单词，个人认为纯属扯淡。用它拿来做方案提纲，还是非常靠谱的，分析老美的风土人情也是可以的。
6、 添加了脑图节点如果是web标记或pdf标记的内容，提供了跳回原文的功能。这样你在梳理主题知识的时候，需要查看节点内容摘抄出处的上下文关系就非常的方便了，当然，前提是你的原文一直都在。
7、修改了pdf笔记与web笔记分页时的bug，修改了pdf标注时截图框选的bug。
8、增加了最近打开功能，使用户能够快速的进入工具。
9、 增加了一个加油打Call的功能，给用户创造了一个帮助我们的机会。搞推广这事，两个老程序员真有点力不从心啊（我们连up主是啥，之前都不知道）。这里补充说明一下：
你为我们加油打call的次数，我们完全不知道，数据也是存在你本地的，也许有一天你删除了你的笔记数据，然后又重新使用了我们的产品，那这部分数据归零。核心意思就是你不帮我们我也不知道。
如果觉得我们是在用心做一款产品，体验到了我们的情怀，想帮我们加油，那么最好是转发、转发、转发。
10、还是增加一点说明吧，凑个整数，web笔记数据，实际上在你的机器中是存储两份的。一份在浏览器中存储，一份在我们的程序中存储，浏览器那份是你会看标注历史使用的，如果你们觉得浪费资源，随时可以清除掉。
11、还得写一条，我们发布了edge浏览器的web标注插件，首页界面也做了引导，用户可以直接到商店中安装，做这个引导没别的意思，免于用户安装插件时极差的操作体验，再不需要搬梯子、搬凳子了，当然我个人还是用Chrome的，因为我是程序员。程序员跳坑必须得有梯子。
