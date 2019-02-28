# usefull
# find most recent files 
find /path/to/dir -type f -exec stat -c "%y %n" {} + | sort -r | head -n 100 

# check and repair a Linux filesystem

fsck

# fs benchmark
https://postmarkapp.com/blog/performance-testing-at-postmark

# docker nginx reverse-proxy with ssl
https://dev.to/domysee/setting-up-a-reverse-proxy-with-nginx-and-docker-compose-29jg
