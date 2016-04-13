# Gestus
Control your drones and RC toys with your hands!
13.04.16 This file was created by Evgeniy Popravka aka Riconec.

This is project of making hand gesture controlled remote control for different RC stuff.
First tests were made on ground RC platform with DC motors and 868MHz RF modules.
Second generation uses NRF51822 USB dongle for receiving data from two NRF51822 Evaluation kits with MPU6050 on it. Calculation is made on PC by C# program. Data transmitted by Arduino with A7105 2.4GHz RF module to the Hubsan X4.
Third generation is under developement and uses NRF24LE1 modules + ADXL345 as controls, NRF51822 as receiver with A7105 to communicate with Hubsan x4.
