# make-leveldb-for-ios

    leveldb： https://github.com/google/leveldb
    
    修改了build_detect_platform文件使在OSX环境下为iOS编译时生成的的build_config.mk文件具有正确的参数。

    修改了Makefile文件，生成的静态库文件支持bitcode。

    build for iOS:

    OSX环境下终端编译命令：make PLATFORM=IOS IPHONEOS_DEPLOYMENT_TARGET=7.0
