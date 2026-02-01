# OpenRecord - 定制版

> 基于 [TuiliRec by Tuili AI](https://github.com/tuili-ai/openrecord) 的定制版本

## 🎯 用途

本项目用于面试作品展示，展示前端开发和产品定制能力。

## ✨ 定制功能

在原项目基础上，我添加了以下功能：

### 1. 去除音频可视化效果
- **位置**：`components/CanvasStage.tsx`
- **修改**：注释掉摄像头周围的蓝色声音边缘动画
- **原因**：提供更简洁的视觉效果

### 2. 摄像头大小调整
- **位置**：`App.tsx`, `components/ControlDock.tsx`
- **功能**：添加 4 档摄像头大小选择（Small/Medium/Large/X-Large）
- **实现**：
  - 在 App.tsx 中添加 `changeCamSize()` 函数
  - 在 ControlDock 中添加大小选择下拉菜单
  - 支持实时调整，无需重启

### 3. Windows 启动脚本
- **文件**：桌面 `启动OpenRecord.bat`
- **功能**：一键启动开发服务器
- **特点**：中文界面，自动检查项目目录

## 🚀 快速开始

### 本地运行

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 或使用桌面快捷方式
双击 "启动OpenRecord.bat"
```

访问 http://localhost:3000

### 在线演示

🔗 [在线体验地址](https://your-vercel-url.vercel.app)

## 📝 技术栈

- React 19 + TypeScript
- Vite 6
- TailwindCSS
- Canvas API + MediaRecorder API
- Web Audio API

## 🎨 修改说明

本项目保留了原项目的所有核心功能，仅在用户体验层面进行了优化：

- ✅ 保留：屏幕录制、摄像头叠加、音频混合
- ✅ 保留：多种画幅比例、背景切换、缩放平移
- ➕ 新增：摄像头大小调整功能
- ➖ 移除：音频可视化边缘效果

## 📄 许可证

本项目基于 [TuiliRec](https://github.com/tuili-ai/openrecord) 开发，遵循 MIT License。

原项目版权归 Tuili AI 所有。

## 🙏 致谢

感谢 [Tuili AI](https://github.com/tuili-ai) 开发的优秀开源项目 TuiliRec。

---

**面试展示项目** | 定制开发 | 2026
