# MicLawAgent - AI法律智能代理平台

<div align="center">
  <img src="https://img.shields.io/badge/技术栈-HTML%20CSS%20JavaScript%20PHP-brightgreen.svg" alt="技术栈">
  <img src="https://img.shields.io/badge/适配-PC%20%7C%20移动端-blue.svg" alt="适配">
  <img src="https://img.shields.io/badge/AI对接-豆包大模型-orange.svg" alt="AI对接">
  <img src="https://img.shields.io/badge/开源协议-MIT-green.svg" alt="开源协议">
</div>

<div align="center">
  <strong>基于豆包大模型的AI法律文书自动生成系统，轻量化、商用级、一键部署</strong>
</div>

## 🔥 核心功能
- 📝 **AI法律文书生成**：对接豆包大模型，自动生成民事起诉状、答辩状、借款合同等6+类专业法律文书
- 🎨 **高端UI设计**：暗黑模式+渐变配色，适配PC/手机全端，交互流畅
- 📱 **自适应布局**：下拉导航菜单，移动端自动切换汉堡菜单，用户体验拉满
- 🖥️ **管理后台**：支持LOGO上传、公告修改、资讯管理、密码修改等核心运营功能
- 🛠️ **一键安装**：傻瓜式安装页，无需复杂配置，本地/服务器均可快速部署
- 💪 **容错兜底**：AI接口异常时自动切换本地专业法律模板，保障服务可用

## 📸 演示截图（建议替换为你的实际截图）
| 前台首页 | AI文书生成 | 管理后台 |
|---------|-----------|---------|
| ![前台首页](https://placeholder.com/600x300?text=前台首页) | ![AI文书生成](https://placeholder.com/600x300?text=AI文书生成) | ![管理后台](https://placeholder.com/600x300?text=管理后台) |

## 🚀 快速开始

### 环境要求
- PHP 5.6+（推荐7.4+）
- 任意Web服务器（Apache/Nginx/PHP内置服务器）
- 浏览器（Chrome/Firefox/Edge等现代浏览器）

### 本地测试
1. 克隆仓库
```bash
git clone https://github.com/你的用户名/MicLawAgent.git
cd MicLawAgent

2.启动 PHP 内置服务器
php -S localhost:8080

3.访问地址
安装页：http://localhost:8080/install.php
前台首页：http://localhost:8080/index.html
管理后台：http://localhost:8080/admin.html
服务器部署
将仓库所有文件上传到服务器网站根目录
确保upload/文件夹拥有可写入权限（chmod 755）
访问域名 +install.php完成一键安装
安装完成后即可正常使用
📋 目录结构
plaintext
MicLawAgent/
├── index.html       # 前台核心页面（AI文书+核心服务+商业规划）
├── admin.html       # 管理后台（LOGO/公告/资讯管理）
├── api.php          # 接口文件（适配前台数据请求）
├── install.php      # 一键安装页
└── upload/          # LOGO存储目录（需可写入权限）
🎯 核心特色
零配置 AI 对接：内置豆包大模型调用逻辑，无需手动配置 API Key，开箱即用
商用级体验：去掉冗余模块，保留核心盈利点，适合法律服务机构 / 个人创业者
轻量化架构：无数据库依赖，纯文件级存储，降低部署门槛
容错机制完善：AI 接口异常时自动切换本地模板，避免服务中断
全端适配：PC 端下拉导航，移动端汉堡菜单，适配各种设备尺寸
⚙️ 自定义修改
1. 更换 AI 模型
修改index.html中generateByDoubao()函数内的 API 地址 / 参数，可对接其他大模型（如 GPT / 文心一言 / 通义千问）
2. 新增法律文书类型
在index.html的<select id="docType">中添加<option>标签，并补充getLocalTemplate()函数内的对应模板
3. 更换 UI 配色
修改 CSS 中#4EE2FF（主色）、#05070F（背景色）等颜色值，即可快速更换品牌配色
📄 开源协议
本项目基于 MIT 协议开源，你可以自由修改、商用、二次分发，无需授权（保留版权声明即可）
📞 联系我们
商务合作：contact@miclawagent.com
技术支持：support@miclawagent.com
GitHub：https://github.com/你的用户名 / MicLawAgent
⚠️ 免责声明
本项目仅提供技术框架，生成的法律文书仅供参考，不构成专业法律意见，实际使用请咨询执业律师。
plaintext

### 优化建议（提升仓库吸引力）：
1. **替换截图占位符**：将`https://placeholder.com/xxx`替换为你实际的页面截图（推荐用免费图床如https://imgur.com/存储）；
2. **补充演示地址**：如果有线上演示地址，可在「快速开始」后添加`在线演示：https://你的域名`；
3. **个性化信息**：将所有`你的用户名`/`miclawagent.com`替换为你的实际信息；
4. **添加Star趋势图**：可使用https://starchart.cc/生成仓库Star趋势图，插入到README顶部，提升视觉效果。

### 总结
1. 这份README覆盖了GitHub仓库的核心要素：功能、安装、结构、自定义、协议，符合开源项目规范；
2. 突出了「AI对接豆包」「商用级」「零配置」等核心卖点，吸引目标用户；
3. 步骤清晰，新手也能快速理解部署和使用方式；
4. 包含免责声明，规避法律风险（适配法律类项目特性）。




