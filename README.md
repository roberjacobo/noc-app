# noc-app

## Descripción
Una aplicación Node.js construida con TypeScript. Utiliza `cron` para tareas programadas.

Este proyecto es parte del curso de Udemy "Desarrollo de aplicaciones Node.js con TypeScript", impartido por el profesor Fernando Herrera. A través de este curso, los estudiantes aprenden a construir aplicaciones robustas utilizando Node.js y TypeScript, incluyendo la implementación de tareas programadas con `cron`.

## Requisitos
# Asegúrate de tener Node.js y npm instalados
node --version
npm --version

## Instalación
# Clona el repositorio
git clone <URL_DEL_REPOSITORIO>

# Navega al directorio del proyecto
cd noc-app

# Instala las dependencias
npm install

## Scripts Disponibles
# Ejecuta la aplicación en modo de desarrollo con ts-node-dev
npm run dev

# Compila los archivos TypeScript a JavaScript en la carpeta `dist`
npm run build

# Ejecuta `npm run build` y luego inicia el servidor desde `dist/app`
npm start

## Dependencias
# cron para tareas programadas
npm install cron

# rimraf para eliminar la carpeta `dist`
npm install rimraf

# ts-node-dev para ejecutar y reiniciar automáticamente el servidor
npm install ts-node-dev

# typescript como el lenguaje principal
npm install typescript

## Licencia
MIT
