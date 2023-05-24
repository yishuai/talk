class: middle, center

# 基于数据的逻辑推理

#### 交大附中大数据系统基础系统课程

##### 陈一帅
###### 北京交通大学电子信息工程学院
###### 2023年5月

---
# 什么是量化推理？

- 基于数据（量化）信息，理解和推理
  - quantitative reasoning
- 大数据时代，关键素养能力（ literacy ）
  - quantitative literacy

???
class: middle, center
# 数学文化

Mathematics knows no races or geographic boundaries; for mathematics, the cultural world is one country

David Hilbert (1862–1943), mathematician

---
# 三级语言素养

- 3: 阅读小说和杂志，以及安全规则和设备说明。以正确的格式和标点符号编写报告。在听众面前说得很好

- 4: 阅读小说、诗歌、报纸和手册。准备商业信函、摘要和报告。参加小组讨论和辩论。就各种主题即兴发言

- 5: 阅读文学作品、书评、科技期刊、财务报告和法律文件。可以撰写社论、演讲和评论

---
# 三级数学素养

- 3: 理解基本的几何和代数。计算折扣、利息、损益、加价和佣金

- 4: 具有真正的定量推理能力。理解逻辑、解决问题、统计和概率的概念以及建模

- 5: 精通微积分和统计学。能够处理计量经济学

---
# 职业与数学素养的关系（6级）

- Biochemist 6 6 （生物化学家）
- Computer engineer 6 6 （计算机工程师）
- Mathematician 6 6 （数学家）

---
# 职业与数学素养的关系（5级）

- Social psychologist 6 5 （社会心理学家）
- Cardiologist 6 5 （心脏病专家）
- Accountant 5 5 （会计师）
- Corporate president 5 5 （公司总裁）
- Weather forecaster 5 5 （天气预报员）
- Financial analyst 5 5 （金融分析师）
- Secondary teacher 5 5 （中学教师）
- Corporate executive 5 5 （企业高管）

---
# 职业与数学素养的关系（4级）

- Lawyer 6 4 （律师）
- Tax attorney 6 4 （税务律师）
- Newspaper editor 6 4 （报纸编辑）
- Personnel manager 5 4 （人事经理）
- Elementary teacher 5 4 （小学教师）
- Journalist 5 4 （记者）
- Web page designer 5 4 （网页设计师）

---
# 职业与数学素养的关系（4级）

- Computer sales agent 4 4 （电脑销售代理）
- Athlete’s agent 4 4 （运动员经纪人）
- Management trainee 4 4 （管理培训生）
- Insurance sales agent 4 4 （保险销售代理人）
- Retail store manager 4 4 （零售店经理）

---
# 职业与数学素养的关系（3级）

- Cement mason 3 3 （水泥工）
- Poultry farmer 3 3 （家禽养殖户）
- Tile setter 3 3 （贴砖机）
- Travel agent 3 3 （旅行社）

---
# 职业与数学素养的关系（2级）

- Janitor 3 2 （看门人）
- Short-order cook 3 2 （快餐厨师）
- Assembly-line worker 2 2 （流水线工人）
- Toll collector 2 2 （收费员）

---
# 职业与数学素养的关系（1级）

- Laundry worker 1 1 （洗衣工）

---
# 课程目标

- 利用基本的数学技能（其中大部分你已经具备）
- 进行大数据分析
- 以批判和分析的方式理解和研究问题
- 培养逻辑思想、批判性思考能力

---
class: middle, center
# 第一讲：逻辑

## Mathematics is just logic with numbers attached. 

Marilyn vos Savant, Author

---
# 媒体时代

- 物理媒体：书籍、报纸、杂志和广告牌
- 电子媒体：互联网、平板电脑和智能手机、电视、电影
- 我们依赖这些媒体来源获取信息，形成观点和信念

---
# 挑战

- 媒体中的许多信息不准确、有偏见
- 其目的是让我们“相信”某些事
- 这些事可能真实，也可能不真实

---
# 逻辑

- 了解人们试图操纵我们观点的方式
- 这是“基于数据的逻辑推理”的基础

