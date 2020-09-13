
### Setup local wordpress with docker and vagrant


To execute:

In the root folder:

```
vagrant up
```
```
vagrant ssh
```
```
cd /home/vagrant/wordpress
```

```
docker-compose up -d 
```

Accessing wordpress in the browser:

```
192.168.33.10:8080
```

Accessing phpmyadmin in the browser:

```
192.168.33.10:8181
```