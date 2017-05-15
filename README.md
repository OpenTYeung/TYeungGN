# TYeung-gn-build

GN is a meta-build system that generates NinjaBuild files so that you can build Chromium with Ninja.


gn-stuff:GN的一些相关东西，实际项目中，可以删除该目录

build:GN使用时用的基础定义文件，包括windows/linux/macos/ios/android等跨平台编译

buildtools:depot_tools中gn会自己调用buildtools中相应的系统版本GN，生成Ninja文件

source:源文件存放目录，可修改BUILD.gn文件实现


使用方法：（前提得安装depot_tools,见gn-stuff中depot_tools）

	将项目文件放到source文件中（已含demo）,修改BUILD.gn
	在根目录调用命令：gn gen ./out(可换其他目录)
	cd ./out && ninja-mac(mac os 下操作)




