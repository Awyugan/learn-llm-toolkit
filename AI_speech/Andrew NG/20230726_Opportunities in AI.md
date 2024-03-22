# Opportunities in AI - 2023 吴恩达：人工智能的机遇 - 2023

> This discussion took place on July 26, 2023, at Cemex Auditorium, Stanford University, and was hosted by the Stanford Graduate School of Business.

> 此次讨论于 2023 年 7 月 26 日在斯坦福大学 Cemex 礼堂举行，由斯坦福商学院主办。 

## 正文

What I want to do today is chat to you about some opportunities in AI.  
所以，我今天想做的就是和你聊天关于人工智能的一些机会。

So I've been saying AI is a new electricity.  
所以我一直在说人工智能是一种新电力。

One of the difficult things to understand about AI is that it is a general purpose technology, meaning that it's not useful only for one thing but it's useful for lots of different applications, kind of like electricity.  
理解人工智能最困难的事情之一是它是一类通用技术，意味着它不仅仅用于一件事，而是对许多不同的应用都有用，有点像电力。

If I were to ask you, what is electricity good for? It's not any one thing, it's a lot of things.  
如果我问你，电有什么用？这不是任何一件事，而是很多事情。

So what I'd like to do is start off sharing with you how I view the technology landscape, and this will lead into the set of opportunities.  
所以我想做的是开始与大家分享我如何看待技术前景，这将带来一系列的机会。

There's a lot of hype, a lot of excitement about AI. And I think, a good way to think about AI is as a collection of tools.  
关于人工智能有很多炒作、很多兴奋。我认为，这是思考人工智能的好方法，将其视为一系列工具的集合。

This includes, a technique called supervised learning, which is very good at recognizing things or labeling things, and generative AI, which is a relatively new, exciting development.  
这包括一种称为监督学习的技术，非常擅长识别事物或标记事物，以及生成人工智能，这是一个相对较新的、令人兴奋的发展。

If you're familiar with AI, you may have heard of other tools. But I'm going to talk less about these additional tools, and I'll focus today on what I think are, currently, the two most important tools, which are supervised learning and generative AI.  
如果您熟悉人工智能，您可能听说过其他工具。但我将少谈这些额外的工具，今天我将重点关注我认为目前两个最重要的工具，监督学习和生成人工智能。

So supervised learning is very good at labeling things or very good at computing input to outputs or A to B mappings, given an input A, give me an output.  
所以监督学习非常擅长标记事物，或者非常擅长计算输入到输出或A到B的映射，给定一个输入A，给我一个输出。

For example, given an email, we can use supervised learning to label it as spam or not spam.  
例如，给定一个电子邮件，我们可以使用监督学习将其标记为垃圾邮件或非垃圾邮件。

The most lucrative application of this that I've ever worked on is probably online advertising, where given an ad, we can label if a user is likely to click on it, and therefore show more relevant ads.  
我所从事过的最赚钱的应用可能是在线广告，如果给定广告，我们可以标记用户是否可能会点击它，因此显示更多相关的广告。

For self-driving cars, given the sensor readings of a car, we can label it with where are the other cars.  
对于自动驾驶汽车，给定汽车的传感器读数，我们可以用标记它，其他汽车在哪里。

One project that my team, AI Fund, worked on was ship route optimization.  
我的团队 AI Fund 从事的一个项目是船舶航线优化。

Where given a route the ship is taking or considering taking, we can label that with how much fuel we think this will consume, and use this to make ships more fuel efficient.  
在给定航线的情况下，船舶正在采取或考虑采取，我们可以用多少燃料来标记，我们认为这会消耗，并用它来制造船舶更省油。

Did a lot of work in automated visual inspection in factories.  
在工厂的自动化视觉检测方面做了很多工作。

So you can take a picture of a smartphone that was just manufactured and label, is there a scratch or any other defect in it.  
所以你可以拍一张刚生产的智能手机的照片并标记，有划痕或其他任何缺陷吗。

Or if you want to build a restaurant review, reputation monitoring system, you can have a little piece of software that looks at online restaurant reviews, and labels that as positive or negative sentiment.  
或者，如果您想建立餐厅评论、声誉监控系统，你可以有一个小软件查看在线餐厅评论，并将其标记为积极或消极情绪。

So one nice thing, one cool thing about supervised learning is that it's not useful for one thing, it's useful for all of these different applications, and many more, besides.  
所以关于监督学习的一件好事，一件很酷的事是它对一件事没有用，但对所有人都有用这些不同的应用程序，以及更多。

Let me just walk through, concretely, the workflow one example of a supervised learning, labeling things kind of project.  
让我具体来说一下，工作流程一个监督学习的例子，给事物贴上标签的项目。

If you want to build a system to label restaurant reviews, you then collect a few data points or collect a data set.  
如果您想构建一个系统来标记餐厅评论，那么您需要收集一些数据点或收集一个数据集。

Where it says, the pastrami sandwich is great, say that is positive. Servers are slow, that's negative. My favorite chicken curry, that's positive.  
上面说，熏牛肉三明治很棒，说这是积极的。服务器很慢，这是负面的。我最喜欢的鸡肉咖喱，这是积极的。

And here, I've shown three data points, but you are building this, you may get thousands of data points like this or thousands of training examples, we call it.  
在这里，我展示了三个数据点，但你正在建设这个，你可能获得数千个像这样的数据点或数千个训练示例，我们称之为。

And the workflow of a machine learning project, of an AI project is, you get labeled data, maybe thousands of data points.  
以及机器学习项目的工作流程，人工智能项目的工作流程是，你可能会得到标记数据，数千个数据点。

Then you have an AI entry team train an AI model to learn from this data.  
然后你就有了一个人工智能入门团队训练一个人工智能模型从这些数据中学习。

And then finally, you would find, maybe a cloud service to run the trained AI model.  
最后，你会发现，也许是一个云服务来运行经过训练的人工智能模型。

And then you can feed it, best bubble tea I've ever had, and that's positive sentiment.  
然后你就可以喂它了，我喝过的最好的珍珠奶茶，这就是积极的情绪。

And so, I think the last decade was maybe the decade of large scale supervised learning.  
所以，我认为过去十年可能是大规模监督学习的十年。

What we found, starting about 10, 15 years ago, was if you were to train a small AI model, so train a small neural network or small deep learning algorithm, basically, a small AI model, maybe not on a very powerful computer, then as you fed it more data, its performance would get better for a little bit but then it would flatten out.  
我们发现了什么，从大约 10、15 年前开始，如果你要训练一个小型人工智能模型，所以训练一个小型神经网络或小型深度学习算法，基本上，一个小型人工智能模型，也许不是在一台非常功能强大的计算机上，然后当你给它提供更多数据时，它的性能会好一点，但随后它就会变平。

It would plateau, and it would stop being able to use the data to get better and better.  
它会趋于稳定，并且它会停止能够利用数据变得越来越好。

But if you were to train a very large AI model, lots of compute on maybe powerful GPUs, then as we scaled up the amount of data we gave the machine learning model, its performance would kind of keep on getting better and better.
但如果你要训练一个非常大的人工智能模型，需要大量计算在可能强大的GPU上，然后随着我们扩大了给机器学习模型的数据量，它的性能会保持越来越好。

So this is why when I started and led the Google Brain team, the primary mission that I directed the team to solve, at the time, was let's just build really, really large neural networks, that we then fed a lot of data to.
这就是为什么我开始并领导 Google Brain 团队时，我当时指导团队解决的主要任务是，让我们真正构建非常大的神经网络，然后我们输入大量数据给这些网络。

And that recipe, fortunately, worked. And I think the idea of driving large compute and large scale of data, that recipe's really helped us driven a lot of AI progress over the last decade.
幸运的是，这个方案奏效了。我认为，驱动大型计算和大规模数据的想法，这个方案确实帮助了我们，在过去十年推动了人工智能的巨大进步。

So if that was the last decade of AI, I think this decade is turning out to be also doing everything we had in supervised learning but adding to it the exciting tool of generative AI.
所以如果那是人工智能的上一个十年，我认为这个十年正在成为我们在监督学习中所做的一切的基础上，再加上生成人工智能这一令人兴奋的工具。

So many of you, maybe all of you, have played with ChatGPT and Bard, and so on. But just given a piece of text, which you call a prompt, like I love eating, if you run this multiple times, maybe you get bagels cream cheese or my mother's meatloaf or out with friends, and the AI system can generate output like that.
你们很多人，也许你们所有人，都玩过 ChatGPT 和 Bard 等。但只要给出一段文本，你称之为提示，比如“我喜欢吃东西”，如果你多次运行这个，也许你会得到“百吉饼奶油奶酪”或“我妈妈的肉饼”或“和朋友出去”，人工智能系统可以生成这样的输出。

Given the amounts of buzz and excitement about generative AI, I thought I'd take just half a slide to say a little bit about how this works.
鉴于有关生成式人工智能的大量讨论和兴奋，我想我只需要一半一张幻灯片来说明一下这是如何运作的。

So it turns out that generative AI, at least this type of text generation, the core of it is using supervised learning that inputs output mappings to repeatedly predict the next word.
事实证明，生成人工智能，至少这种类型的文本生成，它的核心是使用监督学习输入输出映射来重复预测下一个单词。

And so, if your system reads, on the internet, a sentence like, my favorite food is a bagel with cream cheese and lox, then this is translated into a few data points, where if it sees, my favorite food is A, in this case, try to guess that the right next word was bagel or my favorite food is a bagel, try to guess the next word is with, and similarly, if it sees that, in this case, the right guess for the next word would have been cream.
因此，如果您的系统在互联网上读取一句话，比如“我最喜欢的食物是一个带奶油奶酪和熏鲑鱼的百吉饼”，那么这就被翻译成了一些数据点，如果它看到“我最喜欢的食物是A”，在这种情况下，尝试猜测下一个正确的单词是百吉饼，或者“我最喜欢的食物是一个百吉饼”，尝试猜测下一个单词是with，同样，如果它看到，在这种情况下，下一个单词的正确猜测将是奶油。

So by taking texts that you find on the internet or other sources, and by using this input, output, supervised learning to try to repeatedly predict the next word, if you train a very large AI system on hundreds of billions of words, or in the case of the largest models, now more than a trillion words, then you get a large language model like ChatGPT.
因此，通过获取您在互联网上找到的文本或其他来源，并使用此输入、输出、监督学习尝试反复预测下一个单词，如果您用数千亿个单词训练一个非常大的人工智能系统，或者在最大模型的情况下，现在超过一万亿个单词，那么您就得到了一个像 ChatGPT 这样的大型语言模型。

And there are additional, other important technical details. I talked about predicting the next word. Technically, these systems predict the next subword or part of a word called a token, and then there are other techniques like RLHF for further tuning the AI output to be more helpful, honest, and harmless.
还有其他重要的技术细节。我谈到了预测下一个单词。从技术上讲，这些系统预测下一个子词或称为标记的单词的一部分，然后还有其他技术，例如 RLHF，用于进一步调整人工智能输出，使其更加有帮助、更诚实，并且无害。

But at the heart of it is this using supervised learning to repeatedly predict the next word. That's really what's enabling the exciting, really fantastic progress on large language models.
但其核心是使用监督学习重复预测下一个单词。这确实是在大型语言模型上取得令人兴奋的、真正巨大的进展的关键。

So while many people have seen large language models as a fantastic consumer tool. You can go to a website like ChatGPT's website or Bard's or other large language models and use it as a fantastic tool.
所以虽然很多人都将大型语言模型视为一个非常棒的消费工具。您可以访问像 ChatGPT 的网站或 Bard 或其他大型语言模型的网站，并将其作为一个非常棒的工具来使用。

## 需要处理顺序

还有另一种趋势，我认为仍然没有得到充分重视，那就是大型语言模型的力量，不仅仅是作为消费者工具，而是作为开发者工具。  
There's one other trend, I think is still underappreciated, which is the power of large language models, not just as a consumer tool but as a developer tool.

所以，原来花了我几个月的时间来构建的应用，现在很多人可以通过使用大型语言模型更快地构建。  
So it turns out that there are applications that used to take me months to build, that a lot of people can now build much faster by using a large language model.

具体来说，监督学习的工作流程，比如建立餐厅评论系统，你需要获取一堆标记数据。也许需要一个月的时间，我们才能获得几千个数据点。  
Specifically, the workflow for supervised learning, building the restaurant review system, say, would be that you need to get a bunch of labeled data. Maybe that takes a month, we get a few thousand data points.

然后让人工智能团队进行训练和调整，并真正在您的AI模型上获得优化性能。也许这需要三个月的时间。  
Then have an AI team train, and tune, and really get optimized performance on your AI model. Maybe that'll take three months.

然后找到一个云服务来运行它。确保它运行稳健。确保它被识别，也许这会再花三个月。  
Then find a cloud service to run it. Make sure it's running robustly. Make sure it's recognized, maybe that'll take another three months.

所以对于构建商业级机器学习系统来说非常现实的时间表大约需要6到12个月。  
So pretty realistic timeline for building a commercial grade machine learning system is like 6 to 12 months.

相比之下，使用基于提示的AI，您可以在其中编写提示。这就是工作流程的样子。您可以指定提示，可能需要几分钟或几小时。然后，您可以将其部署到云端，这可能需要数小时或数天。  
In contrast, with prompt-based AI, where you write a prompt. This is what the workflow looks like. You can specify a prompt, that takes maybe minutes or hours. And then, you can deploy it to the cloud, that takes maybe hours or days.

所以现在有了某些AI应用，这曾经花了我，字面意思，六个月，也许需要一年的时间来建立，世界各地的许多团队现在大约可以在一周内建成。  
So now there are certain AI applications that used to take me, literally, six months, maybe a year to build, that many teams around the world can now build in maybe a week.

我认为这已经开始了，但最好的还在后面。这开始开启更多人工智能的洪流，可以由很多人构建的应用程序。  
I think this is already starting, but the best is still yet to come. This is starting to open up a flood of a lot more AI applications that can be built by a lot of people.

所以我觉得很多人还是低估了定制人工智能应用程序的泛滥程度，我认为这将会落下帷幕。  
So I think many people still underestimate the magnitude of the flood of custom AI applications that I think is going to come down the pipe.

现在，我知道你可能不是期待我在这个演示文稿中编写代码，但这就是我要做的。  
Now, I know you probably were not expecting me to write code in this presentation, but that's what I'm going to do.

所以，这就是全部代码，我需要编写情感分类器。  
So it turns out, this is all the code I need in order to write a sentiment classifier.

我猜你们中的一些人会了解Python。导入一些来自OpenAI的工具，然后添加这个提示，即对下面的文本进行分类，由三个破折号分隔为具有积极或消极情绪。  
I guess some of you will know Python. Import some tools from OpenAI, and then add this prompt, that says, classify the text below delimited by three dashes as having either a positive or negative sentiment.

我在斯坦福大学商学院度过了一段美妙的时光。学到了很多东西，也结识了很棒的新朋友。  
 I had a fantastic time at Stanford GSB. Learnt a lot, and also made great new friends.

好的。这就是我的提示。然后我只是想运行它。  
All right. So that's my prompt. And then I'm just going to run it.

我从未运行过它。所以我真的希望——谢天谢地，它得到了正确的答案。  
I've never run it before. And so I really hope--thank goodness, it got the right answer.

这就是字面上的所有代码，需要构建一个情感分类器。  
And this is literally all the code it takes to build a sentiment classifier.

因此，今天，世界各地的开发者可以或许只需要10分钟建立一个像这样的系统。  
So, today, developers around the world can take, literally, maybe 10 minutes to build a system like this.

这就是一个非常令人兴奋的发展。  
And that's a very exciting development.

所以我一直在工作中的一件事是试图在在线课程上教授如何使用提示，不仅仅是作为消费者工具，也作为开发者。  
So one of the things I've been working on was trying to teach online classes about how to use prompting, not just as a consumer tool but as a developer too.

我只是谈论技术前景，现在让我分享我的想法，我看到的人工智能机会。  
So just talking about the technology landscape, let me now share my thoughts on what are some of the AI opportunities I see.

这显示了我认为当今不同人工智能技术的价值，我将谈论三年的情况。  
This shows what I think is the value of different AI technologies today, and I'll talk about three years from now.

但当今人工智能的绝大多数财务价值是，我认为，监督学习，对于像Google这样的单一公司来说价值可能超过每年1000亿美元。  
But the vast majority of financial value from AI today is, I think, supervised learning, where for a single company like Google can be worth more than $100 billion US a year.

而且还有数以百万计的开发者构建监督学习应用程序。  
And also, there are millions of developers building supervised learning applications.

所以它已经非常有价值了，而且气势磅礴，背后只是因为寻找应用程序的巨大努力和构建应用程序。  
So it's already massively valuable, and also with tremendous momentum behind it just because of the sheer effort in finding applications and building applications.

然后，生成式人工智能是真正令人兴奋的新进入者，现在要小得多。  
And then, generative AI is the really exciting new entrant, which is much smaller right now.

如果这些圆圈的大小代表今天的价值，这是我认为它可能在三年内增长到的程度。  
If the size of these circles represent the value today, this is what I think it might grow to in three years.

所以监督学习，已经非常庞大了，可能会翻倍，比如说，在接下来的三年时间里可能会翻倍。  
So supervised learning, already really massive, may double, say, in the next three years, from truly massive to even more massive.

而今天的生成式人工智能要小得多，我认为，未来三年将增加一倍以上，因为开发者兴趣的数量、风险资本投资额、探索应用程序的大型企业的数量。  
And generative AI, which is much smaller today, I think, will much more than double in the next three years because of the number-- the amount of developer interest, the amount of venture capital investments, the number of large corporates exploring applications.

我也只是想指出，三年是一个非常短的时间跨度。如果它继续以接近这个速度的速度复合，那么六年后，它将会变得更大。  
But this is a very short time horizon. If it continues to compound in anything near this rate, then in six years, it will be even vastly larger.

但这点亮阴影的区域在绿色或橙色中，这点亮阴影的区域就是机会所在，无论是新的初创公司还是大公司、现有企业，创造并享受价值捕获。  
But this light shaded region in green or orange, that light shaded region is where the opportunity is for either new startups or for large companies, incumbents, to create and to enjoy value capture.

但我希望您从这张幻灯片中学到一件事，那就是所有这些技术都是通用技术。  
But one thing I hope you take away from this slide is that all of these technologies are general purpose technologies.

所以在监督学习的情况下，过去十年中必须完成的许多工作，但在接下来的十年里将会继续是识别并执行具体用例。  
So in the case of supervised learning, a lot of the work that had to be done over the last decade, but is continuing for the next decade, is to identify and to execute on the concrete use cases.

而这个过程也正在为生成人工智能而拉开帷幕。  
And that process is also kicking off for generative AI.

因此，对于演示的这一部分，我希望你能从中汲取的是，通用技术对于许多不同的任务很有用，有很多价值，使用监督学习仍有待创建。  
So for this part of the presentation, I hope you take away from it that general purpose technology is useful for many different tasks, lot of value remains to be created using supervised learning.

