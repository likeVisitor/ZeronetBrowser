# Troubleshooting

## Fail to load plugins

Absolute path needs to be given to add the plugins.
in PluginManager.py (line 22)
```
#sys.path.append(self.plugin_path)
sys.path.append(os.path.join(os.getcwd(), self.plugin_path))
```

## Use Zeronet as a module

Create a file inside ZeroNet folder

`__init__.py`
```
import main
import Config
```

# Qt 5.12

Using QT 5.12

## PYTHON3

```
$ pip3 install PyQt5-sip PyQt5 PyQtWebEngine
$ cd ZeroNet
$ pip3 install -r requirements.txt
```


## TEST

[zero://mixtape.bit](zero://mixtape.bit)
