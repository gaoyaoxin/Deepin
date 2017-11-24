# 1 前期工作  
## 1.1 备份浏览器收藏夹  
## 1.2 备份桌面、我的文档、下载、视频、音乐  
## 1.3 备份其他硬盘文件
## 1.4 制作启动U盘  

# 2 安装
## 2.1 设置BIOS第一启动为外置U盘或硬盘

# 3 使用
## 3.1 安装色温调节软件 redshift
### 3.1.1 在应用商店中搜索 redshift 并安装
### 3.1.2 在文件管理器中主目录后继续输入 /.config 进入该目录
### 3.1.3 新建 redshift.conf 文件，格式参照 [redshift.conf.sample](https://github.com/jonls/redshift/blob/master/redshift.conf.sample)
### 3.1.4 更改第3、4行的白天、夜间默认色温（参考值4000，2700或4000，2400）
### 3.1.5 任务栏右击 redshift 图标->信息，查看纬度、经度，参照这两个值更改第45、46行的纬度、经度
### 3.1.6 关闭并重新打开 redshift 以使设置生效
## 3.2 打开、关闭外接键盘背光
### 3.2.1 方法一
### 3.2.1.1 打开终端，输入 xset led 3 以打开背光
### 3.2.1.2 打开终端，输入 xset -led 3 以关闭背光
### 3.2.2 方法二（详见 repo [keyboardLed](https://github.com/gaoyaoxin/keyboardLed)）


/etc/ImageMagick-6/policy.xml  
line 53  
  <policy domain="resource" name="memory" value="256MiB"/>
 -->2GiB
 ## sudo gedit 打开文本编辑器


## 解决 WiFi, Bluetooth 驱动问题
### 下载并解压Zip，进入主目录 https://github.com/lwfinger/rtlwifi_new
```
make
sudo make install
reboot
```
