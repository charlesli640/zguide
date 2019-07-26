The prebuilt dll files are built form libzmq v4.2.3 using Visual Studio 2015/2017

To build the examples, try below command

sh build_ming32 all

g++ -O2 -o bin\wuclient3.exe  -I./include -L./lib -lzmq  wuclient.cpp

sh.exe c -p -li ./include/ -ll ./lib/ wuclient
