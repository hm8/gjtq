狗急跳墙
========
1. GAE注册
2. 修改local文件夹中的proxy ini文件,将appid修改成你的appid
3. 找到local文件夹下面ca.crt文件，双击导入ca.crt证书，选择‘系统选项’。
4. 切换到server目录，python uploader.zip
5. 勾选自动代理配置，URL：http://127.0.0.1:8086/proxy.pac
6. 切换到local目录，python proxy.py