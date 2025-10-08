
setting vhosts
IP=""
printf "%s\t%s\n\n" "$IP" "<vhosts>" | sudo tee -a /etc/hosts
