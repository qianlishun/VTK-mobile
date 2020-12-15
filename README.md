# VTK-mobile
VTK iOS Android

开发环境：macOS。
需要装的各种东西：CMake,libXt,mesa，以及安装这几个需要的其他依赖，看报什么警告和错误，缺什么装什么。

## Android
参考了 https://www.michaelapp.com/posts/2019/VTK-Android移植和示例/

Android用的是VTK8.2.0。
下了一堆乱七八糟的包，各种错误警告，搞了几天，算是搞完了。

先占位，想起来了再写详细的。

## iOS

iOS用的是VTK7.0.0，最新版的9.0版本搞了好久没搞定。

官方例程 https://github.com/Kitware/VTK/tree/master/Examples/iOS

iOS相对简单，CMake编译工程/或者直接命令行，调整好配置，编译完后，再用make命令生成静态库。
