# chatserver
基于moduo实现的工作在nignx tcp负载均衡环境中的集群聊天服务器和客户端源码(数据库redis mysql）

编译方式
cmake ..
make
环境 ：
muduo网络库(muduo库依赖boost库),nginx的tcp负载均衡配置，redis数据库，mysql数据库

bin:可执行文件包括客户端和服务器，运行时输入ip加端口
include:项目实现所写的头文件
src:对应头文件声明的定义cpp文件及main.cpp
thirdparty:项目实现数据序列反序列化所用的三方库
CMakeLists.txt:cmake

