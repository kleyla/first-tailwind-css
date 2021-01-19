First proyect with TAILWIND

```
npm init -y
npm install tailwindcss
```

Creamos styles.css en src/ con las siguientes lineas:

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Luego en los scripts de node agregamos:

```
"build-css": "tailwindcss build src/styles.css -o public/styles.css"
```

De esta menera podemos obtener nuestros estilos en public/styles.css

El siguiente comando nos mostrara las configuraciones por defecto:

```
npx tailwindcss init --full
```

Podemos crear un archivo vacio, para configurar a nuestro gusto:

```
npx tailwindcss init
```
