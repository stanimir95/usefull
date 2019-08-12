# usefull

# Task 9: Recover data from a broken LVM configuration
vgcfgrestore -l vg_1

# Create Linux USB
cat debian.iso > /dev/sdX; sync


# find most recent files 
find /path/to/dir -type f -exec stat -c "%y %n" {} + | sort -r | head -n 100 

# Complete sys info
inxi -Fxz

# check and repair a Linux filesystem

fsck

# fs benchmark
https://postmarkapp.com/blog/performance-testing-at-postmark

# simple python HTTPserver : port 
sudo python -m SimpleHTTPServer 80

# docker nginx reverse-proxy with ssl
https://dev.to/domysee/setting-up-a-reverse-proxy-with-nginx-and-docker-compose-29jg

# TCP and UDP connections
nc

# Attack a volume to an already running container
https://jpetazzo.github.io/2015/01/13/docker-mount-dynamic-volumes/
