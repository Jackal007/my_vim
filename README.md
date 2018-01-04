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