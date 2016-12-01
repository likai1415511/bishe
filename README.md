### 毕设论文

### 预安装

- 安装Texlive(for Ubuntu) sudo apt-get install texlive-full
- [安装Adobe fonts](http://m.blog.csdn.net/article/details?id=41981815)

#### 编译命令

- 安装 ./makethesis install
- 编译 ./makethesis install
- 统计字数 ./makethesis wordcount生成wordcount.html文件

#### 论文架构

- bare\_thesis.tex 论文主文件
- metadata.tex 导言区
- acronyms.tex 缩略语定义
- notations.tex 符号对照表
- ch\_intro/ch\_concln.tex 论文主体
- ackgmt.tex 致谢
- pubs.tex 发表论文列表
- bare\_thesis.bib 参考文献列表
- 论文的正文以ch\_开头,论文的附录以app\_开头


#### 删除的代码备份
```
%% 每一章节的最后的代码（如果每一章节后面紧随参考文献，需要添加）
%% 本章参考文献
\ifx\usechapbib\empty
\nocite{BSTcontrol}
\setcounter{NAT@ctr}{0}
\bibliographystyle{buptgraduatethesis}
\bibliography{bare_thesis}
\fi
```

脚注使用带圈数字的表示方法，此处为示例 1\footnote{测试脚注一} 和示例 2\footnote{测试脚注二}。
参考文献可以使用\cite{BUPT_Thesis_Format_2014}和\onlinecite{BUPT_Thesis_Format_2004}的表示方法。

#### 需要在论文中替换的图片
- RabbitMQ rabbitmq
- 需求分析图  demand
- 系统整体架构图 architecture-a

#### 现阶段存在的问题
- 没有写国内外研究现状