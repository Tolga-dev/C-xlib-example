# auto clicker in linux 

### basic implementation
All you need to do is include <X11/Xlib.h>

---

**Hello World c file**

-> Include Screen, Keyboard, Mouse Button

gcc HelloWorld.c -o hello  -lX11 -Wall -Wextra; ./hello 


**auto clicker file**

gcc autoClicker.c -o hello -lX11 -lXtst; ./hello
