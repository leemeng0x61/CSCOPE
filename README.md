说明：
========

这个工程是为了方便`vimer`所建，`vimer`编写/查看比较大的工程代码时，该工程能达到类似`source insight`的效果！使得建立仓库和寻找变量都变得简单！

工程文件：
========
======

*CSCOPE     #当前只加入了对`.c .cpp .csp .h `的支持，如需特别加入支持，请在`CSCOPE`中添加
*GVIM_CMP   #选中两个文件进行对比
*GVIM_LEFT  #选为左侧对比
*GVIM_RIGHT #与左侧进行对比
*install   #安装程序
*vimrc     #vim 脚本
*.vim      #vim 插件 加入c代码补全功能，函数补全功能，`Tlist dirlist supertab`等等

安装：
========

`chmod +x install`
`./install`

使用：
========

`cd project`
`CSCOPE`
`vim .` 或者 `gvim .`

PS:`cscope` 使用请在命令行模式输入`:cs` 查看帮助
