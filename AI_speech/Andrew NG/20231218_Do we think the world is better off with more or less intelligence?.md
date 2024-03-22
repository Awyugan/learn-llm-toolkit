# Do we think the world is better off with more or less intelligence?

中文稿🇨🇳：[吴恩达：“我们认为世界的智慧是越多越好还是越少越好？”](https://mp.weixin.qq.com/s/-KcuXdUMhx0nSn-mjryabg)
英文稿[Do we think the world is better off with more or less intelligence?](https://www.ft.com/content/2dc07f9e-d2a9-4d98-b746-b051f9352be3)

在《金融时报》记者Ryan McMorrow造访Andrew Ng位于硅谷帕洛阿托的办公室时，他拿出了一台没有联网的笔记本电脑，演示了一个来自法国人工智能初创公司Mistral的开源大模型。运行该模型可以不依赖云端。“模型就存储在我的硬盘上，通过笔记本上的GPU和CPU运行”Ng说。

当你向该模型提问“记者应该采访Andrew Ng哪些人工智能问题”时，它会提供关于Ng本人和他的工作背景信息，这和ChatGPT的回应相差无几。

RM：你在什么情况下会用这些开源模型？

AN：我的笔记本上运行着多个模型——包括Mistral、LLaMa和Zefa，我也经常用ChatGPT。但对于那些我不想上传云端的敏感信息，我更倾向于在笔记本电脑上使用它们。例如，涉及高度机密项目的构思，或者我要撰写的含敏感财务数据的文档，我会选择使用开源模型。事实上，开源模型现在的表现已经相当出色了。

RM：许多科技公司迫切需要Nvidia芯片来运行人工智能。如果你笔记本上的Mistral模型可以胜任任务，那么他们（科技公司）为什么还要费尽心思获取这些芯片呢？

AN：Mistral是一个规模较小的语言模型：它只有70亿参数，对于复杂推理任务来说，无法与GPT-4相提并论。但对于简单的构思和基础事实，Mistral已经足够了。你也看到了，它的响应速度有时非常快。

不过，在我笔记本上从零开始训练一个模型是根本不可能的——这需要数千万美元的成本、巨大计算量的训练、在非常大的模型上进行推理，这超出了我能在笔记本上完成的范畴。

实际上，我也尝试在笔记本上运行一个700亿参数的模型，但速度实在太慢了。如果你拿一个1750亿参数的模型（GPT-3规模）在我的笔记本上也是行不通的。大模型上的推理仍然需要数据中心级别的资源。现在开源软件已经变得足够简单，大多数人都可以轻松安装和使用。

我并不是沉迷监管问题——但如果一些监管者如愿以偿，那么这样的开源模型会更难持续更新。

RM：监管如何扰乱开源模型？

AN：比如一些提案要求LLMs拿到报告，甚至是许可证明。大型科技公司有能力处理这些复杂的合规要求，但小型企业则没有这个条件。

举个例子，当一个中等规模的公司想发布一个开源模型时，公司法律顾问会说：“如果你这样做，可能会有各种法律风险”。那么在这种情况下，我认为会有更少的公司愿意承担这种风险。无论是对什么加大监管，我们都会看到相关模型的减少。

一个开源模型是一种通用技术：它可以用于构建医疗应用、客户服务应用、金融服务应用等等。因此，如果你对开源模型这个核心技术进行监管，你实际上是在减慢所有事物的发展速度，而且可能并没有实质性地提高安全性。

RM：在讨论监管的框架时，必须了解人工智能目前的能力。今年6月，你和Hinton进行了一次对话，他曾警告过人工智能的危险。你们讨论了人工智能模型是否真正理解世界，当时你似乎不完全相信它们能做到。现在呢？你的看法是？

AN：我认为人工智能模型确实有这种能力。问题在于，像“理解”（understands）这样的术语，或者说“意识”（conscious）、“知觉”（sentient）没有明确的定义。因此，我们没有一个公认的标准来测试某事物何时真地理解了某物，而不是仅仅表现得像是理解了。

但根据我所看到的科学证据，人工智能模型确实在构建它们的世界观。所以，如果一个人工智能拥有了一个“世界模型”，我倾向于认为它理解了世界——这是基于我个人对“理解”（understands）一词的解释。

RM：你所说的“世界模型”是什么？

AN：如果你有一个“世界模型”，你就有了对世界运作方式的理解，而且可以预测，未来在不同情况下会作何发展。科学证据表明，经过大量数据训练的LLMs确实构建了一个世界模型。

研究人员让一个LLM模拟预测奥赛罗棋盘游戏的下一步走法——C4、D5、B3等等。之后，他们再探究“LLM是否学会了棋盘布局，是否学会了奥赛罗游戏的规则”。研究人员发现，神经网络内部似乎真的构建了一个可以预测下棋的棋盘模型。基于这个实验和其他类似实验，我相信LLMs确实构建了某种世界模型。我可以由衷地说，它们确实理解了世界。

RM：你认为LLMs有“意识”（conscious）吗？

AN：我可能会回避关于“意识”（conscious）的问题。因为对我而言，这更像是一个哲学问题而不是科学问题。哲学家说，我们假设别人是有意识的。我认为这是一种礼貌的说法。因为你怎么知道我有意识？也许我只是一个看起来有意识的僵尸。因此，我认为意识是无法测试的，这就是为什么它是哲学问题而不是科学问题的原因。

RM：撇开“意识”（conscious）不谈，你认为LLM能够“自行思考”吗？

AN：我不清楚“自行思考”这个词的确切含义。我倾向于是的，但由于缺乏对“思考” （think）的明确定义，这个说法很难站得住脚。换个说法，吸顶灯里的继电器开关能否“自行思考”？我倾向于认为它可以，但我认为很难用严谨的方式来为这一点辩护。

RM：LLMs是在什么时候能够“理解”（understands）的？

AN：“理解”是逐步实现的，不是一蹴而就。例如，随着LLMs的发展，我们有了GPT-2、GPT-3、ChatGPT，我觉得它们的理解水平不断提升——直到让我相当自信地说，LLMs在某种程度上，的确“理解”了这个世界。
2

有风险但概率小，AI灭绝论≈外星人灭绝论
RM：如果大家都认同LLMs具备“理解”（understands）能力，那么关于人工智能的争论似乎可以归结为像你这样的乐观主义者，比如更关注技术当前具备的能力。相对地，末日论者则更关注我们所见证的人工智能指数级进步对未来可能造成的影响。你认为末日论者的推论合理吗？

AN：我不同意这个描述，因为许多乐观主义者也在展望几十年后人工智能构建的美好世界。其实涉及“人工智能灭绝人类”话题时，和我交谈过的人们对此的担忧似乎非常模糊，而且没人能确切地讲出“人工智能将如何导致全人类灭亡”。

我无法证明人工智能不会导致人类灭亡，正如我也无法证明地球发出的无线电波会引来外星人并消灭人类一样。但我不会过度担心无线电波导致人类灭绝，就像我也看不到人工智能可能导致人类灭绝一样。

RM：然而，有一些德高望重的科学家认为人工智能导致灭绝的风险是存在的。我想问的是，作为人类，我们该如何确保人工智能的发展不会导致人类灭绝？

AN：无线电信号引来外星人并灭绝全人类的可能性确实非零，但这个几率如此之小，以至于我们不应该为了防范这种微乎其微的危险而浪费大量资源。我看到的是，我们正对几乎为零的风险，投入巨大到不成比例的资源。

RM：所以从监管的角度来看，我们需要哪些措施，如果有的话？

AN：我们需要好监管。例如，当我们用人工智能构建关键型应用程序时，确保它们本身安全，并保护消费者的监管是绝对必要的。但我看到的却是很多糟糕的监管，我们不需要更多这样的监管。

RM：简单来说，“好监管”和“坏监管”是什么？

AN：如果有人在构建医疗、金融核算或自动驾驶汽车的应用程序，我们希望它们是安全的，无偏见的。采取分层风险管理方法——思考应用软件的实际风险，并对可能出现的不良结果进行监管——这将是“好监管”。

但对我来说，像LLMs具有“系统性风险”的说法没有任何意义。比如，一些政府只声称LLMs存在更大风险，但是人们也可以用其他小型或大型的语言模型来构建具有潜在危险的医疗设备。同样，不论是小模型还是大模型，都可能会被用来散播虚假信息。

因此，模型的大小并不是衡量风险的有效标准。更合理的衡量方式应当是：应用程序的本质是什么？例如，医疗应用本身风险就更高。另一个衡量标准是应用程序的影响范围。如果是一个社交媒体平台拥有亿万用户，那么，它传播虚假信息的风险显然要比只有百名用户的小论坛高。因此，我们应该对大型科技公司实施更严格的监管。

这样的做法不是没有先例。例如，美国劳工部OSHA-工作安全与健康法规对大型雇主的要求就比对小型雇主的要求多，这种平衡了工人保护和小企业负担的做法值得借鉴。
3

Open AI们的“自愿承诺”形同虚设
RM：去年十月，白宫发布了旨在加强人工智能政府监管的行政令。这是否走得太远了？

AN：我认为我们可能走错了方向。如果我们能在宪法中确立——针对人工智能技术发展的限制到此为止，不会再进一步。我或许还能接受。但当前的情况是，各种政府部门被指派去想象出更多人工智能发展的障碍。我认为这将导致我们走上扼杀创新、建立极具反竞争性监管的道路。

RM：我们目前所了解的只有大纲，但不知道将接下来的具体实施？例如，如果公司开发任何可能对国家安全构成风险的基础模型，应通知联邦政府，且必须共享所有红队安全测试结果。我们不知道上述基础模型、共享信息的具体界定标准。

AN：现在很多游说者忙着给政府塑造立场。白宫的行政令最初设定的强制通知门槛是计算所需，我认为这是衡量模型风险的非常简单化的方法。（适道注：行政令要求——如果新的人工智能模型计算量超过一定阈值，开发该模型的公司要在训练系统时通知联邦政府。）

我们知道，今天的超级计算机可能就是明天的智能手表。随着初创公司规模扩大，更多的计算资源变得普遍可用，我们将看到越来越多的组织会触及这个门槛。将计算资源设为门槛，就像说一个用超过50瓦电的设备比用10瓦的设备具有更大系统性危险一样：虽然这可能是真的，但这是一个非常简单粗暴的风险衡量方式。

RM：如果我们不以计算量作为门槛，那么更好的风险衡量方式是什么？

AN：当我们观察应用程序时，我们可以理解到底什么意味着安全，什么意味着危险，并据此进行适当的监管。因为技术的用途广泛，如果对技术层面进行监管，只会减缓技术进步的速度。

最根本的问题是：我们是否认为世界会因为“智慧”增加而变得更好？“智慧”包括“人类智慧”和“人工智能”。

毫无疑问，“智慧”可以被用于不良用途。但经过多个世纪的发展，随着人类更聪明和教育普及化增加，社会得以进步。我相信，世界如果拥有更多的“智慧”，无论是人类的还是人工的，都将帮助我们更好地解决问题。因此，仅仅因为“智慧”可能被用于某些不良目的，就设置监管障碍，我认为这会让社会倒退。

RM：我们如何保障不将“智慧”用于不良用途？

AN：当然应该识别“智慧”的不良用途，并对其进行防范。如果我们思考人工智能灭绝主义的观点，会发现其描述的场景是如此模糊和夸张，我认为这并不现实，也很难防范。

但现实中确实存在一些风险，例如我们不希望保险核算应用带有偏见，那么就可以制定审计保险核算应用的规则，并且评估应用的公平性——这会是一个积极的变化。至于那些会影响大量用户的社交媒体或聊天机器人公司，则存在虚假信息或偏见的风险。此时，我认为，透明度就是有意义的。

总而言之，如果我们对影响巨大、风险更高的企业实施监管，我们就不应该同时也阻碍小型初创企业的发展，这会剥夺它们成长为大型企业的机会。

RM：人工智能生成的假视频等内容可能会激增，政府该管吗？

AN：这是一个棘手的问题。我认为加水印可能是一个好主意。今年7月，包括Google、Meta和OpenAI在内的公司向白宫承诺，在开发人工智能时遵守三个基本原则：安全、保障和信任。但如果你仔细阅读这些承诺，我认为除了“加水印”之外，其他都是空话。因为公司完全可以阳奉阴违。

为了防范通过视频或文本——尤其是文本——大规模散播虚假信息的风险，我认为加水印是真正应该考虑的措施。很不幸，自从上述的白宫承诺以来，我看到一些公司在给文本内容加水印上反而倒退了。所以，我觉得将自愿承诺作为一种监管手段是失败的。

4

糟糕的监管不如没有监管
RM：我们或许能感受到，呼吁更严格监管的声音更响亮。那么，你能否感到自己的立场是孤单的？

AN：其实，我非常希望政府能积极出击，制定出一些好规则，而不是我们现在所看到的不良监管提案。所以，我不主张放任不管。但在糟糕的监管和没有监管之间，我宁愿没有监管。然而，一些包括巨头科技公司在内的强大势力过分夸大人工智能的风险。诚然，大公司更想避开和开源人工智能的竞争。他们的策略往往是夸大恐惧，然后实施规则来延缓创新，放慢开源的步伐。

我的笔记本电脑上所展现的，证明了开源软件和一些专有模型的竞争非常激烈——尽管它们可能不是最优秀的，但比一些早期版本已经很不错了。而对于一些公司来说，如果没有开源软件的竞争，那将会畅通无阻。

RM：你能指出一些在推动人工智能威胁论述的公司吗？

AN：你知道他们都有谁。多家公司都在强调威胁论述。对于那些更愿意避免和开源竞争的大型企业来说，这是一种动力；对于一些非营利组织来说，夸大恐惧，制造幻象，然后筹集资金来对抗他们自己制造的幻象，这也是振奋人心的；一些个人可以夸大恐惧得到更多关注和更高演讲费。不过，我认为有一些人是真诚的——他们可能误入歧途，但确实是真诚的——但在这之上，存在为了某些利益而夸大恐惧的动机。

我不认为我是唯一这么想的人。Bill Gurley（Benchmark的合伙人）对监管捕获的思考非常深刻。他在YouTube的一次演讲非常精彩，准确地预测了现在正在发生的许多监管捕获行动。Yann LeCun也在这个问题上发表了看法。我认为实际上有很多人对此有非常深思熟虑的看法。（适道：监管捕获——监管者 被 监管对象用各种方法“捕获”，沦为少数利益集团的工具人。）

RM：只是似乎另一方声音更响亮。

AN：坦白说，你们是媒体，所以你们可以扩大声音。血腥的头条总是更受欢迎，恐惧也是一样。当很多人签署声明，称人工智能像核武器一样危险时，媒体就会给予了大量关注。而当更理性的声明出现时——例如，Mozilla表示开源是确保人工智能安全的好方法——几乎没有媒体报道。

我认为人工智能安全中心（CAIS）的措施非常差劲。因为很多监管者不理解人工智能，当那个将人工智能和核武器相提并论的声明，将误导信息非常清楚地传播开来，就扭曲了监管者的思考。我已经看到了该声明对美国政府的影响。然而，将人工智能类比为核武器非常荒谬。人工智能可以帮助我们做出更好的决策；而核武器却能摧毁城市。这二者能有什么关联？

如今，更多国家已经意识到了监管捕获的风险，因为当前许多生成式人工智能的顶尖人才都集中在美国。如果出台的规则阻碍了开源模型的传播，猜猜谁会落后？几乎是所有除了美国之外的国家。

当然美国的一部分力量也希望看到这种局面，因为他们认为美国的竞争对手通过开源软件获得了好处。没有人希望看到人工智能被用于不义之战，但减缓全球创新的进程、让全世界的智慧和决策质量下降的代价太高。

我希望欧洲的监管者也能意识到这一点。坦白说，如果我们放慢了开源的步伐，那么谁将被遗弃在后面？
5

软件层面，各国同等受限
RM：在阅读李开复的《人工智能超级大国（AI Superpowers）》（2018）一书后，我曾确信中国将引领人工智能发展的浪潮。但这似乎并没有发生。你认为原因何在？

AN：李开复论述了中国的数据获取优势，但数据是非常垂直化的东西。例如，Google有大量网络搜索数据，但这些数据对物流、智能手机制造或药物研发不产生直接作用。

不同国家在不同垂直行业拥有的数据可以创造各自的优势。中国在监控技术方面暂时领先美国，这是得益于中国数字支付的兴起。但我认为，美国在其强势领域拥有大量数据并持有优势，比如网络搜索、药物研发、制药等行业。

技术发展是阶段性的，中国只是错过了生成式人工智能浪潮的起点。许多早期，甚至现在的生成式人工智能工作是由两个团队完成的：我的前团队Google Brain和OpenAI，二者都在硅谷。有时这些团队成员离开后会另起炉灶，这就是如今生成式人工智能人才在硅谷云集的原因。尽管英国、加拿大、中国也有人才聚集，但实际上集中度远不如硅谷。即便是西雅图、纽约，也比不上硅谷。

RM：中国对人工智能的监管态度相当激进——任何公司想要公开发布LLM都必须获得批准，且当局要审查其训练使用的数据集。你认为这会扼杀创新吗？

AN：我不是这方面的专家。我认为在很大程度上，规定具体如何让实施会影响其是否会扼杀创新。

RM：最近，腾讯和阿里巴巴都在表达他们因缺少Nvidia 芯片而在人工智能发展上受限。你如何看待美国的做法？

AN：美国对芯片的出口控制无疑对中国的人工智能发展产生了实质性影响。但我注意到中国在没有先进Nvidia 和AMD芯片的情况下，用低功耗芯片在LLMs推理上做了大量创新。至少现在，出口管制还存在足够多的漏洞，我认为中国公司也在尝试寻找海外计算资源。未来一切如何发展还有待观察。

RM：你认为美国应该这样做吗——基本上是试图削弱中国的人工智能产业？

AN：我对这个问题的情感有些复杂，我不是地缘政治专家。不过显而易见，美国正试图监管基础模型——有一个派系影响了白宫的行政令，因为他们担心美国的对手会利用开源软件。所以，在软件层面，我认为美国自己受到的限制和其他国家一样多，这是一个错误。至于硬件，我了解得不多。

RM：听起来，你认为中国的企业可以找到方法绕过芯片限制。

AN：是的，我已经见到很多创新，尽管有芯片限制，也能够完成工作。

## 英文

Ryan McMorrow DECEMBER 19 2023


Just over a decade ago, Andrew Ng was part of a Google Brain project that showed the power of deep learning technology.

For three days, Ng’s team fed a neural network millions of unlabelled images from YouTube videos. After training, the system could identify features such as cats in images it had not encountered before — even though it had not been explicitly taught how. This research became known informally as the “Cat Paper” and laid the groundwork for future advances in artificial intelligence. 

At around the same time, from his perch as a Stanford professor, Ng pushed into online teaching, making a course on machine learning available to anyone with an internet connection. Its popularity, along with that of other “massive open online courses”, or Moocs, at the time, led Ng and his colleague Daphne Koller to found online education provider Coursera. 

A few years later Ng moved to Baidu, the Chinese search giant, to help deepen its autonomous driving and AI research efforts. Today he invests in and builds an array of AI start-ups, runs one of his own, and continues to teach courses on AI. 

When the FT visited Ng’s Palo Alto offices, he pulled out a laptop and turned off its WiFi to demonstrate how an open-source large language model (LLM) from French AI start-up Mistral can run without needing to send data to the cloud. 

Tech Exchange 

The FT’s top reporters and commentators hold monthly conversations with the world’s most thought-provoking technology leaders, innovators and academics, to discuss the future of the digital world and the role of Big Tech companies in shaping it. The dialogues are in-depth and detailed, focusing on the way technology groups, consumers and authorities will interact to solve global problems and provide new services. Read them all here

“The model is saved on my hard disc and then it’s using the GPU and CPU [graphics processing unit and central processing unit] on my laptop to just run inference,” he said. When it was given the question of what a reporter should ask Andrew Ng about AI, the background it delivered on Ng and his work looked like the kind of response one would get from ChatGPT, OpenAI’s hit LLM-powered chatbot.  

An advocate of open-source AI development, Ng has emerged as an outspoken critic of some government efforts to regulate it. Here he speaks about AI’s current capabilities, why warnings of extinction risk are overblown, and what good regulation would look like.

Ryan McMorrow: When do you use these open-source AI models? 

Andrew Ng: I run multiple models on my laptop — Mistral, Llama, Zefa. And I use ChatGPT quite often. But for privacy-sensitive things that I don’t want to send to a cloud provider, I would tend to use them all on my laptop. Like brainstorming on really confidential projects, or helping me with writing that contains sensitive financial figures. Open-source language models are actually getting pretty good.

RM: Yet many tech companies are desperate for Nvidia’s chips to run AI. Why should they bother if the Mistral model on your laptop can handle it?

AN: This is a smaller language model: it’s only 7bn parameters, and not competitive with GPT-4 for sophisticated reasoning tasks. GPT-4 is much better at answering complex questions. But for simple brainstorming, simple facts, this is fine. And it’s sometimes pretty fast as well, as you see.


Hot chip: sales of Nvidia’s processors have soared, as big tech companies favour them for developing AI systems © I-Hwa Cheng/Bloomberg
Training a model from scratch, though, is completely unfeasible on my laptop — that still needs tens of millions of dollars. Training that uses the massive amount of compute and inference [problem solving with fresh data] on the very large models would be beyond what I could do on my laptop.

Actually, I have done inference on a 70bn parameter model on my laptop and it is annoyingly slow. And so if you have a 175bn-parameter model, which is the size of GPT-3, that would not be something I could do on my laptop. Inference on the large models still needs data centre-level resources. 

An open-source model can get used to build many kinds of app. If you regulate that core technology, you’re slowing everything down, and probably without making anything safer

Open-source software’s getting easy enough for most people to just install it and use it now. And it’s not that I’m obsessed about regulation — but if some of the regulators have their way, it’d be much harder to let open-source models like this keep up.

RM: How would regulations disrupt open-source?

AN: Some proposals, for instance, have reporting or even licensing requirements for LLMs. And while the big tech companies have the bandwidth to deal with complex compliance, smaller businesses just don’t.

Just as an example, I’m picturing a midsize company that wants to release an open-source model. If a lawyer in that company starts saying, “Hey, just so you know, there could be all sorts of liability if you do this,” then I think fewer companies would take that liability risk. Whatever we put more regulatory burdens on, that’s what we’ll see less of.

An open-source model is a general purpose technology: it can get used to build a healthcare app, a customer service app, a financial services app, and on and on. So if you regulate that core technology, you’re slowing everything down, and probably without making anything meaningfully safer.

RM: Framing any discussion of regulation has to be a sense of what AI is capable of — of where AI stands today. And in June you had a conversation with Geoffrey Hinton [a computer scientist who has warned of the dangers of AI] about whether AI models understand the world and it seemed like you were not fully convinced that they do. What’s your current view?

AN: I think they do. One of the problems with terms like “understands” or, going even further, “conscious” or “sentient”, is that they are not well defined. So there’s no widely accepted test for when something understands something, as opposed to merely looks like it understands something. 

But from the scientific evidence I’ve seen, AI models do build models of the world. And so if an AI has a model of the world, then I’m inclined to believe it does understand the world. But that’s applying my own sense of what the word “understanding” means. 

RM: What do you mean by a model of the world?

AN: If you have a world model, then you have a sense of how the world works and can make predictions about how it may evolve under different scenarios. And there’s been scientific evidence showing that LLMs, when trained on a lot of data, do build a world model. 

What the researchers did was basically to take an LLM and train it to model moves in the board game Othello — C4, D5, B3, whatever. And then, after Othello-GPT, as they called it, had learned to predict the next move, they asked, “Has this system learned a model of the board, and has it learned a model of the rules of the game of Othello?”. And when they probed it, the insides of the neural network appeared to have built a model of the board in order to predict the next moves. Because of that experiment, and others like it, I believe LLMs are building, internally, some model of the world, and so I feel comfortable saying they do understand the world.


Learn the rules, grasp the world: researchers who trained a large language model to predict moves in Othello found that it had built a (digital) model of the board to do so © Alamy
RM: Do you think they have consciousness as well?

AN: I might skirt the consciousness question, because it feels to me like a philosophical question rather than a scientific one. I think philosophers say that, as people, out of politeness, we all assume other people are conscious — but how do you know if I am conscious? Maybe I’m just a zombie, and I just act like a conscious being. So I think there’s no test for consciousness, which is why it’s a philosophical rather than a scientific problem.

RM: Leaving aside consciousness, do you think an LLM can think for itself?

AN: I don’t know what that phrase means. I’m inclined to say yes, but, because of the lack of a clear definition of what it means to think, it’s hard to say. Can a relay switch in my ceiling lamp think for itself? There is a whole spectrum [that includes] this kind of relay switch thinking for itself . . . I’d be inclined to say it does, but I think I’d have a hard time defending that in a rigorous way.

RM: When did LLMs get to the point of understanding?

AN: Understanding comes in gradual degrees. I don’t think it’s a binary criterion. But as LLMs grew, and we had GPT-2, GPT3, ChatGPT, I feel like they were demonstrating increasing levels of understanding — to the point where I feel quite comfortable saying that, to some extent, LLMs understand the world today. 

RM: If it’s agreed that LLMs have the capacity to understand, the debate on AI seems to come down to optimists like yourself, who focus on what the technology is currently capable of, and doomers, who focus on projecting what the exponential advances we’re seeing will mean for the future. Do you think there’s any reason to extrapolate like they do? 

AN: I don’t agree with that characterisation. A lot of the AI optimists are looking decades into the future at the amazing things we can build with AI. When I think about the AI human extinction scenarios, when I speak with people who say they’re concerned about this, their concerns seem very vague. And no one seems to be able to articulate exactly how AI could kill us all.

We are spending vastly disproportionate resources against a risk that is almost zero

I can’t prove that AI won’t kill us all, which is akin to proving a negative, any more than I can prove that radio waves being emitted from Earth won’t allow aliens to find us and wipe us out. But I am not overly concerned about our radio waves leading to our extinction, and in a similar way I don’t see how AI could lead to human extinction.

RM: Yet there are well-regarded scientists who think there is some chance of that. I guess the question is: how should we as humans make sure that AI’s development doesn’t lead to our extinction?

AN: There is also some chance that is absolutely non-zero of our radio signals causing aliens to find us and wipe us all out. But the chance is so small that we should not waste disproportionate resources to defend against that danger. And what I’m seeing is that we are spending vastly disproportionate resources against a risk that is almost zero.

RM: So in terms of regulation, what, if any, do we need?

AN: We need good regulation. When we use AI to build critical applications, regulations to ensure that they’re safe and protect consumers is absolutely needed. But what I’m seeing is a lot of bad AI regulation, and we don’t need more of that.


Things not to come: Ng argues that worries about AI posing an extinction risk are overblown — on a par with fears that radio waves from Earth could attract hostile extraterrestrials © Alamy
RM: What is good and bad regulation in a nutshell?

AN: If someone is building a healthcare or underwriting or self-driving car application, we want it to be safe and unbiased. Taking a tiered risk approach — thinking through what are the actual risks with applications and regulating against the bad outcome — would be good regulation.

But there is this phrase going around that LLMs represent a systemic risk, and that makes no sense to me. Some governments are just asserting that LLMs represent a bigger risk, but people can build dangerous medical devices with a small language model or with a large language model. And people can build systems for misinformation with a small or large language model. So the size of the language model is a very weak measure for risk. 

A better measure would be: what is the nature of the application? Because healthcare applications will be more risky, for example. Another metric would be the reach of the application. If a social media company has 100mn users, the risk of disinformation is much bigger than a message board with just 100 users. And consequently we would regulate big tech companies more. 

This is a common practice. For example, the US’s Osha [Occupational Safety and Health Administration] laws put more requirements on big employers than on small employers. That balances protecting workers with not overly burdening small businesses.   

RM: In October, the White House issued an executive order intended to increase government oversight of AI. Has it gone too far?

AN: I think that we’ve taken a dangerous step. If we were to enshrine in the constitution that barriers to AI technology development will stop here and go no further, maybe it’s OK. But with various government agencies tasked with dreaming up additional hurdles for AI development, I think we’re on the path to stifling innovation and putting in place very anti-competitive regulations. 

RM: From what we have so far, it’s a broad outline — do we know how they’re going to implement it? For example, companies developing foundation models considered a risk to national security must notify the government and share the results of safety tests. Do we know what counts as a foundation model and how people are supposed to share information? 

AN: At this moment there are certainly lots of lobbyists who are very busy helping the government shape its perspective. The White House EO took its initial cut [on the threshold for mandatory notification] as the amount of computation needed, which I think is a very naive way to measure the risk of a model.

Having more intelligence in the world, be it human or artificial, will help all of us better solve problems

We know that today’s supercomputer is tomorrow’s smartwatch, so as start-ups scale and as more compute becomes pervasive, we’ll see more and more organisations run up against this threshold. Setting a compute threshold makes as much sense to me as saying that a device that uses more than 50 Watts is systematically more dangerous than a device that uses only 10W: while it may be true, it is a very naive way to measure risk.

RM: What would be a better way to measure risk? If we’re not using compute as the threshold?

AN: When we look at applications, we can understand what it means for something to be safe or dangerous and can regulate it properly there. The problem with regulating the technology layer is that, because the technology is used for so many things, regulating it just slows down technological progress. 

At the heart of it is this question: do we think the world is better off with more or less intelligence? And it is true that intelligence now comprises both human intelligence and artificial intelligence. And it is absolutely true that intelligence can be used for nefarious purposes. But over many centuries, society has developed as humans have become better educated and smarter. I think that having more intelligence in the world, be it human or artificial, will help all of us better solve problems. So throwing up regulatory barriers against the rise of intelligence, just because it could be used for some nefarious purposes, I think would set back society.

RM: How do we safeguard against the possibility of using intelligence for nefarious purposes?

AN: I think we should absolutely identify the nefarious uses of intelligence and safeguard against them. If we look at AI extinctionism, its scenarios are so vague and fantastical that I don’t think they’re realistic. And they’re also hard to defend against. 

But there are realistic scenarios. We want underwriting software to be fair. Putting in place regulations to make sure that underwriting software is audited and measured for fairness — that would be a welcome change. And with social media or even chatbot companies that reach large numbers of users, and there is a risk of misinformation or bias, transparency makes sense to me. But if we regulate businesses that impact a lot of users and therefore carry more risk, we shouldn’t also slow down the small start-ups and deny them a shot at becoming bigger businesses that then should rightfully become more heavily scrutinised.

RM: What about the potential proliferation of fake videos and other content created by AI? Is that something for the government to regulate?

AN: That’s a tricky one. I think watermarking could be a good idea. There was a White House voluntary commitment to AI [in July, when companies including Google, Meta and OpenAI pledged not to compromise safety, security and public trust in developing the technology]. And if you read those commitments carefully, I think all of them were fluff — meaning that companies could say they [were complying while] doing nothing differently from what they were already doing — except for one, which was the commitment to watermark generated content.

To guard against large-scale misinformation through videos or text — text is the important one to pay attention to — I think watermarking is something we should seriously consider. Unfortunately, since that White House voluntary commitment, I’ve seen companies step back from watermarking text content. So I feel that the voluntary commitment approach is failing as a regulatory approach.

RM: It seems like the voices urging tighter regulation are a lot louder and maybe more numerous than those arguing the opposite. Do you feel like you’re alone in pushing for the hands-off approach? 

AN: Actually I would love for governments to be hands on and to write good regulation, as opposed to the bad regulatory proposals we’re seeing, so I’m not advocating hands off. But between bad regulation and no regulation, I’d rather see no regulation.

Unfortunately, there are massive forces, including some very large companies, that I think are overhyping the risks of AI. Big companies would frankly rather not have to compete with open-source AI. And unfortunately the recipe is to hype up fears, and then try to put in place regulations to slow down innovation and slow down open-source.

Look at what we just did on my laptop: open-source software is surprisingly competitive with some of the proprietary [models] — not with the best, but with some of the earlier versions. And it’d be very convenient for some companies not to have to compete with this.

RM: Can you name some companies that are pushing this AI threat narrative?

I see no reason to make an analogy between AI and nuclear weapons. It is an insane analogy

AN: You can imagine [who they are]. Multiple companies are overhyping the threat narrative. For large businesses that would rather not compete with open-source, there is an incentive. For some non-profits, there is an incentive to hype up fears, hype up phantoms, and then raise funding to fight the phantoms they themselves conjured. And there are also some individuals who are definitely commanding more attention and larger speaker fees because of fear that they are helping to hype up. I think there are a few people who are sincere — mistaken but sincere — but on top of that there are significant financial incentives for one or multiple parties to hype up fear.

I don’t think I’m alone in feeling this way. Bill Gurley [general partner at venture capital firm Benchmark] has been very thoughtful about regulatory capture. He gave a talk that’s on YouTube, a fantastic talk, he accurately predicted a lot of regulatory capture moves that are being played out now. [Computer scientist] Yann LeCun has been speaking about this as well. I think there are actually quite a few people with a very thoughtful perspective on this.

RM: It just seems like the other side is louder. 

AN: And frankly, you’re the media. So you can help. “If it bleeds, it leads”, and similarly for fear as well. When lots of people signed [the Center for AI Safety statement] saying AI is dangerous like nuclear weapons, the media covered that. When there have been much more sensible statements — for example, Mozilla saying that open source is a great way to ensure AI safety — almost none of the media cover that.  


West is best: tech investor Bill Gurley has said that Silicon Valley’s success in innovation owes a lot to its being so far from regulators in Washington, DC © David Paul Morris/Bloomberg
I think that Cais move was one of the most unfortunate things, because a lot of regulators are confused about AI. The statement that when you think about AI, you should think about nuclear weapons — that message, that misleading message, came through loud and clear, and distorted the thinking among the regulators. I saw the impact it had in DC.

I see no reason to make an analogy between AI and nuclear weapons. It is an insane analogy. One brings more intelligence and helps make better decisions, and the other blows up cities. What have these two things to do with each other? 

The risk of regulatory capture is starting to dawn on more nations, because a lot of generative AI talent is concentrated in the US today and one of the best ways to make sure that cutting-edge technology is widely disseminated is open source. If regulations come up that hamper dissemination of open source, guess who will be left behind? Pretty much everyone other than the US.

There are forces in the US that would like to see that happen because of the perceived risk that the US’s adversaries are benefiting from open source. But while no one wants to see AI used to wage an unjust war, I think the price of slowing down global innovation, of letting there be less intelligence and poorer decision-making all around the world, is too high a price to pay. I hope the European regulators figure this out, too, because, frankly, who will be left behind if we slow down open source?

RM: After reading Kai-Fu Lee’s book AI Superpowers, which came out in 2018, I was convinced that China would be the one leading the way on AI development. But that doesn’t really seem to have happened. Why do you think that is? 

AN: Kai-Fu made an argument about China’s access to data. But data is very verticalised — data is not a single, featureless glob of things that you just want more of. For example, while Google has tons of web search data, that data by itself is not very useful for logistics, or smartphone manufacturing, or drug discovery.

And different countries will have data in different verticals that they can leverage to their own advantage. China is cyclically ahead of the US in its application of surveillance technology, and also because of the rise of digital payments in China. But I think that the US, in the industries where it is strong, has lots of its own data, and has assets to maintain its strengths — sectors like web search, drug discovery, pharmaceuticals. 

US export controls on semiconductor chips are definitely having a meaningful impact on China’s AI development

Technology comes in bursts. China just missed the beginnings of the generative AI wave. A lot of the early generative AI work — and even now, frankly — was done by two teams: Google Brain, my former team, and OpenAI, which both happened to be here in Silicon Valley. And sometimes people leave these teams and start other companies, which is why at this moment I see a very heavy concentration of deep tech talent in generative AI in Silicon Valley and nowhere else. There are pockets of talent, in the UK, in Canada, in China, but it’s actually very concentrated just in Silicon Valley. Even Seattle, say, and New York have much less generative AI talent than Silicon Valley.

RM: Beijing has been taking a pretty aggressive approach with regulating AI. Any LLM that a company wants to release to the public has to be approved, and the authorities want to look at what data sets it has been trained on. Do you think that’s going to stifle innovation? 

AN: I’m not an expert on this. I think the implementation of these regulations will have a big impact on how much they are or are not stifling. 

RM: Recently, Tencent and Alibaba have been talking about their lack of access to Nvidia chips as a possible constraint on their development of AI. What do you think about the US’s approach?

AN: US export controls on semiconductor chips are definitely having a meaningful impact on China’s AI development. I’m seeing a lot of innovation in China on getting things done without access to the advanced Nvidia and AMD chips — innovation on how to do inference on LLMs using lower power chips. And at least right now, the export controls have enough loopholes that I think companies in China are sometimes trying to find their compute overseas. So how it all shakes out remains to be seen. 

RM: Do you think the US should be doing this — essentially trying to hobble their industry?

AN: I have very mixed feelings about it, but I’m not an expert in geopolitics. But one thing that is clear is that the US is trying to regulate foundation models — there is definitely a faction in Washington, DC, that is influencing things like the White House executive order because of fears about the US’s adversaries getting access to open-source software.

For the software layer, I think the US is hobbling itself as much as anyone else. And that’s a mistake. The hardware I’m less of an expert on.

RM: It sounds like you think that Chinese companies can find ways around these chip constraints.

AN: I’ve seen a lot of innovation to get things done despite the chip constraints, right. 
