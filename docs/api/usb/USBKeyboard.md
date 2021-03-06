## USBKeyboard

<span class="images">![](https://os.mbed.com/docs/development/feature-hal-spec-usb-device-doxy/class_u_s_b_keyboard.png)<span>USBKeyboard class hierarchy</span></span>

The USBKeyboard class provides the functionality of a keyboard. You can send key presses, check the status of control keys and send a key press sequences though a stream interface. If you need mouse or keyboard and mouse functionality, please see the [USBMouse](USBMouse.html) and [USBMouseKeyboard](USBMouseKeyboard.html) classes.

### USBKeyboard class reference

[![View code](https://www.mbed.com/embed/?type=library)](http://os.mbed.com/docs/development/feature-hal-spec-usb-device-doxy/class_u_s_b_keyboard.html)

### USBKeyboard example

```C++ TODO
#include "mbed.h"
#include "USBKeyboard.h"

USBKeyboard key;

int main(void)
{
  while (1) {
      key.printf("Hello World\r\n");
      wait(1);
  }
}
```

### Related content

- [USBMouse](USBMouse.html).
- [USBMouseKeyboard](USBMouseKeyboard.html).
