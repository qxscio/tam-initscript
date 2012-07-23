tam-initscript
==============

IBM TAM (Tivoli Access Manager) init scripts for RedHat/CentOS 5 and 6 useful when creating an active/passive cluster with Red Hat Cluster Suite.

__pdmgrd__: start/stop IBM Tivoli Access Manager policy server  
__pdacld__: start/stop IBM Tivoli Access Manager authorization server


Copy the scripts to `/etc/init.d/` and give them execute permissions:

    # cp pdmgrd /etc/init.d/
    # cp pdacld /etc/init.d/
    # chmod +x /etc/init.d/pdmgrd
    # chmod +x /etc/init.d/pdacld

Usage:

    service pdmgrd {start|stop|restart|status}
    service pdacld {start|stop|restart|status}
