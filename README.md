# WebIB - Proyecto Web

Proyecto web desarrollado utilizando **Svelte, TypeScript y Vite** como parte del taller de montaje de entorno.

## Integrantes

- Roberth Solórzano
- Carlos Espinoza

## Tecnologías utilizadas

- Svelte
- TypeScript
- Vite
- Node.js
- npm
- Supabase

## Requisitos

Antes de ejecutar el proyecto, es necesario tener instalado:

- [Node.js](https://nodejs.org/)
- npm (incluido con Node.js)
- Git

Para comprobar que Node.js y npm están instalados correctamente, ejecutar:

```bash
node -v
npm -v
```

## Instalación y ejecución

### 1. Clonar el repositorio

Abrir una terminal y ejecutar:

```bash
git clone https://github.com/uleam-web-2026-2/webIB-Espinoza-Ponce.git
```

### 2. Ingresar a la carpeta del proyecto

```bash
cd webIB-Espinoza-Ponce
```

### 3. Instalar las dependencias

```bash
npm install
```

Este comando instalará todas las dependencias necesarias para ejecutar el proyecto.

### 4. Levantar el servidor de desarrollo

```bash
npm run dev
```

Después de ejecutar el comando, la terminal mostrará una dirección similar a:

```text
http://localhost:5173/
```

Abrir esa dirección en el navegador.

Si el puerto `5173` está ocupado, Vite utilizará automáticamente otro puerto y mostrará la nueva dirección en la terminal.

## Configuración de Base de Datos

El proyecto utiliza **Supabase** como servicio de base de datos.

**URL del proyecto de Supabase:**

```text
https://mwcvhhnyioybdwfscgtm.supabase.co
```

En el repositorio se incluye únicamente la URL del proyecto de Supabase.

## Verificación

Para comprobar que el proyecto funciona correctamente desde cero:

```bash
git clone https://github.com/uleam-web-2026-2/webIB-Espinoza-Ponce.git
cd webIB-Espinoza-Ponce
npm install
npm run dev
```

Luego abrir en el navegador la URL mostrada por Vite.

Si la aplicación carga correctamente, el proyecto está funcionando correctamente.