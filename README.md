# NOLIA — Tienda GitHub Pages

## Publicación
Subí `index.html`, `productos.json` y la carpeta `assets/` a la raíz del repositorio. Activá Settings → Pages → Deploy from a branch → main / root.

## Configuración pendiente
En `index.html`, buscá `const CONFIG` y reemplazá `whatsapp:''` con el número en formato internacional (Argentina: 549 + código de área + número, sin signos ni espacios). Cuando exista Instagram, completá `instagram:''` con el usuario.

## Precios
Todos los modelos publicados están provisionalmente clasificados como **chicos ($1.750)**. El precio para **grandes con dijes es $2.500**, pero no se identificó inequívocamente cuáles de las fotos corresponden a esa categoría: cambiá en el arreglo `products` de `index.html` y en `productos.json` los campos `price` a 2500 y `size` a `grande` solo para esos modelos.

## Pagos y envíos
La tienda **no cobra online**: el pedido se arma en WhatsApp, el comercio confirma stock y cotiza el envío de Correo Argentino según código postal, y después comparte un link de Mercado Pago o alias/CBU/CVU por privado. No publiques datos bancarios personales en GitHub.

## Fotos
`assets/pulsera-01.webp` a `pulsera-09.webp` son fotos originales mejoradas levemente en brillo, contraste y color. No se sustituyeron pulseras, cartoncitos ni elementos físicos. Algunas imágenes originales están desenfocadas y no pueden recuperar detalle real. Hay 9 modelos identificables sin duplicar fotos de diferentes ángulos.
