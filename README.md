Grid Forge β (Web-based Architectural Layout Tool)
Grid Forge is a lightweight, single-file web application designed specifically for architectural students and designers to create "Swiss Style" board layouts effortlessly. No installation required—just open and design.

Grid Forge 是一款专为建筑学生和设计师打造的轻量级网页排版工具。它采用单文件架构，无需安装，旨在帮助用户轻松创建具有“瑞士国际主义风格”的图纸排版。

✨ Features / 核心功能
Zero Installation: Just one HTML file. Runs entirely in your browser.

零安装：仅需一个 HTML 文件，在浏览器中直接运行。

Smart Layout Algorithms: Toggle between "Priority" (v5) and "Recursive" (v4) algorithms to automatically arrange your images based on hierarchy (Hero, Standard, Detail).

智能排版算法：支持“优先级 (Priority)”和“递归 (Recursive)”两种算法，根据图片层级（Hero/普通/细节）自动生成布局。

3D Overview Mode: Press O or click the "View" button to visualize your layout sheets in a 3D space.

3D 总览模式：按 O 键或点击视图按钮，在 3D 空间中查看你的图纸序列。

Auto-Save System: Your work is automatically saved to your browser's local database (IndexedDB). Never lose your progress.

自动保存系统：进度自动保存至浏览器本地数据库 (IndexedDB)，防止数据丢失。

AI Integration: Connect with SiliconFlow API to generate layouts or render mock-up images via text prompts.

AI 集成：支持连接 SiliconFlow API，通过文字提示词生成布局方案或渲染草图。

Export Ready: Export high-resolution PNGs or multi-page PDFs for printing.

图纸导出：支持导出高清 PNG 图片或多页 PDF 文件用于打印。

Dark Mode: Optimized for late-night design sessions.

深色模式：适配深夜绘图场景的护眼模式。

🚀 Quick Start / 快速开始
Download: Clone this repository or simply download the index.html file.

下载：克隆本仓库或直接下载 index.html 文件。

Run: Open the file in a modern browser (Chrome, Edge, or Safari recommended).

运行：在现代浏览器（推荐 Chrome, Edge 或 Safari）中打开该文件。

Design:

Drag and drop images/videos into the list or canvas.

Set columns/rows and adjust margins.

Assign levels (Hero, S1, S2) to images to control their size.

设计：拖拽图片/视频进入列表或画布；设置行列数与边距；为图片分配层级（Hero, S1, S2）以控制其大小。

🛠 Tech Stack / 技术栈
Core: HTML5, Vanilla JavaScript

Styling: Tailwind CSS (CDN)

Libraries:

html2canvas (for rendering)

jspdf (for PDF export)

cropperjs (for image cropping)

🔒 Privacy & Security / 隐私与安全
Local Processing: All logic runs locally in your browser. Your images are NOT uploaded to any server unless you explicitly use the AI features.

本地处理：所有逻辑均在本地浏览器运行。除非使用 AI 功能，否则您的图片不会上传至任何服务器。

API Keys: If you use AI features, your API Key is stored in your browser's localStorage and is never collected by us.

API 密钥：如果您使用 AI 功能，API 密钥仅存储在您的浏览器本地 (localStorage)，我们不会收集。

🤝 Contributing / 贡献
Issues and Pull Requests are welcome! If you are an architecture student with coding skills, feel free to help improve the tool.

欢迎提交 Issue 或 Pull Request！如果你是懂代码的建筑生，欢迎一起完善这个工具。

📄 License
MIT License © 2026 Grid Forge Project
