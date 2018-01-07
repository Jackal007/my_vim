# my_vim


## 1.使用前要配置环境变量

windows：VIM_HOME vim安装路径
其他：xxxxx xxxxx
修改vimrc中的：
```
set rtp+=$VIM_HOME/bundle/Vundle.vim/
call vundle#begin('$VIM_HOME/bundle/')
```
为正确的

## 2.打开vim，命令模式输入 `:PluginInstall` ，有输出说明成功了

vimrc中的配置

from http://blog.csdn.net/trochiluses/article/details/21776365

1.键盘绑定 :help map-overview
vim最大的特点在于可以把所有的操作能够用一个命令字符串表达出来，
因此这带来了编写脚本的最大的便利。键盘绑定就是一个例子，这个功能允许
把一个命令字符串绑定到一个按键/按键组合。

一般格式：映射命令 按键组合 命令组合
例子：nmap c ^i#<Esc>j
解释：映射normal模式下的按键c为：^i#<Esc>j，就是在该行开头加上#号
，然后下移一行

常用映射命令：
map :全模式映射
nmap :normal模式映射
vmap :visual模式映射
imap :insert模式映射