尽管如此，我们还远远没有接近完成弄清楚监督学习令人兴奋的用例，我们还有另一个很棒的生成人工智能工具，它进一步扩展了我们现在可以使用人工智能做的事情。  
And even though, we're nowhere near finishing figuring out the exciting use cases of supervised learning, we have this other fantastic tool of generative AI, which further expands the set of things we can now do using AI.

但有一点需要注意，这将会有短期时尚。

But one caveat, which is that there will be short term fads along the way.

所以我不知道你们中的一些人是否会记得名为Lensa的应用程序。这是个好主意，人们喜欢它。但它是一个相对薄弱的软件层在其他人的真正强大的API之上。
 So I don't know if some of you might remember the app called Lensa. This is the app that will let you upload pictures of yourself, and then will render a cool picture of you as an astronaut or a scientist or something. It was a good idea and people liked it. But it was a relatively thin software layer on top of someone else's really powerful APIs.

所以即使它是一个有用的产品，它也是在一个可以防御的行业中。
 So even though it was a useful product, it was in a defensible business.

当我想到像Lensa这样的应用程序时，我实际上想起了史蒂夫·乔布斯给我们iPhone的时候。不久之后，有人写了一个应用程序，我花了1.99美元来这样做，打开LED，将手机变成手电筒。
 When I think about apps like Lensa, I'm actually reminded of when Steve Jobs gave us the iPhone. Shortly after, someone wrote an app that I paid $1.99 for, to do this, to turn on the LED, to turn the phone into a flashlight.

这也是编写应用程序的好主意，打开LED灯，但它也不是一个可以防御的长期目标——也没有创造非常长期的价值，因为它很容易被复制，而且价格低廉，并最终并入iOS。
 This was also a good idea to write an app to turn on the LED light, but it also wasn't a defensible long term goal——also didn't create very long term value because it was easily replicated, and underpriced, and eventually incorporated into iOS.

但随着iOS的崛起，随着iPhone的崛起，有人还弄清楚了如何构建像Uber、Airbnb和Tinder这样的东西。
 But with the rise of iOS, with the rise of iPhone, someone also figured out how to build things like Uber, and Airbnb, and Tinder.

从长远来看，非常有防御性的企业创造了持续价值。
 The very long term, very defensible businesses that created sustaining value.

我认为，随着生成式人工智能的兴起或新的人工智能工具的兴起，真正让我兴奋的是创建那些非常深入、非常困难的应用程序的机会，希望能够创造非常长期的价值。
 And I think, with the rise of generative AI or the rise of new AI tools, what excites me is the opportunity to create those really deep, really hard applications that hopefully can create very long term value.

所以第一个趋势我想分享的是人工智能是一种通用目的技术。
 So the first trend I want to share is AI as a general purpose technology.

我们面前的很多工作就是找到非常多样化的用例并构建它们。
 A lot of the work that lies ahead of us is to find the very diverse use cases and to build them.

我想分享的第二个趋势与为什么人工智能还没有被更广泛地采用有关。
 The second trend I want to share with you, which relates to why AI isn't more widely adopted yet.

所以这是为什么呢？事实证明，如果你要采取所有当前和潜在的人工智能项目，并按照值的递减顺序对它们进行排序，那么在这条曲线的头部，是像广告这样的数十亿美元的项目？
 So why is that? It turns out, if you were to take all current and potential AI projects, and sort them in decreasing order of value, then to the left of this curve, of the head of this curve, are the multi-billion dollar projects like advertising or web search or for e-commerce product recommendations or company like Amazon.

事实证明，大约10、15年前，我的朋友和我，我们找到了一个如何招聘的秘诀，比如说100名工程师编写一个软件投放更相关的广告，并应用该广告给十亿用户，并产生巨大的财务价值。
 It turns out that about 10, 15 years ago, my friends and I, we figured out a recipe for how to hire, say, 100 engineers to write one piece of software to serve more relevant ads, and apply that one piece of software to a billion users, and generate massive financial value.

但一旦你走出消费软件互联网，几乎没有人拥有100百万或十亿用户您可以编写并应用一个软件。
 But once you go outside consumer software internet, hardly anyone has 100 million or a billion users that you can write and apply one piece of software to.

所以一旦你去了其他行业，正如我们从左边这条曲线的头部开始过渡到长尾，这些是我看到的一些项目，我很兴奋。
 So once you go to other industries, as we go from the head of this curve on the left over to the long tail, these are some of the projects I see, and I'm excited about.

我正在与一家披萨店合作，他们正在给他们做的披萨拍照，因为他们需要做一些事情，例如确保奶酪铺好均匀。
 I was working with a pizza maker that was taking pictures of the pizza they were making because they needed to do things like make sure that the cheese is spread evenly.

所以这是一个大约500万美元的项目。
 So this is about a $5 million project.

但那个古老的秘诀雇用一大群高度熟练的工程师在这个项目上工作没有意义。
 But that old recipe of hiring a large group of highly skilled engineers to work on this one project, that doesn't make sense.

同样材料分级，布料分级，钣金分级，很多这样的项目。
 Similarly materials grading, cloth grading, sheet metal grading, many projects like this.

所以在这条曲线的头部，有一小部分数十亿美元的项目，我们知道如何执行那些创造价值的事情。
 So in the head of this curve, there's a small number of, let's say, multi-billion dollar projects, and we know how to execute those delivering value.

在其他行业中，我看到了一条很长的尾巴，数以万计的500万美元的项目，到目前为止，由于定制成本很高，这些项目一直非常难以执行。
 In other industries, I'm seeing a very long tail of tens of thousands, of let's call them, $5 million projects, that until now, have been very difficult to execute on because of the high cost of customization.

我认为令人兴奋的趋势是，人工智能社区一直在构建更好的工具，让我们可以聚合这些用例，并使最终用户可以轻松进行定制。
 The trend that I think is exciting is that the AI community has been building better tools that lets us aggregate these use cases, and make it easy for the end user to do the customization.

具体来说，我看到了很多令人兴奋的低代码和无代码工具，使用户能够定制AI系统。
 Specifically, I'm seeing a lot of exciting low code and no code tools, that enable the user to customize the AI system.

这意味着而不是我需要担心那么多披萨的图片，我们开始看到可以启用的工具，披萨制作工厂的IT部门能够在他们自己的披萨图片上训练人工智能系统，以实现价值500万美元的价值。
 This means instead of me needing to worry that much about pictures of pizza, we have tools——we're starting to see tools that can enable the IT department of the pizza making factory to train AI system on their own pictures of pizza to realize this $5 million worth of value.

顺便说一下，披萨的图片，它们在互联网上不存在。所以Google和Bing无法访问这些图片，我们需要可以使用的工具，真的，披萨工厂自己，建造和部署，并维护自己的有效的自定义人工智能系统在他们自己的披萨照片上。
 By the way, the pictures of pizza, they don't exist on the internet. So Google and Bing don't have access to these pictures, we need tools that can be used by, really, the pizza factory themselves, to build, and deploy, and maintain their own effective custom AI system that works on their own pictures of pizza.

从广义上讲，实现这一点的技术，其中一些是提示、文本提示、视觉提示，但实际上，大型语言模型和类似的工具，像这样的技术或称为以数据为中心的人工智能的技术，而不是要求披萨工厂编写大量代码，我们可以要求他们提供数据，事实证明更加可行。
 From a broad perspective, the technology for enabling this, some of it is prompting, text prompting, visual prompting, but really, large language models and similar tools, technologies like that or a technology called data-centric AI, whereby, instead of asking the pizza factory to write a lot of code, which is challenging, we can ask them to provide data which turns out to be more feasible.

我认为第二个趋势很重要，因为我认为这是服用配方的关键部分，将AI的价值，至今仍然让人感觉非常集中于科技世界和消费软件互联网世界，并将其推广到所有行业，真的到其他经济体，其中——有时很容易忘记，经济的其他部分比科技世界大得多。
 I think the second trend is important, because I think this is a key part of the recipe for taking the value of AI, which so far still feels very concentrated in the tech world and the consumer software internet world, and pushing this out to all industries, really to the rest of the economy, which-- sometimes it's easy to forget, the rest of the economy is much bigger than the tech world.

所以我分享的两个趋势，AI作为一种通用目的技术，大量具体用例需要实现，以及低代码、无代码、简单易用的工具，使AI能够部署到更多行业。
 So the two trends I shared, AI as a general purpose technology, lots of concrete use cases to be realized as well as low code, no code, easy to use tools, enabling AI to be deployed in more industries.

我们如何抓住这些机会？
 How do we go after these opportunities?

大约五年前，我想解决一个难题，我觉得很多有价值的人工智能项目现在都是可能的。我在想，我们如何完成它们？  
So about five years ago, there was a puzzle I wanted to solve, I felt that many valuable AI projects are now possible. I was thinking, how do we get them done?

并曾在大型科技公司领导过团队，我很难弄清楚我如何在一家大型科技公司运营团队，去追求非常多样化的机会集，从海运到教育到金融服务到医疗保健等等。  
And having led teams in big tech companies, I had a hard time figuring out how I could operate a team in a big tech company to go after a very diverse set of opportunities in everything from maritime shipping to education to financial services to healthcare, and so on and so forth.

它只是非常多样化的用例，非常多样化的去市场，以及非常多样化的客户群和应用程序。  
It's just very diverse use cases, very diverse go to markets, and very diverse customer bases and applications.

我觉得最有效的方法就是如果我们可以让很多不同的公司去追求这些非常多样化的机会。  
I felt that the most efficient way to do this would be if we can start a lot of different companies to pursue these very diverse opportunities.

所以这就是为什么我最终启动了人工智能基金，这是一家风险投资工作室，建立初创公司去追求多样化的人工智能机会。  
So that's why I ended up starting AI Fund, which is a venture studio that builds startups to pursue a diverse set of AI opportunities.

当然，除了许多初创公司，现有企业也有很多将人工智能融入现有业务的机会。  
Of course, in addition to lots of startups, incumbent companies also have a lot of opportunities to integrate AI into existing businesses.

事实上，我看到的现有企业的一种模式是，分布往往是现有公司的一个显着优势，如果他们打得好，可以让他们将人工智能集成到他们的产品中，相当有效。  
In fact, one pattern I'm seeing for incumbent businesses is distribution is often one of the significant advantages of incumbent companies, if they play their cards right, can allow them to integrate AI into their products, quite efficiently.

但具体来说，机会在哪里？  
But just to be concrete, where are the opportunities?

所以我认为这就是我所认为的人工智能堆栈。最底层是硬件、半导体层。  
So I think of this as-- this is what I think of as an AI stack. At the bottom level is the hardware, semiconductor layer.

那里有绝佳的机会，但资本密集型，非常集中。所以需要大量资源，获胜者相对较少。  
Fantastic opportunities there, but very capital intensive, very concentrated. So needs a lot of resources, relatively few winners.

所以有些人可以并且应该在那里玩。我个人不喜欢自己去那里玩。  
So some people can and should play there. Personally, I don't like to play there myself.

还有基础设施层。也是绝佳的机会，但资本密集型，非常集中。  
There's also the infrastructure layer. Also fantastic opportunities, but very capital intensive, very concentrated.

所以我自己也倾向于不在那里玩。  
So I tend not to play there myself, either.

然后是开发者工具层。  
And then there's the developer tool layer.

我刚才给你看的是——我实际上使用OpenAI的API作为开发工具。  
What I showed you just now was-- I was actually using OpenAI's API as a developer tool.

开发者工具行业是一个高度竞争的行业。看看现在所有追逐OpenAI的初创公司。  
But there will be some mega winners. And so I sometimes play here, but primarily, when I think of a meaningful technology advantage, because I think that earns you the right or earns you a better shot at being one of the mega winners.

最后，尽管很多媒体关注和嗡嗡声在基础设施和开发者工具层，事实证明该层只有在应用层更成功的情况下才能成功。  
And lastly, even though a lot of the media attention and the buzz is in the infrastructure and developer tooling layer, it turns out that layer can be successful only if the application layer is even more successful.

我们看到了很多机会，似乎有一个非常大的市场，但竞争的地点是相对轻微的，相对于机会的大小而言。  
So, actually, let me mention one example. A company called Amorai-- I was actually just texting the CEO yesterday. But Amorai is a company that we built that uses AI for romantic relationship coaching. And just to point out, I'm an AI guy. And I feel like I know nothing really about romance. And if you don't believe me, you can ask my wife, she will confirm that I know nothing about romance. But when we went to build this, we wanted to get together with the former CEO of Tinder, Renate Nyborg. And with my team's expertise in AI, and her expertise in relationships because she ran Tinder, she knows more about relationships than I think anyone I know, we're able to build something pretty unique using AI for kind of romantic relationship mentoring. And the interesting thing about applications like these is when we look around, how many teams in the world are simultaneously expert in AI and in relationships? And so at the application layer, I'm seeing a lot of exciting opportunities that seem to have a very large market, but where the competition sets is very light, relative to the magnitude of the opportunity. It's not that there are no competitors, but it's just much less intense compared to the developer tool or the infrastructure layers.

所以，因为我花了很长时间迭代建立初创公司的过程，我要做的是只是非常透明地告诉你我们开发的建立初创公司的秘诀。  
So, because I've spent a lot of time iterating on a process of building startups, what I'm going to do is just, very transparently, tell you the recipe we've developed for building startups.

所以经过多年的迭代和改进，这就是我们现在建立初创公司的方式。  
So after many years of iteration and improvement, this is how we now build startups.

我的团队总是能够获得很多不同的想法，内部产生的想法，来自合作伙伴的想法。  
My team's always had access to a lot of different ideas, internally generated, ideas from partners.

我想通过一个例子来解释这一点，我们做到了，这是一家名为Bearing AI的公司，它使用人工智能提高船舶的燃油效率。  
I want to walk through this with one example of something we did, which is a company Bearing AI, which uses AI to make ships more fuel efficient.

所以这个想法是，想想看，作为船舶的谷歌地图。我们可以建议一艘船或告诉一艘船如何驾驶，以便您仍然准时到达目的地，但使用后可以减少约10%的燃料。  
So the specific idea was, think of it as a Google Maps for ships. We can suggest a ship or tell a ship how to steer, so that you still get to your destination on time, but using, it turns out, about 10% less fuel.

所以我们现在做的是花了大约一个月的时间验证这个想法。所以仔细检查一下，这个想法在技术上是否可行，然后与潜在客户交谈，确保有市场需求。  
So we now do is we spend about a month validating the idea. So double check, is this idea even technically feasible, and then talk to prospective customers to make sure there is a market need.

如果它通过了这个阶段，那么我们将去招募一位首席执行官与我们一起开展该项目。  
If it passes this stage, then we will go and recruit a CEO to work with us on the project.

当我开始时，我曾经花费很长时间自己在一个项目上工作，然后才任命首席执行官。  
When I was starting out, I used to spend a long time working on a project myself before bringing on a CEO.

但经过迭代，我们意识到一开始就带来领导者可以减轻很多负担，让我们合作，它可以减少很多负担。  
But after iterating, we realized that bringing on a leader at the very beginning to work with us, it reduces a lot of the burden of having to transfer knowledge or having a CEO come in and having to revalidate what [? we ?] discovered.

所以这个过程是，我们学到了更有效的知识，我们一开始就带了领导者。  
So the process is, we've learned much more efficient, we just bring the leader at the very start.

所以在Bearing AI的情况下，我们找到了一位出色的首席执行官，迪伦·凯尔，他是一位知名企业家，曾经成功退出过。  
So in the case of Bearing AI, we found a fantastic CEO, Dylan Keil, who is a reputed entrepreneur, one successful exit before.

然后我们花了三个月、六个月、两周的冲刺，与他们合作构建原型以及进行深度客户验证。  
Then we spent three months, six, two week sprints, to work with them to build a prototype as well as do deep customer validation.

如果它能活过这个阶段，我们大约有三分之二，66%的存活率，然后我们写第一张支票，这为公司提供了资源聘请高管团队，建立关键团队，让MVP发挥作用，最低限度可行的产品发挥作用，并获得一些真正的客户。  
If it survives this stage, and we have about a two thirds, 66% survival rate, we then write the first check in, which then gives the company resources to hire an executive team, build the key team, get an MVP working, minimum viable product working, and get some real customers.

然后在那之后，希望，然后成功筹集额外的外部几轮融资，并可以继续成长和扩展。  
And then after that, hopefully, then successfully raises additional external rounds of funding, and can keep on growing and scaling.

所以我真的为我的团队所做的工作感到自豪，能够支持三井的想法，和迪伦·凯尔作为首席执行官。  

–缺少英文

