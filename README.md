# Script to cleanup /boot

Linux utilitites like apt-get  install kernel updates by adding the new kernel to /boot list. 
This typically fills up /boot and when you do an apt-get install you will get error messages saying 
that /boot is out of space.

The fix is to clean up the old kernel files and updates. However, YOU MUST NOT remove the one that 
you are using! 

This is a one line script to clean up /boot automatically (yes this intro is even longer!)
