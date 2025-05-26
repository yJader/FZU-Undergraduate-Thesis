# 福州大学本科生毕业论文 LaTeX 模板
>
> ==**注意**==：本模板为非官方版本，具体格式请以当年学校发布的最新规范为准。

本项目为福州大学本科生毕业设计（论文）LaTeX 模板，旨在帮助同学们规范、高效地撰写毕业论文。模板参考了福州大学研究生毕业论文模板，并根据[本科生论文格式要求](./20.福州大学本科生毕业设计（论文）撰写规范.doc)进行了调整和优化。

- **使用范围**: 福州大学本科生毕业设计环节中的 文献综述, 外文原文及翻译, 论文撰写等。

- **答辩后更新**: 答辩评委评价"论文格式比较规范"

  - 注: 答辩评委会检查论文格式，请确保你的论文符合学校要求。

## 目录结构（主要文件说明）

- `main.tex`：主控文件，包含各章节与模块的引用。
- `Text/pre-defined.tex`：预定义宏包、字体、字号、环境等。
- `Text/Abstract.tex`：中英文摘要模板。
- `Text/Chapter_1.tex` 等：正文各章节内容。
- `Text/Reference.tex`、`Text/reference.bib`：参考文献及其数据库。
- `TemplateAssets/`：图片与学校相关素材。
- 字体文件（`simfang.ttf`、`simhei.ttf`、`simkai.ttf`、`simsun.ttc`）：确保跨平台一致性。

## 使用说明

1. **编译方式**  
   推荐使用 XeLaTeX 进行编译，支持中文和自定义字体。完整编译流程如下：

   ```sh
   xelatex main.tex
   biber main
   xelatex main.tex
   xelatex main.tex
   ```

   或在 Overleaf 上直接编译（选择 XeLaTeX）。

2. **格式规范**
   - 模板已按福州大学本科毕业论文格式要求设置页边距、字体、字号、行距、章节编号、目录、参考文献等。
   - 公式、图表、定义等均支持自动编号与交叉引用。

## 致谢

本模板基于 [Shifan He 的福州大学研究生毕业论文模板](https://www.overleaf.com/latex/templates/fu-zhou-da-xue-yan-jiu-sheng-bi-ye-lun-wen-mo-ban/pdccsztcptxy) 修改，感谢学长的贡献。  
感谢 Xiuqi Cui 对模板样式提出的宝贵建议。

## 参与贡献

如有建议或希望参与改进，请联系 <yjader@foxmail.com>。