---
class: middle, center

# 吵架还是争论？

## People generally quarrel because they cannot argue.

G. K. Chesterton (1874–1936), English author

quarrel：吵架

---
# 没有逻辑的争论

- A：过量的碳排放是不道德的
- B：不，不是
- A：是的！它会让气候变暖
- B：你都不懂气候是如何变暖的
- A：我知道的比你知道的多！
- B：我不能和你谈。你简直就是一个白痴！

---
# 没有逻辑的争论的问题

- 效果一般
- 不会让任何一方理解对方的想法
- 也不太可能改变任何一方的观点

---
# 有逻辑的争论

- 使用逻辑（Logic）
  - 学习推理方法和原则
- 可能仍不会改变任何一方的立场
- 但可以帮助我们相互理解

---
# 逻辑基本概念

- “论证”（Argument）
  - 推理或思考的过程
- “前提”（Premise）
  - 支持结论（conclusion）的事实或假设（证据）
- “谬误”（Fallacy）
  - 一种“欺骗”或“诡计”式的论证
  - 它采取的论证方式，仔细分析后，会发现不合理

---
# 广告充满“谬误”

- 因为通常没有很好的理由说明你应该购买某个品牌或产品
- 但它们必须奏效
- 企业每年花上万亿元做广告，让我们买东西

---
# 谬误的识别

- 媒体中的谬误如此普遍，几乎不可能避免
  - 识别它们很重要
- 谬论尽管存在逻辑错误，但通常听起来很有说服力
  - 因为广告公司花费了数十亿元研究如何说服我们购买产品或支持特定观点

---
### 常见谬误

- 诉诸流行
- 虚假原因
- 诉诸未知
- 草率概括
- 有限选择
- 诉诸情感
- 人身攻击
- 循环推理
- 转移视线
- 稻草人

---
# 诉诸流行

- Appeal to Popularity

- “长城汽车制造了世界上最好的皮卡车。开长城皮卡的人比开任何其他轻型卡车的人都多。”

- 分析
  - 第一步：识别哪些陈述句是“前提”（证据），哪些是“结论”
  - 论点：长城制造了世界上最好的皮卡
  - 证据：驾驶长城皮卡的人比驾驶其他任何轻型卡车的人都多

- 许多人相信 p 是真的；因此 ... p 为真

???
# 练习

(Appeal to popularity) 

Apple’s iPhone outsells all other smart phones, so it must be the best smart phone on the market.

---
# 练习

（诉诸流行）

Apple 的 iPhone 销量超过所有其他智能手机，因此它一定是市场上最好的智能手机。

<!-- 举一个生活中的例子 -->

---
# 虚假原因

- False Cause
- “我把水晶石放在额头上，五分钟后我的头痛就消失了。是水晶让我的头痛消失了。”
- 分析
  - 一件事（额头上放水晶）先于另一件事（头痛消失）发生，
  - 但并没有证明它们之间有任何联系。也就是说，我们不能断定水晶使头痛消失
- A 先于 B；因此 A 导致了 B

???
# 练习

(False cause) 

I became sick just hours after eating at Burger Hut, so its food must have made me sick.

---
# 练习

（虚假原因）

在 Burger Hut 吃了几个小时后我就生病了，所以它的食物一定让我生病了。

<!-- 举一个生活中的例子 -->

---
# 诉诸未知

- Appeal to ignorance
- “科学家们还没有发现任何外星人访问地球的具体证据。所以
外星人不存在”
- 分析
  - 前提：没有证据表明外星人访问过地球
  - 结论：外星人不存在
- 利用对结论的未知，得出相反的结论
  - 没有证据表明 p 是真的；因此 p 为假
- 缺乏证据并不是“否命题”的证据

???
# 练习

(Appeal to ignorance) 

Decades of searching have not revealed life on other planets, so life in the universe must be confined to Earth.

---
# 练习

（诉诸无知）

数十年的搜寻并没有发现其他行星上的生命，因此宇宙中的生命必定局限在地球上。

<!-- 举一个生活中的例子 -->

---
# 讨论

