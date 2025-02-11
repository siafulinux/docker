# Useful docker commands

Docker images can be found at https://hub.docker.com/.


## OPERATING SYSTEMS

### Windows 11
docker run -it --rm -p 8006:8006 --device=/dev/kvm --device=/dev/net/tun --cap-add NET_ADMIN --stop-timeout 120 dockurr/windows

### Parrot OS
docker pull kasmweb/parrotos-5-desktop:1.14.0-rolling

### Terminal
docker pull kasmweb/terminal:1.14.0-rolling



## PROGRAMMING

### Python
docker pull python


## TOOLS

### Firefox
docker pull kasmweb/firefox:1.16.0-rolling-daily

## COMMUNICATIONS

### Signal
docker pull kasmweb/signal:1.16.0-rolling-daily
