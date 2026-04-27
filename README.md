# EliteG2

## Desarrollo

Este proyecto ahora compila `script.js` (con JSX) a `dist/app.js` usando **esbuild**.

### Instalar dependencias

```bash
npm install
```

### Generar build

```bash
npm run build
```

### Modo watch

```bash
npm run build:watch
```

`index.html` carga el bundle compilado desde `dist/app.js` y ya no usa Babel en runtime.
