## Pre-requisites
### OS : Linux->Ubuntu

* Openocd tool              (https://elinux.org/OpenOCD_Ubuntu_Package)
* Telnet                     (sudo apt-get install telnetd -y)
* Expliot Framework install 

    https://expliot.readthedocs.io/en/latest/installation/intro.html

* Bless tool                (sudo apt-get install bless)
* Disable linux modem manger on your host machine.
    

      * systemctl |grep Modem    (may show ModemManger.service)
      * systemctl {stop|start|enable|disable} ModemManager.service
      * So, disable ModemManager using :
         * systemctl disable ModemManager.service


