

<aside>
💡 Apple Vision Pro让我重燃起了计算机的兴趣，虽然VR设备一堆堆，但是只有Apple Vision Pro让我突然觉得计算机的未来很快就要来了，像chatrGPT这样的Machine Learning加上Apple Vision Pro这样的VR设备，可能一个十分真实的虚拟人物和世界要在5-10年后就能看见了。

虽然我一直很排斥Machine Learning这样的黑箱技术，但是还是有必要再深入了解一下，但是我的首要兴趣还是Apple Vision Pro这样的MR设备，虽然此文主要是Developing on Vision OS，但这只是我没有能力参与设计像Apple Vision Pro这样设备的权衡。所以，一边Developing on Vision OS，一边了解Apple Vision Pro的技术和原理咯。

</aside>

# Reference

[Designing for visionOS | Apple Developer Documentation](https://developer.apple.com/design/human-interface-guidelines/designing-for-visionos/)

[Learn - visionOS - Apple Developer](https://developer.apple.com/visionos/learn/)

[Creating your first visionOS app | Apple Developer Documentation](https://developer.apple.com/documentation/visionOS/creating-your-first-visionos-app)

[Apple Vision Pro Tech](Apple%20Vision%20Pro%2060aecfc08c524ee2a9df631616af016d/Apple%20Vision%20Pro%20Tech%20eb2964c6dc6e4c6f960d711ab3ad3690.csv)

[Developing on Vision OS](Apple%20Vision%20Pro%2060aecfc08c524ee2a9df631616af016d/Developing%20on%20Vision%20OS%20dac523886af54873bea3c8ec13ea1cdf.csv)

# R1 chip

Tags: R1
Created time: February 22, 2024 2:43 PM
Status: Not started

AppleR1来负责透传，也就是实时处理摄像头采集的信息（其实是ISP处理过的数据了已经是，它比如处理相机畸变等），处理深度信息，甚至建模（建模不清楚是不是M系列芯片做的），然后渲染。M系列芯片主要是运行visionOS系统，渲染VR的模型

# 畅想

以后苹果可以用Mac studio这种开始及作为本地渲染的工具来运行大型的VR游戏什么应用之类，所以这时候就是M2制作系统机应用的渲染，然后R1负责就是周围环境的采集和处理，这样的话，然后用无线传输协议，然后把这个数据传到Apple V Pro上，相当于就是他的Apple in Pro的就是提升了很多，然后发热的降低了很多，然后他只渲染画面与类似于你有个外置显卡的那种感觉。

# [[Apple架构]]

关于Apple架构之前写过一个浅谈，这次想在此基础上深挖一下Apple最近在m芯片统一硬件设计之后，软件架构有哪些变化，还有Apple vision pro出来之后有哪些更新？

