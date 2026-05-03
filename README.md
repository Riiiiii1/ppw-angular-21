# ppw-angular-21

El proyecto sirve para revisar las configuraciones básicas de Angular 21, incluyendo la creación del proyecto base, la configuración del enrutamiento, la estructura de componentes por features y los estilos globales.

## ¿Qué se hizo?

- Se creó el proyecto `ppw-angular-21` usando Angular CLI con routing habilitado y sin SSR
- Se configuró `app.routes.ts` con la ruta raíz apuntando a `HomePage` y una ruta wildcard que redirige a inicio
- Se simplificó `app.ts` para que el componente raíz solo contenga el `RouterOutlet`
- Se creó el componente `HomePage` dentro de `src/app/features/home/pages/`
- Se ajustaron los estilos globales en `styles.scss` con una base visual neutra
- Se verificó `app.config.ts` con `provideZoneChangeDetection` y `provideRouter`

## Estructura del proyecto

```
src/
  app/
    app.config.ts
    app.routes.ts
    app.ts
    features/
      home/
        pages/
          home-page.ts
```

## Comandos

```bash
pnpm install
pnpm start
```

Abrir en el navegador: `http://localhost:4200`
