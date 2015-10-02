# Get source #
You must install git to get source
```
sudo apt-get install git
```
Get lastest source
```
git clone git://github.com/mrlequoctuan/ibus-unikey.git ibus-unikey
```

# Install essential packages #
### Ubuntu: ###
```
sudo apt-get install build-essential automake autoconf libtool gettext cvs libibus-dev libgtk2.0-dev
```
### Fedora ###
```
su
yum install gcc-c++ automake autoconf libtool gettext cvs ibus-devel gtk2-devel
```

# Compile & install #
```
cd ibus-unikey
./autogen.sh --prefix=/usr # add --with-gtk-version=3 to compile with gtk-3
make
sudo make install
```