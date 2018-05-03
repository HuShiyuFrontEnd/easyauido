# easyaudio
一个简单易用的音频模块 无框架版本/VUE单文件组件版本
一个由webAudio API搭建起来的功能强大的音频操作模块

## 这个模块要解决什么问题？
对于一般前端开发者，比较熟悉的可能是`<audio>`标签引入并操作音频，这个思路能解决绝大多数情况下的音频播放需求，而且也足够简单。如果你的开发需求仅限于，播放一段bgm，并且让它无限循环，那么你并不需要这个模块
但在比较倒霉的情况下，你会接到这样的需求，需要播放一些生僻的音频格式，你发现在有些平台上出现了解析的兼容问题。或者你需要添加进度、音量等控件，需要音频的一些值能够以数据的形式暴露出来。甚至你需要做一个音频list的播放，需要一个还过得去得封装，并提供多种播放策略可以直接使用。当然更夸张的可能你想要做个音频可视化，需要每一帧的音频频谱数据，或者做一些滤波器、声道混合、声源位置操作之类的有趣玩意儿。这些情况下，如果你懒得自己去学习、封装，可以考虑使用easyaudio

## WebAudio
webaudio是audio标签后，一个对于开发者更为透明的音频处理方案，虽然学习成本提高了，但是开发者可以参与的过程也更多了，更加丰富的API。另外webaudio尚处于未完全制定完成的过程中，虽然现代浏览器的支持足够了，不过有些地方确实有些细节不同。

## 简单开始
