echo "# BootTime-CPU-control-script" >> README.md

This script works with rc.local to execute at during boot

By default it sets cpu to powersave when booting without charger connected.
Have not implemented event handle to go to performance when charger is connected.

But the settings do execute.

How to set the script to run @boot

1. Add rc.local file to /etc/
or execute : sudo touch /etc/rc.local

2. 
