### 丁陈辉 · dingchenhui0618-arch

AI 视觉 · 品牌 GEO

- 个人主页：<https://dionysusding.cn>
- WaVisionAI：<https://wavisionai.cn>

## 最近在做

### [dsh-in-hand](https://github.com/dingchenhui0618-arch/dsh-in-hand) · 掌上 DSH [![npm](https://img.shields.io/npm/v/dsh-in-hand?style=flat-square)](https://www.npmjs.com/package/dsh-in-hand)

不用装 App 的 DeepSeek Harness 手机端（PWA）：同一 Wi-Fi 走局域网直连，人在外面走中继，页面右上角随时切。

<p align="center">
  <img src="https://raw.githubusercontent.com/dingchenhui0618-arch/dsh-in-hand/main/docs/assets/flow-approve.gif" width="240" alt="手机上的待批准卡片，一次点掉">
  <img src="https://raw.githubusercontent.com/dingchenhui0618-arch/dsh-in-hand/main/docs/assets/flow-sessions.gif" width="240" alt="抽屉里挑一条会话">
  <img src="https://raw.githubusercontent.com/dingchenhui0618-arch/dsh-in-hand/main/docs/assets/flow-theme.gif" width="240" alt="调字号与明暗">
</p>

- **待批准一次点掉**：手机在线时直接给「批准一次 / 拒绝」，超时或手机切走就自动退回桌面
- **接着聊**：还是桌面上那批会话，手机上回一句就继续，逐字看着它跑
- **拍一张直接发**：发送前压到长边 1600、保留拍摄方向，原图不出手机
- **等待和交付物都在这一页**：进度、生成的图和 PDF 直接打开

### [VisionQA](https://github.com/dingchenhui0618-arch/VisionQA) · 视觉评审插件

可嵌入宿主智能体（Chrome / MCP / 桌面）的视觉评审插件：接收截图/产物、DOM 摘要、对话目标和 revision，输出可追溯的视觉判断、证据锚点、人工确认动作和有界修正方向。

- 默认走离线 Mock；真实多模态 Provider 只在本地显式配置后启用
- 证据不足时明确标 `NEEDS_CONTEXT` / `MANUAL_REVIEW`，不伪造像素结论
- 网页 `/plugin` 可运行，支持本地产物缩略图、证据锚点和离线 fixture 评审

<sub>演示 GIF：这个仓库还没有录屏，待补。</sub>

### [dsh-tab-complete](https://github.com/dingchenhui0618-arch/dsh-tab-complete) · Tab 补全

在 DeepSeek Harness 输入框里预测你接下来要打的**整句**：灰色幽灵文本贴在光标后面，按 Tab 一键填入。

<p align="center">
  <img src="https://raw.githubusercontent.com/dingchenhui0618-arch/dsh-tab-complete/main/docs/ghost.png" width="70%" alt="输入到一半时的幽灵文本">
</p>

- **Tab** 整句收下；**Alt+→** 只收第一句；**Esc** 丢掉这条
- 只把「你和助手说过的话」喂给模型，技能目录这类框架注入会被挡掉
- 收下的句子只记在本机，越用越像你

### [dsh-doudizhu](https://github.com/dingchenhui0618-arch/dsh-doudizhu)

三人局域网斗地主，DSH 浮窗插件：一台做房主，两人凭码加入。

更多见 [仓库列表](https://github.com/dingchenhui0618-arch?tab=repositories)
