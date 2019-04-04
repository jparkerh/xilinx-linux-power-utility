# xilinx-linux-power-utility

Small test utility for logging power consumption on Xilinx dev boards using a Linux build.
Reads TI INA226 current sense amplifiers included on some development platforms, logs voltage & current from the hwmon driver.
Automatically finds any INA* devices and logs all.

Tested on:

Xilinx ZCU102
Avnet Ultra96 v1

Usage:

./ina_bm

-n number of samples (default: 1)
-t period between samples (default: 1)
-l list all found INA devices at start
-o specify output text file (default: out.txt)

Run app with & at end of line to run in background.
