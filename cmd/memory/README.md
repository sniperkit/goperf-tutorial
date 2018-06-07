# Go Memory Management

## Analysis

```bash
# start application
go build main.go && ./main

# find pid
ps aux | grep "./main"

# analyze memory usage
ps -p 44722 -o %cpu,%mem,vsz,rss,stat,start,time,command

```