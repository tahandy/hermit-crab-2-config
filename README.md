# hermit-crab-2-config

## Ensure U2C CAN interface is up
```bash
ip -s link show can0

4: can0: <NOARP,UP,LOWER_UP,ECHO> mtu 16 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1024
    link/can
    RX:  bytes packets errors dropped  missed   mcast
       1349785  169299      0       0       0       0
    TX:  bytes packets errors dropped carrier collsns
          5340     937      0       0       0       0
```
