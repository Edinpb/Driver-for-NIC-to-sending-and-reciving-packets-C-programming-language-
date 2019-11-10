1) Code is for Linux kernel.
2) Code is Compilng with MAKE file which is given in document.
3) Make file is compiled in terminal with this command: $ make -C /lib/modules/(uname -r)/build M=$PWD modules
4) $ is for sudo.

Transmiting part of this driver enables to send ranodom message to devices in LAN network.
For reading packets we put pointers to read ping packets(actually payload of ping packets) and this can bi change moving pointers.