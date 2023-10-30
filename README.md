## Guia

1* cmd, todo en linea de comandos.
2* armo la carpeta                            ---> mkdir CarpetaAplicacion
3* abro la carpeta                            ---> cd CarpetaAplicacion
4* dentro de la carpeta, corro el comando     ---> npm init -y
5* sigo dentro de la carpeta, corro el comando--->npm install express ejs typescript ts-node @types/  express @types/node
esta ultima linea, instala express con la pantilla ejs y crea los typesscript
6* code. esta ultima ya instacia visualdev



* Crear carpeta "test-express-mvc"
* Ingresar a la carpeta con  ```cd test-express-mvc```
* Ejecutar el comando ```npm init -y```
* Instalar todas la dependencias necesarias para iniciar el proyecto
    ```
    npm install express ejs typescript ts-node @types/express @types/node
    ```
* Crear archivo tsconfig.json
```
{
    "compilerOptions": {
        "target": "ES2018",
        "module": "commonjs",
        "outDir": "./dist",
        "rootDir": "./src",
        "strict": true,
        "esModuleInterop": true,
    }
}
```
* Crear estructara 
```
test-mvc-express/
  ├─ src/
  │   ├─ app.ts
  │   ├─ views/
  │   │     ├─ home.ejs
  ├─ package.json
  ├─ tsconfig.json

```
* agregar script en el package.json
```
		"start": "ts-node src/app.ts"
```
* corre con run dev start