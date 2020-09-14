# pyqt_traceback_fn

```
def except_hook(cls, exception, traceback):
    sys.__excepthook__(cls, exception, traceback)
    sys.exit()
    
if __name__ == "__main__":
    sys.excepthook = except_hook
```
