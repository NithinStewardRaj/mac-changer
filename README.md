you can use this file or automate it by yourself with a simple code

#!/bin/bash

ifconfig eth0(your interface) down
sleep 1
macchanger -r eth0
sleep 1
ifconfig eth0 up

save it in a file and make it executable by changing the permission (chmod +x )
