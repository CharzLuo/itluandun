# Apple Wtach - Apple Wtach设计需知

越来越多的朋友已经收到了Apple Watch，甚至已经开始了第四次充电。作为设计师，面对正在或者准备适配Apple Watch的设计工作，我们应该注意什么呢？  

> 在SoundWave从事UI/UX工作的John Sherwin，给了我们5点建议。
> 末尾有11分钟的赶货视频，建议在WIFI环境下观看。

---- 

## 5 Things You Need to Know When Designing For Apple Watch

Apple Watch相比iPhone来说，交互和体验有了很大的区别。  

Apple Watch主要还是以场景补充作为主要目的，辅助以其他类似于运动记录、心跳等传感器相关功能。  

因此在做Apple Watch的相关设计时，我们不能依旧只参照iPhone的设计规则，而更应该结合场景，来让用户体验到iPhone与Apple Watch无缝使用体验。

1. Learn the Guidelines
研究设计规则

Apple Watch的设计规则非常严格。iOS其实也一样，但由于现在iOS设计规则很成熟了，设计师们也通过很长时间对规则的探索和创新，因此让他们的App变得独一无二。

估计到目前为止，大家还都停留在对Apple Watch的熟悉阶段。不过比较好的是，Apple官方发布了很多PSD文件来供大家使用，来研究他们的新设计规则，当然开发者也可以作为素材使用。  

Apple官方对设计规则也给出了非常详细的说明，比如按钮，字体大小，间距，表格和层次结构，作为设计师，研究设计规则，是基本也是很重要的。

2. Simplify Interactions
简化交互

在2013/14年开始，视觉设计变得非常重要。iOS的风格变得更加简洁，扁平。其实在此之前，设计师就已经开始使用自定义的过场特效和动画效果，来提高App的体验和引导效果。  

Apple Watch则把这种简化提升到了一个新的高度，开始着重关注更高级和更小的交互操作，最终用户只需要很短的时间最快的完成他们的目标。  

因为手表的客观因素限制，所以屏幕不会有太多的地方让我们设计自定义的场景转换动画。这样也许是个好事，可以强迫设计师们更加关注用户体验，尽可能的优化操作。

在设计交互时，设计师是要确保用户在两步内，就可以完成他们任何想要的操作。
  

3. Use Animations Effectively
动画效果

在与UI元素进行交互的时候，常常伴随的就是动画效果。运用恰当，可以帮助用户更好的理解一些特定的操作，甚至提升用户在达成期待的整个过程的体验，有时候则可以创建全新、特有的用户体验。

最近，在使用Twitter的" favorite“ 按钮时，被点击开始到点击结束的反馈动画给征服，很简单的状态改变被一个小的爆炸效果所代替。

虽然这个动画没有提高实际内容，但是对用户而言，却很明确地解释了当前操作的意义。