And today, there are hundreds of ships, on the high seas right now, that are steering themselves differently because of Bearing AI.  
如今，公海上有数百艘船只，因为Bearing AI，它们的转向方式正在发生变化。  
And 10% fuel savings translates to around to maybe $450,000 in savings in fuel, per ship per year.  
而且，节省10%的燃油可能意味着每艘船每年可以节省大约450,000美元的燃料费用。  
And, of course, it's also, frankly, quite a bit better for the environment.  
当然，坦白说，这对环境也更好。  
And I think this startup, I think, would not have existed if not for Dylan's fantastic work, and then also, Mitsui bringing this idea to me.  
我认为这个初创公司，如果没有迪伦出色的工作，以及三井将这个想法带给我，就不会存在。  
And I like this example because this is another one is like-- this is a startup idea that, just to point out, I would never have come up with myself.  
我喜欢这个例子，因为这是一个创业想法，我要指出的是，我永远不会自己想出来。  
Because I've been on a boat but what do I know about maritime shipping.  
因为我虽然在船上待过，但我对海运了解多少呢？  
But is the deep subject matter expertise of Mitsui, that had this insight, together with Dylan, and then my team's expertise in AI, that made this possible.  
但是三井深厚的专业知识，加上迪伦，以及我的团队在人工智能方面的专业知识，使得这一切成为可能。  
And so as I operate in AI, one thing I've learned is my swim lane is AI, and that's it.  
所以，当我在人工智能领域工作时，我了解到我的专长就是人工智能，仅此而已。  
Because I don't have time or it's very difficult for me to be expert in maritime shipping, and romantic relationships, and health care, and financial services, and on, and on, and on.  
因为我没有时间，或者对我来说很难成为海运、浪漫关系、医疗保健、金融服务等等领域的专家。  
And so I've learned that if I can just help get accurate technical validation, and then use AI resources to make sure the AI tech is built quickly and well, and I think, we've always managed to help the companies build a strong technical team, then partnering with subject matter experts often results in exciting new opportunities.  
所以我了解到，如果我能帮助获得准确的技术验证，然后使用人工智能资源确保人工智能技术快速且良好地构建，我认为，我们总是能够帮助公司建立一个强大的技术团队，那么与主题专家合作通常会产生令人兴奋的新机会。  
And I want to share with you one other weird aspect of-- one other weird thing I've learned about building startups, which is I like to engage only when there's a concrete idea.  
我想和你分享关于建立初创公司的另一个奇怪的方面，那就是我喜欢在有一个具体的想法时才参与。  
And this runs counter to a lot of the advice you hear from the design thinking methodology, which often says, don't rush to solutioning.  
这与你所听到的许多设计思维方法论的建议背道而驰，它们通常说，不要急于寻找解决方案。  
Explore a lot of alternatives before you do a solution.  
在制定解决方案之前，先探索许多替代方案。  
Honestly, we tried that, it was very slow.  
老实说，我们尝试过那样做，但速度非常慢。  
But what we've learned is that at the ideation stage, if someone comes to me and says, hey, Andrew, you should apply AI to financial services.  
但我们学到的是，在构思阶段，如果有人来找我说，嘿，安德鲁，你应该将人工智能应用于金融服务。  
Because I'm not a subject matter expert in financial services, it's very slow for me to go and learn enough about financial services to figure out what to do.  
因为我不是金融服务领域的专家，我去了解金融服务并弄清楚该怎么做是非常缓慢的过程。  
I mean, eventually, you could get to a good outcome, but it's a very labor intensive, very slow, very expensive process for me to try to learn industry after industry.  
我的意思是，最终，你可能会得到一个好的结果，但对我来说，尝试学习一个又一个行业是一个非常劳动密集型、非常缓慢、非常昂贵的过程。  
In contrast, one of my partners wrote this idea as a tongue in cheek, not really seriously.  
相比之下，我的一个合伙人半开玩笑地写下了这个想法，并不是真的认真。  
But, let's say, [INAUDIBLE] by GPT, let's eliminate commercials by automatically buying every product advertised in exchange for not having to see any ads, it's not a good idea, but it is a concrete idea.  
但是，比如说，[听不清] GPT，让我们通过自动购买所有广告中的产品来消除广告，以换取不看任何广告，这不是一个好主意，但这是一个具体的想法。  
And it turns out, concrete ideas can be validated or falsified efficiently.  
事实证明，具体的想法可以被高效地验证或证伪。  
They also give a team a clear direction to execute.  
它们还为团队提供了明确的执行方向。  
And I've learned that in today's world, especially with the excitement, the buzz, the exposure to AI of a lot of people, it turns out that there are a lot of subject matter experts in today's world that have deeply thought about a problem for months, sometimes even one or two years.  
我了解到，在当今世界，特别是随着许多人对人工智能的兴奋、炒作和接触，事实证明，当今世界上有很多主题专家已经深入思考一个问题数月，有时甚至是一两年。  
But they've not yet had a build partner.  
但他们还没有找到构建合作伙伴。  
And when we get together with them, and hear, and they share the idea of us, it allows us to work with them to very quickly go into validation and building.  
当我们与他们聚在一起，听到他们的想法并与我们分享时，这使我们能够与他们迅速进入验证和构建阶段。  
And I find that this works because there are a lot of people that have already done the design thinking thing of exploring a lot of ideas and winnowing down to really good ideas.  
我发现这样做有效，因为有很多人已经完成了设计思维的过程，探索了许多想法，并筛选出了真正好的想法。  
And there are-- I find that there are so many good ideas sitting out there that no one is working on.  
而且我发现有很多好想法就在那里，没有人在努力实现它们。  
That finding those good ideas that someone has already had, and wants to share with us, and wants to build partner for, that turns out to be a much more efficient engine.  
发现那些已经有人想到并愿意与我们分享、希望建立合作伙伴的好想法，结果证明这是一个更高效的引擎。  
So before I wrap up, we'll go to the question in a second, just a few slides to talk about risk and social impact.  
所以在我结束之前，我们马上会讨论问题，只是几张幻灯片来谈谈风险和社会影响。  
So AI is very powerful technology.  
所以人工智能是一种非常强大的技术。  
To say something you'd probably guess, my teams and I, we only work on projects that move humanity forward.  
说一些你可能已经猜到的事情，我和我的团队只致力于推动人类前进的项目。  
And we have multiple times killed projects that we assess to be financially sound, based on ethical grounds.  
我们多次终止了我们认为在财务上可行，但基于道德理由的项目。  
It turns out, I've been surprised and sometimes dismayed at the creativity of people to come up with good ideas.  
事实证明，我对人们的创造力感到惊讶，有时甚至感到沮丧，因为他们想出了好主意。  
So to come up with really bad ideas that seem profitable but really should not be built.  
所以提出了一些看似有利可图但实际上不应该构建的非常糟糕的想法。  
We've killed a few projects on those grounds.  
我们已经因为这些理由取消了一些项目。  
And then, I think, has to be acknowledged that AI today does have problems with bias, fairness, and accuracy.  
然后，我认为，必须承认今天的人工智能确实存在偏见、公平性和准确性问题。  
But also the technology is improving quickly.  
但同时，技术正在迅速改进。  
So I see that AI systems today are less biased than six months ago, and more fair than six months ago, which is not to dismiss the importance of these problems.  
所以我认为今天的人工智能系统比六个月前偏见更少，比六个月前更公平，这并不是忽视这些问题的重要性。  
They are problems and we should continue to work on them.  
它们是问题，我们应该继续努力解决它们。  
But I'm also gratified at the number of teams working hard on these issues to make them much better.  
但我也很欣慰看到有很多团队正在努力解决这些问题，使它们变得更好。  
When I think of the biggest risks of AI.  
当我想到人工智能的最大风险时。  
I think that the biggest risks-- one of the biggest risks is the disruption to jobs.  
我认为最大的风险之一是工作中断。  
This is a diagram from a paper by our friend at the University of Pennsylvania, and some folks at OpenAI, analyzing the exposure of different jobs to AI automation.  
这是我们宾夕法尼亚大学的朋友和OpenAI的一些人士的论文中的图表，分析了不同工作对人工智能自动化的暴露程度。

And it turns out that, whereas, the previous wave of automation mainly-- the most exposed jobs were often the lower wage jobs, such as when we put robots into factories.
 事实证明，上一次自动化浪潮主要是那些工资较低的工作最容易受到影响，比如当我们把机器人引入工厂时。
 With this current wave of automation, is actually the higher wage jobs, further to the right of this axis, that seems to have more of their tasks exposed to automation.
 而当前的自动化浪潮实际上是那些工资较高的工作，在这个轴的右侧，似乎有更多的任务暴露于自动化。
 So even as we create tremendous value using AI, I feel like, as citizens, and our corporations, and our governments, and, really, our society, I feel a strong obligation to make sure that people, especially people whose livelihoods are disrupted, are still well taken care of, are still treated well.
 所以即使我们使用人工智能创造了巨大的价值，我觉得，作为公民，我们的公司，我们的政府，真的，我们的社会，我有强烈的义务确保那些生计受到影响的人们，特别是那些生计被打断的人们，仍然得到良好的照顾，仍然受到良好的待遇。
 And then lastly, there's also been-- it feels like every time there's a big wave of progress in AI, there's a big wave of hype about artificial general intelligence as well.
 最后，还有——感觉每次人工智能领域有一大波进步时，关于通用人工智能的炒作也会随之兴起。
 When DeepLearning started work really well 10 years ago, there was a lot of hype about AGI.
 当深度学习在10年前开始真正发挥作用时，关于AGI有很多炒作。
 And now, the generative AI is working really well, there's another wave of hype about AGI.
 现在，生成式人工智能运行得非常好，关于AGI的炒作又来了一波。
 But I think that artificial general intelligence, AI that can do anything a human can do is still decades away, maybe 30 to 50 years, maybe even longer.
 但我认为，能够做任何人类能做的事情的人工智能通用智能，还有几十年的时间，也许30到50年，甚至更长。
 I hope we'll see it in our lifetimes.
 我希望我们能在有生之年看到它。
 But I don't think there's any time soon.
 但我不认为很快就会有。
 One of the challenges is that the biological path to intelligence, like humans and the digital path to intelligence, AI, they've taken very different paths.
 挑战之一是，人类这样的生物智能路径和人工智能这样的数字智能路径，它们走的是截然不同的道路。
 And the funny thing about the definition of AGI is you're benchmarking this very different digital path to intelligence with really the biological path to intelligence.
 有趣的是，AGI的定义是你正在用真正的生物智能路径来基准测试这条非常不同的数字智能路径。
 So I think, large language models are smarter than any of us in certain key dimensions, but much dumber than any of us in other dimensions.
 所以我认为，大型语言模型在某些关键维度上比我们任何人都聪明，但在其他维度上却比我们任何人都愚蠢。
 And so forcing it to do everything a human can do is like a funny comparison.
 所以强迫它做人类能做的一切就像是一个有趣的比较。
 But I hope we'll get there.
 但我希望我们能到达那里。
 Hopefully, within our lifetimes.
 希望在我们有生之年。
 And then there's also a lot of, I think, overblown hype about AI creating extinction risks for humanity.
 然后还有，我认为，关于人工智能给人类带来灭绝风险的过度炒作。
 Candidly, I don't see it.
 坦白说，我没有看到。
 I just don't see how AI creates any meaningful extinction risk for humanity.
 我只是不明白人工智能如何创造出对人类有意义的灭绝风险。
 I think that people worry we can't control AI.
 我认为人们担心我们无法控制人工智能。
 But we have lots of, AI will be more powerful than any person.
 但我们有很多，人工智能将比任何人都更强大。
 But with lots of experience, steering, very powerful entities, such as corporations or nation states that are far more powerful than any single person, and making sure they, for the most part, benefit humanity.
 但凭借丰富的经验，引导非常强大的实体，如公司或国家，它们比任何一个人都要强大得多，确保它们在很大程度上造福人类。
 And also technology develops gradually.
 而且技术也是逐渐发展的。
 The so-called hot take off scenario, where it's not really working today, and then suddenly, one day, overnight, it works brilliantly, and we achieve super intelligence, takes over the world.
 所谓的热启动场景，今天它并不真正工作，然后突然有一天，一夜之间，它工作得非常出色，我们实现了超级智能，接管了世界。
 That's just not realistic.
 这是不现实的。
 And I think the AI technology will develop slowly, like all the others, and then it gives us plenty of time to make sure that we provide oversight and can manage it to be safe.
 我认为人工智能技术会像所有其他技术一样慢慢发展，然后它会给我们充足的时间来确保我们提供监督并能够管理它以确保安全。
 And lastly, if you look at the real extinction risk to humanity, such as, fingers crossed, the next pandemic or climate change leading to a massive de-population of some parts of the planet, or much lower odds, but maybe someday, an asteroid doing to us what it had done to the dinosaurs.
 最后，如果你看看对人类真正的灭绝风险，比如，手指交叉，下一次大流行或气候变化导致这个星球某些地区人口大规模减少，或者几率更低，但也许有一天，一颗小行星对我们做它对恐龙所做的事情。
 I think if we look at the actual real extinction risk to humanity, AI having more intelligence, even artificial intelligence in the world, would be a key part of the solution.
 我认为，如果我们看看对人类真正的灭绝风险，人工智能拥有更多的智能，即使是世界上的人工智能，将是解决方案的关键部分。
 So I feel like if you want humanity to survive and thrive for the next 1,000 years, rather than slowing AI down, which some people propose, I would rather make AI go as fast as possible.
 所以我觉得，如果你希望人类在接下来的1000年里生存和繁荣，而不是像一些人提议的那样放慢人工智能的发展，我宁愿让人工智能尽可能快地发展。
 So with that, just to summarize, this is my last slide.
 所以，总结一下，这是我的最后一张幻灯片。
 I think that AI, as a general purpose technology creates a lot of new opportunities for everyone.
 我认为人工智能作为一种通用技术为每个人创造了很多新的机会。
 And a lot of the exciting and important work that lies ahead of us all is to go and build those concrete use cases, and hopefully, hopefully, I'll have opportunities to maybe engage with more of you on those opportunities as well.
 我们所有人面前的许多令人兴奋和重要的工作是去构建那些具体的用例，希望我将有机会与你们更多的人在这些机会上合作。
 So with that, let me just say, thank you all very much.
 那么，让我就说，非常感谢大家。



## srt 字幕

1
00:00:00,0 --> 00:00:02,970
[MUSIC PLAYING]
[音乐播放]

2
00:00:05,450 --> 00:00:11,379
It is my pleasure to welcome
Dr. Andrew Ng, tonight.
我很高兴欢迎
博士。吴恩达，今晚。

3
00:00:11,380 --> 00:00:16,769
Andrew is the managing
general partner of AI Fund,
Andrew是AI Fund的管理
普通合伙人，

4
00:00:16,769 --> 00:00:22,850
founder of DeepLearning.AI
and Landing AI,
DeepLearning.AI
和Landing AI创始人，

5
00:00:22,850 --> 00:00:26,120
chairman and
co-founder of Coursera,
Coursera 主席兼
联合创始人，

6
00:00:26,120 --> 00:00:29,870
and an adjunct professor
of Computer Science, here
以及计算机科学的兼职教授
，在这里

7
00:00:29,870 --> 00:00:31,130
at Stanford.
在斯坦福大学。

8
00:00:31,129 --> 00:00:35,570
Previously, he had started
and led the Google Brain
此前，他曾启动
并领导 Google Brain

9
00:00:35,570 --> 00:00:39,289
team, which had helped
Google adopt modern AI.
团队，帮助
谷歌采用现代人工智能。

10
00:00:39,289 --> 00:00:43,189
And he was also director
of the Stanford AI lab.
他还是斯坦福人工智能实验室的主任。

11
00:00:43,189 --> 00:00:49,429
About eight million people, 1
in 1,000 persons on the planet,
大约八百万人，地球上 1,000 人中就有 1
，

12
00:00:49,429 --> 00:00:52,159
have taken an AI class from him.
上过他的人工智能课程。

13
00:00:52,159 --> 00:00:56,149
And through, both, his
education and his AI work,
通过他的
教育和他的人工智能工作，

14
00:00:56,149 --> 00:00:58,920
he has changed numerous lives.
他改变了无数人的生活。

15
00:00:58,920 --> 00:01:01,370
Please welcome Dr. Andrew Ng.
欢迎吴恩达博士。

16
00:01:01,369 --> 00:01:04,310
[APPLAUSE]
[掌声]

17
00:01:07,250 --> 00:01:08,60
Thank you, Lisa.
谢谢你，丽莎。

18
00:01:08,60 --> 00:01:09,480
It's good to see everyone.
很高兴见到大家。

## 正文

19
00:01:09,480 --> 00:01:12,109
what I want to do today is chat to you
所以，我今天想做的就是和你聊天


20
00:01:12,109 --> 00:01:15,49
about some opportunities in AI.
关于人工智能的一些机会。

21
00:01:15,49 --> 00:01:18,230
So I've been saying AI
is a new electricity.
所以我一直在说人工智能
是一种新电力。

22
00:01:18,230 --> 00:01:20,750
One of the difficult things
to understand about AI
理解人工智能最困难的事情之一


23
00:01:20,750 --> 00:01:23,760
is that it is a general
purpose technology,
是它是一种通用
目的技术，

24
00:01:23,760 --> 00:01:26,270
meaning that it's not
useful only for one thing
这意味着它不仅仅
仅用于一件事

25
00:01:26,269 --> 00:01:28,549
but it's useful for lots
of different applications,
但它对于许多不同的应用程序很有用，

26
00:01:28,549 --> 00:01:29,780
kind of like electricity.
有点像电。

27
00:01:29,780 --> 00:01:32,570
If I were to ask you, what
is electricity good for?
如果我问你，电有什么用？

28
00:01:32,569 --> 00:01:35,172
It's not any one thing,
it's a lot of things.
这不是任何一件事，
而是很多事情。

29
00:01:35,173 --> 00:01:37,340
So what I'd like to do is
start off sharing with you
所以我想做的是
开始与大家分享

30
00:01:37,340 --> 00:01:39,350
how I view the
technology landscape,
我如何看待
技术前景，

31
00:01:39,349 --> 00:01:43,39
and this will lead into
the set of opportunities.
这将带来
一系列的机会。

32
00:01:43,40 --> 00:01:46,430
So lot of hype, lot of
excitement about AI.
关于人工智能有很多炒作、很多
兴奋。

33
00:01:46,430 --> 00:01:48,830
And I think, a good
way to think about AI
我认为，这是思考人工智能的好方法

34
00:01:48,829 --> 00:01:51,179
is as a collection of tools.
是作为工具的集合。

35
00:01:51,180 --> 00:01:53,880
So this includes, a technique
called supervised learning,
所以这包括一种称为监督学习的技术
，

36
00:01:53,879 --> 00:01:56,89
which is very good at
recognizing things or labeling
非常擅长
识别事物或标记

37
00:01:56,90 --> 00:01:59,870
things, and generative AI, which
is a relatively new, exciting
物，以及生成人工智能，这是一个相对较新的、令人兴奋的

38
00:01:59,870 --> 00:02:00,710
development.
发展。

39
00:02:00,709 --> 00:02:04,99
If you're familiar with AI, you
may have heard of other tools.
如果您熟悉人工智能，您
可能听说过其他工具。

40
00:02:04,99 --> 00:02:06,629
But I'm going to talk less
about these additional tools,
但我将少谈
这些额外的工具，

41
00:02:06,629 --> 00:02:09,508
and I'll focus today on
what I think are, currently,
今天我将重点关注
我目前的想法，

42
00:02:09,508 --> 00:02:12,59
the two most important tools,
which are supervised learning
两个最重要的工具，
监督学习

43
00:02:12,60 --> 00:02:13,860
and generative AI.
和生成人工智能。

44
00:02:13,860 --> 00:02:17,40
So supervised learning is
very good at labeling things
所以监督学习
非常擅长标记事物

45
00:02:17,39 --> 00:02:20,639
or very good at computing
input to outputs or A to B
或者非常擅长计算
输入到输出或A到B

46
00:02:20,639 --> 00:02:23,189
mappings, given an input
A, give me an output.
映射，给定输入
A，给我一个输出。

47
00:02:23,189 --> 00:02:27,210
For Example, given an
email, we can use supervised
例如，给定一个
电子邮件，我们可以使用监督

48
00:02:27,210 --> 00:02:30,60
learning to label it
as spam or not spam.
学习将其标记为垃圾邮件或非垃圾邮件。

49
00:02:30,60 --> 00:02:32,99
The most lucrative
application of this
最赚钱的
这个应用

50
00:02:32,99 --> 00:02:34,680
that I've ever worked on is
probably online advertising,
我曾经从事过的工作就是
可能是在线广告，

51
00:02:34,680 --> 00:02:37,337
where given an ad, we
can label if a user
如果给定广告，我们
可以标记用户是否

52
00:02:37,337 --> 00:02:38,879
likely to click on
it, and therefore,
可能会点击
它，因此，

53
00:02:38,879 --> 00:02:40,349
show more relevant ads.
显示更多相关的广告。

54
00:02:40,349 --> 00:02:43,530
For self-driving cars, given
the sensor readings of a car,
对于自动驾驶汽车，给定
汽车的传感器读数，

55
00:02:43,530 --> 00:02:45,780
we can label it with
where are the other cars.
我们可以用
标记它，其他汽车在哪里。

