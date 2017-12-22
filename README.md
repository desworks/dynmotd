# dynmotd
script to generate a dynamic motd, with arch logo

# don't forget to
edit your targeted partiton at
DISK1=`df -h | grep 'dev/vda3' | awk '{print $2}'`
