 - Museum Art Science & Technology

<p align="center">
  <img style="max-width:400px" src="https://mast-thu.github.io/logo.png" alt="Logo"/>
</p>

## 课程介绍

本课程依托清华大学艺术博物馆的丰富馆藏、标志性建筑空间和整体艺术氛围，通过“设计思维”、“为生活策展”、“博物馆之光”和“剪出你的艺博故事”四个单元，将美育与我校本科专业基础课程进行有机融合，以期达到辅助专业教学、服务大学美育和拓展师生通识视野的总体目标，让同学在感知、理解、表达和创造美的过程中，理解专业知识与技能在科技伦理与艺术生活中具备同样的价值，最终达成健全人格的养成。


### 多媒体部分

视频在博物馆中也是一种特殊的展品。例如，荷兰的犹太人纪念馆里，将二战大屠杀幸存者的访谈放在显示器上，旁边有耳机，观众走到旁边，可以坐下，戴上耳机（可以是多副），听取口述历史。再如美国的二战博物馆，在Youtube上有口述历史系列访谈。

剪辑长篇访谈音视频(talking heads)，特别是在资源有限(设备、人员、时间、资金）的情况下，有几个问题。一是尽可能保证音频/视频的高品质，使用20%的成本，达到80%的专业制作团队的水平；二是提高剪辑效率，Radiolab声称的素材比是45:1，Apocalypse Now的素材比是90:1，Michael Rosenblum的建议是600分钟真实事件-20分钟的拍摄素材-1分钟成片，在这样海量素材之下，需要有高效的剪辑工具。任课老师之一康师傅将录制自己的Podcast时的经验，结合[BBC Paper Edit](https://bbcnewslabs.co.uk/projects/digital-paper-edit/)的方法论，制作了开源工具["糙音速剪辑"](https://github.com/scateu/tsv_edl.vim)，发布到欧洲开源开发者大会[FOSDEM](https://fosdem.org/2024/schedule/event/fosdem-2024-2804-edit-video-audio-with-or-without-vim/)，来自德国的记者试用后甚至主动帮忙写了一篇[教程](https://zerwuerfnis.org/paper-cut-audio-editing-for-radio-journalism)。



进一步，我们不止于剪辑talking heads 🗣️，我们尝试从百年电影工业中汲取养分，服务于展览叙事。

<details markdown="1"><summary> ▶️  点此展开 </summary>

 - 多机位(Multicam): 采访中多机位的必要性: 把说话过程剪断，会使人的变化显得跳跃。而人类的视觉对于小的变化很敏感，但对于大的角度变化(大于30度的机位变化，30度原则)反而可以接受。在谈话的剪断跳跃点需要切到另一台摄像机，才能显得比较自然。
 - 多机位-好声音: 使用另一只手机作为录音机，近场收声。以击掌代替场记版🎬
 - 180度原则(不要越轴)，30度原则(机位变化要大)
 - 景别: 如音阶，不要跑调，记住各景别的高度(下缘)，如CU(到肩)，BCU(Big Close-Up, 也称Choke，掐脖)，ECU(Extreme CU, 也称意大利西部片CU，只拍眼)，MS，WS等。尽可能使用标准景别语言。
 - Interview的拍法 - BBC的Mojo持机法: 左手抱在右腋下撑住右肘，右手持手机(镜头一定擦干净)，作奥特曼状，构图使受访人在画面左侧看向右(或居右侧看向左)，直视采访人，而非镜头。
 - 视线: Eye line match: 画面双方地位要平等，眼睛的位置要平齐，眼看向的角度要对称。
 - 目光坚定: 受访者看向的位置一定要固定，平行于地面，向上或向下，或斜视，可以将采访者打造成反派。
 - B-roll的拍法 - Michael Roseblum 的 5-shot 方法，在BBC、汤森等新闻机构广泛使用。擦干净镜头，一动不动，屏住呼吸，以下5步各拍10秒。1. CU on action(手) 2. CU on face 3. WS on both 4. OTS(Over the Shoulder，也称PoV，Point of view，主观视觉) 5. 任意creative角度。
 - "Shoot where it's not": 抢占先机，例如拍门把手，守画面而等受访者入；
 - "Let her leave": 同时在受访者离开画面后，不要追着画面，让受访者离开画面，观众自然会想去看受访者去哪里了，即为一个非常好的剪辑点。
 - 结构风格: Michael Rosenblum 的 "Wow - Pirate - Star - Arc of story - Conclusion" 方法，每一个部分都是5 shots方法拍摄
 - 结构风格: Establishing Shots + B-roll over talking heads，不会出差错，四平八稳
 - 画面时长: 以自然语速能完整描述画面的时长为宜
 - 画面时长: Walter Murch经常会练习以正常速度播放，在剪辑点按下空格暂停，像打靶。如果多次打靶都打到同一个位置上，则证明剪辑点是精确的。
 - Cut on matched action: 比如电影Matrix中，Morpheus的转身，由Master shot转为CU。
 - Cut near the blink of an eye: In the blink of an eye书中，作者Walter Murch认为，人的眨眼表示对信息的接收完成，眨眼类似于存盘，在观众或演员的自然眨眼点处剪辑，也是较好的位置。
 - Inserts, Cutaway: 都属于B-roll，但Insert和主画面之间动作连贯，比如主画面在拧一个旋钮，Insert可以拍拧旋钮的动作；比如上菜，盘子由服务员贴近桌子的那一刻，就可以变到盘子内容特写了(包括服务员的手)。据说片场中专门会有Insert Day，专门留最后一天拍所需要的Inserts。这一点，借鉴之，采访后补拍对应的B-roll。
 - Reaction, Kuleshov effect
 - 音画时机: Always J Cut - Steve Audette of PBS
 - 音画时机: MTV，剪辑点先于重拍出现，就像闪电打雷轰隆隆。
 - 剪辑时机: 对话双方，一方说完话镜头应该立即切到对方，若多停留，则可能造成此方说话者被打造成反派。
 - Plan: 一页纸的script为一分钟，场记在script上标线的作用
 - Plan: 使用Spreadsheet来规划也是有效的办法
 - Plan: Michael Rosenblum也建议用纸和笔画出剪辑软件的时间线，V1 A1 A2, Sound bites, Narration，是行之有效的方法

如Walter Murch的Rule of 6: Emotion 51%, Story 23%, Rhythm 10%, Eye-trace 7%, Two-dimensional plane of screen 5%, Three-dimensional space of action 4%，给观者带来的情感永远是最重要的。

参考:
 - In the blink of an eye, by Walter Murch
 - iPhone Millionaire How to Create and Sell Cutting-Edge Video, by Michael Rosenblum
 - 纪录片 The Cutting Edge - The Magic of Movie Editing

</details>

器识其先，文艺其从。器量与见识，人的内在涵养、精神境界，故事、展品的内容总是最重要的。上述注意事项/Cheatsheet，只是文艺，永远要为故事服务。


## 课程花絮

## 展览回顾

## 正在展出 - 2024秋季学期

### 艺术家简介

### 展品一览

### 展陈设计

### 影像资源

## 过往展出 - 2024春季学期

### 艺术家简介

### 展品一览

### 展陈设计

### 影像资源

## 互动留言 & 联系方式

## Projects 开源项目

 - <https://github.com/scateu/tsv_edl.vim>

