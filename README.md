# noc-app

## Descripción

Una aplicación Node.js construida con TypeScript. Utiliza `cron` para tareas programadas.

Este proyecto es parte del curso de Udemy "Desarrollo de aplicaciones Node.js con TypeScript", impartido por el profesor Fernando Herrera. A través de este curso, los estudiantes aprenden a construir aplicaciones robustas utilizando Node.js y TypeScript, incluyendo la implementación de tareas programadas con `cron`.

## 1.- Requisitos
### Asegúrate de tener Git, Node.js y npm instalados

git --version
node --version
npm --version

## 2.-Instalación

### Clona el repositorio
`git clone <URL_DEL_REPOSITORIO>`
  
### Navega al directorio del proyecto

`cd ~/noc-app`

### Instala las dependencias

`npm install`

### Ejecuta la aplicación en modo de desarrollo con ts-node-dev

`npm run dev`

  

### Compila los archivos TypeScript a JavaScript en la carpeta dist
`npm run build`

  

### luego inicia el servidor desde `dist/app`

`npm start`

  

## Dependencias


"@types/node": "^20.11.19"
"rimraf": "^5.0.5"
"ts-node-dev": "^2.0.0"
"typescript": "^5.3.3"
"cron": "^3.1.6"

## Licencia

MIT