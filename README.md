# A2T1 STM32F407VET6 KnightRider

**Assignment Description:** Implement knight rider running light

**Group Name:** Smart Dolphins\
**Owners:** Veknes Benjaman; Saw Jun Chao

**Source Code:** [main.c](/A2T1_STM32F407VET6_KnightRider/Core/Src/main.c)\
**Video Demonstration:** [https://youtu.be/X_kCsgKNavA](https://youtu.be/X_kCsgKNavA)

## Descriptions on Board and Microcontroller

**STM32 development board model:** STM32F4VE\
**Microcontroller:** STM32F407VET6\
**Core:** ARM Cortex-M4

## GPIO Pins Configuration, Components and Code Functions

[1] Pinout configuration in STM32CubeIDE

-> PD0 to PD7 configured as GPIO_Output

[2] Components

- Yellow LEDs (Voltage Drop, Vd ~= 2.2V) connected in active low configuration (LOW pin state turns LED on)
- Resistor (100 ohms)

<center><img src="/pictures/schematics.png"></center>

[3] Code function

HAL_Delay(Delay) : Creates delay (in ms)\
GPIOD->ODR : Output data register

## References

[1] Board Details and Schematics:\
[https://stm32-base.org/boards/STM32F407VET6-STM32-F4VE-V2.0.html](https://stm32-base.org/boards/STM32F407VET6-STM32-F4VE-V2.0.html)\
[2] STM32CubeIDE Tutorial:\
[https://www.st.com/resource/en/user_manual/um2609-stm32cubeide-user-guide-stmicroelectronics.pdf](https://www.st.com/resource/en/user_manual/um2609-stm32cubeide-user-guide-stmicroelectronics.pdf)\
[https://www.youtube.com/playlist?list=PLnMKNibPkDnFCosVVv98U5dCulE6T3Iy8](https://www.youtube.com/playlist?list=PLnMKNibPkDnFCosVVv98U5dCulE6T3Iy8)\
[3] Previous Assignment:\
[https://github.com/SawJunChao/stm32blinky](https://github.com/SawJunChao/stm32blinky)\
[https://github.com/SawJunChao/stm32morse](https://github.com/SawJunChao/stm32morse)