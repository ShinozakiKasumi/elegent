# 高中数学基础一本通（ElegantBook 版）

> ⚠️ **此版本已归档**，不再维护。请移步 [exercise 仓库](https://github.com/ShinozakiKasumi/exercise) 获取最新版本。

高中数学之旅的初版书稿，使用 [ElegantBook](https://github.com/ElegantLaTeX/ElegantBook) 模板排版，涵盖高中数学基础知识与核心题型的系统讲解。

## 📖 简介

本书以"保姆级解析"为特色，遵循"**思路分析 → 核心技巧 → 解题步骤 → 归纳总结**"的讲解模式，侧重于基础知识的扎实掌握和思维逻辑的清晰构建，拒绝偏难怪题和华而不实的秒杀技巧。

## 📚 章节内容

| 章节 | 内容 |
|------|------|
| 前言 | 写在前面、关于作者、常见问题与解答 |
| 第一章 基础 | 数学基础预备知识 |
| 第二章 集合与逻辑 | 集合运算、命题与逻辑用语 |
| 第三章 不等式 | 不等式性质与解法 |
| 第四章 函数 | 函数概念、性质与应用 |

## 📂 项目结构

```
elegent/
├── elegantbook-cn.tex       # 主文件
├── elegantbook-cn.pdf       # 编译输出 PDF
├── chapters/                # 各章源文件
│   ├── 前言.tex
│   ├── 基础.tex
│   ├── 集合.tex
│   ├── 不等式.tex
│   └── 函数.tex
├── image/                   # 封面与 Logo 图片
│   ├── cover.png
│   └── logo.png
├── LICENSE                  # Apache License 2.0
└── README.md
```

## 🔨 编译方式

本项目使用 **XeLaTeX** 编译，依赖 [ElegantBook](https://github.com/ElegantLaTeX/ElegantBook) 模板：

```bash
xelatex elegantbook-cn.tex
xelatex elegantbook-cn.tex   # 两次编译以生成目录
```

### 编译依赖

- TeX 发行版（推荐 [TeX Live](https://www.tug.org/texlive/) 完整安装）
- ElegantBook 模板（包含在项目中或通过 CTAN 安装）
- 中文字体：方正字体系列（founder）

## 🎨 设计特色

- **ElegantBook 模板**：专业书籍排版，典雅的章节样式
- **自定义封面**：配有封面图与 Logo
- **章节扉页**：每章配有章节序号、标题与名言引语
- **保姆级解析**：思路分析→核心技巧→解题步骤→归纳总结
- **数形结合**：丰富的 TikZ 图示辅助理解

## 📥 下载

前往 [Releases](https://github.com/ShinozakiKasumi/elegent/releases) 页面下载 PDF。

## 📝 致谢

致那些不是从知乎来的游客：请访问知乎@余命数的文章，或添加作者 QQ 2454167821，获取详情。

## 📄 License

[Apache License 2.0](LICENSE)
