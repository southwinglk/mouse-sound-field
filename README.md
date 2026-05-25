# Mouse Sound Field

一个可以部署到 GitHub Pages 的单页声音实验网站。

## 在线页面

- Mouse Sound Field: https://southwinglk.github.io/mouse-sound-field/
- Flying Bird: https://southwinglk.github.io/mouse-sound-field/flyingbird.html

## 玩法

1. 打开网页后点击一次页面，允许浏览器播放声音。
2. 移动鼠标。
3. 鼠标移动越快，声音的声调越高；鼠标位置和移动速度会切换不同音色。

网页内置 12 种由 Web Audio API 生成的声音，不需要音频文件、服务器或数据库。

## Flying Bird 玩法

1. 打开 `flyingbird.html`。
2. 点击屏幕、触摸屏幕或按空格让小鸟上飞。
3. 穿过障碍物得分。
4. 撞到障碍物、天花板或地面会死亡，并播放惨叫音效。

小鸟上飞时会播放三连激光“啾啾啾”音效，第一次点击后会启动 8-bit 风格电子背景音乐。游戏同样不需要外部图片、音频文件或服务器。

## GitHub Pages 部署

1. 把 `index.html` 和这个 `README.md` 上传到 GitHub 仓库的默认分支。
2. 进入仓库的 `Settings`。
3. 打开 `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. Branch 选择默认分支，目录选择 `/ (root)`。
6. 保存后等待 GitHub Pages 发布。

发布后的访问链接通常是：

```text
https://<username>.github.io/<repo-name>/
```

任何拿到这个链接的人都可以直接访问。
