# 中文社区推广文案

## V2EX

**标题：** 做了一个语音跟踪的提词器，录视频再也不用手动滚屏了

**内容：**
```
起因是老婆录视频总是 NG，用提词器还要手动控制滚动速度，经常跟不上或者跟太快。

于是花了几天做了这个：VoicePrompter

核心功能：语音跟踪
- 用 Web Speech API 识别你说的话
- 自动匹配到稿子对应位置
- 说到哪，滚到哪

其他功能：
- 7 种主题
- 字体大小可调
- 支持相机预览模式
- 纯前端，不需要后端

技术栈很简单：Vanilla JS + Web Speech API + GitHub Pages

完全免费开源：
- 在线使用：https://jzocb.github.io/teleprompter/
- 源码：https://github.com/jzOcb/teleprompter

欢迎 Star 和提 Issue，有什么想加的功能可以说。
```

---

## 掘金

**标题：** 周末写了个语音跟踪提词器，用 Web Speech API 实现"说到哪滚到哪"

**内容：**
```
## 背景

老婆是小红书博主，录视频的时候用提词器，但传统提词器有个问题：

1. 滚动速度是固定的
2. 说快了跟不上，说慢了又超前
3. 停下来想一下，字就飘走了

所以我想：能不能让提词器"听懂"我在说什么？

## 实现思路

用 Web Speech API 做语音识别，把识别结果和稿子文本做模糊匹配。

核心逻辑：
1. 实时获取语音识别结果
2. 在稿子中查找匹配的文本片段
3. 如果匹配到下一行的内容，自动滚动过去

关键代码：
- 监听 `recognition.onresult`
- 用 3 字符滑动窗口做模糊匹配
- 检测当前行说完（末尾字符出现）提前滚动

## 效果

说到哪，滚到哪。暂停也不怕，继续说就接上。

## 在线体验

https://jzocb.github.io/teleprompter/

源码：https://github.com/jzOcb/teleprompter

欢迎 Star ⭐
```

---

## 即刻

**内容：**
```
做了个小工具：语音跟踪提词器 🎤

录视频的时候，提词器能听懂你说话
说到哪，字就自动滚到哪
不用手动控制速度了

给老婆录小红书用的，她说终于不用 NG 二十遍了 😂

免费开源，网页直接用
👉 jzocb.github.io/teleprompter

#独立开发 #效率工具 #开源
```

---

## Reddit (r/SideProject)

**Title:** I built a voice-tracking teleprompter that scrolls as you speak

**Content:**
```
My wife records videos for social media and always complained about teleprompter apps - you have to guess the scroll speed, and if you pause or speed up, you lose your place.

So I built VoicePrompter: a teleprompter that listens to what you're saying and scrolls automatically.

Features:
- Voice tracking using Web Speech API
- Camera preview mode
- 7 themes
- Works on mobile and desktop
- Free, no signup, open source

Try it: https://jzocb.github.io/teleprompter/
GitHub: https://github.com/jzOcb/teleprompter

Would love feedback! What features would you want?
```
