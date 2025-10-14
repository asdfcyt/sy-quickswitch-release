# Quick Switch - 快速切换插件

[English](#english) | [简体中文](#简体中文) | [繁體中文](#繁體中文)

---

## 简体中文

一个为思源笔记设计的快速切换插件，提供快速标签切换、文档搜索、文档内搜索和快速提醒等功能。

### ✨ 功能特性

- ⚡ **快速标签切换**：一键切换已打开的文档标签页
- 🔍 **文档搜索**：全局搜索所有文档，支持模糊匹配
- 🎯 **文档内搜索**：在当前文档中搜索并高亮关键词
- ⏰ **快速提醒**：快速创建任务提醒（需要任务笔记管理插件 https://github.com/Achuan-2/siyuan-plugin-task-note-management）
- 📝 **快速日记**：一键插入内容到今日日记
- ⌨️ **键盘导航**：完整的键盘导航支持
- 🎨 **现代化界面**：美观直观的用户界面

### 📖 使用方法

#### 触发快速切换
- 点击顶栏的闪电图标 ⚡
- 使用快捷键：`⌘O` (Mac) 或 `Ctrl+O` (Windows/Linux)

#### 快捷键操作
- `↑` / `↓`：在结果中导航
- `Enter`：打开选中的文档
- `⌘Enter` / `Ctrl+Enter`：将内容插入到今日日记
- `Alt+Enter`：创建快速提醒
- `Tab`：切换到文档内搜索模式
- `Esc`：关闭快速切换面板

#### 功能说明
- 已打开的文档会显示 ✓ 标记
- 已打开的文档会优先显示在搜索结果顶部
- 模糊匹配支持部分文本和路径匹配
- 实时搜索，带防抖优化

### ⚙️ 设置

通过插件设置面板可以配置：
- **搜索范围**：选择搜索所有笔记本、当前笔记本或自定义选择
- **显示选项**：切换路径显示和设置最大结果数
- **笔记本设置**：配置默认笔记本和日记笔记本

### 📦 安装

#### 从集市安装（推荐）
1. 打开思源笔记
2. 进入 `设置` → `集市` → `插件`
3. 搜索 "快速切换" 或 "Quick Switch"
4. 点击 `下载` 并启用

#### 手动安装
1. 从 [Releases](https://github.com/asdfcyt/sy-quickswitch/releases) 下载最新的 `package.zip`
2. 解压到思源笔记的 `工作空间/data/plugins/` 目录
3. 重启思源笔记或重新加载插件


### 🐛 问题反馈

如遇到问题或有功能建议，欢迎提交 [Issue](https://github.com/asdfcyt/sy-quickswitch/issues)。

感谢下面这些项目给予的参考与帮助：
https://github.com/Achuan-2/siyuan-plugin-task-note-management
https://github.com/TCOTC/siyuan-plugin-hsr-mdzz2048-fork

### 📄 许可证

MIT License

---

## English

A quick switcher plugin for SiYuan Note, providing quick tab switching, document search, in-document search, and quick reminders.

### ✨ Features

- ⚡ **Quick Tab Switching**: Switch between opened document tabs
- 🔍 **Document Search**: Search all documents with fuzzy matching
- 🎯 **In-Document Search**: Search and highlight keywords in current document
- ⏰ **Quick Reminders**: Create task reminders quickly (requires task management plugin)
- 📝 **Quick Journal**: Insert content to today's journal with one click
- ⌨️ **Keyboard Navigation**: Full keyboard support
- 🎨 **Modern UI**: Beautiful and intuitive interface

### 📖 Usage

#### Trigger Quick Switcher
- Click the lightning icon ⚡ in the top bar
- Use keyboard shortcut: `⌘O` (Mac) or `Ctrl+O` (Windows/Linux)

#### Keyboard Shortcuts
- `↑` / `↓`: Navigate through results
- `Enter`: Open selected document
- `⌘Enter` / `Ctrl+Enter`: Insert to today's journal
- `Alt+Enter`: Create quick reminder
- `Tab`: Switch to in-document search mode
- `Esc`: Close quick switcher

#### Features
- Opened documents are marked with ✓
- Opened documents appear at the top
- Fuzzy matching supports partial text and path
- Real-time search with debouncing

### ⚙️ Settings

Configure through plugin settings:
- **Search Scope**: All notebooks, current notebook, or custom selection
- **Display Options**: Toggle path display and set maximum results
- **Notebook Settings**: Configure default notebook and journal notebook

### 📦 Installation

#### From Marketplace (Recommended)
1. Open SiYuan Note
2. Go to `Settings` → `Marketplace` → `Plugins`
3. Search for "Quick Switch"
4. Click `Download` and enable

#### Manual Installation
1. Download latest `package.zip` from [Releases](https://github.com/asdfcyt/sy-quickswitch/releases)
2. Extract to `workspace/data/plugins/` directory
3. Restart SiYuan Note or reload plugins

### 🔒 About Source Code

This repository contains the compiled release version. The plugin is developed with TypeScript and Svelte, but the source code is not publicly available.

The compiled JavaScript code is auditable - you can review the `index.js` file to understand the implementation.

### 🐛 Issue Reporting

If you encounter issues or have feature suggestions, please submit an [Issue](https://github.com/asdfcyt/sy-quickswitch/issues).

Due to closed source, Pull Requests cannot be accepted at this time, but suggestions and feedback are very welcome.

### 📄 License

MIT License

---

## 繁體中文

一個為思源筆記設計的快速切換插件，提供快速標籤切換、文檔搜索、文檔內搜索和快速提醒等功能。

### ✨ 功能特性

- ⚡ **快速標籤切換**：一鍵切換已打開的文檔標籤頁
- 🔍 **文檔搜索**：全局搜索所有文檔，支持模糊匹配
- 🎯 **文檔內搜索**：在當前文檔中搜索並高亮關鍵詞
- ⏰ **快速提醒**：快速創建任務提醒（需要任務管理插件）
- 📝 **快速日記**：一鍵插入內容到今日日記
- ⌨️ **鍵盤導航**：完整的鍵盤導航支持
- 🎨 **現代化界面**：美觀直觀的用戶界面

### 📖 使用方法

#### 觸發快速切換
- 點擊頂欄的閃電圖標 ⚡
- 使用快捷鍵：`⌘O` (Mac) 或 `Ctrl+O` (Windows/Linux)

#### 快捷鍵操作
- `↑` / `↓`：在結果中導航
- `Enter`：打開選中的文檔
- `⌘Enter` / `Ctrl+Enter`：將內容插入到今日日記
- `Alt+Enter`：創建快速提醒
- `Tab`：切換到文檔內搜索模式
- `Esc`：關閉快速切換面板

#### 功能說明
- 已打開的文檔會顯示 ✓ 標記
- 已打開的文檔會優先顯示在搜索結果頂部
- 模糊匹配支持部分文本和路徑匹配
- 實時搜索，帶防抖優化

### ⚙️ 設置

通過插件設置面板可以配置：
- **搜索範圍**：選擇搜索所有筆記本、當前筆記本或自定義選擇
- **顯示選項**：切換路徑顯示和設置最大結果數
- **筆記本設置**：配置默認筆記本和日記筆記本

### 📦 安裝

#### 從集市安裝（推薦）
1. 打開思源筆記
2. 進入 `設置` → `集市` → `插件`
3. 搜索 "快速切換" 或 "Quick Switch"
4. 點擊 `下載` 並啟用

#### 手動安裝
1. 從 [Releases](https://github.com/asdfcyt/sy-quickswitch/releases) 下載最新的 `package.zip`
2. 解壓到思源筆記的 `工作空間/data/plugins/` 目錄
3. 重啟思源筆記或重新加載插件

### 🔒 關於源代碼

本倉庫包含的是編譯後的發布版本。插件使用 TypeScript 和 Svelte 開發，源代碼不公開。

編譯後的 JavaScript 代碼是可以審查的，你可以查看 `index.js` 文件了解插件的實現。

### 🐛 問題反饋

如遇到問題或有功能建議，歡迎提交 [Issue](https://github.com/asdfcyt/sy-quickswitch/issues)。

由於源代碼不公開，暫時無法接受 Pull Request，但非常歡迎提出建議和反饋。

### 📄 許可證

MIT License
