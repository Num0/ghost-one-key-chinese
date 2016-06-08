# ghost-one-key-chinese
## ghost 0.7.4中文版 一键包
#### 仅支持debian7，其他不知道
### 安装
sudo apt-get update

sudo wget https://github.com/Num0/ghost-one-key-chinese/raw/master/EasyGhost.sh

sudo sh EasyGhost.sh
### 开机运行
wget -P /etc/init.d/ https://raw.githubusercontent.com/Num0/ghost-one-key-chinese/master/ghost

sudo useradd -r ghost -U

sudo chown -R ghost:ghost /home/wwwroot/ghost/

sudo chmod 755 /etc/init.d/ghost 

sudo update-rc.d ghost defaults

sudo update-rc.d ghost enable

sudo adduser root ghost
#### 别问我什么，我也不知道怎么写出来的。用此搭的站 http://num0.net
##### Base on http://www.zzfly.net/easyghost/
