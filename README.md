# Latex Template

## Description:

This is a Latex template that I use to write some simple notes or articles. We you are using Latex, you will find adding a lot of commands in the front of your ``.tex`` file is really annoying. Moreover, some packages are really useful but you are constantly looking for their names and putting them in your preamble. To save my time, I put them all into a ``.cls`` file, and you just need one statement in yout tex file to load them all. Therefore, your draft looks much clearer and neater, just like this

```latex
%!TEX TS-program = xelatex
%!TEX encoding = UTF-8 Unicode
% Use Xelatex and UTF-8

\documentclass[CHN]{Sketch}
% 用这一句引用Sketch类 选项不填默认英文 可以写[ENG]或者[CHN] 

\title{Title}
\author{Zhang Chuheng \\ \href{mailto:zhangchuheng123@live.com}{zhangchuheng123@live.com}}
\date{\today} 

\begin{document} 
\maketitle

% Your text goes here...

\bibliographystyle{gbt7714-2005}
\bibliography{Sample}

\end{document}
```

If you want to use it, just download the folder and write your tex file in ``sample.tex``. All the folders and files are prepared ready for your writting, including bibtex related files. 

Let's get started...
