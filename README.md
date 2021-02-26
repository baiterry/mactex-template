# 用于 MacTex 撰写中文期刊的模版


<img src="https://s2.ax1x.com/2020/03/09/89Pjxg.png" alt="89Pjxg.png" border="0" />


## Usage

安装 `MacTex` 套件，推荐：
```shell
brew cask install mactex
```

生成文件 `main.pdf`：
```shell
xelatex main
bibtex main
xelatex main
xelatex main
```

P.S. 模板的源代码位于 `cjc.cls` 文件中，可自定义页眉、页脚等文档元素。
