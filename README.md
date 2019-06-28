# PufferPanel app for YunoHost
PufferPanel Server

- [Yunohost project](https://yunohost.org)
- [PufferPanel website](https://www.pufferpanel.com/)

![](http://i.imgur.com/YCy8Md2.png)


[![Install PufferPanel with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=pufferpanel)

### Installing guide

 App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/pufferpanel_ynh
         
### Server Location

Server is installed on /var/lib/pufferd/servers/*

Command Exemple :

        $ chmod -R 775 /var/lib/pufferd/servers/40b93af5-c378-4ec5-857e-5ff50b09170d
        $ chown -R pufferd:pufferd /var/lib/pufferd/servers/40b93af5-c378-4ec5-857e-5ff50b09170d

 
### Upgrade this package:

        $ sudo yunohost app upgrade pufferpanel -u https://github.com/YunoHost-Apps/pufferpanel_ynh

