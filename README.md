## redis cluster docker in local

this is only for development, running redis cluster in docker with port 6363-6368 

steps
1. get host machine ip by 

```
ifconfig | grep "inet " | grep -v 127.0.0.1 | awk '{print $2}'
```

2. copy one of the ip to the replace all ${IP} in this repository
3. run command

```
docker-compose up
```