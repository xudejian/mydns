##mydns

### my dnsmasq config

### How to use it?

#### Install dnsmasq first
##### OSX `brew install dnsmasq`
##### ubuntu `sudo apt-get install dnsmasq`

#### Enable your dnsmasq.d in dnsmasq.conf
##### add config like this
##### `conf-dir=/usr/local/etc/dnsmasq.d`
##### or `conf-dir=/etc/dnsmasq.d`
##### install with brew, it should be `/usr/local/etc/dnsmasq.d`
##### install with apt-get, it should be `/etc/dnsmasq.d`

#### Choose a method
##### download and drop it into your dnsmasq.d
##### or `git clone git://github.com/xudejian/mydns.git dnsmasq.d`
##### or `git submodule add git://github.com/xudejian/mydns.git dnsmasq.d`

#### Restart your dnsmasq
