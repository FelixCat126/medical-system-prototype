# 肺动脉介入手术管理系统

## 项目目录

项目已移至byhx文件夹下，当前项目结构如下：

```
byhx/
├── betaUI/               # 低保真原型和界面设计
│   ├── index.html        # 原型导航页
│   ├── homepage.html     # 系统首页/患者列表
│   ├── workstation.html  # 工作站界面
│   ├── modeling.html     # 三维建模界面
│   └── modeling.js       # 三维建模交互脚本
├── docs/                 # 项目文档
│   ├── requirements.md   # 需求文档
│   └── PRD.html          # 产品需求文档
├── figma-plugin/         # Figma设计插件
└── show/                 # 演示和展示文件
```

## 更新说明

1. 项目路径变更：项目从根目录移至byhx文件夹下
2. 相对路径更新：betaUI中的HTML文件引用路径已更新
3. 未实现功能：部分原型文件尚未实现，在导航页中已标记为"暂不可用"

## 本地运行

直接在浏览器中打开以下文件即可查看对应原型：

- 原型导航页：`byhx/betaUI/index.html`
- 系统首页：`byhx/betaUI/homepage.html`
- 工作站界面：`byhx/betaUI/workstation.html`
- 三维建模界面：`byhx/betaUI/modeling.html`

## 配置说明

系统当前为前端原型阶段，尚未包含服务器配置。未来会添加：

1. 服务器配置：后端API服务器地址配置
2. PACS系统连接配置：医疗影像存档与通信系统配置
3. 数据库配置：患者数据和影像元数据存储配置

## 联系方式

有关项目的任何问题，请联系项目管理团队。
