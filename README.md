# Proxy Switcher
Set systemwide proxy in XFCE for Arch-based distributions

### Requirements
1. dbus

```sh
$ sudo pacman -S dbus
```

### Installation

Make script as executable:

```sh
$ chmod +x proxySwitch.sh
```
```sh
$ sudo cp proxySwitch.sh /usr/sbin/
```

### Usage

To set up proxy server:

```sh
$ sudo proxySwitch.sh <proxy> <port>
```

To remove proxy server:
```sh
$ sudo proxySwitch.sh off
```
