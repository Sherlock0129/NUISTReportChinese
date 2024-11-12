# 南京信息工程大学课程报告模板

该仓库提供南京信息工程大学（NUIST）课程报告的 LaTeX 模板。模板包含格式说明及常用功能，包括分节、插入表格、插图和数学环境等内容。

## 功能特性

- **文档结构**：预定义结构，方便快速设置。
- **公式插入**：轻松添加行内和显示公式。
- **图像支持**：插入带标题的图片示例。
- **文本框**：圆角灰底文本框，用于高亮显示内容。
- **表格支持**：快速插入表格。
- **数学逻辑环境**：支持定理、定义和证明等环境。
- **参考文献管理**：使用 `bibtex` 管理文献引用。

## 开始使用

### 环境要求

编译该模板需要以下工具：
- **XeLaTeX**：用于排版。
- **bibtex**：用于管理参考文献。

### 文件结构

- `main.tex`：主文档文件。
- `nuistReport.sty`：样式文件，控制文档格式。
- `references.bib`：参考文献文件。
- `figures/`：存放图片的文件夹。

### 编译步骤

1. 修改 `nuistReport.sty`，填写标题、姓名、学号等个人信息。
2. 在 `main.tex` 中添加内容。
3. 使用 `xelatex -> bibtex -> xelatex*2` 的顺序编译。

## 示例

模板包含以下示例：
- 添加公式（如 \( v - \epsilon + \varphi = 2 \)）。
- 插入图片并添加标题。
- 使用数学逻辑环境，支持定理、证明和定义等。
- 使用 `\cite{}` 命令添加参考文献。

## 发布与访问

- **GitHub**： [NUIST Report Repository](https://github.com/Sherlo0129ck0129/nuistReport)
- **Overleaf 模板**： [NUIST Report on Overleaf](https://cn.overleaf.com/latex/templates/nuistreport)

## 许可证

该项目使用 MIT 许可证 - 详情参见 [LICENSE](LICENSE) 文件。
