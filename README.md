#win10 n2n vs2019

编译环境:cmake, visual studio 2010及以上(需安装C++的功能模块)

运行环境:visual studio对应版本的vcredist++运行


下载代码：

        https://github.com/YueJia123/n2n.git

cd n2n/n2n_v2/

mkdir build

cd build

cmake -G "Visual Studio 16" --build .\ ..\

在build目录下生成一个vs c++的解决方案

使用vs2019打开n2n.sln

选择相应的项目编译生成即可，
在build/Release/目录或build/Debug/目录下运行即可
