# PickerView
自定义单列滚动选择器，一行代码，简单调用。

后期会增加多列选择，滚轮联动

![image](https://github.com/HoHoDoDo/PickerView/blob/master/PickerView/screenshots/PickerViewTest.gif?raw=true)

如何使用
------

```
[[[HDPickerView alloc] initPickerViewWithDataSource:dataSource
                                        selectVaule:^(NSString *value, NSInteger component, NSInteger row) {
                                            // TODO:...
                                        }] show];
```
