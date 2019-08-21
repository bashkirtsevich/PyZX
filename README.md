# PyZX Python ZX Spectrum Emulator


Based on Vadim Kataev's PyZX Python Spectrum Emulator
License: GPL-2 (free)

PyZX is ZX Spectrum emulator.

It is written fully in Python programming language. 


## Requirements:

* Python 3.x (python.org)
* PyGame 1.7+ (pygame.org)


## Run:

```
python3 spectrum.py
```

Optionally you can try to use `-OO optimization` flags:

```
python3 -OO spectrum.py
```


## Keys:

* Ctrl + Alt => switch into special mode
* Alt + AnyKey => symbol shift
* Ctrl(being in normal mode) + AnyKey => big/small chars
* Ctrl(being in special mode) + AnyKey => symbol shift 2


## TODO: 

* Another, real Python approach for the core (Z80 CPU)
* Threads in parallel (video and maybe keyboard)
* TAP/TZX files reading


## Author: 

Vadim Kataev (initial version)
Stanislav Yudin (initial conversion to py3)
Vladimir Berezenko

---

Thanks to Jasper(http://www.spectrum.lovely.net/) for real great Java emulator of
ZX Spectrum. Big amount of code was just automatically translated from Java into
Python, so we need more optimization/rewriting to reach good speed of emulation.