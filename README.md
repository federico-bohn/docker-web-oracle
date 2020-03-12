# docker-web-oracle
Contenedor Docker que sirve como base para proyectos basados en SIU-Toba que se conecten con base de datos Oracle.

## Uso
Los proyectos que quieran utilizar este proyecto deberán basar sus imagenes desde **federicobohn/docker-web-oracle** usando FROM en el Dockerfile
del proyecto:

```
FROM federicobohn/docker-web-oracle
```

## Build
Para buildear manualmentel la imagen
```
docker build -t="federicobohn/docker-web-oracle" .
```
