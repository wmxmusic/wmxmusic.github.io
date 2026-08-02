---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 2dc02c410d4799a8564beefc54554009_a704ffc48e1511f1bfea525400e6dd8f
    ReservedCode1: EApCCbBlvixGuv8DkoBCjBaREQgQ0fem642aiTCXIjrKHjyQb/+UTyjr/ZfFPnowmGzCT07Bn9T8jF5cQcUuaCVGqO/UOdhOCq4EKg2mdZ7Mo+sGRoWkRK/wYhKavXlaKDLIJTCQiY1lzaLwSjeEfFsAAm5Zb4SHnjWgb9iZUjRcxczkKbl/+Tq3aqw=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 2dc02c410d4799a8564beefc54554009_a704ffc48e1511f1bfea525400e6dd8f
    ReservedCode2: EApCCbBlvixGuv8DkoBCjBaREQgQ0fem642aiTCXIjrKHjyQb/+UTyjr/ZfFPnowmGzCT07Bn9T8jF5cQcUuaCVGqO/UOdhOCq4EKg2mdZ7Mo+sGRoWkRK/wYhKavXlaKDLIJTCQiY1lzaLwSjeEfFsAAm5Zb4SHnjWgb9iZUjRcxczkKbl/+Tq3aqw=
---



# WMx Music

这是 **wmxmusic** 的个人音乐作品展示网站，基于 Hugo + PaperMod 主题构建，托管于 GitHub Pages。

## 关于

网站展示以下三类内容：

- **AI 音乐**：利用 AI 工具辅助生成的音乐作品
- **原创音乐**：独立作词、作曲、编曲、混音的全流程原创歌曲
- **短视频创作**：音乐与视觉融合的短视频作品

## 技术栈

- 静态网站生成器：[Hugo](https://gohugo.io/)
- 主题：[PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- 托管平台：[GitHub Pages](https://pages.github.com/)
- 域名：https://wmxmusic.github.io

## 本地开发

```bash
# 安装 Hugo（Windows）
winget install Hugo.Hugo.Extended

# 启动本地开发服务器
hugo server -D

# 构建静态文件
hugo
```

## 如何添加作品

在 `content/works/` 下创建新的 `.md` 文件，参考已有示例页面。

### 嵌入网易云音乐外链播放器

1. 打开 [网易云音乐](https://music.163.com/) 网页版，找到你的歌曲
2. 进入歌曲页面，点击"生成外链播放器"
3. 复制生成的 iframe 代码
4. 粘贴到 Markdown 文件中，示例：

```html
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0"
        width="100%" height="86"
        src="//music.163.com/outchain/player?type=2&id=你的歌曲ID&auto=0&height=66">
</iframe>
```

### 跳转汽水音乐链接

汽水音乐暂不支持外链嵌入，可使用链接跳转：

```html
<a href="https://www.douyin.com/your-song-link" target="_blank">在汽水音乐中收听</a>
```

### 嵌入 B站视频

1. 打开 [B站](https://www.bilibili.com/) 视频页面
2. 点击视频下方的"分享"按钮
3. 选择"嵌入代码"，复制 iframe 代码
4. 粘贴到 Markdown 文件中，示例：

```html
<iframe src="//player.bilibili.com/player.html?bvid=你的BVID&page=1"
        scrolling="no" border="0" frameborder="no" framespacing="0"
        allowfullscreen="true" width="100%" height="500">
</iframe>
```

### 嵌入 YouTube 视频

```html
<iframe width="100%" height="500"
        src="https://www.youtube.com/embed/你的视频ID"
        frameborder="0" allowfullscreen>
</iframe>
```
*（内容由AI生成，仅供参考）*
*（内容由AI生成，仅供参考）*
