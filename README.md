By: Moeiz Riaz 07/03/2015

Thrift-Javascript-to-C++

Run these commands in terminal:

1. thrift --gen cpp --gen js hello.thrift
2. g++ gen-cpp/helloSvc.cpp server.cpp -o server -lthrift
3. npm install thrift 
4. ./server

Open up firefox and open file on hello.html
