# KFchat
Cluster chat server code source code that can work in nginx tcp load balancing environment, implemented based on muduo library--感谢陈硕大神施磊老师
编译方式：
cd build
rm -rf *
cmake ..
make

运行程序的必要条件：
nginx的TCP负载均衡
启动redis
boost+muduo/json(json.hpp已提供)/mysql/cmake环境
