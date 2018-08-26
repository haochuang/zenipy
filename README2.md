# Python一行代码实现 GUI弹框

JS中有两个方法: alert 和 confirm, 虽然它们登不了大雅之堂, 只能在测试时候用用. 但是因为可以直接调用, 而且会弹一个GUI框出来, 总是觉得很提神醒脑. 


现在, Python也能一行代码弹框出来了. 比如我在脚本中加入如下这行
```
from pythonzenity import Calendarresult = Calendar(title="Awesome Calendar",text_info="Your birthday ?")
```

这个功能依赖于库python-zenity



这个库的依赖


Python 2.x (x>6)

PyGTK

安装办法依旧简单
```
$ pip install python-zenity
```

除了日期选择框, 还有很多其他可用的弹框, 如提示\报错\警告\提问 等等.

项目github地址是:

https://github.com/poulp/python-zenity

https://github.com/haochuang/zenipy/

后续看时间使用场景，择况更新
