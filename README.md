# RT-Thread for Gowin GW1NSR-4C Soc

Hello everyone, this project based on RT-THREAD NANO 3.1.3 and GOWIN GW1NSR-4C Soc chip. The compilation environment is MDK 5.35. The GCC version will be developed in the future. In this code, two user threads are running and two lights are controlled. The crystal oscillator on my development board is 27M, so the main frequency of my MCU is 78M. If your main frequency is 80M, you need to modify the __SYSTEM_CLOCK macro.

Finsh is also ported to this project, using UART0, the parameter is 115200 8n1.

Thanks!