56
00:02:45,780 --> 00:02:47,849
One project, that my
team, AI Fund, worked on
我的
团队 AI Fund 从事的一个项目

57
00:02:47,849 --> 00:02:49,199
was ship route optimization.
是船舶航线优化。

58
00:02:49,199 --> 00:02:52,589
Where given a route the ship is
taking or considering taking,
在给定航线的情况下，船舶正在
采取或考虑采取，

59
00:02:52,590 --> 00:02:54,689
we can label that
with how much fuel
我们可以用多少燃料来标记


60
00:02:54,689 --> 00:02:56,939
we think this will consume,
and use this to make
我们认为这会消耗，
并用它来制造

61
00:02:56,939 --> 00:02:58,979
ships more fuel efficient.
船舶更省油。

62
00:02:58,979 --> 00:03:02,619
Did a lot of work in automated
visual inspection in factories.
在工厂的自动化
视觉检测方面做了很多工作。

63
00:03:02,620 --> 00:03:04,620
So you can take a picture
of a smartphone, that
所以你可以拍一张智能手机的照片


64
00:03:04,620 --> 00:03:06,840
was just manufactured and
label, is there a scratch
刚生产的和
标签，有划痕吗

65
00:03:06,840 --> 00:03:08,400
or any other defect in it.
或任何其他缺陷。

66
00:03:08,400 --> 00:03:11,400
Or if you want to build a
restaurant review, reputation
或者，如果您想建立
餐厅评论、声誉

67
00:03:11,400 --> 00:03:14,39
monitoring system, you can
have a little piece of software
监控系统，你可以
有一个小软件

68
00:03:14,39 --> 00:03:15,840
that looks at online
restaurant reviews,
查看在线
餐厅评论，

69
00:03:15,840 --> 00:03:19,60
and labels that as positive
or negative sentiment.
并将其标记为积极
或消极情绪。

70
00:03:19,60 --> 00:03:21,840
So one nice thing, one cool
thing about supervised learning
所以关于监督学习的一件好事，一件很酷的事


71
00:03:21,840 --> 00:03:24,870
is that it's not useful for
one thing, it's useful for all
是它对
一件事没有用，但对所有人都有用

72
00:03:24,870 --> 00:03:28,80
of these different applications,
and many more, besides.
这些不同的应用程序，
以及更多。

73
00:03:28,80 --> 00:03:30,60
Let me just walk
through, concretely,
让我具体来说一下


74
00:03:30,60 --> 00:03:33,629
the workflow one example
of a supervised learning,
工作流程一个监督学习的例子
，

75
00:03:33,629 --> 00:03:35,430
labeling things kind of project.
给事物贴上标签的项目。

76
00:03:35,430 --> 00:03:38,250
If you want to build a system
to label restaurant reviews,
如果您想构建一个系统
来标记餐厅评论，

77
00:03:38,250 --> 00:03:41,129
you then collect a few data
points or collect a data set.
然后，您收集一些数据
点或收集数据集。

78
00:03:41,129 --> 00:03:43,740
Where it say, the
pastrami sandwich great,
上面说，
熏牛肉三明治很棒，

79
00:03:43,740 --> 00:03:45,330
say that is positive.
说这是积极的。

80
00:03:45,330 --> 00:03:47,790
Servers are slow,
that's negative.
服务器很慢，
这是负面的。

81
00:03:47,789 --> 00:03:50,340
My favorite chicken
curry, that's positive.
我最喜欢的鸡肉
咖喱，这是积极的。

82
00:03:50,340 --> 00:03:52,853
And here, I've shown
three data points,
在这里，我展示了
三个数据点，

83
00:03:52,853 --> 00:03:54,270
but you are building
this, you may
但你正在建设
这个，你可能

84
00:03:54,270 --> 00:03:56,340
get thousands of
data points like this
获得数千个
这样的数据点

85
00:03:56,340 --> 00:03:58,409
or thousands of training
examples, we call it.
或数千个训练
示例，我们称之为。

86
00:03:58,409 --> 00:04:01,139
And the workflow of a machine
learning project, of an AI
以及机器
人工智能学习项目的工作流程

87
00:04:01,139 --> 00:04:03,839
project is, you get
labeled data, maybe
项目是，你可能会得到
标记数据

88
00:04:03,840 --> 00:04:05,830
thousands of data points.
数千个数据点。

89
00:04:05,830 --> 00:04:08,640
Then you have an AI
entry team train an AI
然后你就有了一个人工智能
入门团队训练一个人工智能

90
00:04:08,639 --> 00:04:10,589
model to learn from this data.
模型从这些数据中学习。

91
00:04:10,590 --> 00:04:12,300
And then finally,
you would find,
最后，
你会发现，

92
00:04:12,300 --> 00:04:15,840
maybe a cloud service to
run the trained AI model.
也许是一个云服务来
运行经过训练的人工智能模型。

93
00:04:15,840 --> 00:04:18,689
And then you can feed it,
best bubble tea I've ever had,
然后你就可以喂它了，
我喝过的最好的珍珠奶茶，

94
00:04:18,689 --> 00:04:20,639
and that's positive sentiment.
这就是积极的情绪。

95
00:04:20,639 --> 00:04:23,610
And so, I think the
last decade was maybe
所以，我认为
过去十年可能是

96
00:04:23,610 --> 00:04:26,850
the decade of large scale
supervised learning.
大规模
监督学习的十年。

97
00:04:26,850 --> 00:04:29,910
What we found, starting
about 10, 15 years ago
我们发现了什么，从
大约 10、15 年前开始

98
00:04:29,910 --> 00:04:32,189
was if you were to
train a small AI model,
如果你要
训练一个小型人工智能模型，

99
00:04:32,189 --> 00:04:34,439
so train a small neural
network or small deep learning
所以训练一个小型神经
网络或小型深度学习

100
00:04:34,439 --> 00:04:36,449
algorithm, basically,
a small AI model,
算法，基本上，
一个小型人工智能模型，

101
00:04:36,449 --> 00:04:38,849
maybe not on a very
powerful computer,
也许不是在一台非常
功能强大的计算机上，

102
00:04:38,850 --> 00:04:41,585
then as you fed it more
data, its performance
然后当你给它提供更多
数据时，它的性能

103
00:04:41,584 --> 00:04:42,959
would get better
for a little bit
会好一点
一点点

104
00:04:42,959 --> 00:04:44,250
but then it would flatten out.
但随后它就会变平。

105
00:04:44,250 --> 00:04:46,19
It would plateau,
and it would stop
它会趋于稳定，
并且它会停止

106
00:04:46,19 --> 00:04:49,240
being able to use the data
to get better and better.
能够利用数据
变得越来越好。

107
00:04:49,240 --> 00:04:53,340
But if you were to train a very
large AI model, lots of compute
但如果你要训练一个非常
大型人工智能模型，需要大量计算

108
00:04:53,339 --> 00:04:58,199
on maybe powerful GPUs, then as
we scaled up the amount of data
在可能强大的 GPU 上，然后随着
我们扩大了数据量

109
00:04:58,199 --> 00:05:00,202
we gave the machine
learning model,
我们给出了机器
学习模型，

110
00:05:00,202 --> 00:05:01,619
its performance
would kind of keep
它的性能
会保持

111
00:05:01,620 --> 00:05:03,280
on getting better and better.
越来越好。

112
00:05:03,279 --> 00:05:06,0
So this is why when I started
and led the Google Brain
这就是为什么我开始
并领导 Google Brain

113
00:05:06,0 --> 00:05:09,329
team, the primary mission that
I directed the team to solve,
团队，
我指导团队解决的主要任务，

114
00:05:09,329 --> 00:05:11,79
at the time, was let's
just build really,
当时，让我们
真正构建，

115
00:05:11,79 --> 00:05:13,870
really large neural networks,
that we then fed a lot of data
非常大的神经网络，
然后我们输入大量数据

116
00:05:13,870 --> 00:05:14,370
to.
到。

117
00:05:14,370 --> 00:05:16,350
And that recipe,
fortunately, worked.
幸运的是，这个食谱很有效。

118
00:05:16,350 --> 00:05:19,650
And I think the idea of
driving large compute
我认为
驱动大型计算的想法

119
00:05:19,649 --> 00:05:23,819
and large scale of data, that
recipe's really helped us,
和大规模的数据，
食谱确实对我们有帮助，

120
00:05:23,819 --> 00:05:27,250
driven a lot of AI progress
over the last decade.
过去十年推动了人工智能的巨大进步
。

121
00:05:27,250 --> 00:05:29,790
So if that was the
last decade of AI,
所以如果那是人工智能的最后十年

122
00:05:29,790 --> 00:05:32,250
I think this decade
is turning out
我认为这十年
正在结果

123
00:05:32,250 --> 00:05:34,889
to be also doing everything
we had in supervised
也做我们在监督下所做的一切

124
00:05:34,889 --> 00:05:39,629
learning but adding to it the
exciting tool of generative AI.
学习，但添加
生成人工智能的令人兴奋的工具。

125
00:05:39,629 --> 00:05:42,389
So many of you,
maybe all of you,
你们很多人，
也许你们所有人，

126
00:05:42,389 --> 00:05:44,800
have played with ChatGPT
and Bard, and so on.
玩过ChatGPT
和Bard，等等。

127
00:05:44,800 --> 00:05:48,360
But just given a piece of
text, which you call a prompt,
但只要给出一段
文本，你称之为提示，

128
00:05:48,360 --> 00:05:50,879
like I love eating, if you
run this multiple times,
就像我喜欢吃东西一样，如果你
运行多次，

129
00:05:50,879 --> 00:05:53,939
maybe you get bagels cream
cheese or my mother's meatloaf
也许你会得到百吉饼奶油
奶酪或我妈妈的肉饼

130
00:05:53,939 --> 00:05:56,519
or out with friends,
and the AI system
或者和朋友出去，
和人工智能系统

131
00:05:56,519 --> 00:05:59,99
can generate output like that.
可以生成这样的输出。

132
00:05:59,100 --> 00:06:01,780
Given the amounts of buzz and
excitement about generative AI,
鉴于有关生成式人工智能的大量讨论和兴奋，

133
00:06:01,779 --> 00:06:05,69
I thought I'd take just half
a slide to say a little bit
我想我只需要一半
一张幻灯片来说明一点

134
00:06:05,69 --> 00:06:06,879
about how this works.
关于这是如何运作的。

135
00:06:06,879 --> 00:06:11,670
So it turns out that generative
AI, at least this type of text
事实证明，生成
AI，至少是这种类型的文本

136
00:06:11,670 --> 00:06:14,910
generation, the core of
it is using supervised
生成，
它的核心是使用监督

137
00:06:14,910 --> 00:06:18,420
learning that inputs output
mappings to repeatedly predict
学习输入输出
映射来重复预测

138
00:06:18,420 --> 00:06:19,540
the next word.
下一个词。

139
00:06:19,540 --> 00:06:22,270
And so, if your system
reads, on the internet,
因此，如果您的系统
在互联网上读取，

140
00:06:22,269 --> 00:06:25,379
a sentence like, my favorite
food is a bagel with cream
一句话，我最喜欢的
食物是奶油百吉饼

141
00:06:25,379 --> 00:06:29,310
cheese and lox, then this is
translated into a few data
奶酪和熏鲑鱼，那么这就是
翻译成一些数据

142
00:06:29,310 --> 00:06:32,834
points, where if it sees,
my favorite food is A,
点，如果看到的话，
我最喜欢的食物是A，

143
00:06:32,834 --> 00:06:37,109
in this case, try to guess that
the right next word was bagel
在这种情况下，尝试猜测
下一个单词是 bagel

144
00:06:37,110 --> 00:06:39,600
or my favorite food
is a bagel, try
或者我最喜欢的食物
是百吉饼，试试

145
00:06:39,600 --> 00:06:42,900
to guess the next word
is with, and similarly,
猜测下一个词
是 with，同样，

146
00:06:42,899 --> 00:06:45,569
if it sees that, in this
case, the right guess
如果它看到，在这种情况下
正确的猜测

147
00:06:45,569 --> 00:06:47,969
for the next word
would have been cream.
下一个词
将是奶油。

148
00:06:47,970 --> 00:06:50,940
So by taking texts that
you find on the internet
因此，通过获取
您在互联网上找到的文本

149
00:06:50,939 --> 00:06:54,930
or other sources, and by using
this input, output, supervised
或其他来源，并通过使用
此输入、输出、监督

150
00:06:54,930 --> 00:06:57,389
learning to try to repeatedly
predict the next word,
学习尝试反复
预测下一个单词，

151
00:06:57,389 --> 00:07:01,709
if you train a very large AI
system on hundreds of billions
如果你用数千亿训练一个非常大的人工智能
系统

152
00:07:01,709 --> 00:07:04,49
of words, or in the case
of the largest models, now
文字，或者在最大模型的情况下，现在

153
00:07:04,50 --> 00:07:07,329
more than a trillion words, then
you get a large language model
超过一万亿个单词，那么
你就得到了一个大的语言模型

154
00:07:07,329 --> 00:07:08,439
like ChatGPT.
就像 ChatGPT 一样。

155
00:07:08,439 --> 00:07:12,430
And there are additional, other
important technical details.
还有其他
重要的技术细节。

156
00:07:12,430 --> 00:07:14,139
I talked about
predicting the next word.
我谈到
预测下一个单词。

157
00:07:14,139 --> 00:07:15,909
Technically, these
systems predict
从技术上讲，这些
系统预测

158
00:07:15,910 --> 00:07:18,790
the next subword or part
of a word called a token,
称为标记的单词的下一个子词或部分
，

159
00:07:18,790 --> 00:07:22,120
and then there are other
techniques like RLHF
然后还有其他
技术，例如 RLHF

160
00:07:22,120 --> 00:07:25,899
for further tuning the AI output
to be more helpful, honest,
进一步调整人工智能输出
使其更加有帮助、更诚实，

161
00:07:25,899 --> 00:07:26,769
and harmless.
并且无害。

162
00:07:26,769 --> 00:07:30,219
But at the heart of it
is this using supervised
但其核心
是使用监督

163
00:07:30,220 --> 00:07:32,440
learning to repeatedly
predict the next word.
学习重复
预测下一个单词。

164
00:07:32,439 --> 00:07:36,339
That's really what's
enabling the exciting, really
这确实是
令人兴奋的事情，真的

165
00:07:36,339 --> 00:07:39,759
fantastic progress on
large language models.

大型语言模型取得了巨大进展。

166
00:07:39,759 --> 00:07:46,180
So while many people have
seen large language models
所以虽然很多人都见过
大型语言模型

167
00:07:46,180 --> 00:07:48,100
as a fantastic consumer tool.
作为一个很棒的消费工具。

168
00:07:48,100 --> 00:07:51,100
You can go to a website
like ChatGPT's website
您可以访问网站
例如 ChatGPT 的网站

169
00:07:51,100 --> 00:07:53,20
or Bard's or other
large language models
或 Bard 或其他
大型语言模型

170
00:07:53,19 --> 00:07:54,729
and use it as a fantastic tool.
并将其用作一个很棒的工具。

171
00:07:54,730 --> 00:07:57,189
There's one other trend, I
think is still underappreciated,
还有另一种趋势，我认为仍然没有得到充分重视，

172
00:07:57,189 --> 00:08:01,89
which is the power of
large language models,
这就是
大型语言模型的力量，

173
00:08:01,89 --> 00:08:06,129
not just as a consumer tool
but as a developer tool.
不仅仅是作为消费者工具
而是作为开发者工具。

174
00:08:06,129 --> 00:08:09,579
So it turns out that
there are applications
原来
有应用

175
00:08:09,579 --> 00:08:14,169
that used to take me months
to build, that a lot of people
过去花了我几个月的时间
来构建，很多人

176
00:08:14,170 --> 00:08:18,189
can now build much faster by
using a large language model.
现在可以通过使用大型语言模型来更快地构建。

177
00:08:18,189 --> 00:08:21,339
So specifically, the workflow
for supervised learning,
具体来说，监督学习的工作流程
，

178
00:08:21,339 --> 00:08:22,989
building the restaurant
review system,
建立餐厅
审核系统，

179
00:08:22,990 --> 00:08:26,500
say, would be that you need to
get a bunch of labeled data,
比如说，你需要
获取一堆标记数据，

180
00:08:26,500 --> 00:08:30,310
and maybe that takes a month, we
get a few thousand data points.
也许需要一个月的时间，我们
才能获得几千个数据点。

181
00:08:30,310 --> 00:08:33,668
And then have an AI
team train, and tune,
然后让人工智能
团队进行训练和调整，

182
00:08:33,668 --> 00:08:37,210
and really get optimized
performance on your AI model.
并真正在您的 AI 模型上获得优化
性能。

183
00:08:37,210 --> 00:08:39,610
Maybe that'll take three months.
也许这需要三个月的时间。

184
00:08:39,610 --> 00:08:42,70
Then find a cloud
service to run it.
然后找到一个云
服务来运行它。

185
00:08:42,70 --> 00:08:43,480
Make sure it's running robustly.
确保它运行稳健。

186
00:08:43,480 --> 00:08:45,279
Make sure it's
recognized, maybe that'll
确保它被
识别，也许这会

187
00:08:45,279 --> 00:08:46,759
take another three months.
再花三个月。

188
00:08:46,759 --> 00:08:50,590
So pretty realistic timeline
for building a commercial grade
对于构建商业级来说非常现实的时间表


189
00:08:50,590 --> 00:08:53,629
machine learning system
is like 6 to 12 months.
机器学习系统
大约需要 6 到 12 个月。

190
00:08:53,629 --> 00:08:57,610
And so teams I've led, we often
took roughly 6 to 12 months
所以我领导的团队，我们经常
花了大约 6 到 12 个月的时间

191
00:08:57,610 --> 00:08:59,259
to build and deploy
these systems.
构建和部署
这些系统。

192
00:08:59,259 --> 00:09:01,929
And some of them turned
out to be really valuable.
其中一些被证明是非常有价值的。

193
00:09:01,929 --> 00:09:05,379
But this is a realistic timeline
for building and deploying
但这是构建和部署的现实时间表


194
00:09:05,379 --> 00:09:08,259
a commercial grade AI system.
商业级人工智能系统。

195
00:09:08,259 --> 00:09:11,500
In contrast, with prompt-based
AI, where you write a prompt.
相比之下，使用基于提示的
AI，您可以在其中编写提示。

196
00:09:11,500 --> 00:09:13,409
This is what the
workflow looks like.
这就是
工作流程的样子。

197
00:09:13,409 --> 00:09:18,159
You can specify a prompt, that
takes maybe minutes or hours.
您可以指定提示，
可能需要几分钟或几小时。

198
00:09:18,159 --> 00:09:20,339
And then, you can
deploy it to the cloud,
然后，您可以
将其部署到云端，

199
00:09:20,340 --> 00:09:22,750
and that takes
maybe hours or days.
这可能需要
数小时或数天。

200
00:09:22,750 --> 00:09:24,929
So there are now
certain AI applications
所以现在有了
某些AI应用

