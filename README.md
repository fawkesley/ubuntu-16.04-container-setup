# Ubuntu 16.04 container setup

```
cd $(mktemp -d)
wget 'https://github.com/paulfurley/ubuntu-16.04-container-setup/archive/master.zip'
unzip -version || apt install unzip
unzip master.zip
cd ubuntu-16.04-container-setup-master
./setup
```
