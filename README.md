CodeSourcery
============

ZYNQ交叉编译工具链

vim ~/.bashrc

export ARCH=arm
export CROSS_COMPILE=arm-xilinx-linux-gnueabi-
export PATH=/home/ray/workspace/CodeSourcery/bin/:$PATH

sudo apt-get install lib32ncurses5 lib32z1