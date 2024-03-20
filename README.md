# Plex app for YunoHost
Plex Media Server

Shipped version: 1.40.1.8227

- [Yunohost project](https://yunohost.org)
- [Plex website](https://plex.tv/)

![](https://nyro.ovh/wp-content/uploads/2017/12/plex_wallpaper_011-1040x585.jpg)


[![Integration level](https://dash.yunohost.org/integration/plexmediaserver.svg)](https://dash.yunohost.org/appci/app/plexmediaserver)  
[![Install plexmediaserver with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=plexmediaserver)

### Installing guide

 1. App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/plexmediaserver_ynh
 
 After install :

   1. Open a Terminal window or your command prompt
   2. Enter the following command (substituting the IP address of your server as appropriate) :
   
   - `ssh admin@ip.address.of.server -L 8888:localhost:32400`
   
      or
   
   - `ssh -l admin -L 8888:127.0.0.1:32400 ip.address.of.server`
   
   3. Open a browser window
   4. Type http://localhost:8888/web into the address bar
   5. The browser will connect to the server as if it were local and load Plex Web App

 
### Upgrade this package:

        $ sudo yunohost app upgrade plexmediaserver -u https://github.com/YunoHost-Apps/plexmediaserver_ynh

