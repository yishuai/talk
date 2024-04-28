class: middle, center
## AI 解难题 3：寻找更好的问题

陈一帅、陈宇晗

<!-- [yschen@bjtu.edu.cn](mailto:yschen@bjtu.edu.cn)

北京交通大学电子信息工程学院

.footnote[网络智能实验室] -->

---
## 提问不简单

- 识别、分析和描述问题
- 需要对问题所在领域的全面理解，和提炼现实世界问题的能力

---
## 问题的重构
- 描绘问题的焦点、范围和边界，重新定义问题
- 如果没有精心设计的问题，即使是最复杂的提示也将达不到要求
- 一旦问题被明确定义，提示的语言学细微差别就还好

???
It is problem formulation — the ability to identify, analyze, and delineate problems.
In contrast, problem formulation emphasizes defining the problem by delineating its focus, scope, and boundaries. 
problem formulation necessitates a comprehensive understanding of the problem domain and ability to distill real-world issues. 
The fact is, without a well-formulated problem, even the most sophisticated prompts will fall short. However, once a problem is clearly defined, the linguistics nuances of a prompt become tangential to the solution.

???
AI Prompt Engineering Isn’t the Future
by Oguz A. Acar
June 06, 2023

https://hbr.org/2023/06/ai-prompt-engineering-isnt-the-future

what is a more enduring and adaptable skill that will keep enabling us to harness the potential of generative AI? 

It is problem formulation — the ability to identify, analyze, and delineate problems.

Problem formulation and prompt engineering differ in their focus, core tasks, and underlying abilities. Prompt engineering focuses on crafting the optimal textual input by selecting the appropriate words, phrases, sentence structures, and punctuation. 

In contrast, problem formulation emphasizes defining the problem by delineating its focus, scope, and boundaries. 

Prompt engineering requires a firm grasp of a specific AI tool and linguistic proficiency while 

problem formulation necessitates a comprehensive understanding of the problem domain and ability to distill real-world issues. 

The fact is, without a well-formulated problem, even the most sophisticated prompts will fall short. However, once a problem is clearly defined, the linguistics nuances of a prompt become tangential to the solution.

---
## 问题的重构

- 诊断
  - 追问根原因
- 分解
- 重构
  - 问题原因多方面，寻找更好的问题，改变问题的陈述
- 约束

???
four key components for effective problem formulation: problem diagnosis, decomposition, reframing, and constraint design.

---
## A. 诊断

- 追问：到底是什么问题

---
## 5 个为什么

- 连问很多个“为什么”，来深入挖掘一个问题的根本原因，直到达到问题的根本源头
- 通常需要连问 5个，才能更全面了解问题并找到解决方案
- 更好理解问题本质，采取针对性措施来解决问题，而不仅仅是应对问题的表面症状

---
## 5 Why 步骤

- 首先，明确发现的问题是什么。这可能是一个具体的故障、挑战或不良结果
- 问第一个“为什么”：问自己为什么发生了这个问题。这有助于识别问题的直接原因
- 回答第一个“为什么”：回答问题，然后问自己为什么这个答案是正确的
- 问第二个“为什么”：基于第一个答案，问自己为什么这个问题出现了，深入挖掘问题的根本原因
- 重复过程：继续这个过程，依次问五个“为什么”，直到找到问题的根本原因为止。通常，五个“为什么”就足够了，但有时可能需要更多

???
discern the fundamental underlying a problem. In fact, they often start their problem formulation process by using the “Five Whys” technique to distinguish the root causes from mere symptoms.

    A particular instance is the subarctic oil problem, which involved cleaning up subarctic waters after the catastrophic Exxon Valdez oil spill. Collaborating with the Oil Spill Recovery Institute, InnoCentive pinpointed the root cause of the oil cleanup issue as the viscosity of the crude oil: the frozen oil became too thick to pump from barges. This diagnosis was key to finally cracking the two-decade-old problem with a solution that involved using a modified version of construction equipment designed to vibrate the oil, keeping it in a liquid state.

---
## B. 分解

