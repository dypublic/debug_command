# debug_command  
### thread number  
ps -mq pid

### perf look call stack  
perf record -g -p 55

### report memory map of a process  
pmap -x 75  

### net stats  
netstat -s

### socket stats tcp listen  
ss -nlt
