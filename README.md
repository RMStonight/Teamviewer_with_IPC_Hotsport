# Teamviewer搭配工控机热点实现无线远程控制（搭配虚拟显示或者HDMI欺骗器）

可实现小范围内，笔记本无线控制工控机（使用工控机发布的热点），工控机不接显示器

## 1.创建热点
终端输入：`nm-connection-editor`

点击图中“+”号，选择WiFi并创建

不要设置密码（可能会使笔记本连不上），ipv4：shared，ipv6：ignore

## 2.连接热点
网络连接处打开热点

选择连接隐藏网络

找到设置的热点名称即可连接

## 3.Teamviewer设置
安装后勾选开机自启

设置允许LAN接入

设置密码
