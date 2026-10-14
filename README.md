# TRAMA

Tienda de muestra de gorras, pilusos y gorros. Proyecto de portfolio: no tiene backend y no procesa compras reales. El carrito, la cuenta, los pedidos y las preferencias se guardan en el `localStorage` del navegador.

## Ver en local

Abrí `index.html` en el navegador, o serví la carpeta con cualquier servidor estático:

```
npx serve .
# o
python3 -m http.server 8000
```

Para publicar en Vercel o GitHub Pages no hace falta build: subí la carpeta tal cual. La navegación usa rutas con `#`, así que no requiere reglas de reescritura.

## Estructura

```
trama/
├── index.html          HTML, CSS y JS del sitio
├── README.md
├── favicon.png
├── assets/
│   ├── logo_trama.png
│   ├── video/          trama_giro.mp4, trama_frontal.jpg
│   └── img/            fotos de galería, siluetas, detalle, drop, colección y nosotros
└── 360/                36 frames .webp por pieza (gorra-negra, piluso-negro, gorro-negro)
```

## Datos de prueba

- Usuario demo: `demo@trama.com` / `trama2026`
- Tarjeta aprobada: `4242 4242 4242 4242`
- Tarjeta rechazada: `4000 0000 0000 0002`

Cualquier vencimiento futuro y código de seguridad de 3 dígitos.
