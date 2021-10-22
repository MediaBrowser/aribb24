aribb24
=======

A library for ARIB STD-B24, decoding JIS 8 bit characters and parsing MPEG-TS stream.

## Building with MSYS2 + MAS

## 32bit

make distclean

source /local32/etc/profile2.local

./bootstrap

./configure --prefix=/local32 --exec-prefix=/local32
 
make 

make install

 ## 64bit

make distclean

source /local64/etc/profile2.local

./bootstrap

./configure --prefix=/local64 --exec-prefix=/local64
 
make 

make install

 