201
00:09:24,929 --> 00:09:29,169
that used to take me,
literally, six months,
这曾经花了我，
字面意思，六个月，

202
00:09:29,169 --> 00:09:32,309
maybe a year to build, that
many teams around the world
也许需要一年的时间来建立
世界各地的许多团队

203
00:09:32,309 --> 00:09:34,199
can now build in maybe a week.
现在大约可以在一周内建成。

204
00:09:34,200 --> 00:09:36,900
And I think this is
already starting,
我认为这
已经开始了，

205
00:09:36,899 --> 00:09:38,730
but the best is
still yet to come.
但最好的还在后面
。

206
00:09:38,730 --> 00:09:41,940
This is starting to open
up a flood of a lot more AI
这开始开启
更多人工智能的洪流

207
00:09:41,940 --> 00:09:44,530
applications that can be
built by a lot of people.
可以由很多人构建的应用程序。

208
00:09:44,529 --> 00:09:46,409
So I think many people
still underestimate
所以我觉得很多人
还是低估了

209
00:09:46,409 --> 00:09:49,929
the magnitude of the flood
of custom AI applications
定制人工智能应用程序的泛滥程度


210
00:09:49,929 --> 00:09:51,939
that I think is going
to come down the pipe.
我认为这将会
落下帷幕。

211
00:09:51,940 --> 00:09:54,780
Now, I know you
probably were not
现在，我知道你
可能不是

212
00:09:54,779 --> 00:09:58,500
expecting me to write
code in this presentation,
期待我在这个演示文稿中编写
代码，

213
00:09:58,500 --> 00:10:02,350
but that's what I'm going to do.
但这就是我要做的。

214
00:10:02,350 --> 00:10:05,250
So it turns out,
this is all the code
事实证明，
这就是全部代码

215
00:10:05,250 --> 00:10:09,889
that I need in order to
write a sentiment classifier.
我需要
编写情感分类器。

216
00:10:09,889 --> 00:10:11,297
So I'm going to--
所以我要——

217
00:10:11,297 --> 00:10:12,879
some of you will
know Python, I guess.
我猜你们中的一些人会
了解Python。

218
00:10:12,879 --> 00:10:15,399
Import some tools
from OpenAI, and then
从OpenAI导入一些工具
，然后

219
00:10:15,399 --> 00:10:19,120
add this prompt, that says,
classify the text below
添加此提示，即
对下面的文本进行分类

220
00:10:19,120 --> 00:10:21,159
delimited by three
dashes as having
由三个
破折号分隔为具有

221
00:10:21,159 --> 00:10:26,269
either a positive or
negative sentiment.
积极或
消极情绪。

222
00:10:26,269 --> 00:10:32,304
[INAUDIBLE],, I had a fantastic
time at Stanford GSB.
[听不清]，我在斯坦福大学商学院度过了一段美妙的
时光。

223
00:10:36,519 --> 00:10:40,929
Learnt a lot, and also
made great new friends.
学到了很多东西，也
结识了很棒的新朋友。

224
00:10:40,929 --> 00:10:41,529
All right.
好的。

225
00:10:41,529 --> 00:10:42,602
So that's my prompt.
这就是我的提示。

226
00:10:42,602 --> 00:10:44,19
And then I'm just
going to run it.
然后我就
运行它。

227
00:10:44,19 --> 00:10:45,227
And I've never run it before.
而且我以前从未运行过它。

228
00:10:45,227 --> 00:10:46,162
So I really hope--
所以我真的希望——

229
00:10:46,163 --> 00:10:47,830
thank goodness, it
got the right answer.
谢天谢地，它
得到了正确的答案。

230
00:10:47,830 --> 00:10:50,626
[APPLAUSE]
[掌声]

231
00:10:52,490 --> 00:10:54,700
And this is literally
all the code
这就是字面上的
所有代码

232
00:10:54,700 --> 00:10:57,200
it takes to build a
sentiment classifier.
需要构建一个
情感分类器。

233
00:10:57,200 --> 00:11:00,370
And so, today, developers
around the world
因此，今天，世界各地的开发者


234
00:11:00,370 --> 00:11:02,259
can take, literally,
maybe 10 minutes
从字面上看，可能需要 
也许 10 分钟

235
00:11:02,259 --> 00:11:04,899
to build a system like this.
建立一个这样的系统。

236
00:11:04,899 --> 00:11:11,120
And that's a very
exciting development.
这是一个非常
令人兴奋的发展。

237
00:11:11,120 --> 00:11:16,909
So one of the things
I've been working on
所以其中一件事
我一直在努力

238
00:11:16,909 --> 00:11:21,500
was trying to teach
online classes about how
试图在在线课程上教授
如何

239
00:11:21,500 --> 00:11:23,269
to use prompting, not
just as a consumer
使用提示，而不是
仅仅作为消费者

240
00:11:23,269 --> 00:11:24,889
tool but as a developer too.
工具，但也作为开发人员。

241
00:11:24,889 --> 00:11:28,399
So just talking about
the technology landscape,
所以只是谈论
技术前景，

242
00:11:28,399 --> 00:11:32,209
let me now share my
thoughts on what are some
现在让我分享我的想法


243
00:11:32,210 --> 00:11:34,960
of the AI opportunities I see.
我看到的人工智能机会。

244
00:11:34,960 --> 00:11:38,680
This shows what I think is
the value of different AI
这说明了我认为的
不同AI的价值

245
00:11:38,679 --> 00:11:41,589
technologies today, and
I'll talk about three years
当今的技术，以及
我将谈论三年

246
00:11:41,590 --> 00:11:42,320
from now.
现在起。

247
00:11:42,320 --> 00:11:46,90
But the vast majority of
financial value from AI today
但当今人工智能的绝大多数
财务价值

248
00:11:46,90 --> 00:11:48,220
is, I think,
supervised learning,
我认为，
监督学习，

249
00:11:48,220 --> 00:11:50,590
where for a single
company like Google
对于像 Google 这样的单一公司来说在哪里

250
00:11:50,590 --> 00:11:53,649
can be worth more than
$100 billion US a year.
每年价值可超过 
1000 亿美元。

251
00:11:53,649 --> 00:11:56,590
And also, there are
millions of developers
而且，还有
数以百万计的开发者

252
00:11:56,590 --> 00:11:58,670
building supervised
learning applications.
构建监督
学习应用程序。

253
00:11:58,669 --> 00:12:01,389
So it's already massively
valuable, and also
所以它已经非常有价值了，而且

254
00:12:01,389 --> 00:12:03,490
with tremendous momentum
behind it just because
气势磅礴
背后只是因为

255
00:12:03,490 --> 00:12:06,220
of the sheer effort in
finding applications

寻找应用程序的巨大努力

256
00:12:06,220 --> 00:12:07,779
and building applications.
和构建应用程序。

257
00:12:07,779 --> 00:12:11,559
And then, generative AI is the
really exciting new entrant,
然后，生成式人工智能是
真正令人兴奋的新进入者，

258
00:12:11,559 --> 00:12:13,871
which is much smaller right now.
现在要小得多。

259
00:12:13,871 --> 00:12:15,329
And then, there
are the other tools
然后，还有
其他工具

260
00:12:15,330 --> 00:12:18,416
that I'm including
for completeness.
为了完整起见，我将其包括在内。

261
00:12:18,416 --> 00:12:21,600
If the size of these circles
represent the value today,
如果这些圆圈的大小
代表今天的价值，

262
00:12:21,600 --> 00:12:24,540
this is what I think it
might grow to in three years.
我认为
三年后可能会发展到这个程度。

263
00:12:24,539 --> 00:12:27,659
So supervised learning,
already really massive,
所以监督学习，
已经非常庞大了，

264
00:12:27,659 --> 00:12:29,819
may double, say,
in the next three
比如说，在接下来的三个时间里可能会翻倍


265
00:12:29,820 --> 00:12:32,910
years, from truly massive
to even more massive.
年，从真正的巨大
到更加巨大。

266
00:12:32,909 --> 00:12:36,312
And generative AI, which is
much smaller today, I think,
我认为，今天的生成式人工智能
要小得多，

267
00:12:36,312 --> 00:12:38,730
will much more than double in
the next three years because

未来三年将增加一倍以上，因为

268
00:12:38,730 --> 00:12:41,279
of the number-- the amount
of developer interest,
数量--开发者利息金额
，

269
00:12:41,279 --> 00:12:43,769
the amount of venture
capital investments,
风险
资本投资额，

270
00:12:43,769 --> 00:12:46,679
the number of large corporates
exploring applications.
大型企业的数量
探索应用程序。

271
00:12:46,679 --> 00:12:48,299
And I also just
want to point out,
我还想指出


272
00:12:48,299 --> 00:12:50,429
three years is a very
short time horizon.
三年是一个非常
很短的时间跨度。

273
00:12:50,429 --> 00:12:53,349
If it continues to compound
in anything near this rate,
如果它继续以接近这个速度的速度复合，

274
00:12:53,350 --> 00:12:56,560
then in six years, it will
be even vastly larger.
那么六年后，它将会
变得更大。

275
00:12:56,559 --> 00:13:00,239
But this light shaded
region in green or orange,
但是这个浅色阴影
区域呈绿色或橙色，

276
00:13:00,240 --> 00:13:03,90
that light shaded region
is where the opportunity is
浅色阴影区域
就是机会所在

277
00:13:03,90 --> 00:13:06,660
for either new startups or for
large companies, incumbents,
无论是新的初创公司还是
大公司、现有企业，

278
00:13:06,659 --> 00:13:09,947
to create and to
enjoy value capture.
创造并
享受价值捕获。

279
00:13:09,947 --> 00:13:12,29
But one thing I hope you
take away from this slide
但我希望您从这张幻灯片中学到一件事


280
00:13:12,29 --> 00:13:13,889
is that all of
these technologies
是所有
这些技术

281
00:13:13,889 --> 00:13:15,730
are general purpose
technologies.
是通用
技术。

282
00:13:15,730 --> 00:13:17,940
So in the case of
supervised learning,
所以在
监督学习的情况下，

283
00:13:17,940 --> 00:13:21,340
a lot of the work that had to
be done over the last decade,
过去十年中必须完成的许多工作，

284
00:13:21,340 --> 00:13:23,290
but is continuing
for the next decade,
但在接下来的十年里将会继续


285
00:13:23,289 --> 00:13:27,309
is to identify and to execute
on the concrete use cases.
是识别并执行
具体用例。

286
00:13:27,309 --> 00:13:32,259
And that process is also
kicking off for generative AI.
而这个过程也正在为生成人工智能而拉开帷幕。

287
00:13:32,259 --> 00:13:34,9
So for this part of
the presentation,
因此，对于
演示的这一部分，

288
00:13:34,9 --> 00:13:36,789
I hope you take away from it
that general purpose technology
我希望你能从中汲取
通用技术

289
00:13:36,789 --> 00:13:39,370
is a useful for many
different tasks, lot of value
对于许多
不同的任务很有用，有很多价值

290
00:13:39,370 --> 00:13:41,379
remains to be created
using supervised learning.
仍有待使用监督学习来创建
。

291
00:13:41,379 --> 00:13:44,889
And even though, we're nowhere
near finishing figuring out
尽管如此，我们还远远没有
接近完成弄清楚

292
00:13:44,889 --> 00:13:47,679
the exciting use cases
of supervised learning,
监督学习令人兴奋的用例
，

293
00:13:47,679 --> 00:13:51,309
we have this other fantastic
tool of generative AI, which
我们还有另一个很棒的
生成人工智能工具，它

294
00:13:51,309 --> 00:13:55,389
further expands the set of
things we can now do using AI.
进一步扩展了我们现在可以使用人工智能做的事情。

295
00:13:55,389 --> 00:13:57,580
But one caveat, which
is that there will be
但有一点需要注意，
 将会有

296
00:13:57,580 --> 00:13:59,540
short term fads along the way.
一路上的短期时尚。

297
00:13:59,539 --> 00:14:02,439
So I don't know if
some of you might
所以我不知道你们中的一些人是否会


298
00:14:02,440 --> 00:14:04,750
remember the app called Lensa.
还记得名为 Lensa 的应用程序吗？

299
00:14:04,750 --> 00:14:06,759
This is the app
that will let you
这个应用程序
可以让您

300
00:14:06,759 --> 00:14:08,389
upload pictures of
yourself, and then
上传
您自己的照片，然后

301
00:14:08,389 --> 00:14:09,970
will render a cool
picture of you
将为您呈现一张很酷的
照片

302
00:14:09,970 --> 00:14:12,730
as an astronaut or a
scientist or something.
作为一名宇航员或
科学家或其他什么。

303
00:14:12,730 --> 00:14:14,920
And it was a good idea
and people liked it.
这是个好主意
人们喜欢它。

304
00:14:14,919 --> 00:14:17,319
And its revenue just took
off like crazy like that,
它的收入就这样疯狂地起飞
，

305
00:14:17,320 --> 00:14:19,160
through last December.
到去年12月。

306
00:14:19,159 --> 00:14:20,990
And then it did that.
然后它就这么做了。

307
00:14:20,990 --> 00:14:25,70
And that's because Lensa
was-- it was a good idea.
那是因为Lensa
是——这是一个好主意。

308
00:14:25,70 --> 00:14:26,60
People liked it.
人们喜欢它。

309
00:14:26,59 --> 00:14:28,699
But it was a relatively
thin software layer
但它是一个相对薄弱的软件层

310
00:14:28,700 --> 00:14:31,879
on top of someone else's
really powerful APIs.
在其他人的
真正强大的 API 之上。

311
00:14:31,879 --> 00:14:34,909
And so even though it
was a useful product,
因此，尽管它
是一个有用的产品，

312
00:14:34,909 --> 00:14:39,500
it was in a defensible business.
这是一个可以防御的行业。

313
00:14:39,500 --> 00:14:42,350
And when I think
about apps like Lensa,
当我想到像 Lensa 这样的应用程序时，

314
00:14:42,350 --> 00:14:45,800
I'm actually reminded of when
Steve Jobs gave us the iPhone.
我实际上想起了 
史蒂夫·乔布斯给我们 iPhone 的时候。

315
00:14:45,799 --> 00:14:49,99
Shortly after,
someone wrote an app
不久之后，
有人写了一个应用程序

316
00:14:49,100 --> 00:14:54,290
that I paid $1.99 for, to
do this, to turn on the LED,
我花了 1.99 美元来
这样做，打开 LED，

317
00:14:54,289 --> 00:14:56,480
to turn the phone
into a flashlight.
将手机
变成手电筒。

318
00:14:56,480 --> 00:14:59,810
And that was also a good
idea to write an app
这也是编写应用程序的好主意


319
00:14:59,809 --> 00:15:01,909
to turn on the LED
light, but it also
打开 LED 
 灯，但它也

320
00:15:01,909 --> 00:15:03,740
wasn't a defensible long term--
不是一个可以防御的长期目标——

321
00:15:03,740 --> 00:15:05,810
also didn't create
very long term value
也没有创造
非常长期的价值

322
00:15:05,809 --> 00:15:08,689
because it was easily
replicated, and underpriced,
因为它很容易被复制，而且价格低廉，

323
00:15:08,690 --> 00:15:11,390
and eventually
incorporated into iOS.
并最终
并入iOS。

324
00:15:11,389 --> 00:15:14,509
But with the rise of iOS,
with the rise of iPhone,
但随着iOS的崛起，
随着iPhone的崛起，

325
00:15:14,509 --> 00:15:17,629
someone also figured out how
to build things like Uber,
有人还弄清楚了如何
构建像 Uber 这样的东西，

326
00:15:17,629 --> 00:15:19,620
and Airbnb, and Tinder.
以及 Airbnb 和 Tinder。

327
00:15:19,620 --> 00:15:22,169
The very long term, very
defensible businesses
从长远来看，非常
有防御性的企业

328
00:15:22,169 --> 00:15:24,939
that created sustaining value.
创造了持续价值。

329
00:15:24,940 --> 00:15:27,900
And I think, with the
rise of generative AI
我认为，随着生成式人工智能的兴起

330
00:15:27,899 --> 00:15:31,529
or the rise of new AI
tools, I think, really,
或者新的人工智能工具的兴起，我认为，真的，

331
00:15:31,529 --> 00:15:33,360
what excites me
is the opportunity
让我兴奋的
是机会

332
00:15:33,360 --> 00:15:37,950
to create those really deep,
really hard applications that
创建那些非常深入、
非常困难的应用程序

333
00:15:37,950 --> 00:15:42,230
hopefully can create
very long term value.
希望能够创造
非常长期的价值。

334
00:15:42,230 --> 00:15:43,840
So the first trend
I want to share
那么第一个趋势
我想分享

335
00:15:43,840 --> 00:15:45,620
is AI is a general
purpose technology.
人工智能是一种通用
目的技术。

336
00:15:45,620 --> 00:15:47,452
And a lot of the work
that lies ahead of us,
还有许多工作
摆在我们面前，

337
00:15:47,452 --> 00:15:50,995
is to find the very diverse
use cases and to build them.
就是找到非常多样化的
用例并构建它们。

338
00:15:50,995 --> 00:15:53,289
There's a second
trend I want to share
我想分享第二个
趋势

339
00:15:53,289 --> 00:15:56,620
with you, which relates to why
AI isn't more widely adopted
和你在一起，这关系到为什么
人工智能没有被更广泛地采用

340
00:15:56,620 --> 00:15:57,340
yet.
然而。

341
00:15:57,340 --> 00:15:59,680
It feels like a bunch of us
have been talking about AI
感觉就像我们一群人
一直在谈论人工智能

342
00:15:59,679 --> 00:16:01,519
for 15 years or something.
15年什么的。

343
00:16:01,519 --> 00:16:04,449
But if you look at where
the value of AI is today,
但如果你看看今天人工智能的价值在哪里，

344
00:16:04,450 --> 00:16:07,509
a lot of it is still very
concentrated in consumer
其中很多仍然非常
集中在消费者身上

345
00:16:07,509 --> 00:16:08,679
software internet.
软件互联网。

346
00:16:08,679 --> 00:16:11,799
Once you got outside tech or
consumer software internet,
一旦您接触到外部技术或
消费软件互联网，

347
00:16:11,799 --> 00:16:15,939
there's some AI adoption
but it all feels very early.
有一些人工智能的采用
但这一切感觉还为时过早。

348
00:16:15,940 --> 00:16:17,710
So why is that?
那么这是为什么呢？

349
00:16:17,710 --> 00:16:19,480
It turns out, if
you were to take
事实证明，如果
你要采取

350
00:16:19,480 --> 00:16:21,879
all current and
potential AI projects,
所有当前和
潜在的人工智能项目，

351
00:16:21,879 --> 00:16:24,879
and sort them in
decreasing order of value,
并按照
值的递减顺序对它们进行排序，

352
00:16:24,879 --> 00:16:27,580
then to the left of this curve,
of the head of this curve,
然后到这条曲线的左边，
这条曲线的头部，

