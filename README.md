
# API Gateway

API Gateway utilizado en el proyecto final del Booster Java Middle 2024.

## Descripción del proyecto

El objetivo de este proyecto es la creación de la imagen de docker a utilizar en el despliegue del repositorio: https://github.com/BraulioBarcenas/Booster2024ProyectoFinal


## Creación de imagen de docker

1. Clonar el repositorio

```bash
  git clone https://github.com/BraulioBarcenas/BoosterApiGateway
```

2. Empaquetar el proyecto desde la carpeta del proyecto

```bash
  ./mvnw clean package -DskipTests
```
3. Crear la imagen de docker

```bash
  docker build -t gateway .
```

4. Continuar el despliegue del repositorio https://github.com/BraulioBarcenas/Booster2024ProyectoFinal