分解为子问题

---
## 例

- 问题：实施一个强大的网络安全框架
- 分解为子问题
  - 安全策略
  - 漏洞评估
  - 身份验证协议
  - 员工培训

???
I tested how AI improves with problem decomposition using a timely and common organizational challenge: implementing a robust cybersecurity framework. Bing AI’s solutions were too broad and generic to be immediately useful. But after breaking it down into sub-problems — e.g., security policies, vulnerability assessments, authentication protocols, and employee training — the solutions improved considerably. The snapshots below illustrate the difference. Methods such as functional decomposition or work breakdown structure can help you visually depict complex problems and simplify the identification of individual components and their interconnections are most relevant for your organization.

---
class: middle, center
## 分解问题

巴塞罗那举办奥运会那年，哪支欧洲足球队赢得了冠军联赛？

请一步步回答

---
class: middle, center
## AI 会分解

请一步步回答

巴塞罗那举办奥运会，是哪年？

xx 年，哪支欧洲足球队赢得了冠军联赛？

---
class: middle, center
## C. 重构

寻找更好的问题

用各种形式重构问题

---
class: middle, center
## 寻找更好的问题

创造性的解决方案几乎总是来自对问题的另一种定义

---
class: middle, center
## 抱怨电梯慢

---
class: middle, center
## 寻找更好的问题

人们在电梯里，无事可做，尴尬

---
class: middle, center
## 寻找更好的问题

加一面镜子

大家照镜子了，就不觉得电梯慢了

---
class: middle, center
## 寻找更好的问题

问题的最初理解不一定是错的：安装一部新电梯也可能会奏效

它只是提出了对问题的不同理解

---
class: middle, center
## 寻找更好的问题

问题的原因是多方面的，可以通过多种方式解决

存在单一根本问题的想法可能会产生误导。问题通常是多种原因造成的，可以通过多种方式解决

---
class: middle, center
## 寻找更好的问题

重构的目的不是找到“真正的”问题，而是看看是否有更好的问题需要解决

例如，电梯问题可以重新定义为高峰需求问题（太多人同时需要电梯）

带来新的解决方案：分散需求，错开人们的午休时间

---
class: middle, center
## 改变问题的陈述

---
## 改变问题的陈述，带来创新想法

- 一个人到底是如何想出解决方案的？
- 我们记忆里有答案
- 只是我们的问题还没有形成，我们的大脑不能检索到它
- 问题的陈述是记忆的线索

---
## 改变问题的陈述

- 用许多不同的方式来描述正在解决的问题
- 讨论，从别人的陈述中得到启发
- 改变提示
- 探索各种类比，来表示问题

???

Problem reframing involves changing the perspective from which a problem is viewed enabling alternative interpretations. By reframing a problem in various ways, you can guide AI to broaden the scope of potential solutions, which can, in turn, help you find optimal solutions and overcome creative roadblocks.

Consider Doug Dietz, an innovation architect at GE Healthcare, whose main responsibility was designing state-of-the-art MRI scanners. During a hospital visit, he saw a terrified child awaiting an MRI scan and discovered that a staggering 80% of children needed sedation to cope with the intimidating experience. This revelation prompted him to reframe the problem: “How can we turn the daunting MRI experience into an exciting adventure for kids?” This fresh angle led to the development of the GE Adventure Series, which dramatically lowered pediatric sedation rates to a mere 15%, increased patient satisfaction scores by 90%, and improved machine efficiency.

Now imagine this: employees are complaining about the lack of available parking spaces at the office building. The initial framing may focus on increasing parking space, but by reframing the problem from the employees’ perspective — finding parking stressful or having limited commuting options — you can explore different solutions. Indeed, when I asked ChatGPT to generate solutions for the parking space problem using initial and alternative frames, the former yielded solutions centered on optimizing parking layouts or allocation and finding new spaces. The latter produced a diverse solution set such as promoting alternative transportation, sustainable commuting, and remote work.

To effectively reframe problems, consider taking perspective of users, exploring analogies to represent the problem, using abstraction, and proactively questioning problem objectives or identifying missing components in the problem definition.