353
00:16:27,580 --> 00:16:31,720
are the multi-billion dollar
projects like advertising
是像广告这样的数十亿美元的项目吗？

354
00:16:31,720 --> 00:16:35,529
or web search or for e-commerce
product recommendations
或网络搜索或电子商务
产品推荐

355
00:16:35,529 --> 00:16:37,209
or company like Amazon.
或像亚马逊这样的公司。

356
00:16:37,210 --> 00:16:40,333
And it turns out that
about 10, 15 years ago,
事实证明
大约10、15年前，

357
00:16:40,332 --> 00:16:41,750
[? there's ?] my
friends and I, we
[？有吗？] 我
朋友和我，我们

358
00:16:41,750 --> 00:16:44,480
figured out a recipe
for how to hire, say,
找到了一个如何招聘的秘诀
，比如说，

359
00:16:44,480 --> 00:16:47,690
100 engineers to write
one piece of software
100 名工程师编写
一个软件

360
00:16:47,690 --> 00:16:50,450
to serve more relevant
ads, and apply that one
投放更相关的
广告，并应用该广告

361
00:16:50,450 --> 00:16:52,460
piece of software
to a billion users,
一个软件
给十亿用户，

362
00:16:52,460 --> 00:16:54,389
and generate massive
financial value.
并产生巨大的
财务价值。

363
00:16:54,389 --> 00:16:56,299
So that works.
这样就可以了。

364
00:16:56,299 --> 00:16:59,689
But once you go outside
consumer software internet,
但是一旦你走出去
消费软件互联网，

365
00:16:59,690 --> 00:17:03,110
hardly anyone has 100
million or a billion users
几乎没有人拥有 100
百万或十亿用户

366
00:17:03,110 --> 00:17:07,289
that you can write and apply
one piece of software to.
您可以编写并应用
一个软件。

367
00:17:07,289 --> 00:17:09,868
So once you go to
other industries,
所以一旦你去了
其他行业，

368
00:17:09,868 --> 00:17:12,328
as we go from the head
of this curve on the left
当我们从左边这条曲线的头部开始


369
00:17:12,328 --> 00:17:15,868
over to the long tail, these
are some of the projects I see,
说到长尾，这些
是我看到的一些项目，

370
00:17:15,868 --> 00:17:17,639
and I'm excited about.
我很兴奋。

371
00:17:17,640 --> 00:17:20,369
I was working with
a pizza maker that
我正在与
一家披萨店合作

372
00:17:20,368 --> 00:17:24,348
was taking pictures of the pizza
they were making because they
正在给他们做的披萨拍照
因为他们

373
00:17:24,348 --> 00:17:26,848
needed to do things like make
sure that the cheese is spread
需要做一些事情，例如确保
确保奶酪铺好

374
00:17:26,848 --> 00:17:27,700
evenly.
均匀。

375
00:17:27,700 --> 00:17:31,19
So this is about a
$5 million project.
这是一个大约 
 500 万美元的项目。

376
00:17:31,19 --> 00:17:35,39
But that recipe of hiring a
hundred engineers or dozens
但是雇用
数百名或数十名工程师的秘诀

377
00:17:35,39 --> 00:17:37,409
of engineers to
work on a $5 million
工程师
工作价值 500 万美元

378
00:17:37,410 --> 00:17:40,259
project, that
doesn't make sense.
项目，那
没有意义。

379
00:17:40,259 --> 00:17:42,549
Or there's another
great example.
或者还有另一个
很好的例子。

380
00:17:42,549 --> 00:17:44,669
Working with a
agriculture company
与
农业公司合作

381
00:17:44,670 --> 00:17:47,880
that with them, we figured
out that if we use cameras
和他们一起，我们发现
如果我们使用相机

382
00:17:47,880 --> 00:17:49,800
to find out how
tall is the wheat,
找出小麦
有多高，

383
00:17:49,799 --> 00:17:51,299
and wheat is often
bent over because
小麦经常
弯腰，因为

384
00:17:51,299 --> 00:17:53,309
of wind or rain or
something, and we
风或雨或
什么，而我们

385
00:17:53,309 --> 00:17:55,289
can chop off the wheat
at the right height,
可以在合适的高度砍掉小麦
，

386
00:17:55,289 --> 00:17:57,990
then that results in more
food for the farmer to sell,
然后这会导致更多
农民可以出售的食物，

387
00:17:57,990 --> 00:17:59,980
and is also better
for the environment.
而且对环境也更好
。

388
00:17:59,980 --> 00:18:02,849
But this is another
$5 million project,
但这是另一个
500万美元的项目，

389
00:18:02,849 --> 00:18:06,299
that that old recipe of
hiring a large group of highly
那个古老的秘诀
雇佣一大群高度

390
00:18:06,299 --> 00:18:08,769
skilled engineers to work
on this one project, that
熟练的工程师在这个项目上工作


391
00:18:08,769 --> 00:18:10,150
doesn't make sense.
没有意义。

392
00:18:10,150 --> 00:18:12,730
And similarly materials
grading, cloth grading,
同样的材料
分级，布料分级，

393
00:18:12,730 --> 00:18:15,440
sheet metal grading,
many projects like this.
钣金分级，
很多这样的项目。

394
00:18:15,440 --> 00:18:18,100
So whereas to the left,
in the head of this curve,
因此，在左边，
 在这条曲线的头部，

395
00:18:18,99 --> 00:18:20,349
there's a small
number of, let's say,
有一小部分
数量，比方说，

396
00:18:20,349 --> 00:18:22,149
multi-billion dollar
projects, and we
数十亿美元
项目，而我们

397
00:18:22,150 --> 00:18:24,910
know how to execute
those delivering value.
知道如何执行
那些创造价值的事情。

398
00:18:24,910 --> 00:18:28,600
In other industries, I'm
seeing a very long tail
在其他行业，我看到了一条很长的尾巴

399
00:18:28,599 --> 00:18:31,269
of tens of thousands,
of let's call them,
数以万计的，
让我们称他们为，

400
00:18:31,269 --> 00:18:33,940
$5 million projects,
that until now,
500万美元的项目，
到目前为止，

401
00:18:33,940 --> 00:18:35,799
have been very
difficult to execute on
执行起来非常困难


402
00:18:35,799 --> 00:18:38,710
because of the high
cost of customization.
因为定制成本很高
。

403
00:18:38,710 --> 00:18:40,450
The trend that I
think is exciting
我
认为令人兴奋的趋势

404
00:18:40,450 --> 00:18:44,259
is that the AI community has
been building better tools that
是人工智能社区一直在构建更好的工具

405
00:18:44,259 --> 00:18:46,569
lets us aggregate
these use cases,
让我们聚合
这些用例，

406
00:18:46,569 --> 00:18:49,849
and make it easy for the end
user to do the customization.
并使最终
用户可以轻松进行定制。

407
00:18:49,849 --> 00:18:51,879
So specifically,
I'm seeing a lot
具体来说，
我看到了很多

408
00:18:51,880 --> 00:18:55,390
of exciting low code
and no code tools, that
令人兴奋的低代码
并且没有代码工具，

409
00:18:55,390 --> 00:18:58,670
enable the user to
customize the AI system.
使用户能够
定制AI系统。

410
00:18:58,670 --> 00:19:00,789
What this means
is instead of me,
这意味着
而不是我，

411
00:19:00,789 --> 00:19:04,269
needing to worry that much
about pictures of pizza,
需要担心那么多
披萨的图片，

412
00:19:04,269 --> 00:19:05,529
we have tools--
我们有工具——

413
00:19:05,529 --> 00:19:07,990
we're starting to see
tools that can enable
我们开始看到
可以启用的工具

414
00:19:07,990 --> 00:19:10,900
the IT department of
the pizza making factory

披萨制作工厂的IT部门

415
00:19:10,900 --> 00:19:13,600
to train AI system on
their own pictures of pizza
在
他们自己的披萨图片上训练人工智能系统

416
00:19:13,599 --> 00:19:16,459
to realize this $5
million worth of value.
实现价值 5
百万美元的价值。

417
00:19:16,460 --> 00:19:19,305
And by the way, the
pictures of pizza,
顺便说一下，
披萨的图片，

418
00:19:19,305 --> 00:19:20,680
they don't exist
on the internet.
它们在互联网上不存在
。

419
00:19:20,680 --> 00:19:23,480
So Google and Bing don't have
access to these pictures,
所以 Google 和 Bing 无法
访问这些图片，

420
00:19:23,480 --> 00:19:25,750
we need tools that can
be used by, really,
我们需要可以
使用的工具，真的，

421
00:19:25,750 --> 00:19:28,700
the pizza factory themselves,
to build, and deploy,
披萨工厂自己，
建造和部署，

422
00:19:28,700 --> 00:19:31,630
and maintain their own
custom AI system that works
并维护自己的
有效的自定义人工智能系统

423
00:19:31,630 --> 00:19:33,910
on their own pictures of pizza.
在他们自己的披萨照片上。

424
00:19:33,910 --> 00:19:39,9
And broadly, the technology
for enabling this, some of it
从广义上讲，实现这一点的技术，其中一些

425
00:19:39,9 --> 00:19:42,579
is prompting, text
prompting, visual prompting,
正在提示、文本
提示、视觉提示、

426
00:19:42,579 --> 00:19:45,429
but really, large language
models and similar tools
但实际上，大型语言
模型和类似的工具

427
00:19:45,430 --> 00:19:49,509
like that or a technology
called data-centric AI, whereby,
像这样的技术
称为以数据为中心的人工智能，其中，

428
00:19:49,509 --> 00:19:54,950
instead of asking the pizza
factory to write a lot of code,
而不是要求披萨
工厂编写大量代码，

429
00:19:54,950 --> 00:19:59,140
which is challenging, we can
ask them to provide data which
这是具有挑战性的，我们可以
要求他们提供数据

430
00:19:59,140 --> 00:20:01,840
turns out to be more feasible.
事实证明更加可行。

431
00:20:01,839 --> 00:20:03,779
And I think the second
trend is important,
我认为第二个
趋势很重要，

432
00:20:03,779 --> 00:20:06,599
because I think this is a key
part of the recipe for taking
因为我认为这是服用配方的关键
部分

433
00:20:06,599 --> 00:20:09,179
the value of AI, which
so far still feels
AI的价值，至今
仍然让人感觉

434
00:20:09,180 --> 00:20:12,29
very concentrated in the tech
world and the consumer software
非常集中于科技
世界和消费软件

435
00:20:12,29 --> 00:20:15,899
internet world, and pushing this
out to all industries, really
互联网世界，并将其推广到所有行业，真的

436
00:20:15,900 --> 00:20:17,820
to the rest of the
economy, which--
到其他经济体
，其中——

437
00:20:17,819 --> 00:20:20,220
sometimes it's easy to forget,
the rest of the economy
有时很容易忘记，
经济的其他部分

438
00:20:20,220 --> 00:20:23,809
is much bigger than
the tech world.
比
科技世界大得多。

439
00:20:23,809 --> 00:20:27,549
So the two trends I shared,
AI as a general purpose
所以我分享的两个趋势，
AI 作为通用目的

440
00:20:27,549 --> 00:20:29,859
technology, lots of
concrete use cases
技术，大量
具体用例

441
00:20:29,859 --> 00:20:33,759
to be realized as well as low
code, no code, easy to use
实现也是低
代码，无代码，简单易用

442
00:20:33,759 --> 00:20:37,990
tools, enabling AI to be
deployed in more industries.
工具，让AI能够
部署到更多行业。

443
00:20:37,990 --> 00:20:41,210
How do we go after
these opportunities?
我们如何抓住
这些机会？

444
00:20:41,210 --> 00:20:44,29
So about five years ago, there
was a puzzle I wanted to solve,
大约五年前，我想解决一个难题，

445
00:20:44,29 --> 00:20:44,529
which is--
这是——

446
00:20:44,529 --> 00:20:47,599
I felt that many valuable AI
projects are now possible.
我觉得很多有价值的人工智能
项目现在都是可能的。

447
00:20:47,599 --> 00:20:49,779
And I was thinking, how
do we get them done?
我在想，我们如何
完成它们？

448
00:20:49,779 --> 00:20:54,399
And having led teams in
Google, and Baidu, in big tech
并曾在
谷歌和百度等大型科技公司领导过团队

449
00:20:54,400 --> 00:20:57,340
companies, I had a
hard time figuring out
公司，我很难弄清楚


450
00:20:57,339 --> 00:21:01,0
how I could operate a
team in a big tech company
我如何在一家大型科技公司运营
团队

451
00:21:01,0 --> 00:21:04,750
to go after a very diverse set
of opportunities in everything
在每件事上追求非常多样化的机会


452
00:21:04,750 --> 00:21:08,102
from maritime shipping to
education to financial services
从海运到
教育到金融服务

453
00:21:08,102 --> 00:21:09,310
to healthcare, and on and on.
医疗保健等等。

454
00:21:09,309 --> 00:21:11,980
It's just very diverse
use cases, very diverse
它只是非常多样化
用例，非常多样化

455
00:21:11,980 --> 00:21:15,430
go to markets, and very
diverse customer bases
去市场，以及非常
多样化的客户群

456
00:21:15,430 --> 00:21:17,560
and applications.
和应用程序。

457
00:21:17,559 --> 00:21:20,769
And I felt that the
most efficient way
我觉得
最有效的方法

458
00:21:20,769 --> 00:21:22,389
to do this would
be if we can start
这样做的话
如果我们可以开始的话

459
00:21:22,390 --> 00:21:25,370
a lot of different companies
to pursue these very
很多不同的公司
追求这些非常

460
00:21:25,369 --> 00:21:27,29
diverse opportunities.
多样化的机会。

461
00:21:27,29 --> 00:21:29,509
So that's why I ended up
starting AI Fund, which
这就是为什么我最终
启动了人工智能基金，

462
00:21:29,509 --> 00:21:31,849
is a venture studio
that builds startups
是一家风险投资工作室
建立初创公司

463
00:21:31,849 --> 00:21:34,879
to pursue a diverse set
of AI opportunities.
追求多样化的人工智能机会。

464
00:21:34,880 --> 00:21:37,580
And, of course, in addition
to lots of startups,
当然，除了
许多初创公司，

465
00:21:37,579 --> 00:21:39,769
incumbent companies
also have a lot
现有企业
也有很多

466
00:21:39,769 --> 00:21:43,500
of opportunities to integrate
AI into existing businesses.
将
人工智能融入现有业务的机会。

467
00:21:43,500 --> 00:21:47,359
In fact, one pattern I'm seeing
for incumbent businesses is
事实上，我看到的现有企业的一种模式是

468
00:21:47,359 --> 00:21:52,490
distribution is often one of
the significant advantages
分布往往是
显着优势之一

469
00:21:52,490 --> 00:21:55,99
of incumbent companies, if
they play their cards right,
现有公司，如果
他们打得好，

470
00:21:55,99 --> 00:21:58,339
can allow them to integrate
AI into their products,
可以让他们将
人工智能集成到他们的产品中，

471
00:21:58,339 --> 00:21:59,629
quite efficiently.
相当有效。

472
00:21:59,630 --> 00:22:02,610
But just to be concrete,
where are the opportunities?
但具体来说，
机会在哪里？

473
00:22:02,609 --> 00:22:06,199
So I think of this as-- this is
what I think of as an AI stack.
所以我认为这就是我所认为的人工智能堆栈。

474
00:22:06,200 --> 00:22:09,680
At the bottom level is the
hardware, semiconductor layer.
最底层是
硬件、半导体层。

475
00:22:09,680 --> 00:22:13,220
Fantastic opportunities there,
but very capital intensive,
那里有绝佳的机会，
但资本密集型，

476
00:22:13,220 --> 00:22:14,509
very concentrated.
非常集中。

477
00:22:14,509 --> 00:22:16,849
So needs a lot of resources,
relatively few winners.
因此需要大量资源，
获胜者相对较少。

478
00:22:16,849 --> 00:22:18,809
So some people can
and should play there.
所以有些人可以
并且应该在那里玩。

479
00:22:18,809 --> 00:22:21,19
I personally don't like
to play there myself.
我个人不喜欢
自己去那里玩。

480
00:22:21,19 --> 00:22:22,879
There's also the
infrastructure layer.
还有
基础设施层。

481
00:22:22,880 --> 00:22:26,120
Also fantastic opportunities,
but very capital intensive,
也是绝佳的机会，
但资本密集型，

482
00:22:26,119 --> 00:22:27,319
very concentrated.
非常集中。

483
00:22:27,319 --> 00:22:30,809
So I tend not to play
there myself, either.
所以我自己也不会去那里玩。

484
00:22:30,809 --> 00:22:33,200
And then there's the
developer tool layer.
然后是
开发者工具层。

485
00:22:33,200 --> 00:22:34,940
What I showed you just now was--
我刚才给你看的是——

486
00:22:34,940 --> 00:22:38,450
I was actually using OpenAI's
API as a developer tool.
我实际上使用 OpenAI 的
API 作为开发工具。

487
00:22:38,450 --> 00:22:40,850
And then, I think
the developer tool
然后，我认为
开发者工具

488
00:22:40,849 --> 00:22:43,399
sector is a hypercompetitive.
该行业是一个高度竞争的行业。

489
00:22:43,400 --> 00:22:46,460
Look at all the startups
chasing OpenAI right now.
看看现在所有追逐 OpenAI 的初创公司。

490
00:22:46,460 --> 00:22:48,920
But there will be
some mega winners.
但将会有
一些巨大的赢家。

491
00:22:48,920 --> 00:22:52,400
And so I sometimes play
here, but primarily,
所以我有时会在这里玩
，但主要是，

492
00:22:52,400 --> 00:22:54,769
when I think of a meaningful
technology advantage,
当我想到有意义的
技术优势时，

493
00:22:54,769 --> 00:22:56,839
because I think that
earns you the right
因为我认为
为您赢得了权利

494
00:22:56,839 --> 00:23:00,599
or earns you a better shot at
being one of the mega winners.
或者让您更有机会成为超级赢家之一。

495
00:23:00,599 --> 00:23:04,230
And then lastly, even though
a lot of the media attention
最后，尽管
很多媒体关注

496
00:23:04,230 --> 00:23:07,49
and the buzz is in the
infrastructure and developer
热门话题是
基础设施和开发人员

497
00:23:07,49 --> 00:23:11,159
tooling layer, it turns out
that layer can be successful
工具层，事实证明
该层可以成功

498
00:23:11,160 --> 00:23:15,450
only if the application layer
is even more successful.
除非应用层
更加成功。

499
00:23:15,450 --> 00:23:17,789
And we saw this with the
rise of SaaS as well.
随着 SaaS 的兴起，我们也看到了这一点。

500
00:23:17,789 --> 00:23:20,549
Lot of the buzz and excitement
is on the technology,
很多嗡嗡声和兴奋
都是关于技术的，

501
00:23:20,549 --> 00:23:21,596
the tooling layer.
工具层。

502
00:23:21,596 --> 00:23:22,180
Which is fine.
这很好。

503
00:23:22,180 --> 00:23:23,180
Nothing wrong with that.
没有错。

504
00:23:23,180 --> 00:23:25,170
But the only way for
that to be successful
但
成功的唯一途径

505
00:23:25,170 --> 00:23:27,882
is if the application layer
is even more successful,
如果应用层
更加成功，

506
00:23:27,882 --> 00:23:29,340
so that, frankly,
they can generate
这样，坦率地说，
他们可以生成

507
00:23:29,339 --> 00:23:32,549
enough revenue to pay the
infrastructure, and the tooling
足够的收入来支付
基础设施和工具

508
00:23:32,549 --> 00:23:33,329
layer.
层。

509
00:23:33,329 --> 00:23:36,539
So, actually, let me
mention one example.
所以，实际上，让我
举一个例子。

510
00:23:36,539 --> 00:23:39,899
Amorai-- I was actually just
texting the CEO yesterday.
Amorai——实际上我昨天刚刚给首席执行官发短信。

511
00:23:39,900 --> 00:23:42,630
But Amorai is a
company that we built
但 Amorai 是我们创建的
公司

512
00:23:42,630 --> 00:23:48,180
that uses AI for romantic
relationship coaching.
使用人工智能进行浪漫
关系辅导。

513
00:23:48,180 --> 00:23:50,830
And just to point
out, I'm an AI guy.
只是想指出
，我是一个人工智能专家。

514
00:23:50,829 --> 00:23:56,639
And I feel like I know
nothing really about romance.
我觉得我对浪漫一无所知。

515
00:23:56,640 --> 00:24:00,90
And if you don't believe
me, you can ask my wife,
如果你不相信
我，你可以问我妻子，

516
00:24:00,89 --> 00:24:03,750
she will confirm that I
know nothing about romance.
她会证实我
对浪漫一无所知。

517
00:24:03,750 --> 00:24:05,460
But when we went
to build this, we
但是当我们去
构建这个时，我们

518
00:24:05,460 --> 00:24:09,360
wanted to get together with the
former CEO of Tinder, Renate
想和
Tinder前首席执行官Renate聚在一起

519
00:24:09,359 --> 00:24:09,990
Nyborg.
尼堡。

520
00:24:09,990 --> 00:24:12,809
And with my team's
expertise in AI,
凭借我的团队在人工智能方面的专业知识，

521
00:24:12,809 --> 00:24:14,849
and her expertise
in relationships
以及她在人际关系方面的专业知识


522
00:24:14,849 --> 00:24:17,699
because she ran Tinder, she
knows more about relationships
因为她经营 Tinder，她
对人际关系了解更多

523
00:24:17,700 --> 00:24:19,440
than I think anyone
I know, we're
比我想象的任何人
我知道，我们

524
00:24:19,440 --> 00:24:21,539
able to build something
pretty unique using
能够构建一些东西
非常独特的使用

525
00:24:21,539 --> 00:24:26,39
AI for kind of romantic
relationship mentoring.
人工智能用于浪漫
关系指导。

526
00:24:26,39 --> 00:24:28,559
And the interesting thing
about applications like these
有趣的事情
关于这些应用程序

527
00:24:28,559 --> 00:24:32,549
is when we look around,
how many teams in the world
当我们环顾四周时，
世界上有多少支球队

528
00:24:32,549 --> 00:24:36,720
are simultaneously expert
in AI and in relationships?
同时是人工智能和人际关系方面的专家
？

529
00:24:36,720 --> 00:24:38,850
And so at the
application layer, I'm
所以在
应用层，我

530
00:24:38,849 --> 00:24:41,759
seeing a lot of
exciting opportunities
看到很多
令人兴奋的机会

531
00:24:41,759 --> 00:24:44,39
that seem to have a
very large market,
似乎有一个非常大的市场，

532
00:24:44,39 --> 00:24:46,409
but where the
competition sets is
但
竞争的地点是

533
00:24:46,410 --> 00:24:49,29
very light, relative to the
magnitude of the opportunity.
相对于
机会的大小而言，非常轻微。

534
00:24:49,29 --> 00:24:50,654
It's not that there
are no competitors,
并不是说没有
竞争对手，

535
00:24:50,654 --> 00:24:54,240
but it's just much less intense
compared to the developer tool
但与开发者工具相比，它的强度要低得多


536
00:24:54,240 --> 00:24:55,859
or the infrastructure layers.
或基础设施层。

537
00:24:55,859 --> 00:25:00,809
And so, because I've spent
a lot of time iterating
所以，因为我花了
很多时间迭代

538
00:25:00,809 --> 00:25:03,509
on a process of building
startups, what I'm going to do
在建立
初创公司的过程中，我要做什么

539
00:25:03,509 --> 00:25:05,220
is just, very
transparently, tell
只是，非常
透明地告诉

540
00:25:05,220 --> 00:25:08,470
you the recipe we've developed
for building startups.
我们为您开发了
用于建立初创公司的秘诀。

541
00:25:08,470 --> 00:25:11,370
And so after many years of
iteration and improvement,
所以经过多年的
迭代和改进，

542
00:25:11,369 --> 00:25:14,609
this is how we now
build startups.
这就是我们现在建立初创公司的方式。

543
00:25:14,609 --> 00:25:17,429
My team's always had access
to a lot of different ideas,
我的团队总是能够获得
很多不同的想法，

544
00:25:17,430 --> 00:25:20,100
internally generated,
ideas from partners.
内部产生，
来自合作伙伴的想法。

545
00:25:20,99 --> 00:25:23,189
And I want to walk through this
with one example of something
我想通过一个例子来解释这一点


546
00:25:23,190 --> 00:25:25,529
we did, which is a
company Bearing AI,
我们做到了，这是一家
轴承AI公司，

547
00:25:25,529 --> 00:25:28,750
which uses AI to make
ships more fuel efficient.
它使用人工智能来提高船舶的燃油效率。

548
00:25:28,750 --> 00:25:32,799
So this idea came to me
when, a few years ago,
所以我想到了这个想法
几年前，

549
00:25:32,799 --> 00:25:35,309
a large Japanese
conglomerate called Mitsui,
一家名为三井的日本大型企业集团


550
00:25:35,309 --> 00:25:39,899
that is a major shareholder and
operates major shipping lines,
这是主要股东并
经营主要航运公司，

551
00:25:39,900 --> 00:25:42,330
they came to me and they
said, hey, Andrew, you
他们来找我，他们
说，嘿，安德鲁，你

552
00:25:42,329 --> 00:25:45,329
should build a business to
use AI to make ships more fuel
应该建立一家企业
使用人工智能为船舶提供更多燃料

553
00:25:45,329 --> 00:25:46,289
efficient.
高效的。

554
00:25:46,289 --> 00:25:48,869
And the specific
idea was, think of it
具体的
想法是，想想看

555
00:25:48,869 --> 00:25:50,489
as a Google Maps for ships.
作为船舶的谷歌地图。

556
00:25:50,490 --> 00:25:53,700
We can suggest a ship or
tell a ship how to steer,
我们可以建议一艘船或
告诉一艘船如何驾驶，

557
00:25:53,700 --> 00:25:56,220
so that you still get to
your destination on time,
以便您仍然准时到达
目的地，

558
00:25:56,220 --> 00:26:00,380
but using, it turns out,
about 10% less fuel.
但事实证明，使用后
可减少约 10% 的燃料。

559
00:26:00,380 --> 00:26:04,220
And so what we now do is
we spend about a month,
所以我们现在做的是
我们花了大约一个月的时间，

560
00:26:04,220 --> 00:26:05,420
validating the idea.
验证这个想法。

561
00:26:05,420 --> 00:26:08,300
So double check, is this idea
even technically feasible,
所以仔细检查一下，这个想法在技术上是否可行，

562
00:26:08,299 --> 00:26:09,883
and then talk to
prospective customers
然后与
潜在客户交谈

563
00:26:09,883 --> 00:26:11,383
to make sure there
is a market need.
确保
有市场需求。

564
00:26:11,383 --> 00:26:13,200
So we spent up to about
a month doing that.
所以我们花了大约
一个月的时间来做这件事。

565
00:26:13,200 --> 00:26:16,400
And if it passes
this stage, then we
如果它通过了|​​|||这个阶段，那么我们

566
00:26:16,400 --> 00:26:20,210
will go and recruit a CEO to
work with us on the project.
将去招募一位首席执行官
与我们一起开展该项目。

567
00:26:20,210 --> 00:26:22,160
When I was starting,
out I used to spend
当我开始时，
我曾经花费

568
00:26:22,160 --> 00:26:24,320
a long time working
on a project myself,
我自己在一个项目上工作了很长时间
，

569
00:26:24,319 --> 00:26:25,549
before bringing on a CEO.
在任命首席执行官之前。

570
00:26:25,549 --> 00:26:28,250
But after iterating, we
realized that bringing
但经过迭代，我们
意识到带来

571
00:26:28,250 --> 00:26:30,170
on a leader at
the very beginning

一开始就在领导者身上

572
00:26:30,170 --> 00:26:33,980
to work with us, it reduces
a lot of the burden of having
与我们合作，可以减轻
很多负担

573
00:26:33,980 --> 00:26:36,319
to transfer knowledge
or having a CEO come in
传授知识
或让首席执行官介入

574
00:26:36,319 --> 00:26:38,730
and having to revalidate
what [? we ?] discovered.
并且必须重新验证
什么[？我们？]发现了。

575
00:26:38,730 --> 00:26:41,29
So the process is, we've,
learned much more efficient,
所以这个过程是，我们，
学到了更有效的知识，

576
00:26:41,29 --> 00:26:44,0
we just bring the leader
at the very start.
我们一开始就带了领导者
。

577
00:26:44,0 --> 00:26:45,890
And so in the case
of Bearing AI,
因此，就 Bearing AI 而言，

578
00:26:45,890 --> 00:26:48,50
we found a fantastic
CEO, Dylan Keil,
我们找到了一位出色的
首席执行官，迪伦·凯尔，

579
00:26:48,49 --> 00:26:51,200
who is a reputed entrepreneur,
one successful exit before.
是一位知名企业家，
曾经成功退出过。

580
00:26:51,200 --> 00:26:54,950
And then we spent three
months, six, two week sprints,
然后我们花了三个月、六个月、两周的冲刺，

581
00:26:54,950 --> 00:26:57,500
to work with them
to build a prototype
与他们合作
构建原型

582
00:26:57,500 --> 00:27:01,380
as well as do deep
customer validation.
以及进行深度
客户验证。

583
00:27:01,380 --> 00:27:03,650
If it survives
this stage, and we
如果它能活过
这个阶段，我们

584
00:27:03,650 --> 00:27:06,890
have about a two thirds,
66% survival rate,
大约有三分之二，
66% 的存活率，

585
00:27:06,890 --> 00:27:08,509
we then write the
first check in,
然后我们写
第一次签入，

586
00:27:08,509 --> 00:27:10,640
which then gives the
company resources
然后为
公司提供资源

587
00:27:10,640 --> 00:27:13,970
to hire an executive
team, build the key team,
聘请高管
团队，建立关键团队，

588
00:27:13,970 --> 00:27:16,759
get an MVP working, minimum
viable product working,
让 MVP 发挥作用，最低限度
可行的产品发挥作用，

589
00:27:16,759 --> 00:27:18,680
and get some real customers.
并获得一些真正的客户。

590
00:27:18,680 --> 00:27:21,259
And then after that,
hopefully, then successfully
然后在那之后
希望，然后成功

591
00:27:21,259 --> 00:27:24,29
raises additional external
rounds of funding,
筹集额外的外部
几轮融资，

592
00:27:24,29 --> 00:27:26,359
and can keep on
growing and scaling.
并且可以继续
成长和扩展。

593
00:27:26,359 --> 00:27:28,759
So I'm really proud of
the work that my team
所以我真的为
我的团队所做的工作感到自豪

594
00:27:28,759 --> 00:27:33,140
was able to do to support
Mitsui's idea, and Dylan Keil,
能够支持
三井的想法，迪伦·凯尔，

595
00:27:33,140 --> 00:27:33,950
as CEO.
作为首席执行官。

596
00:27:33,950 --> 00:27:37,250
And today, there are hundreds
of ships, on the high seas
如今，公海上有数百艘
船只

597
00:27:37,250 --> 00:27:40,400
right now, that are steering
themselves differently
现在，它们的转向方式不同


598
00:27:40,400 --> 00:27:41,750
because of Bearing AI.
因为轴承人工智能。

599
00:27:41,750 --> 00:27:46,339
And 10% fuel savings
translates to around to maybe
节省 10% 的燃油
大约相当于

600
00:27:46,339 --> 00:27:49,889
$450,000 in savings in
fuel, per, ship per year.
每艘船每年可节省 450,000 美元
燃料。

601
00:27:49,890 --> 00:27:52,460
And, of course, it's also,
frankly, quite a bit better
当然，坦白说，它也好一点

602
00:27:52,460 --> 00:27:54,0
for the environment.
为了环境。

603
00:27:54,0 --> 00:27:56,980
And I think this
startup, I think,
我认为这个
初创公司，我认为，

604
00:27:56,980 --> 00:28:00,549
would not have existed if not
for Dylan's fantastic work,
如果没有
迪伦的出色工作，就不会存在，

605
00:28:00,549 --> 00:28:04,339
and then also, Mitsui
bringing this idea to me.
然后三井
也把这个想法带给了我。

606
00:28:04,339 --> 00:28:08,319
And I like this example because
this is another one is like--
我喜欢这个例子，因为
这是另一个例子——

607
00:28:08,319 --> 00:28:11,529
this is a startup idea
that, just to point out,
这是一个创业想法
，只是指出，

608
00:28:11,529 --> 00:28:13,869
I would never have
come up with myself.
我永远不会
自己出现。

609
00:28:13,869 --> 00:28:16,419
Because I've been
on a boat but what
因为我一直在船上
但是什么

610
00:28:16,420 --> 00:28:19,210
do I know about
maritime shipping.
我了解
海运吗？

611
00:28:19,210 --> 00:28:23,19
But is the deep subject
matter expertise of Mitsui,
而是三井的深课题
事专长，

612
00:28:23,19 --> 00:28:25,869
that had this insight,
together with Dylan,
具有这种洞察力，
与迪伦一起，

613
00:28:25,869 --> 00:28:29,929
and then my team's expertise
in AI, that made this possible.
然后我的团队在人工智能方面的专业知识让这一切成为可能。

614
00:28:29,930 --> 00:28:33,130
And so as I operate in
AI, one thing I've learned
因此，当我从事人工智能工作时，我学到了一件事

615
00:28:33,130 --> 00:28:36,10
is my swim lane is
AI, and that's it.
我的泳道是
AI，仅此而已。

616
00:28:36,9 --> 00:28:39,220
Because I don't have time or
it's very difficult for me
因为我没有时间或者
这对我来说很难

617
00:28:39,220 --> 00:28:41,19
to be expert in
maritime shipping,
成为
海运专家，

618
00:28:41,19 --> 00:28:43,329
and romantic relationships,
and health care,
和恋爱关系，
和医疗保健，

619
00:28:43,329 --> 00:28:45,710
and financial services,
and on, and on, and on.
和金融服务，
等等，等等，等等。

620
00:28:45,710 --> 00:28:47,799
And so I've learned
that if I can just
所以我了解到
如果我能

621
00:28:47,799 --> 00:28:51,220
help get a accurate
technical validation,
帮助获得准确的
技术验证，

622
00:28:51,220 --> 00:28:53,860
and then use AI
resources to make sure
然后使用AI
资源来确保

623
00:28:53,859 --> 00:28:55,449
the AI tech is built
quickly and well,
人工智能技术构建得又快又好，

624
00:28:55,450 --> 00:28:56,990
and I think, we've
always managed
我想，我们总是


625
00:28:56,990 --> 00:28:59,210
to help the companies build
a strong technical team,
帮助企业打造
强大的技术团队，

626
00:28:59,210 --> 00:29:02,240
then partnering with subject
matter experts often results
然后与主题专家合作
通常会产生结果

627
00:29:02,240 --> 00:29:05,29
in exciting new opportunities.
令人兴奋的新机遇。

628
00:29:05,29 --> 00:29:08,930
And I want to share with you
one other weird aspect of--
我想与你分享
另一个奇怪的方面--

629
00:29:08,930 --> 00:29:10,610
one other weird
thing I've learned
另一件奇怪的事
我学到的东西

630
00:29:10,609 --> 00:29:14,0
about building
startups, which is I
关于建立
初创公司，这就是我

631
00:29:14,0 --> 00:29:16,880
like to engage only when
there's a concrete idea.
仅当
有具体想法时才喜欢参与。

632
00:29:16,880 --> 00:29:20,60
And this runs counter to
a lot of the advice you
这与
你的很多建议背道而驰

633
00:29:20,59 --> 00:29:23,629
hear from the design thinking
methodology, which often says,
听听设计思维
方法论，它经常说，

634
00:29:23,630 --> 00:29:25,430
don't rush to solutioning.
不要急于解决。

635
00:29:25,430 --> 00:29:28,340
Explore a lot of alternatives
before you do a solution.
在制定解决方案之前，请探索多种替代方案
。

636
00:29:28,339 --> 00:29:31,879
Honestly, we tried
that, it was very slow.
老实说，我们尝试过
，但速度非常慢。

637
00:29:31,880 --> 00:29:34,850
But what we've learned
is that at the ideation
但我们学到的
是在构思时

638
00:29:34,849 --> 00:29:37,879
stage, if someone comes to
me and says, hey, Andrew,
舞台上，如果有人来找我说，嘿，安德鲁，

639
00:29:37,880 --> 00:29:40,280
you should apply AI
to financial services.
你应该将人工智能
应用于金融服务。

640
00:29:40,279 --> 00:29:43,730
Because I'm not a subject matter
expert in financial services,
因为我不是金融服务领域的专家


641
00:29:43,730 --> 00:29:45,860
it's very slow for
me to go and learn

我去学习很慢

642
00:29:45,859 --> 00:29:48,552
enough about financial services,
to figure out what to do.
关于金融服务已经足够了，
来弄清楚该怎么做。

643
00:29:48,553 --> 00:29:50,720
I mean, eventually, you
could get to a good outcome,
我的意思是，最终，你
可以获得一个好的结果，

644
00:29:50,720 --> 00:29:53,460
but it's a very labor
intensive, very slow,
但这是一个非常劳动密集型、非常慢的过程，

645
00:29:53,460 --> 00:29:56,480
very expensive process, for
me, to try to learn industry
对于
我来说，尝试学习行业是非常昂贵的过程

646
00:29:56,480 --> 00:29:57,710
after industry.
工业之后。

647
00:29:57,710 --> 00:30:00,980
In contrast, one of my
partners wrote this idea
相比之下，我的一位
合作伙伴写了这个想法

648
00:30:00,980 --> 00:30:03,200
as a tongue in cheek,
not really seriously.
作为开玩笑，
不是很认真。

649
00:30:03,200 --> 00:30:06,289
But, let's say,
[INAUDIBLE] by GPT,
但是，比方说，
[听不清] GPT，

650
00:30:06,289 --> 00:30:08,629
let's eliminate commercials
by automatically
让我们自动消除广告


651
00:30:08,630 --> 00:30:11,160
buying every product advertised
in exchange for not having
购买所有广告产品
以换取没有

652
00:30:11,160 --> 00:30:13,430
to see any ads, it's
not a good idea,
看任何广告，这不是一个好主意，

653
00:30:13,430 --> 00:30:16,160
but it is a concrete idea.
但这是一个具体的想法。

654
00:30:16,160 --> 00:30:19,910
And it turns out, concrete ideas
can be validated or falsified,
事实证明，具体的想法
可以被验证或证伪，

655
00:30:19,910 --> 00:30:22,100
efficiently.
有效率的。

656
00:30:22,99 --> 00:30:25,189
They also give a team a
clear direction to execute.
他们还为团队提供
明确的执行方向。

657
00:30:25,190 --> 00:30:27,240
And I've learned that
in today's world,
我了解到
在当今世界，

658
00:30:27,240 --> 00:30:30,19
especially, with the excitement,
the buzz, the exposure to AI
尤其是，随着兴奋、
嗡嗡声、接触人工智能

659
00:30:30,19 --> 00:30:32,509
of a lot of people, it
turns out that there
对很多人来说，
事实证明，

660
00:30:32,509 --> 00:30:35,89
are a lot of subject matter
experts in today's world,
当今世界有很多主题
专家，

661
00:30:35,89 --> 00:30:38,629
that have deeply thought about
a problem for months, sometimes
有时会深入思考一个问题几个月

662
00:30:38,630 --> 00:30:40,680
even one or two years.
甚至一两年。

663
00:30:40,680 --> 00:30:42,600
But they've not yet
had a build partner.
但他们还没有
构建合作伙伴。

664
00:30:42,599 --> 00:30:45,349
And when we get together
with them, and hear,
当我们与他们聚在一起
并听到，

665
00:30:45,349 --> 00:30:46,879
and they share
the idea of us, it
他们分享
我们的想法，它

666
00:30:46,880 --> 00:30:49,130
allows us to work with
them to very quickly go
允许我们与
他们一起工作，很快

667
00:30:49,130 --> 00:30:51,360
into validation and building.
进入验证和构建。

668
00:30:51,359 --> 00:30:53,839
And I find that this
works because there
我发现这
之所以有效，是因为

669
00:30:53,839 --> 00:30:57,169
are a lot of people that
have already done the design
有很多人
已经完成了设计

670
00:30:57,170 --> 00:31:00,430
thinking thing of exploring
a lot of ideas and winnowing
思考探索的事情
很多想法和筛选

671
00:31:00,430 --> 00:31:01,870
down to really good ideas.
直到真正的好主意。

672
00:31:01,869 --> 00:31:03,549
And there are-- I
find that there are so
还有--我
发现有这么

673
00:31:03,549 --> 00:31:05,169
many good ideas
sitting out there,
很多好主意
坐在那里，

674
00:31:05,170 --> 00:31:06,850
that no one is working on.
没有人在努力。

675
00:31:06,849 --> 00:31:09,669
That finding those good ideas
that someone has already
发现那些好主意
有人已经有了

676
00:31:09,670 --> 00:31:13,420
had, and wants to share with us,
and wants to build partner for,
拥有，并希望与我们分享，
并希望建立合作伙伴，

677
00:31:13,420 --> 00:31:17,890
that turns out to be a
much more efficient engine.
事实证明这是一个更高效的引擎。

678
00:31:17,890 --> 00:31:21,880
So before I wrap up, we'll go
to the question in a second,
所以在结束之前，我们先
讨论这个问题，

679
00:31:21,880 --> 00:31:25,910
just a few slides to talk
about risk and social impact.
只需几张幻灯片来讨论
风险和社会影响。

680
00:31:25,910 --> 00:31:29,19
So AI is very
powerful technology.
所以人工智能是非常
强大的技术。

681
00:31:29,19 --> 00:31:31,420
To say something you'd
probably guess, my teams and I,
说一些你可能会猜到的话，我和我的团队，

682
00:31:31,420 --> 00:31:34,60
we only work on projects
that move humanity forward.
我们只致力于推动人类进步的项目
。

683
00:31:34,59 --> 00:31:37,809
And we have multiple
times killed projects
我们有多个
多次被终止的项目

684
00:31:37,809 --> 00:31:40,569
that we assess to be
financially sound, based
我们评估为
财务状况良好，基于

685
00:31:40,569 --> 00:31:41,500
on ethical grounds.
基于道德理由。

686
00:31:41,500 --> 00:31:43,960
It turns out, I've
been surprised
事实证明，我
很惊讶

687
00:31:43,960 --> 00:31:47,170
and sometimes dismayed at
the creativity of people
有时对
人们的创造力感到沮丧

688
00:31:47,170 --> 00:31:49,279
to come up with good ideas.
想出好主意。

689
00:31:49,279 --> 00:31:52,119
So to come up with
really bad ideas that
所以想出
非常糟糕的想法

690
00:31:52,119 --> 00:31:55,299
seem profitable but really
should not be built.
看似有利可图，但实际上
不应该建造。

691
00:31:55,299 --> 00:31:58,369
We've killed a few
projects on those grounds.
我们已经因为这些原因取消了一些
项目。

692
00:31:58,369 --> 00:32:01,449
And then, I think, has to be
acknowledged that AI today
然后，我认为，必须承认今天的人工智能

693
00:32:01,450 --> 00:32:04,809
does have problems with
bias, fairness, and accuracy.
确实存在
偏见、公平性和准确性问题。

694
00:32:04,809 --> 00:32:07,929
But also the technology
is improving quickly.
而且技术
也在迅速进步。

695
00:32:07,930 --> 00:32:10,299
So I see that AI
systems today are
所以我认为今天的人工智能
系统是

696
00:32:10,299 --> 00:32:12,849
less biased than six
months ago, and more
与六个月前相比，偏见减少了
，而且更多

697
00:32:12,849 --> 00:32:14,889
fair than six months
ago, which is not
比六个月前还公平
，这不是

698
00:32:14,890 --> 00:32:16,990
to dismiss the importance
of these problems.
忽视这些问题的重要性
。

699
00:32:16,990 --> 00:32:19,390
They are problems and we should
continue to work on them.
它们是问题，我们应该
继续努力解决它们。

700
00:32:19,390 --> 00:32:21,730
But I'm also gratified
at the number
但我也很满意
这个数字

701
00:32:21,730 --> 00:32:23,740
of teams working
hard on these issues
的团队
努力解决这些问题

702
00:32:23,740 --> 00:32:25,450
to make them much better.
让他们变得更好。

703
00:32:25,450 --> 00:32:27,289
When I think of the
biggest risks of AI.
当我想到人工智能的最大风险时。

704
00:32:27,289 --> 00:32:28,750
I think that the biggest risks--
我认为最大的风险——

705
00:32:28,750 --> 00:32:33,200
one of the biggest risks
is the disruption to jobs.
最大的风险之一
是就业中断。

706
00:32:33,200 --> 00:32:36,970
This is a diagram from a paper
by our friend at the University
这是我们大学朋友的论文
中的图表

707
00:32:36,970 --> 00:32:39,190
of Pennsylvania, and
some folks at OpenAI,
宾夕法尼亚州和
OpenAI 的一些人，

708
00:32:39,190 --> 00:32:42,70
analyzing the exposure
of different jobs
分析不同工作的暴露


709
00:32:42,69 --> 00:32:43,869
to AI automation.
到人工智能自动化。

710
00:32:43,869 --> 00:32:48,129
And it turns out that, whereas,
the previous wave of automation
事实证明，然而，
上一波自动化浪潮

711
00:32:48,130 --> 00:32:49,330
mainly--
主要是——

712
00:32:49,329 --> 00:32:52,329
the most exposed jobs were
often the lower wage jobs,
最受影响的工作通常是工资较低的工作，

713
00:32:52,329 --> 00:32:56,19
such as when we put
robots into factories.
例如当我们将
机器人放入工厂时。

714
00:32:56,19 --> 00:32:58,329
With this current
wave of automation,
随着当前的
自动化浪潮，

715
00:32:58,329 --> 00:33:00,909
is actually the higher
wage jobs, further,
实际上是工资较高的工作
，更进一步，

716
00:33:00,910 --> 00:33:03,130
to the right of this
axis, that seems
在此
轴的右侧，似乎

717
00:33:03,130 --> 00:33:06,140
to have more of their tasks
exposed to automation.
让他们的更多任务
暴露于自动化。

718
00:33:06,140 --> 00:33:10,410
So even as we create
tremendous value using AI,
因此，即使我们利用人工智能创造
巨大的价值，

719
00:33:10,410 --> 00:33:14,685
I feel like, as citizens,
and our corporations,
我觉得，作为公民，
和我们的公司，

720
00:33:14,684 --> 00:33:16,59
and our governments,
and, really,
还有我们的政府，
而且，真的，

721
00:33:16,59 --> 00:33:18,849
our society, I feel
a strong obligation
我们的社会，我感到
强烈的义务

722
00:33:18,849 --> 00:33:22,269
to make sure that people,
especially people whose
确保人们，
特别是那些

723
00:33:22,269 --> 00:33:25,990
livelihoods are disrupted,
are still well taken care of,
生计被打乱，
仍然得到很好的照顾，

724
00:33:25,990 --> 00:33:28,650
are still treated well.
仍然受到很好的待遇。

725
00:33:28,650 --> 00:33:32,480
And then lastly,
there's also been--
最后，
还有——

726
00:33:32,480 --> 00:33:35,900
it feels like every time there's
a big wave of progress in AI,
感觉每次人工智能领域都有一大波进步，

727
00:33:35,900 --> 00:33:39,590
there's a big wave of hype about
artificial general intelligence
关于
通用人工智能有一大波炒作

728
00:33:39,589 --> 00:33:40,279
as well.
以及。

729
00:33:40,279 --> 00:33:42,990
When DeepLearning started
work really well 10 years ago,
当深度学习在 10 年前开始
效果非常好时，

730
00:33:42,990 --> 00:33:44,436
there was a lot
of hype about AGI.
关于 AGI 有很多
炒作。

731
00:33:44,436 --> 00:33:46,519
And now, the generative
AI is working really well,
现在，生成式人工智能运行得非常好，

732
00:33:46,519 --> 00:33:49,160
there's another wave
of hype about AGI.
关于 AGI 的炒作又一波
。

733
00:33:49,160 --> 00:33:53,157
But I think that artificial
general intelligence,
但我认为人工智能
通用智能，

734
00:33:53,156 --> 00:33:54,740
AI that can do
anything a human can do
人工智能可以做人类能做的任何事情

735
00:33:54,740 --> 00:33:58,410
is still decades away, maybe 30
to 50 years, maybe even longer.
还有几十年的时间，也许是三十
到五十年，也许甚至更久。

736
00:33:58,410 --> 00:33:59,960
I hope we'll see it
in our lifetimes.
我希望我们能在有生之年看到它
。

737
00:33:59,960 --> 00:34:02,690
But I don't think
there's any time soon.
但我不认为
很快就会有时间。

738
00:34:02,690 --> 00:34:06,529
One of the challenges is
that the biological path
挑战之一是
生物途径

739
00:34:06,529 --> 00:34:09,230
to intelligence, like
humans and the digital path
走向智能，就像
人类和数字之路

740
00:34:09,230 --> 00:34:13,309
to intelligence, AI, they've
taken very different paths.
对于智能、人工智能，他们
采取了截然不同的道路。

741
00:34:13,309 --> 00:34:15,769
And the funny thing about
the definition of AGI
有趣的是
AGI 的定义

742
00:34:15,769 --> 00:34:19,39
is you're benchmarking this
very different digital path
您正在对这条非常不同的数字路径进行基准测试吗？

743
00:34:19,39 --> 00:34:21,762
to intelligence with
really the biological path
通过
真正的生物途径实现智力

744
00:34:21,762 --> 00:34:22,429
to intelligence.
到智力。

745
00:34:22,429 --> 00:34:25,489
So I think, large language
models are smarter
所以我认为，大型语言
模型更聪明

746
00:34:25,489 --> 00:34:28,409
than any of us in
certain key dimensions,
在某些关键维度上比我们任何人都强，

747
00:34:28,409 --> 00:34:31,349
but much dumber than any
of us in other dimensions.
但比其他维度的我们任何人都愚蠢得多。

748
00:34:31,349 --> 00:34:33,929
And so forcing it to do
everything a human can do
所以强迫它做
人类能做的一切

749
00:34:33,929 --> 00:34:35,699
is like a funny comparison.
就像一个有趣的比较。

750
00:34:35,699 --> 00:34:37,139
But I hope we'll get there.
但我希望我们能到达那里。

751
00:34:37,139 --> 00:34:38,980
Hopefully, within our lifetimes.
希望在我们有生之年。

752
00:34:38,980 --> 00:34:41,519
And then there's also
a lot of, I think,
然后还有
很多，我想，

753
00:34:41,519 --> 00:34:45,539
overblown hype about AI creating
extinction risks for humanity.
关于人工智能给人类带来灭绝风险的过度炒作。

754
00:34:45,539 --> 00:34:46,900
Candidly, I don't see it.
坦白说，我没有看到。

755
00:34:46,900 --> 00:34:49,889
I just don't see how AI creates
any meaningful extinction
我只是不明白人工智能如何创造
任何有意义的灭绝

756
00:34:49,889 --> 00:34:52,269
risk for humanity.
人类面临的风险。

757
00:34:52,269 --> 00:34:56,219
I think that people worry
we can't control AI.
我认为人们担心
我们无法控制人工智能。

758
00:34:56,219 --> 00:35:00,90
But we have lots of, AI will be
more powerful than any person.
但我们有很多，人工智能将比任何人都更强大。

759
00:35:00,90 --> 00:35:03,0
But with lots of experience,
steering, very powerful
不过经验丰富，
转向，很给力

760
00:35:03,0 --> 00:35:05,309
entities, such as corporations
or nation states that
实体，例如公司
或国家

761
00:35:05,309 --> 00:35:07,980
are far more powerful
than any single person,
比任何一个人都更强大
，

762
00:35:07,980 --> 00:35:11,730
and making sure they, for the
most part, benefit humanity.
并确保它们在很大程度上造福人类。

763
00:35:11,730 --> 00:35:14,610
And also technology
develops gradually.
而且技术也逐渐发展起来。

764
00:35:14,610 --> 00:35:17,130
The so-called hot
take off scenario,
所谓热
起飞场景，

765
00:35:17,130 --> 00:35:18,840
where it's not
really working today,
今天它不
真正起作用的地方，

766
00:35:18,840 --> 00:35:20,640
and then suddenly,
one day, overnight,
然后突然，
有一天，一夜之间，

767
00:35:20,639 --> 00:35:23,99
it works brilliantly, and we
achieve super intelligence,
它工作得非常出色，我们
实现了超级智能，

768
00:35:23,99 --> 00:35:24,360
takes over the world.
接管世界。

769
00:35:24,360 --> 00:35:25,900
That's just not realistic.
那是不现实的。

770
00:35:25,900 --> 00:35:28,650
And I think the AI technology
will develop slowly,
而且我认为AI技术
会慢慢发展，

771
00:35:28,650 --> 00:35:29,760
like all the--
像所有的——

772
00:35:29,760 --> 00:35:31,680
and then it gives
us plenty of time
然后它给了
我们充足的时间

773
00:35:31,679 --> 00:35:34,440
to make sure that we
provide oversight and can
确保我们
提供监督并能够

774
00:35:34,440 --> 00:35:36,90
manage it to be safe.
管理它以确保安全。

775
00:35:36,90 --> 00:35:38,910
And lastly, if you look at
the real extinction risk
最后，如果你看看
真正的灭绝风险

776
00:35:38,909 --> 00:35:42,329
to humanity, such
as, fingers crossed,
对人类，例如
，手指交叉，

777
00:35:42,329 --> 00:35:45,90
the next pandemic
or climate change,
下一次大流行
或气候变化，

778
00:35:45,90 --> 00:35:47,640
leading to a massive
de-population of some parts
导致某些地区人口大量减少


779
00:35:47,639 --> 00:35:51,59
of the planet, or much lower
odds, but maybe someday,
这个星球的概率，或者低得多
几率，但也许有一天，

780
00:35:51,59 --> 00:35:54,809
an asteroid doing to us what
it had done to the dinosaurs.
一颗小行星对我们的影响就像它对恐龙的影响一样。

781
00:35:54,809 --> 00:35:57,269
I think if we look at the
actual real extinction
我想如果我们看看
真正的灭绝

782
00:35:57,269 --> 00:36:01,230
risk to humanity, AI
having more intelligence,
人类面临风险，人工智能
拥有更多智能，

783
00:36:01,230 --> 00:36:03,59
even artificial
intelligence in the world,
甚至世界上的人工智能
，

784
00:36:03,59 --> 00:36:05,230
would be a key part
of the solution.
将是解决方案的关键部分
。

785
00:36:05,230 --> 00:36:08,760
So I feel like if you want
humanity to survive and thrive
所以我觉得如果你想要
人类生存和繁荣

786
00:36:08,760 --> 00:36:12,250
for the next 1,000 years,
rather than slowing AI down,
在接下来的 1000 年里，
而不是放慢人工智能的速度，

787
00:36:12,250 --> 00:36:15,239
which some people
propose, I would rather
有些人
建议，我宁愿

788
00:36:15,239 --> 00:36:18,789
make AI go as fast as possible.
让AI尽可能快地发展。

789
00:36:18,789 --> 00:36:21,719
So with that, just to summarize,
this is my last slide.
总而言之，
这是我的最后一张幻灯片。

790
00:36:21,719 --> 00:36:25,619
I think that AI, as a
general purpose technology
我认为人工智能作为一种
通用技术

791
00:36:25,619 --> 00:36:29,9
creates a lot of new
opportunities for everyone.
为每个人创造了很多新的
机会。

792
00:36:29,10 --> 00:36:31,590
And a lot of the exciting and important work that
还有许多令人兴奋和重要的工作

793
00:36:31,590 --> 00:36:35,700
lies ahead of us all is to go
and build those concrete use
摆在我们面前的就是去
并构建那些具体的用途

794
00:36:35,699 --> 00:36:38,730
cases, and hopefully,
in the future,
案例，并希望
在未来，

795
00:36:38,730 --> 00:36:40,889
hopefully, I'll have
opportunities to maybe
希望我会有
机会

796
00:36:40,889 --> 00:36:43,609
engage with more of you on those opportunities as well.
也可以在这些机会上与更多人互动。

797
00:36:43,610 --> 00:36:46,79
So with that, let me just say, thank you all very much.
那么，让我说 ，非常感谢大家。







## Ref

[1].[Andrew Ng: Opportunities in AI - 2023_Youtube](https://www.youtube.com/watch?v=5p248yoa3oE)