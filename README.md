# DulceLab Navidad — web estática

Sitio responsive en HTML, CSS y JavaScript, listo para GitHub Pages o Render Static Site.

## Probar
Abre `index.html` en un navegador. Para una prueba local más estable puedes usar Live Server en VS Code.

## Publicar en Render
1. Sube esta carpeta a un repositorio de GitHub.
2. En Render crea **New → Static Site** y conecta el repositorio.
3. Build Command: vacío (o `echo static`). Publish Directory: `.`
4. Deploy.

## Configurar WhatsApp
En `script.js`, al inicio cambia `CONFIG.whatsapp` por el número comercial en formato internacional, solo números, sin `+`, espacios ni guiones. Ejemplo de formato Perú: `51` + número móvil.
El checkout abre WhatsApp con el resumen codificado. El cliente debe revisar y enviar el mensaje; no se registra automáticamente en un servidor.

## Precios y fotografías
Los precios están en “Precio por confirmar” porque no se proporcionaron precios oficiales. La lista `products` en `script.js` es editable. Puedes reemplazar las imágenes de muestra por fotografías propias dentro de `assets/` y actualizar las rutas.

## Funciones disponibles
- Catálogo con búsqueda y filtro de categorías.
- Tarjetas de experiencias que se agregan al carrito.
- Carrito persistente mediante `localStorage`, cantidades y eliminación.
- Caja personalizada con tipo de experiencia y dedicatoria.
- Agregado de plantillas de pijama al carrito.
- Resumen de pedido preparado para WhatsApp (requiere configurar el número).
- Pasaporte digital de ejemplo en `pages/passport.html`.
- Diseño responsive para móvil, tablet y PC.

## Nota
La personalización de pijamas y cajas se registra como especificación para coordinar; no se simula fabricación, disponibilidad, pagos ni registro automático de pedidos.