How You Define the Problem Determines Whether You Solve It
by Art Markman
June 06, 2017

https://hbr.org/2017/06/how-you-define-the-problem-determines-whether-you-solve-it?utm_medium=social&utm_campaign=hbr&utm_source=twitter&tpcc=orgsocial_edit

Summary.   

---
class: middle, center
## 改变视角

改变看待问题的视角，从而实现不同的解释

---
class: middle, center
## 改变视角

GE Healthcare 的创新架构师 Doug Dietz

---
class: middle, center
## 初始问题

如果让孩子不害怕 MRI 检查？

---
class: middle, center
## 重构问题

如何让 MRI 检查变成孩子们激动人心的冒险？

???
- 在医院，他看到一名惊恐的孩子正在等待扫描，并发现 80% 的儿童需要镇静剂来应对这种令人恐惧的经历
- 他重新思考了这个问题：“如何才能将令人畏惧的 MRI 体验变成孩子们激动人心的冒险？”
- 这一全新角度催生了 GE Adventure 系列的开发
- 该系列将儿科镇静率大幅降低至仅 15%，将患者满意度评分提高了 90%，并提高了机器效率

---
class: middle, center
## 初始问题

员工抱怨办公楼缺乏可用停车位

问题：停车位不足

优化停车布局或分配以及寻找新空间

---
class: middle, center
## 重构问题

从用户角度重构问题

停车压力、通勤选择有限

其它交通方式、远程工作

---
class: middle, center
## 通过抽象，重构问题

具体问题：吹风机

抽象问题：让空气运动起来

???
- 具体问题
   - 具体的、讨论所作用的物体（例如真空袋）
   - 导致检索与问题高度相关的特定信息（例如不同类型的真空袋）
- 使用抽象
   - 找到几种方法来描述正在解决的问题的本质
   - 重点是对象之间的关系或更抽象的目标描述（例如将污垢与空气分开）
   - 这些描述将帮助人们回忆与问题所涉及的领域关系更远的知识
   - 创造性的来源

???
新的创新似乎凭空而来。怎么会有这么多人这么久都没有找到解决问题的办法呢？第一个人到底是如何想出这个解决方案的呢？事实上，大多数提出创造性解决方案的人都依赖于一种相对简单的方法：在解决问题的人们的集体记忆中寻找解决方案。也就是说，致力于解决问题的人知道一些可以帮助他们找到解决方案的东西——他们只是还没有意识到他们知道这一点。在进行创造性问题解决时，问题的陈述是记忆的线索。这就是进入记忆并提取相关信息的方法。为了生成问题的各种可能的解决方案，问题解决者（或小组）可以改变问题的描述，从而从记忆中提取新的信息。最具创造力的人和团体能够找到许多不同的方式来描述正在解决的问题

如果你想从记忆中检索出其他东西，你需要改变提示。如果我现在让你想想沙拉，你可能会想起有关生菜、西红柿和调料的信息，即使你一分钟前还在考虑生日聚会

最有创造力的人和团体能够找到许多不同的方式来描述正在解决的问题。其中一些陈述将是具体的，并讨论所作用的物体（例如真空袋）。这导致检索与问题高度相关的特定信息（例如不同类型的真空袋）。然后，小组应该找到几种方法来描述正在解决的问题的本质，重点是对象之间的关系或更抽象的目标描述（例如将污垢与空气分开）。这些描述中的每一个都将帮助人们回忆与问题所涉及的领域关系更远的知识

我们大多数人一直在错误的地方寻找我们的创造性见解。我们要求人们“跳出框框思考”，但我们应该要求人们找到更多关于框框的描述，看看是什么让我们记住了

