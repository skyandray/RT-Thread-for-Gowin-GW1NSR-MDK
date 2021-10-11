# RT-Thread-for-Gowin-GW1NSR-4C
Dear friends,

This is my first repository on github about a popular RTOS RT-Thread, which is based on the RT-Thread Nano 3.1.3 and the compiler is MDK 5.35. I will try the porting of GCC version.

There are two threads running in the code, controls two LEDs on/off with different periods.

The crystal on my board is 27MHz, and the frquency to MCU core is 78MHz. If your board runs a 80MHz for MCU, you need to change __SYSTEM_CLOCK define in the code to 80000000.

Thanks!