- 一个人被判无罪，能证明这个人无辜吗？为什么？
- 为什么法律要求检察官证明有罪，而不要求被告（嫌疑人）证明无罪？
- 这个想法与诉诸无知的谬误有什么关系？

---
# 草率概括

- Hasty generalization
- “高压电线所在街道发生了两起儿童白血病病例。电源线一定是这些疾病的原因。”
- 分析
  - 前提是两个白血病病例，但是两个病例都不足以建立一个规律，更不能断定是电源线引起的病症
- 根据数量不足或未充分分析的案例得出结论
  - 要证明电力线与白血病之间存在联系，必须用多得多的证据来证实。（事实上​​，数十年的研究并未发现电线与疾病之间存在关联。）
- A和B连接了一次或几次；因此 A 导致 B（反之亦然）

???
# 练习

(Hasty generalization) 

I saw three people use food stamps to buy expensive steaks, so abuse of food stamps must be widespread.

---
# 练习

（草率概括）

我看到那个乞讨的人拿我给他的钱买昂贵的牛排，所以这些乞讨的人都是骗子。

<!-- 举一个生活中的例子 -->

---
# 有限选择

- Limited Choice
- “你不支持班长，所以你不爱我们班。”
- 分析
  - 该论点表明只有两种类型的同学：支持班长的爱班级的同学，不支持班长的不爱班级的同学
  - 但实际上还有很多其他的可能性，比如爱班级但不爱班长
- 这种谬误被称为有限选择（或虚假的困境），因为它人为地排除了其它可以考虑的选择

---
# 有限选择

- 也会出现在“你戒烟了吗？”之类的问题中
  - 是和否的答案都暗示您过去曾吸烟
  - 该问题排除了您从不吸烟的可能性
- 在法律诉讼中，这类问题是不允许的，因为它们试图“引导证人”
- 这种谬误的另一种简单而常见的形式是“你错了，所以我一定是对的”
- p 是假的；因此...只有 q 可以为真

???
# 练习

(Limited choice) 

He refused to testify by invoking his Fifth Amendment rights, so he must be guilty.

---
# 练习

（有限选择）

他拒绝为自己辩护，因此他一定有罪。

<!-- 举一个生活中的例子 -->

---
# 诉诸情感

- Appeal to Emotion
- 汽车轮胎广告，一张婴儿的照片，写着“因为你的轮胎承受了太多的压力”
- 分析
  - 前提：你爱你的孩子
  - 结论：你应该买我这个轮胎
- 广告商希望你对婴儿的爱会让你想买他们的轮胎
  - 唤起情绪反应，作为说服的工具。这是诉诸情绪的谬误
- p与积极的情绪反应相关；因此... p 为真

---
# 诉诸情感
- 有时诉诸的是负面情绪
- 例如，竞选班长，声明：如果对手当选，同学们的福利会减少
  - 试图说服你相信，选择另一位候选人，将导致不喜欢的后果
- 这种谬误有时被称为诉诸强力（appeal to force）

???
# 练习

(Appeal to emotion) 

Thousands of unarmed people, many of them children, are killed by firearms every year. It’s time we ban the sale of guns.

---
# 练习

（诉诸情感）

每年有数以千计的人死于交通事故，其中许多是可爱的儿童。是时候禁止汽车了。

<!-- 举一个生活中的例子 -->

---
# 人身攻击

- Personal attack
  - A：你应该戒酒，因为它会影响你的成绩，酒后驾车时会危及他人，还会破坏你与家人的关系
  - B：你自己有时也喝得很多！
- 分析
  - A 的论点有充分理由，前提为结论提供了强有力支持
  - B 驳斥了这一论点，指出 A 有时自己喝得太多了
  - 即使 B 的说法是正确的，它也与 A 的观点无关
  - B 对 A 进行人身攻击，而不是逻辑争论
- 我对声称 p 的人或团体有意见 ... p 不是真的
  - 拉丁语 ad hominem，意思是“针对个人”

---
# 人身攻击
- 人身攻击的谬误也适用于集体
- 例如：“这项提案将带来环境灾难，因为它的发起人收到了石油公司的资助。”
- 它没有挑战提案，只质疑资助人的动机
- 这个论证不成立

