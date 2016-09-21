# Mac开发软件推荐

### 1、Go2Shell
* 一个可以快速在当前目录打开Shell的工具,小巧,非常好用!
* [Go2Shell 使用技巧](http://www.jianshu.com/p/88c6e68645c4)
* [Go2Shell 下载连接](https://itunes.apple.com/fr/app/go2shell/id445770608?mt=12)

### 2、Cornerstone SVN
* Cornerstone 是当前Mac上最好用的SVN客户端，Cornerstone除了支持基本的SVN功能外，还能够和Xcode，BBEdit，TextMate，Coda等开发工具无缝的集成使用，其时间线功能能够非常方便的查看一个文件的历史改动情况，具有强大的合并、比较功能，非常强大！
* [Cornerstone 3 for Mac 3.0.1 激活版](http://www.waitsun.com/cornerstone-3-0-1.html)

### 3、MacDown
* 一款Markdwon编辑器
* 和Mou同根生，继承了Mou的优良血统，简洁美观；
* 支持代码高亮，并且可以自定义主题，这显示效果够酷炫；
* 支持导出pdf，而且导出的pdf跟实时预览的相差无几，大赞；
* 自从是上后，会爱上写Markdwon，enjoy
* [MacDown 官方下载地址](http://macdown.uranusjr.com/)

### 4、SourceTree
* SourceTree是一款跨平台的Git和Hg客户端，同时也支持gogit
* [Sourcetree 官网](https://www.sourcetreeapp.com/)

### 5、Gitkraken
* 也是git客户端，感谢李赋凌推荐
* GitKranken是一款国外的软件，界面清晰，能更好的让git新手脑中有分支的概念
* [Gitkraken 使用](http://www.cnblogs.com/Nick-Cai/p/5500738.html)
* [Gitkraken 官网](https://www.gitkraken.com/)

# Sublime Text 实用插件

### 1、CTags
* CTags插件，并实现函数跟踪转跳的开发环境。（lua重要可以跳转了，实在是太棒了）
* [Sublime Text2/3怎样在Mac OSX中配置CTags插件](http://jingyan.baidu.com/article/48206aeafba820216ad6b3f5.html)
* [ctags-5.8.tar.gz 下载](https://sourceforge.net/projects/ctags/files/ctags/5.8/)
* 最后，ctags对lua的支持有限，需要在preference - package setting- ctags-settings user 里面加上以下配置
``` 
	opts" : [
		"--regex-LUA=\"/^.*\\s*function[ \\t]*([a-zA-Z0-9_]+):([a-zA-Z0-9_]+).*$/\\2/f,function/\"",
    	"--regex-LUA=\"/^.*\\s*function[ \\t]*([a-zA-Z0-9_]+)\\.([a-zA-Z0-9_]+).*$/\\2/f,function/\"", 
    	"--regex-LUA=\"/^.*\\s*function[ \\t]*([a-zA-Z0-9_]+)\\s*\\(.*$/\\1/f,function/\"", 
    	"--regex-LUA=\"/[ \\t]{1}([a-zA-Z0-9_]+)[ \\t]*[=][^=]/\\1/v,variable/\"", 
    	"--regex-LUA=\"/[ \\t]*([a-zA-Z0-9_]+)[ \\t]*=[ \\t]*module_define.*$/\\1/m,module/\"", 
    	"--regex-LUA=\"/func_table\\[ msg\\.([A-Z_]+) \\].+/\\1/\"",
    	"--regex-LUA=\"/\\([ \\t]*msg.([A-Z_]+)[ \\t]*\\)/\\1/\""
    ]
```

### 2、Modific
* 在你使用Git或SVN时很有用。就像GitGutter,Modific将对你的代码标记改变。除了高亮变化,您还可以通过按Ctrl + Alt + D来查看或比较当前的代码与最近提交的代码之间的区别。你还可以用Modific做其他事情，包括预览当前行的提交代码和恢复代码修改。
* [Modific github](https://github.com/gornostal/Modific)

> created by wisudom at 2016-9-18