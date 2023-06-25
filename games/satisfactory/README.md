# games > Satisfactory
**not tested** see [#1](https://github.com/BLUEAMETHYST-Studios/Dockerfiles/issues/1) 

## build
```
docker build . -t games/satisfactory:1.0
```
## start
```
docker run -d -p 15777:15777 --name satisfactory games/satisfactory:1.0
```
