# Sublime-Plugin 
>Sublime Text 3 Plugin插件配置；将文件下载放到User目录下即可同步

<!-- MarkdownTOC -->

- [插件列表及开发环境搭建](#%E6%8F%92%E4%BB%B6%E5%88%97%E8%A1%A8%E5%8F%8A%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA)
    - [&emsp;&ensp;Markdown环境](#emspenspmarkdown%E7%8E%AF%E5%A2%83)
    - [&emsp;&ensp;Python环境](#emspensppython%E7%8E%AF%E5%A2%83)
    - [&emsp;&ensp;Matlab环境](#emspenspmatlab%E7%8E%AF%E5%A2%83)
- [Sublime 构建系统](#sublime-%E6%9E%84%E5%BB%BA%E7%B3%BB%E7%BB%9F)
- [快捷键设置](#%E5%BF%AB%E6%8D%B7%E9%94%AE%E8%AE%BE%E7%BD%AE)
- [使用](#%E4%BD%BF%E7%94%A8)

<!-- /MarkdownTOC -->

## 插件列表及开发环境搭建
- [Side bar](https://github.com/SideBarEnhancements-org/SideBarEnhancements):增强侧边栏工具
- [A File Icon](https://github.com/ihodev/a-file-icon):侧边栏文件图标显示，配合Side bar使用
- [Alignment](https://github.com/wbond/sublime_alignment)：等号对齐
- [Auto File Name](https://github.com/BoundInCode/AutoFileName)：文件路径自动提示
- [Boxy Theme](https://github.com/ihodev/sublime-boxy):包含Boxy Monokai、 Boxy Nova、Boxy Ocean、Boxy Solarized Dark、Boxy Solarized Light、Boxy Tomorrow、Boxy Yesterday
- [Vingeous](https://github.com/guillermooo/Vintageous):Vim插件
- [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter):括号（[], (), {}, "", '', #!xml <tag></tag>等）匹配高亮
- [Cndict](https://github.com/divinites/cndict):中英文字典https://github.com/divinites/cndict
- [Ctags](https://github.com/SublimeText/CTags):函数代码生成tag，配合其他插件实现函数的查询、跳转等。系统需安装ctag-我将其安装到了Sublime的User/PluginInstall目录下  
Seetings-User设置：
```css
{
   "command": "C:/Users/vincent/AppData/Roaming/Sublime Text -Packages/User/PluginInstall/ctags-ctags.exe"
}
```
- [DocBlockr](https://github.com/spadgos/sublime-jsdocs):代码注释DocString生成，支持Javascript, PHP, CoffeeScript, Actionscript, C & C++
- [DocBlockr Python](https://github.com/adambullmer/sublime_docblockr_python)：Python的DocBlockr
- [FileDiffs](https://github.com/colinta/SublimeFileDiffs):文件比对
- [FindKeyConflicts](https://github.com/skuroda/FindKeyConflicts):找到Sublime的快捷键冲突项
- [FuzzyFileNav](https://github.com/facelessuser/FuzzyFileNav):简易的文件管理器
- [Glue](https://github.com/chrissimpkins/glue/issues):Shell命令行,让Sublime可以进行shell交互
- [HexViwer](https://github.com/facelessuser/HexViewer):以16制和ASCII模式显示文件
- [LaTeX Word Count](https://github.com/kevinstadler/SublimeLaTeXWordCount):字符统计
- [Local History](https://github.com/vishr/local-history):自动保存本地历史文件
- [Origami](https://github.com/SublimeText/Origami):增强的Sublime分屏工具
- [TabsExtra](https://github.com/facelessuser/TabsExtra):增强Sublime标签选项

![TabsExtra](http://iostream.io/wp-content/uploads/2017/12/Menu.png)

- [Trailing Spaces](https://github.com/SublimeText/TrailingSpaces):高亮文本末尾的空格字符，并可以删除所有末尾空白字符
- [Verilog Automatic](https://github.com/Tian-Changsong/Verilog-Automatic):Verilog语法工具，可以自动生成接口、实例，声明
- [ConvertToUTF8](https://github.com/seanliang/ConvertToUTF8):编辑并保存编码不被 Sublime Text 支持的文件，解决文件乱码问题
- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3):代码语法检测工具；具体的语法检测需要单独安装组件

### &emsp;&ensp;Markdown环境

- [Markdown Extended](https://github.com/jonschlinkert/sublime-markdown-extended):Markdown 语法高亮
- [Markdown Editing](https://github.com/SublimeText-Markdown/MarkdownEditing):增强的Markdown语言编辑器
- [Table Editor](https://github.com/vkocubinsky/SublimeTableEditor):表格编辑工具,实现下面这样的复杂表格
```
|    Name   | Age |   Phone   |
|-----------|-----|-----------|
| Anna      |  -| -|
| Alexander |  -| -|
|           |     |           |
```
- [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview):在浏览器中预览Markdown文本，同时可以将Markdown转为HTML文件
- [MarkdownToc](https://github.com/naokazuterada/MarkdownTOC):Markdown目录生成;  
自动插入并更新TOC：
```
- [插件列表及开发环境搭建](#%E6%8F%92%E4%BB%B6%E5%88%97%E8%A1%A8%E5%8F%8A%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA)
    - [&emsp;&ensp;Markdown环境](#emspenspmarkdown%E7%8E%AF%E5%A2%83)
    - [&emsp;&ensp;Python环境](#emspensppython%E7%8E%AF%E5%A2%83)
    - [&emsp;&ensp;Matlab环境](#emspenspmatlab%E7%8E%AF%E5%A2%83)
- [Sublime 构建系统](#sublime-%E6%9E%84%E5%BB%BA%E7%B3%BB%E7%BB%9F)
- [快捷键设置](#%E5%BF%AB%E6%8D%B7%E9%94%AE%E8%AE%BE%E7%BD%AE)
- [使用](#%E4%BD%BF%E7%94%A8)

<!-- /MarkdownTOC -->
```
&emsp;&ensp;生成的文本目录如本文开头蓝色字体；同时支持目录的跳转

- [AcademicMarkdown](https://github.com/mangecoeur/AcademicMarkdown):添加Markdown文件头，将文档渲染为自定格式的文章，写论文利器;  
模板格式可以参考：[Zotero Style Repository](https://www.zotero.org/styles)
- [Citer](https://github.com/mangecoeur/Citer)：文献搜索与插入工具;本文并没有使用这个插件，如要使用，插件需要配置
- [Pandoc](https://github.com/larlequin/PandocAcademic):文档格式相互转为，支持Markdown、Word、Latex、HTML-PDF等等许多格式;详情可以参考[Pandoc Github](https://github.com/tbfisher/sublimetext-Pandoc);系统需安装Pandoc软件，并设置安装路径
Seetings-User设置：
```
{
   "pandoc-path":"D:/user/software/work/Pandoc/pandoc.exe"
}
```
&emsp;&ensp;如果需要将文档转为PDF需要安装Latex,Windows推荐[TeX Live](https://www.tug.org/texlive/acquire-netinstall.html)(*本文没有配置好pdf的中文支持*)


### &emsp;&ensp;Python环境

- [SublimeLinter-pylint](https://github.com/SublimeLinter/SublimeLinter-pylint):SublimeLinter python组件。首先在系统上安装Python环境，推荐[Anaconda](https://www.anaconda.com/download/);然后安装pyInit '`pip install pylint`' (如果安装了Anaconda,pylint默认已经安装)
- [Jedi](https://github.com/srusskih/SublimeJEDI):Python 自动补全,查找函数定义、使用，显示DocString
- [SublimeREPL](https://github.com/wuub/SublimeREPL):交互式代码执行(解释器)，支持多种语言
- [SublimeTmpl](https://github.com/kairyou/SublimeTmpl):代码模板，支持多种语言；在'`Sublime Text 3\Packages\User\SublimeTmpl\templates`'目录下修改模板'python.tmpl',并设置对应的快捷键即可新建该语言的模板文件  
本文Python模板如下：

```css
'''
****************************************Copyright (c)**************************************************
**                                        ICT
**                                     
**---------------------------------------File Info-----------------------------------------------------
** File name:           template
** Last modified Date:  xx-xx-xx
** Last Version:        1.0
** Descriptions:        xxxxxxxxxxxxxxxxxx
**------------------------------------------------------------------------------------------------------
** Created by:          username
** Created date:        ${date}
** Version:             1.0
** Descriptions:        xxxxxxxxxxxxxxxxxx
**
**------------------------------------------------------------------------------------------------------
** Modified by:         user-name
** Modified date:       x-x-x   
** Version:             1.0
** Descriptions:        xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
**
**------------------------------------------------------------------------------------------------------
********************************************************************************************************
'''

${1:import os}

if __name__ == "__main__" :
    main()

```

快捷键：

```css
{
        "keys": ["ctrl+alt+p"], "command": "sublime_tmpl",
        "args": {"type": "python"}, "context": [{"key": "sublime_tmpl.py"}]
    },
```
### &emsp;&ensp;Matlab环境

- [Matlab-Completions](https://github.com/tushortz/Matlab-Completions):Matlab 语法自动补全
- 系统安装Matlab
- 新建Build System：在Sublime中选择Tools -> Build System -> New Build System，系统会创建一个JSON文件；Windows修改如下,保存即可

```css
{
    "cmd": ["D:/user/software/work/MATLAB2015b/bin/matlab.exe", "-nodesktop", "-nosplash", "-r", "\"run('$file')\""],
    "selector": "source.m",
    "working_dir": "${project_path:${folder}}"
}

```
>matlab -nosplash -nodesktop -r ${file_base_name}表示启动matlab，并运行某个.m文件。-nosplash表示不加载启动界面；-nodesktop表示不加载GUI界面；-r表示运行Matlab命令行（MATLAB_command）

- 使用Sublime 快捷键'Ctrl+B'编译运行Matlab代码；每次运行都会产生新的Matlab命令行界面，有点耗时间；可以第一次启动Matlab命令行，以后在命令中运行新的Matlab代码

## Sublime 构建系统
&emsp;&emsp;&ensp;Sublime Text 3 提供了构建系统（Build System），可以编译并运行程序，本质上调用系统安装的代码编译器。对于任意语言，只要在系统安装了对应的编译器，就可以使用构建系统运行程序。比如C++,在系统上安装gcc/g++(MinGW)环境之后就就可以在C++文件界面按下'Ctrl+B'编译运行C++代码，python类似。  
&emsp;&emsp;&ensp;但是，构建系统不支持交互式界面，即程序接受键盘输入；所以，上文提到利用SublimeREPL交互式解释器运行Python代码。

## 快捷键设置
&emsp;&emsp;&ensp;打开sublime的Preference 下的Key Bindings,在User设置下增加快捷键配置即可绑定快捷键。

- **F1**:调用SublimeREPL运行当前Python文件
- **F2**:调用SublimeREPL在新窗口运行Python shell
- **alt+m**:调用Markdown Preview 在浏览器中预览当前Markdown文本
- **ctrl+alt+v**:调用SublimeTmpl新建Verilog文件
- **ctrl+alt+p**:调用SublimeTmpl新建Python文件

## 使用
- 安装Sublime Text 3以及Package Control
- 通过Sublime的`Preferences/Browse Packages`代开Sublime的配置目录
- 通过Git或下载当前工程’Sublime-Plugin‘
- 将’Sublime-Plugin‘目录下所有文件拷贝到User目录下
- 重启Sublime 即可同步插件即设置
- 如需使用必须独立软件配合的插件，根据上文在系统安装对应软件并更改执行路径
