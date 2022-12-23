<div align='center'>
    <h1>Calculator with  Python  </h1>
    <img src='./demo/demo.gif' title='Demo da calculadora' width='340px' />
</div>



## Start
```
$ python main.py
```

 ```Python
# -*- coding: utf-8 -*-

# Builtin
import tkinter as tk

# Internal module
from app.calculadora import Calculadora

if __name__ == '__main__':
    master = tk.Tk()
    main = Calculadora(master)
    main.start()
```

 