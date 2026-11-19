# Life HQ · 人生参谋部 —— 官网

Life HQ 的官方网站：本地优先的 AI 人生参谋，装在你自己的电脑和手机上。

- 官网（中文）：计划部署于 lifehq.vip
- 产品购买：[淘宝商品页](https://item.taobao.com/item.htm?ft=t&id=1096984688103)

## 本地预览

纯静态站点，无构建、无依赖、无跟踪脚本——直接用浏览器打开 `index.html`，或：

```bash
# 任意静态服务器，例如
npx serve .
python -m http.server 8000
```

## 结构（2026-11-20 改版：单页长卷）

单页 `index.html`（深色星空主题 + 真实软件截图），区段：首屏 → 早安/日间/晚安三步 → 功能屏（今日页/收集箱/Agent 工作台）→ 背景机制 → 定价 → 问答 → 真实界面画廊 → 页脚（含备案号链接）。

- `assets/art/`：主视觉山景插画（自制）
- `assets/shots/`：桌面与手机真实截图（1316×879 / 1080×2460）
- `assets/brand/`：Logo
- `assets/fonts/`：LHQ Display Serif（`LICENSE.txt` 附许可）

## 技术说明

- **纯静态 HTML/CSS + 少量原生 JS**（灯箱/滚动动效）：零框架、零跟踪、零外部依赖（图标为内联 SVG）。
- **响应式**：移动端可用。
- 插画素材位于 `assets/art/`。

## License

网站文案与视觉素材版权归 Life HQ（义乌市酥雾商务信息咨询服务部）所有；插画素材仅供本项目官网使用，未授权其他用途。
