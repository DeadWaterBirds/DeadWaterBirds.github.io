# Dead Water Birds 乐队主页

这是 Dead Water Birds 的官方网站源码，包括三个主要页面：

- **index.html** → 首页  
- **music.html** → 音乐页面  
- **gigs.html** → 演出页面  

---

## 1. 修改网页内容

### 1.1 修改首页（index.html）
- 打开 `index.html` 文件，你会看到以下几个主要部分：
  - **About Us** → 乐队介绍，可以改成你们自己的文字。
  - **Gigs** → 点击后跳转到演出页面。
  - **Music** → 点击后跳转到音乐页面。
  - **Contact** → 邮箱、网易云链接，可以换成你们自己的。

如果要改文字，直接找到对应的 `<p>` 段落，把内容换掉就行。

---

### 1.2 修改音乐页面（music.html）
- 页面头部背景图：`music_bg.jpg` → 可以换成你们喜欢的图片（比如专辑封面）。
- 在 `<iframe>` 里可以嵌入网易云播放器：
  ```html
  <iframe src="https://music.163.com/outchain/player?type=2&id=歌曲ID&auto=0&height=66"></iframe>
