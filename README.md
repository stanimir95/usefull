# usefull

# Kubeadm join command
sudo kubeadm init --apiserver-advertise-address=192.168.101.10 --pod-network-cidr=10.0.0.0/16 --ignore-preflight-errors=all



# Bash has an "until" loop
until [CONDITION]
do
  [COMMANDS]
done


# Test sub-domains if only IP available
curl <IP> -H 'Host: subdomain.domain.com'

# Connect to remote with Visual Studio Code 

Open your terminal application, and run the following command:
ssh cloud_user@PUBLIC_IP_ADDRESS
Enter yes at the prompt.
Enter your cloud_user password at the prompt.
Run exit to close the connection.
Run the following command:
ssh-copy-id cloud_user@PUBLIC_IP
Enter your password at the prompt.
Open Visual Studio Code.
In the seach bar at the top, enter cloud_user@PUBLIC_IP.
Once you've connected, click the square Extensions icon in the left sidebar.
Under Local - Installed, scroll down to Python and click Install on SSH.
Click Reload to make the changes take effect.

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