???
# 练习

(Personal attack) 

Senator Smith’s bill on agricultural policy is a sham, because he is supported by companies that sell genetically modified crop seeds.

---
# 练习

（人身攻击）

他的这个提案是一个骗局，因为他得到了销售这个种子的公司的资助。

<!-- 举一个生活中的例子 -->

---
# 思考（人身攻击）

- 为什么刑事案件中的证人经常被问到关于他们个人生活的问题
  - 一个人（或群体）的性格、环境和动机有时在逻辑上与论点相关
- 如果你是一名法官，你会如何决定何时允许此类问题？

---
# 循环推理

- Circular reasoning
- “社会有义务提供医疗保险，因为医疗保健是公民的权利。”
- 分析 
  - 前提和结论本质上是同一件事
  - 社会义务通常基于公认权利的定义
- 循环推理
  - p 是真的。 用不同的话，反复说

???
# 练习

(Circular reasoning) 

Illegal immigration is against the law, so illegal immigrants are criminals.

---
# 练习

（循环推理）

非法移民是违法的，所以非法移民是罪犯。

<!-- 举一个生活中的例子 -->

---
# 转移视线（红鲱鱼）

- Diversion (red herring)
- “我们不应该继续资助克隆研究，因为这种研究是关乎道德的，我们不能涉及太多道德问题。”
- 分析 
  - 争论：应不应该继续资助克隆研究
  - 然而，讨论都是关于道德的
- 通过关注另一个问题（道德）来转移对真正问题（资助克隆研究）的注意力
  - p 与 q 有关，我对 q 有疑义；所以 ... p 是真实的
- 有时被称为“转移注意力”

---
# 转移视线（红鲱鱼）

- 鲱鱼是一种在腐烂时会变红的鱼
- 19 世纪，英国逃犯发现通过在逃跑路线上擦红鲱鱼，可以转移猎犬的跟踪
- 注意：人身攻击也常用来转移注意力

???
# 练习

(Diversion) 

Good grades are needed to get into college, and a college diploma is necessary for a good career. Therefore, attendance should count in high school grades.

---
# 练习

（转移视线）

上大学需要一份好的高中成绩，找到一份好工作需要一个大学文凭。因此，出勤率应计入高中成绩。

<!-- 举一个生活中的例子 -->

---
# 稻草人

- 同学 A：放开“路边摆摊”，可以减少人们经营成本，促进大众就业
- 同学 B：这位同学不认为“路边摆摊”有什么问题，但我认为 ...
- 分析
  - 同学 A 的提议是要解决大众就业
  - 她并没有说她对路边摆摊的一般看法
  - 同学 B 歪曲了同学 A 的观点
  - 她立了一个稻草人，用它代表和同学 A 的思想有关的一个不合理的表现
- 这种扭曲他人言论或提议的争论被称为“稻草人”

---
# 稻草人
- 稻草人类似于转移注意力
- 主要区别在于
  - 转移注意力，转移到一个不相关的问题
  - 稻草人，转移到真实问题的一个扭曲的版本
- 我有一个关于 p 的扭曲版本的论点；所以 ... 我希望愚弄你，让你相信我关于 p 的真实版本的论点

???
# 练习

(Straw man) 

The mayor wants to raise taxes to fund social programs, so she must not believe in the value of hard work.

---
# 练习

（稻草人）

他想提高失业保险的金额，他一定不相信努力工作的价值。

<!-- 举一个生活中的例子 -->

???
# 小问答

1. A logical argument always includes
- a. at least one premise and one conclusion. 
- b. at least one premise and one fallacy.
- c. at least one fallacy and one conclusion.

---
# 小问答

1. 一个逻辑论证总是包括
- A. 至少一个前提和一个结论。
- B. 至少一个前提和一个谬误。
- C. 至少一个谬误和一个结论。

???
# 小问答

2. A fallacy is
- a. a statement that is untrue. 
- b. a heated argument.
- c. a deceptive argument.

---
# 小问答
2. 一个谬误是
- A. 一个不真实的陈述
- B. 激烈的争论
- C. 欺骗性的论点

