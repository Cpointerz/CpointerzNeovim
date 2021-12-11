# CpointerzNeoVim

一个初二的小垃圾的配置文件。也就写着玩，刚好满足自己的需求。发上来只是为了让更多人了解到NeoVim  

# 注意  
如果保存文件时卡死COMMOND模式可用```Ctrl + q```
# 安装  
在~/.config/nvim/中放置init.vim文件

在~/.config/nvim/autoload/放置dein.vim

# 注意事项

## 快速安装所有模块

SPACE p i + SPACE c i: 安装Rust/Java/Python的语言支持模块

## 首次使用

''':WakaTimeDebugEnable''' + shell运行'''tail -f ~/.wakatime.log'''

# 已配置的快捷键

## NORMAL模式  
```

t :目录树

o :上一个buffer

p :下一个buffer

e :TagBar

SPACE r :Rust/Java/Python运行

SPACE b :Rust编译

SPACE p i :安装配置文件里指定的插件

SPACE p u :更新配置文件里指定的插件

SPACE c i : 安装语言支持模块

SPACE c u : 更新语言支持模块

f :分屏切换

n :纵向窗口分割

w :保存文件

q :退出

b+ a/s/d/f/g/h/j/k/l/; +ENTER:快速切换序号0-9的buffer

fa CR :搜索单词

ff CR :搜索文件

fh CR :搜索记录

tc CR :修改颜色

fb CR :标签

, :上一个搜索结果

. :下一个搜索结果

```


## INSERT模式
```  
jk :ESC
```