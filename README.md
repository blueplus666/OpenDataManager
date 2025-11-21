```markdown
# OpenDataManager

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%2011-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

> 一个功能强大的开源数据管理工具，提供直观的图形界面和丰富的数据处理功能。

## ✨ 主要特性

### 🗂️ 核心功能
- **多格式文件预览** - 支持Excel、Word、PDF、HTML、Markdown、图片等格式
- **可视化工作流** - 拖拽式工作流设计，实时数据流动可视化
- **智能数据映射** - 灵活的映射配置，支持JSON格式存储
- **格式转换** - Excel、Word、PDF、Markdown、HTML、图片格式互转

### 📊 资源管理
- **模板库** - 管理文档模板，支持层级分类
- **范例库** - 存储完整文档范例，支持数据同步
- **工序库** - 建立文件层级框架，实现表格配套生成
- **用户资料库** - 分类管理重要文档

### 🎨 用户体验
- **主题定制** - CSS主题支持，可自定义界面外观
- **模块化界面** - 组件可拖拽、吸附，布局灵活
- **多权限管理** - 管理员/临时用户权限体系

## 🚀 快速开始

### 系统要求
- Windows 11 操作系统
- Python 3.8 或更高版本

### 安装方式

#### 方式一：使用预编译版本（推荐）
1. 从 [Releases](https://github.com/bluehints/OpenDataManager/releases) 下载最新版安装包
2. 运行 `OpenDataManager_Setup.exe` 完成安装
3. 启动程序开始使用

#### 方式二：从源码运行
```bash
# 克隆项目
git clone https://github.com/bluehints/OpenDataManager.git

# 进入项目目录
cd OpenDataManager

# 安装依赖
pip install -r requirements.txt

# 运行程序
python main.py
```

📖 使用指南

基本工作流程

1. 创建项目 - 通过菜单栏"文件"→"新建项目"
2. 导入数据 - 在结构树中右键选择导入文件或文件夹
3. 配置映射 - 使用自定义映射面板建立数据关系
4. 设计工作流 - 在工作流画布中拖拽节点建立处理流程
5. 执行导出 - 运行工作流并导出处理结果

核心功能演示

文件预览

· 支持多种文件格式即时预览
· 点击文件即可在预览窗口查看内容
· 支持文本、表格、图片等格式

工作流设计

1. 拖拽开始节点到画布
2. 添加文件夹/文件节点
3. 配置功能节点（转换、映射等）
4. 连接节点建立流程
5. 保存并执行工作流

模板管理

· 右键文件选择"加入模板库"
· 在模板库中管理模板层级
· 基于模板快速创建新文档

🛠️ 开发相关

项目结构

```
OpenDataManager/
├── src/                    # 源代码目录
│   ├── core/              # 核心模块
│   ├── ui/                # 界面组件
│   ├── utils/             # 工具函数
│   └── plugins/           # 插件系统
├── resources/             # 资源文件
│   ├── themes/            # 主题文件
│   ├── icons/             # 图标资源
│   └── templates/         # 模板文件
├── docs/                  # 文档资料
└── tests/                 # 测试用例
```

技术栈

· 开发语言: Python
· GUI框架: PyQt5
· 数据存储: SQLite + JSON
· 打包工具: PyInstaller
· 图标资源: 开源SVG图标

构建说明

```bash
# 安装构建依赖
pip install pyinstaller

# 构建EXE文件
pyinstaller --onefile --windowed --name OpenDataManager main.py
```

🤝 参与贡献

我们欢迎各种形式的贡献！

贡献方式

1. 报告问题 - 在Issues中提交bug报告或功能建议
2. 代码贡献 - 提交Pull Request改进代码
3. 文档完善 - 帮助改进文档和教程
4. 功能测试 - 测试新功能并反馈问题

开发规范

· 遵循PEP 8 Python代码规范
· 提交前运行完整的测试套件
· 为新功能编写相应的文档
· 确保向后兼容性或提供迁移方案

📄 许可证

本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情。

📞 联系方式

· 开发者: bluehints
· 邮箱: bluehints@outlook.com
· 项目主页: GitHub Repository

🙏 致谢

感谢所有为这个项目做出贡献的开发者！
特别感谢开源社区提供的各种工具和库。

---

注意: 本项目仍在积极开发中，部分功能可能仍在完善。如有问题请随时提交Issue。

```
