# resume-moderncv
使用modercv简历类来制作简历（受一个华科学长启发）

##使用步骤：
1. 下载安装Tex Live。我使用的是windows平台，找半天安装文件，建议使用[TexLive的iso文件](http://tug.org/texlive/acquire-iso.html)安装，下载速度还可以。下载以后，有个exe文件，打开，在任务栏右下角通知区域会出现一个图标，点击图标，选择"command prompt",在弹出的命令行窗口中，输入“install-tl-windows.bat”，就可以安装成功了。在你使用TexLive之前，建议先读一下[TexLive使用文档（中文的，所以不用担心）](http://tug.org/texlive/doc/texlive-zh-cn/)。主要的命令就是``pdflatex **.tex``，就能生成相应的pdf文件。你可以测试一下，如果没有这个命令的话，可能是TexLive的bin目录没有添加到环境变量中。 此外，直接双击``.tex``文件的话，会默认用TexWorks编辑器打开，在窗口的上方有一个开始按钮一样的文件”排版“，点击，也能生成对应的pdf文件。其它技巧需要读者自己去发掘了。（我觉得用其他latex编辑器也可以，比如说windows下的CTEX，但是，用过TextLive以后，感觉TextLive还是好一点，不用破解)
2. clone[我的resume-moderncv内容](https://github.com/wutongjie23hao/resume-moderncv)。当然你也可以自己下载[moderncv](http://www.ctan.org/tex-archive/macros/latex/contrib/moderncv)的文档类，相当于tex模版。
3. 在example文件夹里面使用Tex Live编辑你自己的简历吧。可以参照我的或者实例模版。
