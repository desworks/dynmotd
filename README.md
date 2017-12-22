![archmotd picture](https://github.com/desworks/dynmotd/raw/master/archmotd.jpg)

# dynmotd
script to generate a dynamic motd with fancy arch logo

### don't forget to:
* edit your targeted partiton at line 29-31
```bash
DISK1=`df -h | grep 'dev/vda3' | awk '{print $2}'`  # Gesamtspeicher
DISK2=`df -h | grep 'dev/vda3' | awk '{print $3}'`  # Belegt
DISK3=`df -h | grep 'dev/vda3' | awk '{print $4}'`  # Frei
```
* edit your network adapter at line 40

framework inherited by [Sebastian](https://indibit.de/raspberry-pi-ssh-login-nachricht-anpassen-motd/)
