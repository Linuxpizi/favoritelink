# Elementary OS 桌面恢复

1. 删除现有的桌面

 ```shell
sudo apt remove lightdm
sudo apt install lightdm
 ```
 
 2. 删除认证

```shell
#rm –rf    ~/.gconf                                           //关于图形的配置文件
#rm  -rf  ~/gconfd                                            //关于图形的配置文件
rm  -r  ~/.Xauthority
```

3. 卸载桌面

```shell
sudo apt remove elementary-desktop
sudo apt install elementary-desktop
```

4. ???

```shell
sudo apt install pantheon-terminal
sudo apt remove wingpanel
sudo aptitube install wingpanel
```

5. 完成以下设置,重启

```shell
sudo apt-get update
sudo apt-get upgrade

sudo apt-get install pantheon-xsession-settings
reboot
```
