# exam2
The main.cpp file is in /src/model_deploy, and use "sudo mbed compile --source . --source ~/ee2405/mbed-os-build/ -m B_L4S5I_IOT01A -t GCC_ARM --profile tflite.json -f" to compile.
In the screen, type "/gesture/run" to get in accelerator capture mode.
In accelerator capture mode, uLCD will display the gesture ID. Rotating the mbed counterclockwisely is id0. Rotating the mbed clockwisely is id1. The slope motion from Lab8 is id2.
