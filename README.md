# WEBENUM
This is a opt tool for Web enumeration.
I have builde that tool by the path I have been run for the OSCP, the idea is to use other enumeration tools in one executable file,
which create txt files for each enumeration and allow us to execute search tools on them later like grep and find.

# Installation
wget https://raw.githubusercontent.com/Zwerd/webenum/main/webenum
chmod +X webenum
./webenum

# or
cp ./webenum /usr/local/sbin/webenum

# example
webenum feroxbuster http://10.0.0.11:8080/ dirbuster "-e -r"

