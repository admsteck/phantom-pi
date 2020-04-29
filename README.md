# phantom-pi
Run [phantom](https://github.com/jhead/phantom) on a raspberry pi

## Installation
### Repository setup
- Fork this repo
- Update server-list to be your servers in the format \<name>,\<ip or domain>:\<port>
- Update phantom-version to be the version of Phantom you want to run
- Update the urls in rc.local to point to your fork

### Raspberry Pi setup
- Start with a fresh raspbian lite image
- sudo apt-get install screen
- Update /etc/rc.local with the version in your fork (make sure you don't change the permissions)
- Restart your pi
- Profit!
