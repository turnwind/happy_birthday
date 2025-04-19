# 黑客风格生日祝福 (Hacker-Style Birthday Greeting)

一个漂亮的生日祝福网页，带有动画文字、音乐和爱心特效。

## 特性

- 开始按钮和欢迎界面
- 背景音乐自动播放（可暂停）
- 动画文字祝福
- 爱心动画特效
- 黑客风格的背景效果

## 使用方法

fork 本项目，修改 `2025黑客爱心.html` 文件，将里面的内容替换为你自己的内容，然后在 github pages 或者其它一些托管网站上部署(如 netlify)即可。

### 需要修改的内容

1. 修改音乐文件：替换 `Maple暖枫 - 风居海铃.mp3` 为你自己的音乐文件
2. 修改祝福文字：搜索 `S.UI.simulate` 函数，修改其中的文字内容
3. 修改爱心中的文字：搜索 `❤一定要天天开心哟！` 并替换为你想要的文字

### 部署选项

- Vercel 部署

   [![Deploy with Vercel](https://vercel.com/button)](https://github.com/turnwind/happy_birthday)

- Netlify 部署（国内用户推荐，不被墙）

   [![Deploy with NEtlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/turnwind/happy_birthday)

## 预览

打开 `2025黑客爱心.html` 文件，点击"准备好了，我们开始吧！"按钮即可看到效果。

## 技术栈

- HTML5
- CSS3
- JavaScript
- Canvas

## 许可

MIT
