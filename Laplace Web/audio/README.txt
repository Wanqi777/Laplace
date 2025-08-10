# 音频文件设置指南

为了解决浏览器跨域限制(net::ERR_BLOCKED_BY_ORB)导致的音频播放问题，我们需要将音频文件下载到本地项目中。

## 需要下载的音频文件

请从以下链接下载音频文件，并保存到当前文件夹(/Users/wuwanqi/Desktop/machina/omniscient-cocoon-red-version/audio)：

1. 背景音乐: https://assets.mixkit.co/music/preview/mixkit-ambient-drone-594.mp3
2. 点击音效: https://assets.mixkit.co/sfx/preview/mixkit-select-click-1109.mp3
3. 成功音效: https://assets.mixkit.co/sfx/preview/mixkit-unlocking-563.mp3
4. 失败音效: https://assets.mixkit.co/sfx/preview/mixkit-error-fail-notification-946.mp3

## 下载方法
1. 点击上面的链接
2. 右键点击音频播放器上的下载按钮
3. 选择"保存链接为..."
4. 导航到项目的audio文件夹
5. 确保文件名与上面列出的完全一致

## 为什么需要这样做

浏览器的ORB(Origin-Related Blocking)策略会阻止跨域请求，特别是对于音频和视频资源。通过将音频文件下载到本地项目中，我们可以避免这个问题，确保音频正常播放。

完成后，刷新页面即可正常使用音频功能。