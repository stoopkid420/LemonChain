#LemonChain

similar projects:
https://github.com/odipar/spread/
https://github.com/unisonweb/unison
http://ceptr.org/
and ofc http://ethereum.org/



Under development. 

To run example: "./tau < examples/socrates"  

For verbose print: "./tau --level 100 < examples/socrates"  

###deps:  
apt-get install libboost-system-dev libboost-filesystem-dev libcurl4-openssl-dev    #todo:not all necessary, update  
####For building libmarpa
apt-get install -y build-essential autoconf automake libtool
####for the n3 parser:  
apt-get install libboost-regex-dev  

C++ Compiler has to support C++11, gcc-4.9 and clang++-3.6 are known to work.  

Building: run make. You can also use cmake, but the hand-written Makefile is the primary method.  




apt-get install -y build-essential autoconf automake libtool libboost-regex-dev clang-3.6 libc++-dev
CXX="clang++-3.6  -stdlib=libc++ " DEBUG="" make -e
