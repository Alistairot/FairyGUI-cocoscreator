# FairyGUI-cocoscreator
 A flexible UI framework for Cocos Creator, working with the FREE professional Game UI Editor: FairyGUI Editor.  
 基于 https://github.com/fairygui/FairyGUI-cocoscreator 修改

# CocosCreator版本3.7.2
# 安装
 npm i github:Alistairot/FairyGUI-cocoscreator.git#发布的tag  
 例如:  
 npm i github:Alistairot/FairyGUI-cocoscreator#v3.7.2.2  
# 编译
1.初始化环境 npm install  
2.开始编译 gulp build

# 常见错误
 1.安装的时候Git报错解决：OpenSSL SSL_read: Connection was reset, errno 10054  
    解决：git config --global http.sslVerify "false"
 2.git出现报错: Permission denied (publickey).  
    可能是因为git没有配置ssh key，需要配置ssh key, 先用'ssh -T git@github.com'这个命令测试一下是否配置了ssh key, 如果没有配置ssh key的话会提示: Permission denied (publickey).  
    解决: https://cloud.tencent.com/developer/article/1635471  