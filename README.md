# listviewEx
给winform的listview控件增加编辑框和下拉选择框交互功能 . for winform listview+editBox+comboBox function. 


![运行后gif](https://raw.githubusercontent.com/popde/listviewEx/main/1667054381830566.gif)


一直以来winform的listview都只是作为数据输出显示来用, 想要实现数据的双向操作比较难


之前都需要用其他表格类控件实现这个双击编辑文本,双击实现下拉列表框选择文本功能, 而且其中有很大一部分是ocx组件, 


那么就需要在客户电脑上regsvr32 注册它, 这样就需要管理员权限, 这样操作并不是很好, 


于是考虑着手动改造listview使其满足我的需求.


还好, aardio范例里有个数据视图win.ui.grid的库可供参考, 我就是根据这个库内的实现方法来升级改造的.


下面我在原listview grid基础上增加了, 双击指定列 可直接编辑文本  / 弹出下拉框选择文本 功能.

本文首发: https://www.htmlayout.cn/t/21395

