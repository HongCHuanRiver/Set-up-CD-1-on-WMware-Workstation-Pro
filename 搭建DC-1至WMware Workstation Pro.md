# 1.下载DC-1 zip 镜像文件
## 打开Vulnhub官网：
## https://www.vulnhub.com 
## 在网页里的搜索框里面搜索：DC：1，这里已经找好了，搜索：
## https://www.vulnhub.com/entry/dc-1,292
## 直接进入网页，在Download下面找到："- **Download (Mirror)**: https://download.vulnhub.com/dc/DC-1.zip点击，即可下载DC-1的镜像文件DC-1.zip（约732MB）
# 2.解压DC-1 zip 镜像文件
## 利用WinZip或者7-Zip解压Zip文件，可以看到有一个DC-1的文件夹，里面有一个DC-1.ova（）的文件，把它解压到一个你找得到路径的文件夹里（最好不要用到中文路径）
# 3.把DC-1.ova导入WMware Workstation Pro
## 打开你的VMware Workstation Pro,点击最左上角的file,然后在弹出的菜单栏里面点击open...,然后在跳转出来的弹窗里面找到你下好的DC-1.ova,点击打开。
# 4.在v mware workstation Pro里面配置DC-1
## 点击打开后，在弹出的窗口填写你想要给DC-1取的名字，在下方的存储路径里，存储空间应大于等于15GB，避免中文路径然后点击import。由于.ova文件是为VirtualBox做的，VMware Wrokstation Pro导入时会严格检查而且虚拟机配置时可能会用比较老的虚拟硬件版本，所以会出现一个报错，不过没关系直接点retry，点击过后会出现一个importing进度条
# 5.完成搭建，修改配置
## 一般耐心等待完成进度条后WMware Workstation Pro会自动完成配置，如果没有或者想修改配置，右击WMware Workstation Pro左边的虚拟机，滑动到最下面，点击settings...就可以进行配置了,你还可以点击左边你想要配置的虚拟机然后在主页你就可以看到有一个Edite virtual machine settings,双击它也可以进行配置
# 6.打开DC-1，进行验证
## 在WMware Workstation Pro主页左侧点击你配置好的DC-1虚拟机,点击主页中的power on this virtual machine,可能会弹出一个提示框：Cannot connect the virtual device ide1:0 because no corresponding device is available on the host.Do you want to try to connect this virtual device every time you power on the virtual machine?这是正常的，这里我们选择no。等待它启动，启动后如果出现"Debian GNU/Linux 7 DC-1 tty1 DC-1 login:"这样的终端,就说明配置成功了
# 走到这里,那么恭喜你，在WMware Workstation Pro里解锁了DC-1!!!