???
# 小问答

3. Which of the following could not qualify as a logical argument?
- a. a series of statements in which the conclusion comes before the premises
- b. a list of premises that do not lead to a conclusion
- c. a series of statements that generate heated debate

# 小问答
3. 以下哪项不符合逻辑论证？
- A. 结论在前提之前的一系列陈述
- B. 不得出结论的前提清单
- C. 引起激烈争论的一系列声明

# 小问答

4. An argument in which the conclusion essentially restates the premise is an example of
- a. circular reasoning.
- b. limited choice. 
- c. logic.

---
# 小问答
4. 结论基本上重述前提的论证是一个
- A. 循环推理。
- B. 有限选择。

???
# 小问答

5. The fallacy of appeal to ignorance occurs when
- a. the fact that a statement p is true is taken to imply that the opposite of p must be false.
- b. the fact that we cannot prove a statement p to be true is
taken to imply that p is false.
- c. a conclusion p is disregarded because the person who stated it is ignorant.

---
# 小问答
5. 诉诸无知的谬误是以下哪一种情况？
- A. 陈述 p 为真这一事实，用它来暗示 p 的反面必定为假。
- B. 我们不能证明陈述 p 为真，因此 p 是假的。
- C. 结论 p 被忽视，因为提出它的人是无知的。

???
# 小问答

6. Consider the argument “I don’t support the President’s tax plan because I don’t trust his motives.” What is the conclusion of this argument?
- a. I don’t trust his motives.
- b. I don’t support the President’s tax plan. 
- c. The President is not trustworthy.

---
# 小问答
6. 考虑“我不支持班长的这个提议，因为我不相信他是为大家好”这一论点。这个论证的结论是什么？
- A. 我不相信他是为大家好。
- B. 我不支持班长的这个提议。
- C. 班长不值得信任。

???
# 小问答

7. Consider again the argument “I don’t support the President’s tax plan because I don’t trust his motives.” This argument is an example of
- a. a well-reasoned, logical argument.
- b. an argument that uses the fallacy of personal attack.
- c. an argument that uses the fallacy of appeal to emotion.

---
# 小问答
7. 再次考虑“我不支持班长的这个提议，因为我不相信他是为大家好”这一论点。这个论点属于以下哪种情况？
- A. 一个有充分理由的，合乎逻辑的论点。
- B. 人身攻击谬误。
- C. 诉诸情感谬误。

???
# 小问答

8. Consider the argument “Your lack of enthusiasm for soccer proves that you are not a sports fan.” This argument is an example of
- a. a well-reasoned, logical argument.
- b. an argument that uses the fallacy of diversion.
- c. an argument that uses the fallacy of limited choice.

---
# 小问答
8. 考虑“你对足球缺乏热情，这证明你不是体育迷”这个论点。这个论点是以下哪种情况？
- A. 一个有充分理由的，合乎逻辑的论点。
- B. 转移视线谬误。
- C. 有限选择谬误。

???
# 小问答

9. Suppose that the fact that an event A occurs before event B is used to conclude that A caused - B. This is an example of
- a. a well-reasoned, logical argument.
- b. an argument that uses the fallacy of false cause. 
- c. hasty generalization.

---
# 小问答
9. 假设“事件 A 在事件 B 之前发生”这一事实，被用来推断 A 导致了 B. 这是以下哪种情况？
- A. 一个有充分理由的，合乎逻辑的论点
- B. 虚假原因
- C. 草率概括

???
# 小问答

10. When we speak of a straw man in an argument, we mean
- a. a misrepresentation of someone else’s idea or belief.
- b. a person who has not used good logic.
- c. an argument so weak that it is as if it were made of straw.

---
# 小问答
10. 当我们在争论中提到“稻草人”时，我们的意思是
- A. 对他人的想法或信念的歪曲。
- B. 这是一个没有使用好的逻辑的人。
- C. 一个论点如此薄弱，以至于它就像是用稻草制成的。

???
# 应用 1

- Recognizing Fallacies
- Identify the premise(s) and conclusion
- Explain why the argument is deceptive
- If possible, identify the type of fallacy it represents

