
# CREAR CARPETA DEL PROYECTO FULL STACK
 > nestjs-react-mongodb

 

>INSTALAR nestjs

```bash
marin@PC-SALON-JUAN MINGW64 /e/E_2025/PROYECTOS FULL STACK/nestjs-react-mongodb
$ npm i -g @nestjs/cli
 

```


 > ## CREAR PROYECTO BACKEND ----> backend-tasksapi

```bash
 

marin@PC-SALON-JUAN MINGW64 /e/E_2025/PROYECTOS FULL STACK/nestjs-react-mongodb
$ nest new backend-tasksapi

🚀  Successfully created project backend-tasksapi
👉  Get started with the following commands:

$ cd backend-tasksapi
$ npm run start


                          Thanks for installing Nest 🙏
                 Please consider donating to our open collective
                        to help us maintain this package.


               🍷  Donate: https://opencollective.com/nest


```



<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest



RUN APP
--- 

```bash
marin@PC-SALON-JUAN MINGW64 /e/E_2025/PROYECTOS FULL STACK/nestjs-react-mongodb
$ cd backend-tasksapi/

marin@PC-SALON-JUAN MINGW64 /e/E_2025/PROYECTOS FULL STACK/nestjs-react-mongodb/backend-tasksapi (master)
$ npm run start:dev
 
```

VER EN EL NAVEGGADOR ---> http://localhost:3000/
 
STOP APP
--- 
PULSAR Ctrl + C


CORRER MONGO_DB
---------------------

ABRIR UNA POWERSHELL Y EJECUTAR COMANDO: --> NO CERRAR LA POWERSHEL
```bash

mongod --dbpath "C:\data\db"
```

ABRIR OTRA POWERSHELL Y EJECUTAR COMANDO:
```bash
mongosh
```
 
INSTALAR EXTESION THUNDER CLIENT  ---> Para probar los endpoints
 

 
>## CREAR PROYECTO FRONTEND ----> frontend-tasks
--- -

```bash

marin@PC-SALON-JUAN MINGW64 /e/E_2025/PROYECTOS FULL STACK/nestjs-react-mongodb
$ npm create vite

> npx
> create-vite

√ Project name: ... frontend-tasks
√ Select a framework: » React
√ Select a variant: » TypeScript + SWC

Scaffolding project in E:\E_2025\PROYECTOS FULL STACK\nestjs-react-mongodb\frontend-tasks...

Done. Now run:

  cd frontend-tasks
  npm install      
  npm run dev

```

RUN APP
--- 

```bash
marin@PC-SALON-JUAN MINGW64 /e/E_2025/PROYECTOS FULL STACK/nestjs-react-mongodb/frontend-tasks
$  npm run dev

> frontend-tasks@0.0.0 dev
> vite


  VITE v7.1.5  ready in 499 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help

  ```
