# Python库集锦

## 1. wxPython

https://wxpython.org

一个跨平台的GUI库。

```python
import wx

app = wx.App()
frm = wx.Frame(None, title = 'Hello')
frm.Show()
app.MainLoop()
```

## 2. PyYAML

https://pyyaml.org

一个YAML框架。

```python
import yaml

document = '''
    name: Tom
    age: 18
'''

data = yaml.load(document)
print(data['name'])
print(data['age'])
```

## 3. NumPy

http://www.numpy.org

一个科学计算基础包。

```python
import numpy as np

a = np.arange(15).reshape(3, 5)
print(a)
print(a * 3)
```
