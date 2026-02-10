# DialogueMind: AI对话解析与洞察工具

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black)](你的部署链接)

**🚀 项目愿景**：让每一次对话都产生价值。DialogueMind 利用先进的大语言模型（LLM），自动从纷杂的即时通讯对话（如微信、Slack、钉钉）中提取出**待办事项、关键决策和核心摘要**，帮助你告别信息过载，聚焦重点。

**✨ 核心特性**
*   🤖 **AI智能解析**：自动识别对话中的任务、日期、人名和关键结论。
*   📊 **结构化呈现**：将非结构化的文本转化为清晰的任务列表和信息卡片。
*   🔒 **隐私优先**：所有处理可选择在本地或通过安全API完成，原始数据无需上传至第三方。
*   ⚡ **极简交互**：只需粘贴文本，一键获取洞察。

**🖥️ 在线体验**
**👉 [点击这里体验Live Demo](https://chenyusamo.github.io/DialogueMind-/**

![DialogueMind 界面截图](这里可以后续替换成截图URL，暂时留空)

## 🛠️ 技术栈
*   **前端**: React 18, Vite, Tailwind CSS
*   **后端/API**: Python Flask / Node.js (根据你选择的模板)
*   **AI 引擎**: DeepSeek/OpenAI GPT API
*   **部署**: Vercel (前端), Railway (后端)

## 🚀 快速开始

### 前提条件
*   Node.js 16+ 或 Python 3.8+
*   一个 [DeepSeek](https://platform.deepseek.com/) 或 OpenAI API 密钥

### 本地运行
1.  **克隆项目**
    ```bash
    git clone https://github.com/chenyusamo/DialogueMind.git
    cd DialogueMind
    ```
2.  **安装依赖**
    *前端：*
    ```bash
    cd frontend
    npm install
    ```
    *后端（以Flask为例）：*
    ```bash
    cd backend
    pip install -r requirements.txt
    ```
3.  **配置环境变量**
    在 `backend/.env` 文件中设置你的AI API密钥：
    ```
    DEEPSEEK_API_KEY=your_api_key_here
    ```
4.  **启动服务**
    *启动后端：*
    ```bash
    cd backend
    python app.py
    ```
    *启动前端：*
    ```bash
    cd frontend
    npm run dev
    ```
5.  打开浏览器访问 `http://localhost:5173`

## 📁 项目结构# DialogueMind/
├── frontend/ # 前端React应用
├── backend/ # 后端API服务 (Flask/Node.js)
├── docs/ # 项目文档
└── README.md

## 🔮 未来规划
- [ ] 支持直接导入微信、钉钉等平台的聊天记录文件
- [ ] 增加团队协作空间，共享对话洞察
- [ ] 集成日历（Google Calendar, Outlook），一键创建任务
- [ ] 提供自定义解析规则模板

## 🤝 贡献指南
我们欢迎所有形式的贡献！请查看 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详情。

## 📄 许可证
本项目基于 [MIT 许可证](LICENSE) 开源。
