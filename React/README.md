# Guía de instalación de Node.js y creación de un proyecto React con Vite

## Instalación de Node.js

1. Visita el sitio oficial de Node.js: https://nodejs.org/
2. En el apartado "Download" busca y descarga la versión LTS (Long Term Support) para tu sistema operativo.
3. Ejecuta el instalador y sigue las instrucciones en pantalla.
4. Verifica la instalación abriendo cualquier terminal y ejecutando:

```bash
node --version
npm --version
```

El resultado debe ser algo así, el número de versión puede variar pero debe dar un resultado

```bash
v22.4.1
```

## Creación de un proyecto React con Vite

1. Abre una terminal y navega hasta el directorio donde quieres crear tu proyecto.

2. Ejecuta el siguiente comando para crear un nuevo proyecto:

```bash
npm create vite@latest my-react-app -- --template react
```

Reemplaza "my-react-app" con el nombre que desees para tu proyecto.

> [!CAUTION]  
> En el caso de que al ejecutar el comando `npm create vite@latest` tengas un error como este:
> ```bash
> No se puede cargar el archivo C:\Program Files\nodejs\npm.ps1 porque la ejecución de scripts está deshabilitada en este sistema....
>```
> Considera la siguiente [documentación](https://www.cdmon.com/es/blog/la-ejecucion-de-scripts-esta-deshabilitada-en-este-sistema-te-contamos-como-actuar) y vuelve a probar.

3. Navega al directorio del proyecto:

```bash
cd my-react-app
```

4. Instala las dependencias:

```bash
npm install
```

5. Inicia el servidor de desarrollo:

```bash
npm run dev
```


6. Abre tu navegador y visita la URL mostrada en la terminal (generalmente http://localhost:5173).

## Estructura básica del proyecto

Tu nuevo proyecto React con Vite tendrá una estructura similar a esta:


```bash
my-react-app/
├── node_modules/
├── public/
├── src/
│   ├── assets/
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

Ahora puedes empezar a desarrollar tu aplicación React en el directorio `src`.

## Recursos Extra

- [Instalación de Node.js video](https://www.youtube.com/watch?v=29mihvA_zEA)
- [Creación de un proyecto de React con Vite](https://www.youtube.com/watch?v=xqSkjzrnBWY)