# AltServer-Linux-ShellScript

Not finished yet
```
wget https://raw.githubusercontent.com/powenn/AltServer-Linux-ShellScript/main/setup.sh && chmod +x setup.sh
```
`apt setup dependencies`
```
sudo apt-get install \
    build-essential \
    checkinstall \
    git \
    autoconf \
    automake \
    libtool-bin \
    libplist-dev \
    libusbmuxd-dev \
    libssl-dev \
    usbmuxd
  ```
  ```
  git clone https://github.com/libimobiledevice/libimobiledevice.git
cd libimobiledevice
```
```
 ./autogen.sh \
    --prefix=/opt/local \
    --enable-debug
make
sudo make install
```
AltServer from https://github.com/rileytestut/AltStore/files/7393624/AltServer.zip
