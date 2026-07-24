# 刘彤 — 个人网站

> 线上地址：https://tonton-520.github.io/personal-website/

AI 产品经理个人主页，展示工作经历、项目经验、能力矩阵与教育背景。

## 技术栈

- **纯静态**：HTML + CSS + JavaScript，无构建依赖
- **字体**：Noto Serif SC / Noto Sans SC / JetBrains Mono（Google Fonts）
- **部署**：GitHub Pages

## 功能模块

| 模块 | 内容 |
|------|------|
| Hero | 个人定位 + 核心数据卡片（3000+ 经纪人覆盖等关键指标） |
| About | 个人简介 + 三大优势 |
| Skills | 能力矩阵（AI 产品 / 产品方法论 / 工具技术 / 证书认证） |
| Experience | 工作经历时间线 + 可量化业绩 |
| Projects | 两个核心项目完整拆解（背景→设计→效果→数据） |
| Education | 教育背景 |
| Contact | 联系方式（邮箱 / 电话 / GitHub） |

## 设计说明

- **配色**：深海军蓝 + 暖琥珀金 + 冷白底，避免模板化风格
- **排版**：思源宋体（标题）+ 思源黑体（正文）+ JetBrains Mono（数据）
- **交互**：滚动渐显动画、导航栏滚动收缩、响应式移动端适配
- **背景**：Hero 区节点连线 SVG，呼应 Agent 架构设计

## 本地预览

```bash
# 直接在浏览器中打开
open index.html

# 或用 Python 起一个本地服务
python -m http.server 8080
# 然后访问 http://localhost:8080
```

## 更新内容

如需更新个人信息，直接编辑 `index.html` 中的对应 HTML 即可。所有内容为静态文本，无需数据源。

## License

MIT
