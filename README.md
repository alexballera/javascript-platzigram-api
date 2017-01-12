# Práctica de Javascript: Creando una APP Tipo Instagram - API

## Componentes
### Producción
```bash
npm i -S micro request request-promise uuid-base62 babel-runtime http-hash babel-plugin-transform-async-to-generator
```
### Desarrollo
```bash
npm i -D ava standard babel-eslint test-listen transform-runtime  babel-preset-latest babel-register
```
## Microservicios con Micro
*Micro — Async ES6 HTTP microservices*
[https://github.com/zeit/micro](https://github.com/zeit/micro)

### Http Hash para el manejo de las rutas con micro 
[https://github.com/Matt-Esch/http-hash](https://github.com/Matt-Esch/http-hash)

## Requerimos el móduo de la carpeta platzigram-db
[https://docs.npmjs.com/cli/link](https://docs.npmjs.com/cli/link)
Nos ubicamos en la carpeta de **platzigram-db** verificamos que npm esté instalado y enlazamos
```bash
$ npm i 
$ sudo npm link
```  

Nos ubicamos en la carpeta del proyecto **platzigram-api** y enlazamos  
```bash 
$ sudo npm link ../platzigram-db
```  

### Terminado Video 4 "Creacion de endpoint POST Picture"  