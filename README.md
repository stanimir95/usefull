# usefull
# find most recent files 
find /path/to/dir -type f -exec stat -c "%y %n" {} + | sort -r | head -n 100 
