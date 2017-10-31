# biblatex-solution-to-latex-bibliography

latex中文参考文献的biblatex解决方案

针对\LaTeX 文档的中文参考文献问题，分析了参考文献生成的一般需求，基于biblatex宏包，从文献数据源文件准备，tex源文档的组成，tex/bib文件的编译，分章参考文献和书后文献表，文献表标题和内容格式，参考文献著录和标注样式，多语言文献，脚注题注小页环境中的引用，脚注旁注中的文献表，文献表分类筛选打印，beamer 类中的参考文献等方面，针对性地给出了全套解决方案，并提供所有示例代码，为\LaTeX 文档参考文献生成提供参考。同时也给出一个参考文献样式定制项目的示例，介绍了bbx和cbx文件开发的方法、步骤和过程，揭示了基于biblatex标准样式定制参考文献的一般原理，为定制参考文献样式提供完整示范。

%% history:

%% 2016-12-07 v1.0  完成基本内容

%% 2017-01-05 v1.0a beamer类下的内容完善

%% 2017-01-18 v1.0b 修正一些错别字，加了后记

%% 2017-01-19 v1.0b 更正biblatex-gb7714-2015未考虑texlive2015兼容性所带来的问题，主要是修改gb7714-2015样式文件，具体可以参考biblatex-gb7714-2015。

%% 2017-03-15 v1.0c 增加了关于参考文献表文本转换成bib文件的内容，增加了nocite命令的介绍，增加了文献著录表中行溢出问题的解决方法，增加了关于&等特殊字符处理的介绍。

%% 2017-10-31 v1.0d 增加了一个参考文献样式定制项目的示例。

---------------------------------------------------------------

