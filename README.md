# Unlock-netease-cloud-music-silent

静默启动解锁网易云音乐客户端变灰歌曲bat文件

## 解决的问题

* 解决了需要先启动脚本，再启动软件的繁琐性点击问题，通过bat脚本实现了联动启动脚本与软件
* 取消了脚本启动后的CMD黑窗口
* 黑窗口取消后，存在重复启动脚本的问题，通过bat脚本判断52000端口是否占用，未占用则启动脚本，占用则认为脚本正在运行，仅启动软件

## step 

* [打开此链接，下载解锁灰色歌曲项目](https://github.com/meng-chuan/Unlock-netease-cloud-music)
* 先根据原项目的指导按照**Windows端方法一**（本项目仅支持方法一）配置好网易云的网络代理
* 打开网易云所在目录，创建cloudmusic.exe的快捷方式
* 将该快捷方式复制到Unlock-netease-cloud-music项目文件夹下，并将该快捷方式重命名为**cloudmusic**，去掉后面的.exe
* 将本项目的[cloudmusicFake.exe](https://github.com/machangxin/Unlock-netease-cloud-music-silent/blob/main/cloudmusicFake.exe)及[startUnlock.bat](https://github.com/machangxin/Unlock-netease-cloud-music-silent/blob/main/startUnlock.bat)复制到Unlock-netease-cloud-music项目文件夹下
* 在Unlock-netease-cloud-music项目文件夹下，创建cloudmusicFake.exe的快捷方式
* 使用该快捷方式替换原来网易云的桌面快捷方式即可
