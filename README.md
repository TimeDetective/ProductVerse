# ProductVerse ✳

**Think it. Build it. Make it real.**

一个用产品思维与 Vibe Coding 打造的 AI 产品创作者作品集。把企业工具、消费体验和游戏制作放进同一个可交互的创作宇宙，让访客通过体验了解产品设计与实现方式。

黑白视觉、荧光绿点缀、响应式布局。纯 HTML / CSS / JavaScript，无需安装依赖、无需后端、无需 API Key。

## 在线体验

**[打开 ProductVerse →](https://timedetective.github.io/ProductVerse/)**

## 可以体验什么？

- **FlowOS · B 端工作流**：从会议记录到任务草稿，再到人工确认，展示清晰的状态反馈和人机协作流程。
- **Daylight · C 端灵感日常**：通过不同状态生成灵感卡片，探索个性化交互与情绪体验。
- **Pixel Orbit · 可玩小游戏**：收集星星、避开障碍，支持方向键与触屏拖动，包含计分、倒计时和重开。
- **Idea Playground · 想法实验室**：输入一个点子，查看场景、最小体验与验证方式的拆解。
- **合作联系区**：邮件入口与一键复制邮箱。

> 作品案例和界面数据是概念演示，不代表真实客户、项目业绩或商业指标。Idea Playground 使用浏览器内的规则，不调用大模型服务。

## 本地预览

下载或克隆仓库后，在项目目录运行：

```sh
python3 -m http.server 8080
```

打开 `http://localhost:8080`。也可直接打开 `index.html`；复制邮箱功能取决于浏览器的安全上下文和权限。

## 部署到 GitHub Pages

在仓库的 **Settings → Pages** 中，将发布源设置为 **Deploy from a branch**，选择 `main` 分支及 `/(root)`，保存并等待部署完成。网站使用相对资源路径，可部署在项目子目录。

## 做成你的作品集

编辑 `index.html` 修改品牌、介绍、作品信息和邮件地址；编辑 `app.js` 修改演示互动。使用自己的品牌、联系方式和真实案例，避免把演示内容误写成履历。

## 文件结构

- `index.html` — 页面结构与响应式样式
- `app.js` — 分类筛选、产品演示、小游戏、想法拆解和复制邮箱
- `.nojekyll` — 直接发布静态文件
- `LICENSE` — MIT 开源许可

## 合作与交流

AI 产品设计、B / C 端原型开发、游戏与互动体验。

邮箱：[2469152@qq.com](mailto:2469152@qq.com)

欢迎提出 Issue、提交改进或将它改造成自己的创作空间。

## License

MIT © 2026 ProductVerse contributors.
