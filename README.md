# python-training

description ...

## codespace command
htop - to show cpu usage

## compile and create env

**update all with**
`sudo apt-get update`
**and install lib with**
`sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev`

`wget https://www.python.org/ftp/python/3.10.10/Python-3.10.10.tgz`

`tar zxvf Python-3.10.10.tgz`

`./configure --enable-optimizations`

`make -j <num core>`

`make altinstall`
**Open bash file**
vim ~/.bashrc
**set python alias**
alias python="/usr/local/bin/python3.10"
**set source venv**

**set ludwig framework dependence into requirements.txt file**

touch requirements.txt
touch Makefile
