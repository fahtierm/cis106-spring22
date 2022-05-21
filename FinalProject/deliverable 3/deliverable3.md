## Web Server
![](showreviewup.gif)
### Apache and Configuring the Ubuntu Firewall
![](3Apache.PNG)
![](4SHH.PNG)
![](q2.PNG)

### Static IP address setup
![](1.1static.png)
![](1.2static.png.png)
![](1.3static.png)
![](1.4static.png)

I attempted it but came across an road block.
### How to install the server application you chose
First update your local package ``sudo apt update`` onces that is done type this command ``sudo apt install apache2`` this will install apache.



### Basic commands about managing the server application
![](5.1commands.PNG)



### How to start, terminate, and restart a service in Ubuntu
![](15enable.png)


### How to setup virtual hosts
![](7permission.PNG)
![](8html.PNG)
![](9nano.PNG)
![](10.1conf.PNG)
![](10.2conf.PNG)
![](6.2connect.png)
# I had to delete the previous conf and make a new one with vim instead of nano.
![](vim.png)

### Important files and directories
``vim /var/www/html/index.html`` is important because that is where you can design your webserver.

``/etc/apache2/apache2.conf`` you can make changes to the main apache configuration file.

``/var/log/apache2/error.log`` all errors will be brought to this file so you can look back on what happened.



### Server log files
![](log.png)



## Sources
[Source 1](https://www.youtube.com/watch?v=vimZLEd702Y)
[Source 2](https://www.youtube.com/watch?v=w_1quQbOqpI)
[Source 3 static ip](https://www.youtube.com/watch?v=WQyoA35jq24)