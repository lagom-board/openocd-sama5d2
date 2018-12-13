Based on work done at https://github.com/olivierschonken/openocd-sama5.

Tested with Bus Blaster:
```
openocd -f interface/ftdi/dp_busblaster.cfg -f ./scripts/board/at91sama5d2X-ek.cfg -c "init"   
```