[favorite](http://mmbiz.qpic.cn/mmbiz/mGXCselWFsu7EnKmJxfjOG1P7ial9WotticcsDPtjQCVnvbSiao3NV7cdEiadLjFicByerK0lpY4ETzvbuo250wSsLA/640?wx_fmt=png&tp=webp&wxfrom=5)
  
Apple Watch现在的动画特效，还是以设计师设计为主，除非Apple发布Apple Watch 的CoreAnimation组件，否则开发者们只能根据设计师们提供的动画和特效进行开发。  

作者在这部分举了个例子，利用After Effects设计了一个动画，并以30fps导出了PNG序列帧。  

主要步骤如下（鉴于我自己大学学习AE的时候也都是英文版，所以我就不翻译步骤了- -）：
  
[Step1](http://mmbiz.qpic.cn/mmbiz/mGXCselWFsu7EnKmJxfjOG1P7ial9Wott3KbGOx7f5UmxEuBAPeoBj6kVv1GggWvu88JjZxZobGhv92FhKl4ehA/640?wx_fmt=png&tp=webp&wxfrom=5)

Start by selecting Composition \> Add to Render Queue

[Step2](http://mmbiz.qpic.cn/mmbiz/mGXCselWFsu7EnKmJxfjOG1P7ial9Wottrkkmw9f8qoQaj2Xn813qlEbFXsWyDic4KsDrlZb3XKJojibMYdr7msqg/640?wx_fmt=png&tp=webp&wxfrom=5)  

Bring up the ‘Output Module Settings’ by selecting ‘Lossless’
  
[Step3](http://mmbiz.qpic.cn/mmbiz/mGXCselWFsu7EnKmJxfjOG1P7ial9WottibgJhX4my2icZb2qibwc3u9DNibnXfoqT3ZfO23WYOFLkRgUcEXM9gTZUw/640?wx_fmt=png&tp=webp&wxfrom=5)

Change the format from ‘Quicktime’ to ‘PNG Sequence’
  
[Step4](http://mmbiz.qpic.cn/mmbiz/mGXCselWFsu7EnKmJxfjOG1P7ial9WottibgJhX4my2icZb2qibwc3u9DNibnXfoqT3ZfO23WYOFLkRgUcEXM9gTZUw/640?wx_fmt=png&tp=webp&wxfrom=5)  

Change the Channel from ‘RGB’ to ‘RGB + Alpha’

[Step5](http://mmbiz.qpic.cn/mmbiz/mGXCselWFsu7EnKmJxfjOG1P7ial9WottIicLWbDXjKnTT0ZtsOKk5rpG9yLMGibNR3cmYmQxIOia6MIibrXq8RHiaEA/640?wx_fmt=png&tp=webp&wxfrom=5)  

Finally, make sure you deselect ‘Use Comp Frame Number’ so your PNGS are named in numeric order starting from 0, instead of by where they appear on your timeline. Your Files should be named like this (filename0, filename1, filename2) and so on.  

4. Content Is Key
内容为王  

这句话是在做设计时经常听到的一句话，对于Apple Watch设计，依旧是真理。

Apple Watch官方提供预览的App，我们会发现只有重要的信息会被显示。  

向Instagram和Twitter这样提供大量内容的App，也回到了基础图片和文字的形式。  

Soundwave也采取了类似的形式。在Timeline只显示专辑封面，歌手名称和歌名。用户直接点击想看的内容或者播放按钮来听。  

5. Create a Seamless Experience
无缝体验  

Apple Watch不是作为一个独立的产品而存在，Watchkit也是iOS的衍生扩展，所以Watch App也应该是iOS产品的扩展。  

最基本的操作应该在Apple Watch上可以直接操作，更复杂的操作应该留给iPhone来解决。保证我们的App坚持这项准则，只是扩展iOS App功能，而不是添加了新的功能。  
  
[Notifications](http://mmbiz.qpic.cn/mmbiz/mGXCselWFsu7EnKmJxfjOG1P7ial9Wottmab37UVZibmekaW8xh7FKGn4CyHbYP3xMZQN70uhuGzEtOF1bUN7N8A/640?wx_fmt=png&tp=webp&wxfrom=5)

通知是一个很好的例子。

当用户收到了好友分享的一首歌，他们会通过Apple Watch收到推送通知，这时用户有几种操作选择，用语音回复；直接Like反馈或者忽略这条消息。想完成了” Like “ 操作或者回分享一首歌，通过Handoff即可。  

在手机锁屏状态下，点击Hnadoff icon，会直接推送最后一条收到的信息，来确保用户在使用时的无缝体验。  

6. Conclusion  

总的来说，在给Apple Watch做设计时，还是非常有意思的。当用户在使用Watch App时，我们需要确保哪些是需要work的哪些是可以不需要的，那么就需要更多的修改，测试，修改，测试，最终达到我们的目标。

作者11分钟左右的视频，建议WIFI环境下查看。

[A month with the Apple Watch](%5Bhttp://v.qq.com/page/g/t/r/g0152zozrtr.html%5D)
