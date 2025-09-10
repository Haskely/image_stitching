# 图片拼接工具

一个简单易用的在线图片拼接工具，支持多张图片的竖向拼接和拖拽式裁剪，完美支持移动设备和触摸屏操作。

## 🚀 快速开始

### 在线使用
👉 **[立即使用](https://haskely.github.io/image_stitching/)**

### 通过 URL 快速加载图片
直接在浏览器地址栏输入以下格式的 URL，即可自动加载并拼接网络图片：

```
https://haskely.github.io/image_stitching/?img=图片1&img=图片2&img=图片3
```

**真实示例：**
```
https://haskely.github.io/image_stitching/?img=https://picsum.photos/400/600&img=https://picsum.photos/400/500&img=https://picsum.photos/400/700
```

**更多示例：**
- 拼接 GitHub 项目截图：
  ```
  https://haskely.github.io/image_stitching/?img=https://raw.githubusercontent.com/microsoft/vscode/main/resources/linux/code.png&img=https://raw.githubusercontent.com/microsoft/TypeScript/main/doc/logo.svg
  ```

- 拼接 Unsplash 图片：
  ```
  https://haskely.github.io/image_stitching/?img=https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=400&img=https://images.unsplash.com/photo-1519904981063-b0cf448d479e?w=400
  ```

**注意：** 由于浏览器跨域限制，部分网络图片可能无法加载。建议使用支持 CORS 的图片服务或同域图片。

### 本地运行
下载项目后，直接用浏览器打开 `index.html` 文件即可：

```bash
git clone https://github.com/Haskely/image_stitching.git
cd image_stitching
# 用浏览器打开 index.html
```

## 🎯 使用教程

### 1. 上传图片
- **拖拽上传**：将图片拖拽到上传区域
- **点击选择**：点击上传区域选择本地图片
- **URL 加载**：通过 URL 参数自动加载网络图片

### 2. 编辑图片
- **裁剪调整**：
  - 拖动绿色框移动裁剪区域
  - 拖动上下边缘调整裁剪高度
- **顺序调整**：使用"上移"/"下移"按钮调整图片顺序
- **删除图片**：点击"删除"按钮移除不需要的图片

### 3. 预览和导出
- 右侧实时预览拼接效果
- 点击"导出图片"保存为 PNG 格式
- 移动设备上支持直接分享

## 🌟 功能特点

### 核心功能
- ✅ **多图片上传**：支持批量上传和处理
- ✅ **智能裁剪**：可视化拖拽式裁剪，精确控制每张图片的显示区域
- ✅ **顺序调整**：灵活调整图片排列顺序
- ✅ **实时预览**：编辑即预览，所见即所得
- ✅ **高质量导出**：保持原图质量导出 PNG 格式

### 技术优势
- 🔒 **隐私保护**：纯前端实现，图片不会上传到服务器
- ⚡ **快速响应**：本地处理，无需等待网络传输
- 📱 **全平台支持**：完美适配桌面和移动设备
- 🎨 **简洁设计**：直观的用户界面，无需学习成本

## 📱 移动端特性

- **触摸优化**：专为触摸屏优化的交互体验
- **手势支持**：支持拖拽、缩放等触摸手势
- **原生分享**：集成系统分享功能（iOS/Android）
- **响应式布局**：自适应各种屏幕尺寸

## 🎨 使用场景

- 📱 **截图拼接**：将多张手机截图拼接成长图
- 💬 **聊天记录**：保存完整的对话内容
- 📄 **文档整合**：将分页文档合并为一张图
- 🛍️ **产品展示**：制作商品详情长图
- 📊 **数据报告**：整合多个图表和数据

## 🖥️ 浏览器兼容性

| 浏览器 | 支持版本 |
|--------|----------|
| Chrome | ✅ 最新版本 |
| Firefox | ✅ 最新版本 |
| Safari | ✅ 14+ |
| Edge | ✅ 最新版本 |
| iOS Safari | ✅ 14+ |
| Chrome for Android | ✅ 最新版本 |

## 🛠️ 技术栈

- **HTML5** - 语义化标签和现代 Web API
- **CSS3** - 响应式布局和动画效果
- **原生 JavaScript** - 无依赖，轻量高效
- **Canvas API** - 图像处理和导出

## 👨‍💻 开发

### 环境准备
```bash
# 克隆仓库
git clone https://github.com/Haskely/image_stitching.git
cd image_stitching

# 安装 pre-commit（用于代码规范检查）
uvx pre-commit install
```

### 开发规范
```bash
# 运行代码检查
uvx pre-commit run
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

---

<p align="center">
  如果这个工具对你有帮助，请给个 ⭐ Star 支持一下！
</p>

<p align="center">
  <a href="https://github.com/Haskely/image_stitching">GitHub</a> •
  <a href="https://haskely.github.io/image_stitching/">在线演示</a> •
  <a href="https://github.com/Haskely/image_stitching/issues">反馈问题</a>
</p>
