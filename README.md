# 🚀 MyConfig

> ⚠️ **个人自用项目** - 基于开源项目整合的网络代理配置集合

## 📦 项目来源

本项目整合了以下开源项目的内容：

- **[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)** - 代理规则集 + 服务图标
- **[dahaha-365/YaNet](https://github.com/dahaha-365/YaNet)** - Mihomo 网络优化脚本  
- **[sirkey5/clash--singbox--subsotre.js](https://github.com/sirkey5/clash--singbox--subsotre.js)** - 配置转换脚本

## 📁 项目结构

\\\
MyConfig/
├── rules/      # 代理规则集（500+ 应用服务）
├── icons/      # 服务图标（2000+ 精美图标）
├── scripts/    # 实用脚本
└── others/     # 其他配置
\\\

## 🚀 使用方法

### Clash 配置示例
\\\yaml
rule-providers:
  openai:
    type: http
    behavior: classical
    url: \
https://raw.githubusercontent.com/USERNAME/MyConfig/main/rules/OpenAI/OpenAI.yaml\
    interval: 86400
\\\

### Surge 配置示例  
\\\ini
[Rule]
RULE-SET,https://raw.githubusercontent.com/USERNAME/MyConfig/main/rules/OpenAI/OpenAI.list,AI-Services
\\\

## 📜 声明

- 仅供个人学习使用，请遵守当地法律法规
- 所有内容来源于上述开源项目，遵循原项目开源协议
- 项目维护者不承担任何使用责任

---

<div align="center">

**⭐ 如果觉得项目有用，欢迎点个 Star 支持一下！⭐**

💡 *Star 是对项目最好的鼓励和支持*

</div>
