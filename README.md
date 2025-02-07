# compile-python
This is a repo for compiling and installing python from scratch.
https://www.edx.org/learn/computer-science/pragmatic-ai-labs-spark-hadoop-and-snowflake-for-data-engineering

## Compile Python and Create VirtualEnv with it

`sudo apt-get install build-essential gdb lcov libbz2-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev`

`wget https://www.python.org/ftp/python/3.11.11/Python-3.11.11.tgz`

`tar zxvf Python-3.11.11.tgz`

`cd Python-3.11.11`

`./configure --enable-optimizations`

`make -j 8` - use all 8 cores

`sudo make altinstall`
