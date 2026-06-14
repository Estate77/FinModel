# FinModel 优品金融模型官网

一个面向金融场景的智能体 / 模型 / 数据 (MCP) 平台官方主页示例站点，基于 Vue 3 + Tailwind CSS 单文件实现。

## 项目结构

```
FinModel/
├── index.html        # 站点入口（GitHub Pages 默认首页）
└── README.md         # 项目说明
```

## 本地预览

直接双击 `index.html` 即可在浏览器中查看。所有依赖通过 CDN 引入（Vue 3、Tailwind、Phosphor Icons、Font Awesome、Inter/JetBrains Mono 字体），无需任何构建步骤。

也可以使用任一静态服务器：

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .
```

随后访问 <http://localhost:8000>。

## 公网访问（GitHub Pages）

本仓库配置为 GitHub Pages 用户站点（`Estate77.github.io`），地址：

> https://Estate77.github.io/

### 部署步骤

1. 推送代码到 `main` 分支。
2. 在 GitHub 仓库 **Settings → Pages** 中：
   - **Source** 选择 `Deploy from a branch`
   - **Branch** 选择 `main` / `(root)`
3. 保存后等待 1-3 分钟，Pages 即可生效。

## 功能模块

- **广场 (Square)**：推荐金融智能体 / 模型 / MCP
- **智能体 (Agents)**：15+ 金融场景智能体，含个股研报、量化选股、舆情监控等
- **MCP 数据 (MCPs)**：13 类金融数据接口（行情、财报、龙虎榜、估值、研报等）
- **模型市场 (Models)**：GPT-4o、Claude 3.5、DeepSeek、FinGPT-SHUFE 等
- **提示词 (Prompts)**：行业研究、量化回测模板
- **项目空间 (Projects)**：智能体配置与协作
- **Dashboard / 工作台**：实时数据监控、对话式分析

## 技术栈

- Vue 3 (CDN)
- Tailwind CSS (CDN)
- Phosphor Icons / Font Awesome
- Google Fonts: Inter, JetBrains Mono

## 许可

仅作示例展示。
