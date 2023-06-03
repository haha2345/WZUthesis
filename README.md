# `WZUthesis` 温州大学 学位论文 LaTeX 模板 [最新样式]

## 模板下载

* 页面右边点击：**Clone or download -> Download Zip**

## 重要建议

* 关于 WZUsthesis 编译和设计的问题，请先读 **模板使用说明.pdf**。

## 模板简介

* WZUthesis是在ucasthesis模板的基础上，根据《温州大学研究生学位论文格式规定》进行修改开发的一套适用于温州大学研究生毕业论文的论文模板。基于latex，WZUthesis解决了使用word编写论文时格式难以调整、插入公式复杂、参考文献不易管理、图表不美观等问题，极大解放论文生产力，把精力集中于论文的撰写中而不是费时费力地调整word格式、用复杂的工具插入冗长的公式。这里感谢ucasthesis的作者提供了一份简单明了的latex模板。

## 使用指南

- 我本地latex环境为：编译工具MiKTeX，前端为Texstudio，编译器为PdfLaTex。建议和我保持一致，保证可以直接运行。
- `Thesis.tex`为主要tex文件，包含扉页、摘要、正文等内容。
- 封面：模板提供了温州大学硕士学位论文的终稿封面和盲审封面的word文件，在word文件中修改好后导出pdf文件，在Tex/Frontmatter.tex中修改对应的pdf。
- 中英文摘要：在Tex/Frontmatter.tex中编辑中英文摘要。
- 正文：在Tex/Mainmatter.tex中添加需要的tex文件，Tex文件夹中已经给出了实例tex文件。
- 参考文献：本项目只应用了bibtex的导入方式，其他方式没有测试过。bib文件在Biblio文件夹中。
- 致谢和成果：在Tex/Backmatter.tex中进行编辑。

## 更新记录

* `2023-06-03` 上传WZUthesis，制作了使用指南，写了readme

### 联系方式

如果有模板有问题请提issue

如果有latex方面的问题请通过邮箱woden3702@gmail.com联系我获取帮助，注明问题
