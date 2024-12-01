这是“远程诊断维修服务人工诊断“的源码仓库, 当前基于RustDesk v1.4.2

编译参考官方编译教程，使用cargo run --release进行编译。编译后将src/ui文件夹重命名为lib/interface复制到target/release/src文件夹下

正式发布时应将release目录下的rustdesk.exe, sciter.dll, src文件夹与python项目的main.dist文件夹内容放到一起

仅测试windows x64环境

TODO： 测试linux x64环境