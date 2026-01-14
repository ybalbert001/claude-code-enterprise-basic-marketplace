# Claude Code Enterprise Basic Marketplace

一个为 Claude Code 提供企业级插件的 Marketplace 仓库。

## 包含的插件

### 1. claude-code-ent-comm-plugin
企业通用功能插件，提供：
- Langfuse 集成 Hook
- 其他企业级通用功能

**仓库地址**: https://github.com/ybalbert001/claude-code-ent-comm-plugin

### 2. claude-code-aws-plugin
AWS 和工具类技能插件，提供：
- Excalidraw 绘图技能
- Agentcore Browser 技能
- Slidev PPT 演示文稿技能

**仓库地址**: https://github.com/ybalbert001/claude-code-aws-skills

## 使用方法

1. 在 Claude Code 企业版中配置此 Marketplace 地址
2. 从 Marketplace 中选择需要安装的插件
3. 按照各插件的说明进行配置

## 目录结构

```
.
├── .claude-plugin/
│   └── marketplace.json    # Marketplace 配置文件
├── LICENSE                 # Apache 2.0 许可证
└── README.md
```

## 许可证

Apache License 2.0
