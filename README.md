### ec2 ubuntu 18.04 install mongo

https://medium.com/faun/install-mongodb-on-aws-ubuntu-ec2-instance-6794cd8e3b4e

```
mongo
use test
db.users_test.insertMany([
{
 "name": "hunter",
 "age": 36, 
 "title" : "Engineer"
},
{
 "name": "sarra",
 "age": 24, 
 "title" : "clerk"
}])
```

remote ec2  mongodb
```
mongo "54.87.133.19:27017"
```

### more docker 
```
docker stop $(docker ps -aq)    
docker rm $(docker ps -aq)    
docker rmi $(docker images -q)
```

```
sudo docker stop $(sudo docker ps -aq)    
sudo docker rm $(sudo docker ps -aq)    
sudo docker rmi $(sudo docker images -q)
```


### mongoDB1 -> 
```
https://www.youtube.com/watch?v=DzyC8lqbjC8
issue: https://stackoverflow.com/questions/39108992/mongoerror-getaddrinfo-enotfound-undefined-undefined27017
```


### reference
```
https://www.youtube.com/watch?v=DzyC8lqbjC8
issue: https://stackoverflow.com/questions/39108992/mongoerror-getaddrinfo-enotfound-undefined-undefined27017
https://phoenixnap.com/kb/docker-mongodb
```
