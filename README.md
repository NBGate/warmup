warmup
======

android编译步骤：
1. 下载cocos2d-x源码，放在warmup同级目录，并且命名为cocos2d-x，完成后目录结构应该如下：
some_where
 |
 |----cocos2d-x
 |      |
 |      |----cocos2dx
 |      |----CocosDenshion
 |      |----....
 |
 |----warmup

2. 进入warmup/proj.android目录，执行: ./build_native.sh
3. 编译native: android update project -n warmup -p . -t android-10
4. 编译apk: ant debug
