# Daily Learning
## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

###### 使用相对URL展示仓库中已有的图片例子：（此处无图片因此失败了）
###### !：表示这是一个图片，而不是普通的链接。
###### []：中括号内是替代文字（alt text），当图片无法加载时显示这段文字，也用于屏幕阅读器辅助阅读。
###### ()：小括号内是图片的路径或 URL，可以是本地路径或网络地址。

![Mona the Octocat](myrepo/original.png)

###### 使用绝对URL展示互联网上的图片例子：（无法改变图像大小和位置）
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```

###### 使用HTML语言可以改变图像大小和位置例子：
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
###### img = 功能性标签，用来表示需要插入图片；alt = 如果图片加载失败会显示出的/阅读给视障人士的替代文字；src = 来源source