---
# 案例分析

讨论下面的几种谬误，分析以下内容
- 确定前提和结论
- 解释为什么这个论点具有欺骗性
- 如果可能，确定它代表的谬误类型

???
# 应用 2

Obesity has increased steadily, as has the sale of video games. It follows that video games are compromising our health.

# 案例 1

肥胖人数稳步上升，电子游戏的销量也是如此。由此可见，电子游戏正在让我们变得肥胖。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 3

All the mayors of my hometown have been men, which shows that men are better qualified for high office than women.

---
# 案例 2

我家乡的市长、县长、区长都是男性，可见男性比女性更适合担任高级职务。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 4

My father tells me that I should exercise daily. But he never exer- cised when he was young, so I see no need to follow his advice.

---
# 案例 3

我父亲告诉我，我应该每天锻炼。但他年轻的时候从来不锻炼，所以我觉得没有必要听从他的建议。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 5

My baby was vaccinated and later developed autism, which is why I believe that vaccines cause autism.

---
# 案例 4

我的孩子接种了疫苗，后来患上了自闭症，这就是为什么我认为疫苗会导致自闭症的原因。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 6

Everyone loves Shakespeare, because his plays have been read for many centuries.

---
# 案例 5

每个人都喜欢读莎士比亚，因为他的戏剧已经被阅读了多个世纪。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 7

Claims that GMO foods are unsafe are ridiculous, as I’ve never heard of anyone getting sick from them.

---
# 案例 6

声称转基因食品不安全是荒谬的，因为我从未听说过有人因转基因食品而生病。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 8

I will not give money to the earthquake relief effort. After I last gave to a charity, an audit showed that most of the money was used to pay its administrators in the front office.

---
# 案例 7

我不会再给慈善组织捐钱了。我上次捐给一家慈善机构之后，一项对它的审计显示：大部分钱都用来支付其管理人员的工资。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 9

My three friends who drink wine have never had heart attacks. My two friends who have had heart attacks are non-drinkers. Drinking wine is clearly a good therapy.

---
# 案例 8

我的三个喝酒的朋友从来没有心脏病发作过，而我的两个心脏病发作的朋友都不喝酒。看来喝酒是一种很好的治疗心脏病的方法。

属于哪种？
- 诉诸流行、 虚假原因、 诉诸未知、 草率概括、有限选择、诉诸情感、人身攻击、 循环推理、 转移视线、 稻草人

???
# 应用 10

My little boy loves dolls and my little girl loves trucks, so there’s no truth to the claim that boys are more interested in mechanical toys while girls prefer maternal toys.

# 应用 10

我的小男孩喜欢洋娃娃，我的小女孩喜欢卡车，所以说男孩更喜欢机械玩具而女孩更喜欢母性玩具的说法是不正确的。

???
# 其它谬误 1

- Fallacy of division
  - Premise: X has some property.
  - Conclusion: All things or people that belong to X must have the same property.
- Example:
  - Americans use more gasoline than Europeans, so Jake, who is an American, must use more gasoline than Europeans.

---
# 更多谬误

- 部分谬误（Fallacy of division）
- 赌徒谬误 (Gambler’s fallacy)
- 滑坡谬误（slippery slope fallacy）
- 中间地带谬误（middle ground fallacy）

---
# 其它谬误 1

- 部分谬误（Fallacy of division）
  - 前提：X 有一些属性。
  - 结论：属于X的所有事物或人一定具有这一属性。
- 例子：
  - 美国人比欧洲人用更多的汽油，所以杰克，一个美国人，肯定比欧洲人用更多的汽油。

???
# 其它谬误 2

- Gambler’s fallacy
  - Premise: X has been happening more than it should. 
  - Conclusion: X will come to an end soon.
- Example:
  - It has rained for 10 days, which is unusual around here. Tomorrow will be sunny.

---
# 其它谬误 2

- 赌徒谬误 (Gambler’s fallacy)
  - 前提：X 发生的次数超过了它应该发生的次数。
  - 结论：X 即将结束。
- 例子：
  - 下了 10 天的雨，这很不寻常。明天会是晴天。

???
# 其它谬误 3
- The slippery slope fallacy
  - Premise: X has occurred and is related to Y.
  - Conclusion: Y will inevitably occur.
- Example:
  - America has sent troops to three countries recently. Before you know it, we will have troops everywhere.

---
# 其它谬误 3

- 滑坡谬误（slippery slope fallacy）
  - 前提：X 已经发生，X 与 Y 相关。
  - 结论：Y 不可避免地会出现。
- 例子：
  - 我们公司最近向三个国家出口。世界各地都有我们的产品。

???
# 其它谬误 4
- The middle ground fallacy
  - Premise: X and Y are two extreme positions on a question. 
  - Conclusion: Z, which lies between X and Y, must be correct. 
- Example:
  - Senator Peters supports a large tax cut, and Senator Willis supports no tax cut. That means a small tax cut must be best.

---
# 其它谬误 4

- 中间地带谬误（middle ground fallacy）
  - 前提：X 和 Y 是一个问题的两个极端位置。
  - 结论：位于 X 和 Y 之间的 Z 一定是正确的。
- 例子：
  - A 支持房价应该大涨，B 说房价应该大跌。这意味着房价不涨不跌是最好的。

???
## 项目 1

评估媒体信息。
- 选择当前的政策讨论主题（示例可能包括医疗保健、税收政策或许多其他主题）。
- 找到一个在主题的一侧或另一侧争论的网站。
- 根据本单元给出的评估媒体信息的五个步骤评估论点。
- 写一份关于您访问​​过的网站的简短报告以及您对其信息可靠性的结论。

???
### 项目 2

Fallacy Websites. There are many websites devoted to the study of fallacies. Visit one, and choose a fallacy of a type not covered in this unit. Explain the fallacy, and give an example of it.

### 项目 2

谬论网站。有许多网站专门研究谬误。访问一个，然后选择一个本单元未涵盖的谬误类型。解释谬误，并举例说明。

### 项目 3

Editorial Fallacies. Examine editorials and letters to the edi- tor in your local newspaper. Find at least three examples of fallacies. In each case, describe how the argument is decep- tive. If the fallacy represents one or more of the common types described in this unit, state the type.

### 项目 3

编辑谬误。检查当地报纸上的社论和给编辑的信。找出至少三个谬误的例子。在每种情况下，描述论点如何具有欺骗性。如果谬误代表本单元中描述的一种或多种常见类型，请说明类型。

### 项目 4

Fallacies in Advertising. Pick a single night and a single commercial television channel, and analyze the advertisements shown over a one-hour period. Describe how each advertise- ment tries to persuade the viewer, and discuss whether the argu- ment is fallacious. What fraction of the advertisements involve fallacies? Are any fallacy types more common than others?

---
## 小组作业 1： 广告中的谬误

- 选择十个广告或直播带货视频，分析它们。
- 描述每个广告如何试图说服观众，并讨论该论点是否错误。
- 有多少广告涉及谬论？
- 是否有任何谬误类型比其他谬误类型更常见？

???
### 项目 6

Personal Fallacies. Describe an instance in which you were persuaded of something that you later decided was untrue. Explain how you were persuaded and why you later changed your mind. Did you fall victim to any fallacies? If so, how might you prevent the same thing from happening in the future?

---
# 评估媒体信息的方法

- 上述谬误只是个人、团体和公司为塑造你的观点而使用的众多策略中的一小部分
- 没有万无一失的方法可以确保特定媒体信息的可靠性
- 下面是一些指南，可能会有所帮助
  - 后面会学习如何基于大数据，实现这些步骤

---
# 评估媒体信息的五个步骤

- 考虑信源
  - 信息来源是否清楚？消息来源在这个问题上是否可信？
- 检查日期
  - 信息是什么时候写的？它现在仍然相关，还是已经过时？
- 验证准确性
  - 有没有其他信源？有充分理由相信它是准确的吗？它包含任何让你怀疑的东西吗？

---
# 评估媒体信息的五个步骤

