# 调试期间

PyCharm的调试功能很强大，也很智能。

## 调试时实时打开项目外的文件

某次调试项目，遇到import导入了当前项目之外的文件：

![import_external_file](../../assets/img/import_external_file.png)

继续下一步调试`Step Into`的话，则可以打开，当前项目之前的文件去继续调试：

![step_into_open_external_file](../../assets/img/step_into_open_external_file.png)

很是方便。

## 动态显示变量的属性的值

对于代码：

```python
if not connection.isConnected:
```

`isConnected`是对象变量`connection`的属性值，PyCharm都支持显示：

当鼠标移动到`isConnected上`时，可以自动检测到`connection.isConnected`是个整体，然后动态显示出其值：

![show_propety_value](../../assets/img/show_propety_value.png)

还是很好用的。
