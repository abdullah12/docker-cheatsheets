
```

docker container run alpine hostname

# list all conteainer in the system
dokcer container ls --all

# log in to a docker container ssh
docker container run --interactive --tty --rm ubuntu bash
# rm means remove the container when done execution
#interatice and tty => ssh
 
 docker container run --detach --name mydb -e MYSQL_ROOT_PASSWORD=my-secret-pw  mysql:latest
# --detach means run it on the background

```
