# BahasaFlow 🇮🇩 印尼语流利度训练营

针对「反应不过来、听说不流畅、发音不准确」三大问题设计的移动端训练工具。
纯静态单页应用，无需安装，手机浏览器直接打开即可使用。

## 四大训练模块

| 模块 | 训练目标 | 方式 |
|------|---------|------|
| ⚡ 闪电反应 | 提取速度 | 6秒倒计时内中文→脱口说印尼语 |
| 🎧 盲听理解 | 听力流畅度 | 先听不看字，语速三档可调 |
| 🎤 跟读评分 | 发音准确度 | 语音识别逐词比对打分 |
| 🎬 场景实战 | 综合流利度 | 6大场景，8秒限时应答 |

## 部署到 GitHub Pages（3分钟）

1. 登录 GitHub → 右上角 **+** → **New repository**，命名如 `bahasa-flow`，选 Public，创建
2. 在仓库页点 **uploading an existing file**，把本文件夹里的 `index.html` 和 `README.md` 拖进去，点 **Commit changes**
3. 进入仓库 **Settings → Pages**，Source 选 **Deploy from a branch**，Branch 选 `main` / `(root)`，保存
4. 等约1分钟，页面顶部会显示网址：`https://你的用户名.github.io/bahasa-flow/`
5. 用手机浏览器打开该网址 → 分享菜单 → **添加到主屏幕**，就像原生App一样使用

## 使用提示

- 🔊 语音朗读和 🎤 发音评分基于浏览器 Web Speech API
- **手机端推荐 Chrome（安卓）**；iPhone Safari 支持朗读，发音评分功能有限
- 首次使用跟读评分需授权麦克风权限
- 部分手机需先在系统设置中下载印尼语(Bahasa Indonesia)语音包，朗读才有声音

## 技术说明

单文件 `index.html`：React 18 (CDN) + Babel Standalone + Web Speech API，无构建步骤。
