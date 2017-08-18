添加dh_modaliases支持
增加/lib/systemd/system/fcitx-xconfig.service, /usr/bin/fcitx-xconfig,开机时自动探测xorg.conf文件
修改postins，postrm脚本以启动/删除fcitx-xconfig
