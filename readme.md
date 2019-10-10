# Laravel Installer

1 Create Docker machine

```
$ docker-machine create laravel-installer
$ docker-machine env laravel-installer
$ eval $(docker-machine env laravel-installer)
```

2 Adjust the .env file
```
$ vi .env
```

3 Run the install script
```
$ chmod +ux bin/* && ./bin/install
```

4 Open browser
```
$ docker-machine ip laravel-installer
$ open <DOCKER_MACHINE_IP>
``` 

# Uninstall
```
$ docker-machine rm laravel-installer
``` 
