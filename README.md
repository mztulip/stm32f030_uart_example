# stm32f030_uart_example
Simple project with UART TX using stm32f030
LED is connected to PB0
USART TX - PA2


Compile
Update path to arm-none-eabi-gcc in makefile

make
make output.bin

Flasing
Simple bash script which uses openocd with stlinkv2 to program microcontroller.
./flash

Hardware
https://circuitmaker.com/Projects/Details/Mateusz-buleks/Flysky-receiver-8-channels

![alt text](https://github.com/mztulip/stm32f030_uart_example/blob/main/board.jpg?raw=true)