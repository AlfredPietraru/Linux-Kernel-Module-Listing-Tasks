Load module into kernel on a Linux distribution:
In my case an Linux Ubuntu 22.04.

sudo insmod simple.ko

lsmod -> for checking if module was successfully added
Module entry point invoked when module enters the kernel

Check kernel log buffer

sudo dmesg -> check the messages posted by the kernel module

sudo rmmod process_observer -> for deleting the module inserted

sudo dmesg -c -> for clearing kernel buffer,