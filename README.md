# AI Writing Assistant 1.5.12 🎓

![Version](https://img.shields.io/badge/version-1.5.12-blue) ![Type](https://img.shields.io/badge/Web_App-SPA-green) ![Focus](https://img.shields.io/badge/Focus-SSCI_Academic-orange)

一个专为科研人员、博士生及学术工作者设计的 **单页级 (SPA) AI 写作辅助工具**。它集成了顶级 SSCI 期刊主编视角的润色、高熵学术化降重以及模拟同行评审功能，完全在浏览器本地运行，确保数据隐私。

[**🔗 点击此处在线使用 (Live Demo)**](https://jiayouzhu0606.github.io/AI-Writing-Assistant/)

---

## ✨ 核心功能 (Key Features)

本工具内置了经过深度工程化的 Prompt (提示词)，模拟不同角色的学术专家：

### 1. 🖊️ 学术润色 (Polishing Mode) - **[绿色主题]**
*   **角色**：SSCI 顶刊资深主编 (Chief Editor)。
*   **功能**：修复语法错误，提升词汇精确度，优化句式结构（如周期句、强调句），增强逻辑连贯性。
*   **输出**：提供详细的《修改对比表》和最终润色文本，高亮显示修改处。

### 2. 🌱 AI去痕/降重 (Humanize AI) - **[蓝色主题]**
*   **角色**：法医语言学家与学术文本专家。
*   **功能**：通过增加句法熵 (Entropy) 和困惑度 (Perplexity)，消除 AI 生成文本的机械感（如 "Delve", "Crucial" 等高频词），使其通过 AI 检测，同时保持严谨的学术语调。
*   **技术**：采用 "Anti-Pattern" 协议，拒绝口语化，专注于高阶学术表达。

### 3. 🕵️ 模拟审稿 (Peer Review) - **[橙色主题]**
*   **角色**：以严苛著称的 "Reviewer 2"。
*   **功能**：模拟 SSCI 期刊审稿流程，针对方法论、理论框架提出尖锐批评，并自动生成《回复信草稿 (Response Letter)》和具体的修改建议矩阵。

---

## 🚀 版本 1.5.12 新特性

*   **🛑 中断控制**：新增 "Stop Generating" 按钮，可随时中止 AI 的思考过程。
*   **⚛️ 极简科研动效**：摒弃娱乐化元素，采用专业的“数据扫描/神经节点”加载动画，提升沉浸感。
*   **🔧 自定义指令**：新增 "Extra Requirement" 输入框，允许用户叠加个性化要求（如“限制字数”、“保留被动语态”等）。
*   **📱 响应式布局**：左右分栏设计，自动适配屏幕，Markdown 表格支持横向滚动，不再溢出。

---

## 🛠️ 使用指南 (How to Use)

1.  **打开应用**：访问 [GitHub Pages 链接](https://jiayouzhu0606.github.io/AI-Writing-Assistant/)。
2.  **配置 API**：
    *   点击左上角的设置图标（或在侧边栏）。
    *   选择模型提供商（支持 **Moonshot (Kimi)**, **DeepSeek**, **Zhipu (智谱)**, **Qwen (通义)** 等）。
    *   输入您的 API Key（密钥仅保存在本地浏览器缓存中，不会上传服务器）。
3.  **选择模式**：在左侧选择 Polishing, Humanize AI 或 Peer Review。
4.  **输入文本**：
    *   直接粘贴论文段落。
    *   或点击 "Upload" 上传 `.docx` / `.txt` 文件。
    *   *(可选)* 在下方输入框填写额外指令。
5.  **点击 Execute**：观察右侧生成的专业分析与修改结果。

---

## 🔒 隐私与安全 (Privacy)

*   **Client-Side Only**: 本项目是一个纯前端应用 (HTML/JS)。
*   **No Backend Storage**: 您的 API Key 和论文内容**仅在您的浏览器与 AI 服务商之间传输**，不会经过本项目作者的服务器，也不会被第三方存储。
*   **Open Source**: 代码完全开源透明，您随时可以审查 `index.html` 源码。

---

## 💻 技术栈 (Tech Stack)

*   **Vue.js 3**: 响应式数据绑定与组件化。
*   **Tailwind CSS**: 现代化的 UI 样式设计。
*   **Marked.js**: Markdown 实时渲染。
*   **Mammoth.js**: Word 文档解析。

---

## 🤝 贡献与反馈

如果您在使用过程中遇到问题，或者有新的功能建议，欢迎提交 [Issue](https://github.com/JiayouZhu0606/AI-Writing-Assistant/issues) 或 Pull Request。

Welcome to any suggestions and criticism!

**Author**: Jiayou Zhu
