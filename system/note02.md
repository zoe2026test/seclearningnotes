# Day2 Linux 文件与目录基础操作笔记
## 今日实操命令
1. mkdir mytest        创建文件夹mytest
2. cd mytest           进入mytest文件夹
3. touch file1.txt     创建空文件file1.txt
4. touch file2.txt     创建空文件file2.txt
5. ls                  列出当前目录下所有文件
6. cp file1.txt file1_bak.txt    复制文件，原文件保留
7. mv file2.txt newfile.txt      mv用作【重命名】
8. mv newfile.txt ..             mv用作【移动文件到上一级目录】
9. cd  ..               返回上一级目录
10.  rm newfile.txt     删除单个文件
11. rm -r mytest       删除文件夹（文件夹带内容，必须加 -r 参数）

## 核心知识点
- cp：复制，源文件不会消失，产生副本
- mv：双重功能：移动文件 / 文件重命名，源文件会被转移
- rm：删除文件；rm -r：删除目录（文件夹）
- .. 代表上一级目录；. 代表当前目录
Linux删除操作不可逆，禁止执行 rm -rf / ，会直接摧毁系统！
