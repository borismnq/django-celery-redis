# Run project
```
docker-compose -f local.yml build
docker-compose -f local.yml up
```
## Monitor containers
```
docker-compose -f local.yml ps
```
## Run separated django container

```
docker-compose run --rm --service-ports django 
```
## Suggested way to run compose commands
~~~
docker-compose run --rm django COMMAND 
~~~