# compile-python
This is a repo for compiling and installing Python from scratch

## Compile Python and create VirtualEnv with it

`sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev

`wget https://www.python.org/ftp/python/3.12.8/Python-3.12.8.tgz

`tar zxvf Python-3.12.8.tgz

`./configure --enable-optimizations

`make -j 4

`sudo make altinstall 