???
New innovations can seem like they come out of nowhere. How could so many people have missed the solution to the problem for so long? And how in the world did the first person come up with that solution at all? In fact, most people who come up with creative solutions rely on a relatively straightforward method: finding a solution inside the collective memory of the people working on the problem. That is, someone working to solve the problem knows something that will help them find a solution — they just haven’t realized yet that they know it. When doing creative problem solving, the statement of the problem is the cue to memory. That is what reaches in to memory and draws out related information. In order to generate a variety of possible solutions to a problem, the problem solver (or group) can change the description of the problem in ways that lead new information to be drawn from memory. The most consistently creative people and groups are ones that find many different ways to describe the problem being solved.

If you want to retrieve something else from memory, you need to change the cue. If I now ask you to think about salad, you can likely call to mind information about lettuce, tomatoes, and dressing, even though you were thinking about birthday parties just a minute ago.

the most consistently creative people and groups are ones that find many different ways to describe the problem being solved. Some of those statements will be specific and talk about the objects being acted on (e.g. vacuum bags). That leads to retrieval of specific information that is highly related to the problem (e.g. different types of vacuum bags). Then, groups should find several ways to describe the essence of the problem being solved in ways that focus on the relationships among the objects or a more abstract description of the goal (e.g. separate dirt from air). Each of these descriptions will help people to recall knowledge that is more distantly related to the domain in which the problem is stated.

Most of us have been looking in the wrong place for our creative insights. We ask people to “think outside the box,” but we should be asking people to find more descriptions of the box and see what that causes us to remember.

---
class: middle, center
## 重构方法

---
class: middle, center
## 1. 创建重构所必需的讨论空间

问题的原因是多方面的

让大家接受，认为这是合理的

把重构变成日常

---
class: middle, center
## 2. 让局外人参与讨论

最有帮助的重构实践

最有用的输入往往来自那些理解你的世界但不完全属于你的世界的人

选择一个能自由发言的人

期待输入，而不是解决方案

---
## 案例
- 初始问题：员工不创新
    - 管理者最初将其视为能力问题，所以加培训
- 重构问题
  - 一个局外人说：这是激励问题
  - 许多员工知道如何创新，但对公司的投入度不高，不采取超出工作职责范围的主动行动
- 反感
  - 给予人们自主权、灵活工作时间、更具参与性的决策方式，提高员工投入度

---
class: middle, center
## 3. 以书面形式获取人们对问题的定义

写出来，会发现每个人写的不同，对问题有新的发现

---
class: middle, center
## 4. 主动寻找问题定义中缺失的部分

还有什么没想到？

局外人往往能够给予帮助

---
class: middle, center
## 5. 这是一个什么类型的问题？

技术问题？心理问题？

心理定势：技术人员总认为是一个技术问题

但可能并不是

---
class: middle, center
## 6. 分析没有出现问题的例外情况

探索这些积极的例外（亮点）

分析：“该情况有何不同？”，通常可以发现有意思的隐藏因素

分析问题，总让人沮丧，但分析没有问题的例外情况，会很高兴

---
class: middle, center
## 7. 对目标提出质疑

这个目标真的是我们想要的吗？

---
class: middle, center
## 收养宠物 vs 让宠物活下去

让主人有能力继续养育它们

---
class: middle, center
## 战胜敌人 vs 敌人不再冒出来

帮助重建

???

creative solutions nearly always come from an alternative definition of your problem

https://edisciplinas.usp.br/pluginfile.php/4603288/mod_resource/content/1/Are%20You%20Solving%20the%20Right%20Problems_.pdf

it proposes a different understanding of the problem

Note that the initial framing of the problem is not necessarily wrong. Installing a new lift would probably work. The point of reframing is not to find the “real” problem but, rather, to see if there is a better one to solve. In fact, the very idea that a single root problem exists may be misleading; problems are typically multicausal and can be addressed in many ways. The elevator issue, for example, could be reframed as a peak demand problem—too many people need the lift at the same time—leading to a solution that focuses on spreading out the demand, such as by staggering people’s lunch breaks.

seven practices:

1. Establish legitimacy

establish the method’s legitimacy within the group, creating the
conversational space necessary to employ reframing. 

2. Bring outsiders into the discussion.

This is the single most helpful reframing practice.

