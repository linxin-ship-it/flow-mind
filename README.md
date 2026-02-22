# FlowMind - AI 流程图生成器

一个基于AI的流程图生成器，使用自然语言描述生成Mermaid流程图，支持实时预览和多种导出格式。

## 功能特性

- **AI智能生成**：使用OpenAI API将自然语言描述转换为Mermaid流程图代码
- **实时预览**：即时渲染Mermaid代码为流程图
- **多种导出格式**：
  - SVG格式（矢量图，可编辑）
  - PNG格式（图片格式，通用）
  - Mermaid格式（源代码，可编辑）
- **交互功能**：
  - 缩放控制（放大、缩小、重置）
  - 全屏预览
  - 拖拽移动流程图
- **代码编辑**：支持手动编辑Mermaid代码，实时预览效果

## 使用说明

1. **配置API**：点击右上角"配置"按钮，设置OpenAI API信息
2. **输入描述**：在左侧输入框用自然语言描述您想要的流程图
3. **生成图表**：点击"生成流程图"按钮，AI将生成Mermaid代码
4. **编辑代码**：可在代码编辑器中手动修改Mermaid代码
5. **导出分享**：点击"导出"按钮，选择需要的格式下载

## 技术栈

- **前端**：HTML5, CSS3, JavaScript (ES6+)
- **图表库**：Mermaid.js
- **API**：OpenAI GPT API
- **部署**：GitHub Pages

## 本地运行

1. 克隆仓库：
   ```bash
   git clone https://github.com/your-username/flow-mind.git
   ```

2. 打开 `index.html` 文件即可使用

## 在线演示

访问 [https://your-username.github.io/flow-mind/](https://your-username.github.io/flow-mind/) 查看在线演示

## 注意事项

- 需要有效的OpenAI API密钥才能使用AI生成功能
- 配置信息保存在浏览器本地存储中，不会上传到服务器
- 支持手动编辑Mermaid代码，无需API也可使用

## 许可证

MIT License
