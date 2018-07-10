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

一个跨平台的GUI库。

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
