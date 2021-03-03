# CSSE4011 Student Repositories

## Folder Setup

Setup your local workspace as follows, replacing sXXXXXXXX with your student number
```
# Install West
pip3 install --user -U west
# Create a folder for this course
mkdir -p ~/code/csse4011
cd ~/code/csse4011
# Clone your git repository into the folder:
git clone https://sources.eait.uq.edu.au/git/csse4011-sXXXXXXX.git csse4011-sXXXXXXXX
# Tell West what the main repo is
west init -l csse4011-sXXXXXXXX
# Pull down all the required repositories
west update
```

## Toolchain Setup

Follow the getting started guide to install the required toolchains.
https://docs.zephyrproject.org/latest/getting_started/index.html


## Build an Application

```
west build -b thingy52_nrf52832 sXXXXXXXX/apps/p1/blinky
```
