## Setup Vscode

01. Cloning the repo and starting the setup using his command bellow
```bash
git clone https://github.com/codeasylums/FullStackTool_docker.git
cd FullStackTool_docker
bash setup.sh 
```

## After  running the script you will be ask for 4 option | bellow like this :

```
                   _                      _                   
      ___ ___   __| | ___  __ _  ___ _   _| |  _   _  __ ___   ___ 
     / __/ _ \ / _\ |/ _ \/ _\  / __| | | | ||  | | ||_ | _ \ / __| 
    | (_| (_) | (_| |  __/ (_|  \__ \ |_| | ||  |_| || | | | |\__ \ 
     \___\___/ \__/_|\___|\__/'_|___/\__  |_| \__  _|| |_| |_||___) 
                                    |___/ 

Fullstack Learning Bootcamp Kit

 Note : Please select 1 if you're running this script first time. 
1) Setup
2) Start
3) Stop
4) Quit
Please enter your choice [1, 2, 3, 4] : 

```
Note  : Please select '1' If you are running the script for first time  

When setup complete you will redirect to the url which will automatically open in you default browser or you can open Vs-code manually by copy this link ```http://127.0.0.1:8080``` to your browser after setup complete.


##  After opening link it will ask you for login password use the password given bellow :
```
Use Password : summercodeasylums
```

## you can use this listening port in your projects 

you have multiple port open in your Vscode docker you can use in you api servers
 
Ports numbers are :
```
3000 3001 3002 3003 3004 3005 5000 443 80
```

## To access mongodb  database in terminal

use the commands bellow in Vscode terminal:
```
mongo --host  <your-system-ip>
```
note : Always use your system ip instead of localhost/127.0.0.1  in mongo-db 

To find your ip use command bellow :

```
ip addr show 
```
or 
```
ifconfig
```

## Start and Stop

You can Start and Stop you this setup by again running the command bellow :
 
```
bash setup.sh 
```
Select 2 For start again 
Select 3 for stopping the setup