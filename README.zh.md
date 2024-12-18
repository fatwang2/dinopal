# DinoPal

[🇺🇸 English](README.md) | [🇨🇳 中文](README.zh.md)  

一个生活在 Mac 状态栏上的 AI 语音小助手

## 🦖 功能
- **实时语音对话**：与 DinoPal 进行流畅的语音互动。
- **实时视频对话**：通过视频实时沟通，面对面交流更高效。
- **实时视频共享**：共享你的屏幕，与他人轻松协作。
- **实时联网搜索**：快速获取网络上的最新信息和答案。

---

## 📥 安装

1. **下载安装**：从 Release 中下载 DinoPal 安装包并进行安装。
2. **“文件已损坏” 解决方法**：
   - 如果安装时出现“文件已损坏”的提示，请不要慌张。这是因为我目前还没有 Apple 的开发者账号，导致 Mac 触发了自我保护机制。
   - 你可以通过以下命令手动解除限制：

   ```bash
   sudo xattr -d com.apple.quarantine /Applications/DinoPal.app 
   ```

   > ⚠️ 注意：`/Applications/DinoPal.app` 是你的应用安装路径，如果不一样，请根据实际路径自行更改。

---

## 🚀 使用

1. **启动 DinoPal**：
   - 安装完成后，DinoPal 的图标会出现在 Mac 状态栏上。
   - 点击图标，选择你想要的通话方式（语音、视频等），并授予相应的权限。

2. **通话限制**：
   - 出于成本考虑，每次通话限时 **30 分钟**。
   - 通话结束后，你可以再次发起新的会话。

---

## 💬 用户反馈

- 欢迎加入我们的 Discord 频道，与我们交流并反馈你的宝贵意见！  
  👉 [加入 Discord 频道](https://discord.gg/zzrzhNWFCg)
  
---


🔋 Powered by Google Gemini & Pipecat