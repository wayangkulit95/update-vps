### UPDATE VPS UBUNTU 20.04 LTSC


```
sudo apt update && sudo apt upgrade -y && sudo apt full-upgrade -y && sudo apt autoremove -y && sudo apt autoclean && sudo reboot
```



## INSTALL PM2

```
npm install pm2@latest -g
```



### VERIFIED INSTALL

```
pm2 -v
```



## Start a Node.js Application with PM2

```
cd /path/to/your/app
```


## Start the application using PM2:


```
pm2 start app.js
```



## Save PM2 Process List

```
pm2 save
```



## Setup PM2 Startup Script

```
pm2 startup app.js
```




