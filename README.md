# Code in Class

2023 fall term


## Installing into a Conda environment
It's probably a good idea to create a virtual environment to keep this package and its dependencies separated from your other Python code and projects. If you've never used virtual environments before this might be a good time to start, and it is really easy using Conda:

```bash
conda create -n rvc3 python=3.10
conda activate rvc3
pip install rvc3python
```

### Activate `rvc3` environment

```bash
conda activate rvc3
```

## Installing the package

This package provides a simple one-step installation of all the required Toolboxes

```bash
pip install rvc3python
```

## Activate the `rvc3` env

```bash
conda activate rvc3
```

## Starting the toolboxes

```bash
rvctool
```

You will see this if everything was successfully installed.
```
 ____       _           _   _             __     ___     _                ___      ____            _             _   _____ 
|  _ \ ___ | |__   ___ | |_(_) ___ ___    \ \   / (_)___(_) ___  _ __    ( _ )    / ___|___  _ __ | |_ _ __ ___ | | |___ / 
| |_) / _ \| '_ \ / _ \| __| |/ __/ __|    \ \ / /| / __| |/ _ \| '_ \   / _ \/\ | |   / _ \| '_ \| __| '__/ _ \| |   |_ \ 
|  _ < (_) | |_) | (_) | |_| | (__\__ \_    \ V / | \__ \ | (_) | | | | | (_>  < | |__| (_) | | | | |_| | | (_) | |  ___) |
|_| \_\___/|_.__/ \___/ \__|_|\___|___( )    \_/  |_|___/_|\___/|_| |_|  \___/\/  \____\___/|_| |_|\__|_|  \___/|_| |____/ 
                                          |/                                                                                   
for Python (RTB==1.1.0, MVTB==0.9.6, SG==1.1.8, SMTB==1.1.8, NumPy==1.26.0, SciPy==1.11.2, Matplotlib==3.8.0)

    import math
    import numpy as np
    from scipy import linalg, optimize
    import matplotlib.pyplot as plt
    from spatialmath import *
    from spatialmath.base import *
    from spatialmath.base import sym
    from spatialgeometry import *
    from roboticstoolbox import *
    from machinevisiontoolbox import *
    import machinevisiontoolbox.base as mvb
    
    # useful variables
    from math import pi
    puma = models.DH.Puma560()
    panda = models.DH.Panda()

    func/object?       - show brief help
    help(func/object)  - show detailed help
    func/object??      - show source code
    
Results of assignments will be displayed, use trailing ; to suppress

Python 3.10.13 (main, Sep 11 2023, 13:44:35) [GCC 11.2.0]
Type 'copyright', 'credits' or 'license' for more information
IPython 8.15.0 -- An enhanced Interactive Python. Type '?' for help.
Installed tk event loop hook.
'%.3g;'

>>> 


```