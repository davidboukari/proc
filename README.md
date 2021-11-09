# proc

* Get the port open by a process
```
root@apache-http:/usr/local/apache2# cat /proc/1/net/tcp
  sl  local_address rem_address   st tx_queue rx_queue tr tm->when retrnsmt   uid  timeout inode                                                     
   0: 00000000:0050 00000000:0000 0A 00000000:00000000 00:00000000 00000000     0        0 56398589 1 ffff908165cd3a80 100 0 0 10 0                  

root@apache-http:/usr/local/apache2# printf  "%d\n"  "0x0050" 
80

```
