# Finca Verde Inmobiliaria

Proyecto web en Astro y Tailwind CSS para una landing inmobiliaria enfocada en venta rapida y segura de propiedades.

## Comandos

```sh
pnpm dev
pnpm build
pnpm preview
```

## Mantenimiento del catalogo

Las propiedades se actualizan en `src/data/properties.json`.

Cada propiedad incluye:

- `operation`: `venta` o `alquiler`
- `type`: `departamento`, `casa`, `oficina`, etc.
- `district`: distrito usado por el filtro
- `title`, `meta`, `price`, `summary`
- `area`, `bedrooms`, `bathrooms`
- `status`: etiqueta visible en la card
- `highlights`: puntos clave de la ficha
- `image`: URL o ruta de la imagen

Despues de editar el archivo, correr `pnpm build` para validar.