Many of their employees already knew how to innovate, but they didn’t feel very engaged in the company, so they were unlikely to take initiative beyond what their job descriptions mandated

What the managers had first framed as a skill-set problem was better approached as a motivation problem.

They abandoned all talk of innovation workshops and instead focused on improving employee engagement by (among other things) giving people more autonomy, introducing flexible working hours, and switching to a more participatory decision-making style. The remedy worked. Within 18 months workplace satisfaction scores had doubled and employee turnover had fallen dramatically. And as people started bringing their creative abilities to bear at work, financial results improved markedly. Four years later the company won an award for being the country’s best place to work.

Look for “boundary spanners.”

the most useful input tends to come from people who understand but are not fully part of your world

Choose someone who will speak freely.

Expect input, not solutions.

3. Get people’s definitions in writing.

4. Ask what’s missing

5. Consider multiple categories.

6. Analyze positive exceptions.

To find additional problem framings, look to instances when the problem did not occur, asking, “What was different about that situation?” Exploring such positive exceptions, sometimes called bright spots, can often uncover hidden factors whose influence the group may not have considered.

7. Question the objective.

---
class: middle, center
## D. 约束

限制解决方案搜索的：输入、过程和输出

例：写作文稿，限制长度、格式、语气、目标受众

???

限制来描绘问题的边界。您可以使用约束来指导 AI 生成对当前任务有价值的解决方案。当任务主要以生产力为导向时，采用具体且严格的约束来概述背景、边界和结果标准通常更合适。相比之下，对于以创造力为导向的任务，尝试施加、修改和消除约束可以探索更广阔的解决方案空间并发现新的视角

例如，品牌经理已经在使用 Lately 或 Jasper 等多种人工智能工具来大规模制作有用的社交媒体内容。为了确保这些内容与不同的媒体和品牌形象保持一致，他们通常会对长度、格式、语气或目标受众设置精确的限制

然而，在寻求真正的原创性时，品牌经理可以消除格式限制或将输出限制为非常规格式。 GoFundMe 的“帮助改变一切”活动就是一个很好的例子。该公司的目标是制作年度回顾创意内容，不仅能表达对捐助者的感谢并唤起情感，而且能从典型的年终内容中脱颖而出。为了实现这一目标，他们设置了非正统的限制：视觉效果将完全依赖人工智能生成的街头壁画风格的艺术，并以所有筹款活动和捐助者为特色。 DALL-E 和稳定扩散生成单独的图像，然后将其转化为充满情感的视频。结果是：视觉上具有凝聚力和引人注​​目的美感，赢得了广泛的赞誉

???
Problem constraint design focuses on delineating the boundaries of a problem by defining input, process, and output restrictions of the solution search. You can use constraints to direct AI in generating solutions valuable for the task at hand. When the task is primarily productivity-oriented, employing specific and strict constraints to outline the context, boundaries, and outcome criteria is often more appropriate. In contrast, for creativity-oriented tasks, experimenting with imposing, modifying, and removing constraints allows exploring a wider solution space and discovering novel perspectives.

For example, brand managers are already using several AI tools, such as Lately or Jasper, to produce useful social media content at scale. To ensure this content is aligned with different media and brand image, they are often setting precise constraints on the length, format, tone or target audience.

When seeking true originality, however, brand managers can eliminate formatting constraints or restraining the output to an unconventional format. A great example is GoFundMe’s Help Changes Everything campaign. The company aimed to generate year-in-review creative content that would not only express gratitude to its donors and evoke emotions but also stand out from the typical year-end content. To accomplish this, they set unorthodox constraints: the visuals would rely exclusively on AI-generated street mural-style art and feature all fundraising campaigns and donors. DALL-E and Stable Diffusion generated individual images that were then transformed into an emotionally charged video. The result: a visually cohesive and striking aesthetic that garnered widespread acclaim.

---
## 小结

- 识别、分析和描述问题
- 诊断：5 Why，追问根原因
- 分解
- 重构：问题原因多方面，寻找更好问题，改变问题的陈述
- 约束：描绘问题范围和边界