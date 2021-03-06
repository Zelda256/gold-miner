> * 原文链接: [Designing the Icons for Flinto’s UI](https://medium.com/flinto-software/designing-the-icons-for-flinto-s-ui-ddd9e5788cce#.yr5asvf9c)
* 原文作者 : [Peter Nowell](https://medium.com/@pnowelldesign)
* 译文出自 : [掘金翻译计划](https://github.com/xitu/gold-miner)
* 译者 : [edvardhua](https://github.com/edvardHua)
* 校对者 : [Ruixi](https://github.com/Ruixi), [CoderBOBO](https://github.com/CoderBOBO)

# 我是如何为 Mac 应用 Flinto 设计 UI 图标的

[Flinto 团队](https://www.flinto.com/mac) 最近采访了我关于Flinto用户界面图标背后的设计流程。

#### 你是怎么为Mac版本的Flinto贡献自己的设计？

我参与了[Flinto](https://www.flinto.com/mac)新的Mac版本的用户界面部分和用户体验部分的设计，就在他发布之前的几个月。但是因为Flinto是一个特殊的工具，我们越是深入思考每一部分的用户体验，我们越感觉到Flinto需要大量的定制icons。譬如说Flinto应用的列表（List），工具栏（Toolbar），动画的设计面板（Transition Designer），下拉手势（Gestures dropdown）都需要他们独自的一套图标。所以，如何快速的设计图标变成了我的主要工作。

#### 当设计大型应用的图标和菜单的时候，你采用什么样的设计策略？

设计总是情境驱动的。我惊奇的发现专业Mac应用的情境设计是最复杂的工作之一，就算你只是设计图标。工具栏（Toolbar）的图标大小必须一致，而且最好根据图标知道用途。这与侧边栏的图标和下拉菜单看到的图标的设计原则上有所差异。 一些图标会以不同的尺寸和不同的样式重复出现在不同的地方。不是只要调整图标尺寸或者样式就能够适用于每一个用户界面的，所以我在设计图标的时候需要考虑到图标是否具有通用性以及不破坏用户界面的整体一致性。

![](https://cdn-images-1.medium.com/max/600/1*ttfWxwTTFE_Jy0yJhYwtPQ.jpeg)

我都是在纸上开始设计图标的，我一直坚信这个原则。我会在纸上画下我想象中这个图标的所有可能性，譬如设计的这个图标包含了什么暗喻以及图标可能需要/产生的变化。所以在**概念设计**的这个阶段上，我尽量让自己将所有的内容都写在我的纸上，甚至是一些不相关的想法。下一步则**分析**概念设计中的内容如何能够更好符合我们设计的目标，已有的限制以及这个图标的情境联系。

> 我发现将绘图构思和评估这两个过程分开进行是很至关重要的。前者的工作需要想象力，好奇心，而且持有自己主观的判断，是一个加法的过程，是心血来潮的创作。评估则需要批判性，实用性，以及需要考虑图标背后一连串所延伸出来的隐喻，是一个做减法的过程。如果你尝试同时做这两件事情，那么你会考虑不过来从而得不到任何结果。

我最近还在网上授课讲述我认为在[设计图标](http://shrsl.com/?~boxl)中最重要的原则。里面还包含了我是如何来评估我的想法和草稿的。

通常来说，只有一部分的设计想法会被保存到电脑里面。使用sketch可以提高我的生产效率并且在生产的过程中会有一些创造性的决定。但最主要的目的还是要完善和精炼图标的形式，保证每一个图标都是像素完美的。我对此具备相当大的热情，我对其他忽视这个细节的人感到很烦恼。

#### 能够为我们再稍微解释一下什么是“像素完美”和如何实现？

像素完美其实意味着很多东西，它更像是一个想法而不是一个能够具体描述的特征。像“注意细节”一样，当被忽视的时候我们能够很容易的感觉出来。完美的像素对小图标的可辨别度有巨大的影响。想要实现像素完美不仅仅是将设计元素的像素网格对齐（如下图）。这基本上来说就是在和锯齿做斗争。使用抗锯齿是很好的一件事情，但它会让图像一些地方产生模糊，尤其是在对角线和曲线中。

![](http://ww3.sinaimg.cn/large/a490147fjw1f2m0jk2o2kj20go0i4760.jpg)

举个例子，我们想在图层列表中加上一些注释来表明哪些层是被隐藏或者是被锁住的。当然给图层加上隐藏和锁定是很简单的事情，只需要点击按钮操作一下就好了。我们考虑的是我们有一个小的注释，他会占用一小部分空间，来注释两个已经隐藏和锁定图标。为了完成这个目标，我们的图标必须要做到像素完美。我对我设计的8x8大小的图标感到非常的自豪。

![](http://ww3.sinaimg.cn/large/a490147fjw1f2m0k0slikj20m807xjsz.jpg)

<figcaption>对于使用retina显示屏的读者，我们显示**“一半尺寸”**的位图，如图 1x 的全像素图标。对于非retina显示屏的读者，则使用**“双倍尺寸”**的位图，如图 2x 的全像素图标。 请以横向模式显示上图来获得最好的显示效果。</figcaption>

在一个理想的世界中，一枚制作精良矢量图标可以轻易地适应各种像素密度的输出，并在所有对应尺寸中显示效果良好。但是大部分时候，使用一倍大小的图标并不能够处理得到更高尺寸的图标。你可能需要先做一个完美的两倍尺寸的图标，然后再调整成一倍尺寸来创建一个新的视觉满意的图标。在Flinto中至少一半的图标都有其对应1倍和2倍尺寸，譬如贯穿整个过渡动画设计面板的"概念图层"图标。

![](http://ww4.sinaimg.cn/large/a490147fjw1f2m0ksytpgj20m808wq5a.jpg)

**针对于这块感兴趣的读者，这里有我是如何对Flinto图标的抗锯齿进行细调的技术细节。**

*  重新调整和重新定位图形来获得看上去视觉舒服的图形，尽管这样处理后位置或者像素值会有小数点，但在这个阶段视觉是重点。
*  只使用曲线或者圆角时，至少要使用2px来渲染 90° 角的半径圆，或者使用3px渲染180°角的半径圆，来作为圆的线段末尾（如下图）。1pt大小线的线段的圆角线帽的效果是很糟糕的，至少我们使用的屏幕都会将其放大三倍来显示。

![](http://ww4.sinaimg.cn/large/a490147fjw1f2m0lacz7xj20m80bmdha.jpg)

<figcaption>没有人想要模糊的线帽！只有三倍大小（或者更大）的显示器才能够对1pt大小的线条渲染清晰可见的圆角线帽。</figcaption>

*  为了让线条粗细更加一致，调整边框宽度/粗细来达到稍宽或者稍厚会比使用1pt的细曲线或者斜线更好。
*  消除不必要的模糊像素。这在你需要使用图形自身标记自己的时候将会很有效。
*  通过复制图形或者边框（同一方向）来轻微调整图形的粗细。
*  如果图标可以有小模糊锯齿能够为图标的其他部分提供一定帮助，这也是可以的。

当然还有其他有关于如何平滑抗锯齿的技巧，但是我刚才所说的是我从中获益最大的。

#### 什么造就了一枚好图标？

这是个问题！尤其是当图标包含了很多设计原则的时候。我在我的[图标设计课程](http://shrsl.com/?~boxl)里面通过讲我在Flinto工作遇到的一些故事来描述我是如何造就一枚好图标的。

其中的一个原则就是**使用熟悉的符号并且让他显眼**。当我们开始为Flinto的主页面的画布设计图标的时候，内森有一个想法，我们可以设计一个图标让我们回忆起[艾西勒的住宅](http://www.sj33.cn/architecture/slsj/jiaju/201405/38754_3.html)。艾西勒是一位建筑师，他设计了中世纪现代建筑的住宅，这种风格的住宅在加州很流行。

![](http://ww1.sinaimg.cn/large/a490147fjw1f2m0mhofdpj20go0ci74z.jpg)

![](http://ww4.sinaimg.cn/large/a490147fjw1f2m0mwpmrbj20go0cimye.jpg)

<figcaption>艾西勒的中世纪现代建筑的住宅给了我们灵感去探索设计一个独特的“home”图标。</figcaption>

我们认为这个想法很酷而且内森也买了一套使用这种设计元素的房子，所以我们对这个想法很有热情。我做了很多个home图标的概念设计，尝试着将艾西勒住宅的特点萃取到一个16*16正方形的图标里面，而且在图标不添加色彩和透明度效果。我们发现这些看似巧妙的图标并没有很好展现图标本身的职责而且作为home图标也不够显眼。于是我们决定做一个直观并且能够表达艾西勒住宅不对称特点而且对其他用户而言有高辨别度的图标。

![](http://ww4.sinaimg.cn/large/a490147fjw1f2m0nda8s2j20m80ab0sx.jpg)

<figcaption>直观胜过巧妙，我们选择了底部中间图标作为home键。</figcaption>

另外评价一个好图标的原则是他是否能够与周围的元素看上去融洽。这些元素包括图标周围的UI，邻接文本的大小和字重，操作系统的习惯（譬如说，在mac os下cmd+s是保存，而在win下则是ctrl + s），以及其他图标的集合。

所以尽管home图标基本上是单独存在的，但是工具图标，手势图标，排版图标都是集合方式存在的。设计图标的集合的挑战是很大的。你会在设计一个图标集合设计到一半的时候发现你所使用的视觉隐喻不能够适应每一个这个集合里面需要的图标，这意味着你需要重新做一遍。 🙈

![](http://ww3.sinaimg.cn/large/a490147fjw1f2m0nupc7uj20m80283yh.jpg)

这种情况通常发生在手势图标上（上图是以200%比例显示）现在这些图标看上去很简单和直观，然而我们在设计他时是有很多限制条件的，并且还要考虑未来的兼容性。一些我们在这里展示的图标还没有出现在Flinto中...但很重要的一点是，在遇到有需要的时候，我们设计的图标集能够扩展并且容纳它们。
