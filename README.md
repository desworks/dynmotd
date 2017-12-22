# dynmotd
script to generate a dynamic motd, with arch logo

# don't forget to:
edit your targeted partiton at line 29-31
```bash
DISK1=`df -h | grep 'dev/vda3' | awk '{print $2}'`  # Gesamtspeicher
DISK2=`df -h | grep 'dev/vda3' | awk '{print $3}'`  # Belegt
DISK3=`df -h | grep 'dev/vda3' | awk '{print $4}'`  # Frei
```
edit your network adapter at 40
