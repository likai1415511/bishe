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

#### 需要重画/修改的图
- sdn.png该图在新一代网络架构.doc中有viso格式，需要转为pdf
- of-switch.png该图在新一代网络架构.doc中有viso格式，需要转为pdf
- match.png该图在新一代网络架构.doc中有viso格式，需要转为pdf
- ryu.jpg需要自己visio绘制
- ovx.png该图在小论文-中文版.doc中有visio图，需要转pdf
- openstack.png该图在openstack社区Juno版本安装教程中有，需要重新画
- br-tun.png需要visio绘制
- neutron.png需要Visio绘制

#### 现阶段存在的问题
- 没有写国内外研究现状
- 没有写面临的挑战和关键技术