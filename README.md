# Solutions for some errors 

If you would like to delete the message(System program problem detected) popping up after you boot Jeston nano.  
Reboot jetson nano.  
```
sudo rm /var/crash/* 
killall system-crash-notification
```

