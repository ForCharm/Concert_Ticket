# Concert_Ticket
大麦网演唱会抢票程序
* Python3.6
* Selenium
## 准备工作
* 下载anaconda，对应python3.6
* 下载火狐浏览器（推荐）以及对应的geckodriver.exe，并将此exe转移到python.exe旁边。谷歌浏览器的操作类似。
* 打开命令提示窗口，输入pip install selenium
* 如果提示其他包未安装，请用相同的方式下载
* 在user_info.txt中输入提示的信息
* 在主函数中按要求输入演唱会信息
* 运行代码，在这个过程中注意观察串口输出

## （注：自从我在知乎分享了代码后，很多人关注了我的代码，自己也很荣幸，哈哈。但是好多人运行我的代码却出现了这样那样的问题，我刚开始也很纳闷，明明自己当初试了好几个演唱会都可以，为什么现在有这么多问题，上段时间自己正好有事自己也没太关注这个，所以我也只是站在原来研究的基础上进行回答，很多回答可能并没有点到关键上。最近正好有人QQ找我，我好好看了下，发现原来是大麦网的页面源码变了，变了很多很多，所以我原来的代码差不多失效大半了。我的方法太过于依赖页面源码的元素ID、xpath、class_name等等标签，所以应付不了这种变化。em，更新代码这件事，我最近先放放。不过大致思路是对的，大家在我的代码基础上修改下又是可以用的啦~）
