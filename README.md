# RT-Thread-for-Gowin-GW1NSR-4C
Dear friends,

It is my first repository on GitHub about a popular RTOS RT-Thread, which is based on the RT-Thread Nano 3.1.3. The compiler is MDK 5.35. I will try the GCC version.

Two threads are running in the code, controls two LEDs on/off with different periods.

The crystal on my board is 27MHz, and the frequency to MCU core is 78MHz. If your board runs an 80MHz for MCU, you need to change __SYSTEM_CLOCK defined in the code to 80000000.

Thanks!
