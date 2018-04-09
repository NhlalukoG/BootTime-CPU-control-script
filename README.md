echo "# BootTime-CPU-control-script" >> README.md

This script works with rc.local to execute at during boot

By default it sets cpu to powersave when booting without charger connected.
Have not implemented event handle to go to performance when charger is connected.

But the settings do execute.

How to set the script to run @boot

1. Add rc.local file to /etc/
or execute : sudo touch /etc/rc.local

2. Copy cpufreq script to /etc/gscripts

3. Make them executable
sudo chmod +x /etc/gscript/* /etc/rc.local

4. Reboot

Automatic

1. download source

2. open terminal and go to source

3. execute the setscript : ./setscript

if permission denied

4. sudo chmod +x setscript