- 注意隐藏的议程（agenda）
  - 信息是否公平客观地呈现，是否被操纵以服务于某些特定或隐藏的议程？
- 从更高的角度看（do not miss the big picture）
  - 即使一条媒体信息通过了上述所有测试，退一步，从更高的角度思考，它是否真的有意义？例如，它是否与您认为正确的其他事情有冲突，如果有，您如何解决它们之间的冲突？

---
# 示例

- 我们看到这样一个消息：
  - “8 月 27 日，火星会像满月那么大，那么亮。不要错过它，因为今天活着的人再也不会看到它了。”
- 用评估媒体信息的五个步骤来分析

---
# 1. 考虑消息来源

- 消息：“8 月 27 日，火星会像满月那么大，那么亮。不要错过它，因为今天活着的人再也不会看到它了。”

- 未给出原始来源，这意味着您无法知道来源是否权威
- 这应该会让你对这种说法产生怀疑

---
# 2. 检查日期

- 消息：“8 月 27 日，火星会像满月那么大，那么亮。不要错过它，因为今天活着的人再也不会看到它了。”

- 尽管该声明在引用该事件的 8 月 27 日时听起来很具体，但没有给出年份，因此您无法知道该声明是适用于今年、每一年，还是过去或未来的特定年份
- 这应该增加您对它的担忧

---
# 3. 搜索验证

- 消息：“8 月 27 日，火星会像满月那么大，那么亮。不要错过它，因为今天活着的人再也不会看到它了。”

- 该声明很容易在网上搜索相关信息验证，您会发现许多网站都表明它是不真实的。
- 当然，在相信这些网站之前，您还应该检查它们的有效性。但您会发现一些可靠的来源，例如国家天文台或备受推崇的新闻网站。
  - 然后，我们可以得出结论：该断言是错误的。但是无论如何，让我们继续最后两个步骤

---
# 4. 注意隐藏的议程

- 消息：“8 月 27 日，火星会像满月那么大，那么亮。不要错过它，因为今天活着的人再也不会看到它了。”

- 没有明显的隐藏议程，这种说法似乎更有可能只是对事实的错误陈述
- 进一步的研究将表明，这一说法最初出现于 2003 年，当时 8 月 27 日火星离地球的距离比它再次离地球的距离要近 200 年
- 然而，在我们的天空中，火星仍然远不及满月那么大，那么亮

---
# 5. 运用知识，思考其合理性

- 消息：“8 月 27 日，火星会像满月那么大，那么亮。不要错过它，因为今天活着的人再也不会看到它了。”

- 思考这个说法是否有道理
  - 火星是绕太阳公转的行星，而月球绕地球公转。所以月球总是比火星离我们近得多
  - 即使在离地球最近的地方，火星与地球的距离也是月球与地球的距离的 150 倍左右
  - 然而，火星的直径只有月球的两倍左右
- 所以，火星在我们的天空中永远不会像满月那样大而明亮

???
# 一些著名的事实核查网站
- 政治事实核查
  - FactCheck.org，由无党派和非营利性的 Annenberg 公共政策中心支持；
  - PolitiFact.com，来自坦帕湾时报；
  - 《华盛顿邮报》博客 “The Fact Checker”
- Snopes.com
  - 对于谣言、都市神话和其他奇怪的说法
- TruthOrFiction.com
  - 检查消息有效性，网站由一位以公平和准确著称的个人运营

???
### 项目 1

Evaluating Media information. Choose a current topic of policy discussion (examples might include gun control, health care, tax policy, or many other topics). Find a website that argues on one side or other of the topic. Evaluate the arguments based on the five steps for evaluating media information given in this unit. Write a short report on the site you visited and your conclusions about the reliability of its information.

---
## 小组作业 2: 评估媒体信息的方法

- 描述一个例子，在这个例子中，您被说服了某件事，但您后来认为这是不真实的。
- 解释你是如何被说服的，以及为什么你后来改变了主意。
- 你有没有成为任何谬误的受害者？
- 如果是这样，您如何防止将来发生同样的事情？

<!-- .center[.width-110[![](./figures/zhufeng.png)]] -->
