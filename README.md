# FairyGUI-cocoscreator
 A flexible UI framework for Cocos Creator, working with the FREE professional Game UI Editor: FairyGUI Editor.  
 基于 https://github.com/fairygui/FairyGUI-cocoscreator 修改

# CocosCreator版本3.7.2
# 安装
 npm i https://git@github.com:Alistairot/FairyGUI-cocoscreator.git#发布的tag  
 例如:  
 npm i https://git@github.com:Alistairot/FairyGUI-cocoscreator.git#v3.7.2.1  
# 编译
1.初始化环境 npm install  
2.开始编译 gulp build

# 常见错误
 1.安装的时候Git报错解决：OpenSSL SSL_read: Connection was reset, errno 10054  
    解决：git config --global http.sslVerify "false"