# Anotaciones JavaScript Avanzado

## Trabajando con Yarn

```sh
npm install --global yarn
```

## Verificar que tenga todo bien

```sh
yarn --version
```

## Trabajar con VITE

```sh
yarn create vite .
```

## Instalar las dependencias

```sh
yarn
```

## Levantar el servidor de desarrollo

```sh
yarn dev
```

## Subir al hosting, tengo que hacer un build
Para que me genere la carpeta de distribuicion. Con los archivos listos para subir al hosting.

```sh
yarn build
```

## Agregamos Bootstrap al proyecto

```sh
yarn add bootstrap@5.3.1
yarn add bootstrap@latest
```
```sh
 yarn add @popperjs/core
```
## Configurar Bootstrap

```main.js
import * as bootstrap from 'bootstrap'
```

```style.css
@import  'bootstrap'
```