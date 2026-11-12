# TENTÁ · Gres

Sitio web de TENTÁ — cerámica de gres para la mesa. Moodboard de piezas + contacto directo por WhatsApp. Pensado para un QR en el local.

## Qué es

Un sitio **estático**, sin dependencias ni build. Todo vive en:

- `index.html` — la página completa (HTML + CSS + JS en un solo archivo).
- `assets/` — logo e imágenes.

## Cómo verlo / editarlo

Abrí `index.html` en el navegador (doble clic). Para editar, modificá `index.html` con cualquier editor y recargá la página (⌘⇧R para recarga sin caché).

## Configuración pendiente

- **Número de WhatsApp**: en `index.html`, buscá `WHATSAPP_NUMBER` y poné el número real (formato internacional, sin `+`). Ej: Uruguay → `598...`.
- **Instagram / mail**: están como placeholder en la sección de contacto y el footer.
- **Datos de "Cómo trabajamos"** (tiempo de producción, seña, envíos): ajustar a los reales.

## Trabajar desde otra computadora

Este proyecto está en GitHub. En la otra máquina:

```bash
git clone <URL-del-repo>
cd tenta
```

Editás, y para guardar cambios:

```bash
git add -A
git commit -m "describí el cambio"
git push
```

Para traer cambios hechos en la otra compu:

```bash
git pull
```
