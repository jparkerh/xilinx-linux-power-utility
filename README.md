# xilinx-linux-power-utility

Small test utility for logging power consumption on Xilinx dev boards using a Linux build.
Reads TI INA226 current sense amplifiers included on some development platforms, logs voltage & current from the hwmon driver.
Automatically finds any INA* devices and logs all.

Tested on:
<br>
Xilinx ZCU102 <br>
Avnet Ultra96 v1 <br>
<br>
Usage:
<br>
./ina_bm
<br>
-n number of samples (default: 1) <br>
-t period between samples (default: 1) <br>
-l list all found INA devices at start <br>
-o specify output text file (default: out.txt) <br>
<br>
Run app with & at end of line to run in background.
