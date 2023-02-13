# README: Linux Fonts

## Fonts Install

在/usr/share/fonts/下面建立一个文件夹user

`sudo mkdir /usr/share/fonts/user`

修改字体文件的权限

`sudo chmod 777 *`

安装字体

`sudo mkfontscale`

`sudo mkfontdir`

`sudo fc-cache`

查看字体安装情况

`fc-list | grep <font-name>`

# Font config