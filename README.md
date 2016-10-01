# Markdown相关

---

Markdown 由 [John Gruber](http://daringfireball.net/) 创造。其使得用户可以专注于内容本身

一些用途:

- 写作

- 记录待办事项

- 时间轴 timeline: [markline](https://www.npmjs.com/package/markline)

- 演示 presentation: [marp](https://github.com/yhatt/marp)

- 项目管理: [Yash](https://github.com/xumingming/yash)

- 生成图表: [mermaid](https://knsv.github.io/mermaid/)

- gitbook

...


常用语法：

- 标题

\#一级标题

\##二级标题

\###三级标题

依次显示为

#一级标题

##二级标题

###三级标题


- 分割线

\-\-\- 或 \*\*\*

显示为

---


- 列表

    - 无序列表, 如

        ````
        - foo

        - fooo

        - foooo
        ````

        显示为

        - foo

        - fooo

        - foooo

    - 有序列表

- 超链接

````
[w3schools](http://www.w3schools.com/)
````

显示为

[w3schools](http://www.w3schools.com/)

- 图片

````
![](url)
````

- 代码

代码区块前统一缩进四个空格或一个 <kbd>TAB</kbd>


- 换行

段落结束之后空一行

如需强制空行: ````<br></br>````


编辑器 (按平台):

- Win: [MarkdownPad 2](http://markdownpad.com/)

- Android:

    - MarkdownX: [Google Play](https://play.google.com/store/apps/details?id=com.ryeeeeee.markdownx&hl=zh), [酷安](http://coolapk.com/apk/com.ryeeeeee.markdownx)

    - neutriNote: [Google Play](https://play.google.com/store/apps/details?id=com.appmindlab.nano), [酷安](http://coolapk.com/apk/com.appmindlab.nano) (支持数学公式)

    - Writeily Pro: [Google Play](https://play.google.com/store/apps/details?id=me.writeily), [酷安](http://coolapk.com/apk/me.writeily.pro)

- Chrome: [noteroot Editor](https://chrome.google.com/webstore/detail/noteroot-editor/migeiocipmppkdjahehpchaechhbohbo?utm_source=chrome-app-launcher-info-dialog) (支持数学公式)

- 跨平台:

    - [Atom](https://atom.io/) + [Markdown Preview Plus](https://atom.io/packages/markdown-preview-plus) 插件 (按 <kbd>ctrl-shift-m</kbd> 启用预览；支持数学公式)

    - [Visual Studio Code](https://code.visualstudio.com)

    - [Typora](https://www.typora.io)

- 在线编辑器/博客平台:

    - [Cmd Markdown](https://www.zybuluo.com/mdeditor#344907)

    - [简书](http://www.jianshu.com/)


阅读器：

- uwp: [Markdownr](https://www.microsoft.com/zh-cn/store/p/markdownr/9nblggh6blt3)

Tips:

- 输入公式(需编辑器支持):

 比如想输入

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/4ffd15697f84951ae199ef319645c6add13fcb8a)

可以输入:

    $$
    E_0 = mc^2
    $$

详细的用法见最后 “有用的链接” 部分


- 插入视频:

    - 直接插入，可以播放

        - video标签

        以一个Linux的纪录片为例

        ````
        <video id="video" controls="" preload="none"width="480" height="244" poster="http://i0.hdslb.com/u_user/5b3c86b2251400dfe5aaf21a8ffa7378.jpg">
              <source id="mp4" src="http://ws.acgvideo.com/c/7b/6857045-1.mp4?wsTime=1474479606&wsSecret2=f6964fbbcb6bb916271fd5f7aa642301&oi=1780870356&internal=1" type="video/mp4">
              <p>Your user agent does not support the HTML5 Video element.</p>
            </video>
        ````

        - iframe

    - 插入缩略图，点击后跳转

    ````
    [![](http://i0.hdslb.com/u_user/5b3c86b2251400dfe5aaf21a8ffa7378.jpg)](http://ws.acgvideo.com/c/7b/6857045-1.mp4?wsTime=1474479606&wsSecret2=f6964fbbcb6bb916271fd5f7aa642301&oi=1780870356&internal=1)
    ````


有用的链接:

- 基本语法:
http://www.appinn.com/markdown/

- 数学公式: http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference
