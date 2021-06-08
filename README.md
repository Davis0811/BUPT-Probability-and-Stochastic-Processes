# BUPT-Probability-and-Stochastic-Processes (概率论与随机过程习题解答)

## 简介

[![Build Probability and Stochastic Processes PDF](https://github.com/itdevwu/BUPT-Probability-and-Stochastic-Processes/actions/workflows/main.yml/badge.svg)](https://github.com/itdevwu/BUPT-Probability-and-Stochastic-Processes/actions/workflows/main.yml)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/itdevwu/BUPT-Probability-and-Stochastic-Processes)](https://github.com/itdevwu/BUPT-Probability-and-Stochastic-Processes/releases/latest)

“概率论与随机过程”是北京邮电大学计算机类学生在大二秋季学期的“二选一”课程之一。这门课程对于数据科学、深度学习等方向的后续学习都十分重要。

在北京邮电大学，该课程的教材是由理学院数学系张丽华副教授和周清教授编纂的《*Probability and Stochastic Processes*》。由于在大部分学校，随机过程都是单独开课，且北邮所使用的教材是本校自编的英文教材，导致课程学习资料匮乏。考虑到本课程的重要意义，作者希望将学习过程的习题解法加以整理，以期惠及后人。

为了方便读者反馈，改进本文档内容，用于生成本文档的 TeX 代码会被托管在 GitHub 网站上的 [itdevwu/BUPT-Probability-and-Stochastic-Processes](https://github.com/itdevwu/BUPT-Probability-and-Stochastic-Processes) 这一 repo 中。读者可以通过提 issue 和 pull request 等方式来参与到本文档的编修工作中。

受限于作者的知识水平和细致程度，本文档无法做到尽善尽美。恳请各位斧正。

## 使用指南

### 自动编译

GitHub Actions 提供了极为方便的持续集成服务。它会自动在每次 push 时，编译生成新的```.pdf```文件，并将之纳入一个新的 release。

您可以在 [releases](https://github.com/itdevwu/BUPT-Probability-and-Stochastic-Processes/releases/latest) 处直接下载最新的```.pdf```文件。

### 手动编译

首先将本文档代码下载到本地或 clone 到目标目录：

```
git clone https://github.com/itdevwu/BUPT-Probability-and-Stochastic-Processes.git
```

采用 XeLaTeX 编译器和 CTeX 宏包进行编译，获得编译后```.pdf```文件。

LaTeX 教程可参考[一份其实很短的 LaTeX 入门文档](https://liam.page/2014/09/08/latex-introduction/)，CTeX 宏包文档详见 [CTeX 宏集手册](https://mirrors.tuna.tsinghua.edu.cn/CTAN/language/chinese/ctex/ctex.pdf)。

### 查看进度

您可以在 [Milestones](https://github.com/itdevwu/BUPT-Probability-and-Stochastic-Processes/milestones) 处查看本文档的完善进度。

## 版权声明

Copyright (c) 2021 WU Zhenglong

Copyright (c) 2021 itdevwu

本文档指的是“概率论与随机过程习题解答”这一文档。

在未经特别说明的情况下，本文档的内容（包括但不限于文字、图片等）采用“[知识共享署名-相同方式共享4.0国际许可协议](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)”（简称为“CC-BY-SA 4.0协议”）进行许可。该协议由知识共享组织（Creative Commons）撰写。请注意，本作品中注明以其他方式进行许可或著作权人非本文档作者的内容，需按照特殊说明进行处理。

本文档采用 LaTeX 撰写。这意味着作者在撰写本文档内容的同时还撰写了一份软件源代码，以处理本文档内容的排版、渲染等问题。

“CC-BY-SA 4.0 协议”具有对由[自由软件基金会（Free Software Foundation, Inc）](https://www.fsf.org/)提供的“[GNU GENERAL PUBLIC LICENSE Version 3](https://www.gnu.org/licenses/gpl-3.0.html)”（以下简称“GPLv3协议”）的单向兼容性。这意味着如果您希望在本书的 TeX 代码的基础上进行再创作和分发，您亦可遵循“GPLv3协议”。

请注意，上述说明基于“CC-BY-SA 4.0 协议”本身的兼容性，不代表本文档的代码采用“GPLv3协议”进行授权或分发。

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。