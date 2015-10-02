# Get source #
Nếu bạn dùng **ibus 1.1**, tải ibus-unikey 0.2 [Download](http://code.google.com/p/ibus-unikey/downloads/list)

Nếu bạn dùng **ibus 1.2**, tải ibus-unikey >= 0.3 [Download](http://code.google.com/p/ibus-unikey/downloads/list)

# Install essential packages #
### Ubuntu: ###
```
sudo apt-get install build-essential libibus-dev libgtk2.0-dev libgconf2-dev
```
### Fedora ###
```
su
yum install gcc-c++ ibus-devel gtk2-devel GConf2-devel
```

# Compile & install #
```
cd ibus-unikey
./configure --prefix=/usr
make
sudo make install
```